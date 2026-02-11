# Large Language Models – MC-CD05

Bruno Menezes e Daniel de Senna


## Vídeos do Minicurso (LNCC / YouTube)

### Aula 1 — Fundamentos de LLMs e Transformers
[![Aula 1 – Fundamentos de LLMs](https://img.youtube.com/vi/XqyVUyrIYG8/hqdefault.jpg)](https://www.youtube.com/live/XqyVUyrIYG8?si=kmw4Z-0PvCFeXS-2)

---

### Aula 2 — Fine-Tuning, Alinhamento e Avaliação
[![Aula 2 – Fine-Tuning e Alinhamento](https://img.youtube.com/vi/v72LFSUw9D4/hqdefault.jpg)](https://www.youtube.com/live/v72LFSUw9D4?si=SU0VqFl4tO-uFqPs)



**Duração:** 2h30 (2 dias)
**Datas e horários:**

* **09/02/2026** – 11:00–12:30
* **10/02/2026** – 13:30–15:00
* **11/02/2026** – 15:00–16:30 (Sobre Agentes com o professor Eduardo Bezerra)

---

## Objetivo

Apresentar, de forma concisa e aplicada, os fundamentos conceituais e práticos dos **Large Language Models (LLMs)**, destacando a evolução dos **Transformers** e as inovações recentes em **inferência** e **ajuste fino**.

O minicurso oferece uma visão atualizada do ecossistema de **modelos abertos** (LLaMA 3, Qwen2, Mixtral, DeepSeek, entre outros), equilibrando base teórica essencial e demonstrações práticas de **geração** e **fine-tuning**, com foco em **eficiência**, **alinhamento** e **aplicações científicas**.

---

## Ementa Proposta

* Introdução aos LLMs: panorama 2023–2025, evolução, impacto e ecossistema open-source
* Núcleo do Transformer: atenção, embeddings e normalização, com compreensão conceitual e sem excesso matemático
* Variações modernas: Mixture of Experts (MoE), Rotary Embeddings e Attention Scaling, com visão sintética e aplicada
* Controle e inferência: parâmetros de geração (temperatura, top-p) e gerenciamento de contexto (KV cache, expected-attention, cache merging)

### Prática 1 – Inferência Interativa

* Experimentação guiada com prompts e parâmetros de geração

* Exploração de variação de temperatura, top-p e raciocínio via chain-of-thought

* Prompt engineering e in-context learning: few-shot, self-consistency e limites de contexto

* Pré-treinamento e otimização: datasets em larga escala, quantização (FP8, INT4) e eficiência computacional

* Ajuste fino supervisionado (SFT) e métodos eficientes: LoRA 2, QLoRA e estratégias em três estágios para fine-tuning de modelos quantizados

### Prática 2 – Simulação de Fine-Tuning

* Demonstração simplificada de pipeline LoRA/QLoRA

* Seleção de camadas e visualização de pesos adaptados

* Alinhamento de preferências: DPO, RLHF, GRPO e abordagens emergentes de raciocínio (DeepSeek-R1, raciocínio via RL)

* Avaliação moderna (2024–2025): MMLU-Pro/Pro+, AIME-24/25, LiveBench e GPQA

* Riscos de contaminação e limitações do paradigma LLM-as-a-judge

* Tendências e desafios em LLMs abertos: interoperabilidade, governança e impacto científico

---

## Material de Apoio

Livro SBC:
[https://books-sol.sbc.org.br/index.php/sbc/catalog/book/179](https://books-sol.sbc.org.br/index.php/sbc/catalog/book/179)

---

## Bibliografia

1. Yang, A. et al. *Qwen2 Technical Report.* arXiv:2407.10671 (2024).
   [https://arxiv.org/abs/2407.10671](https://arxiv.org/abs/2407.10671)

2. Wang, P. et al. *Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution.* arXiv:2409.12191 (2025).
   [https://arxiv.org/abs/2409.12191](https://arxiv.org/abs/2409.12191)

3. Jiang, A. Q. et al. *Mixtral of Experts.* arXiv:2401.04088 (2024).
   [https://arxiv.org/abs/2401.04088](https://arxiv.org/abs/2401.04088)

4. Zhang, Y. et al. *DeepSeek-Coder-V2: Breaking the Barrier of Closed-Source Models in Code Intelligence.* arXiv:2406.11931 (2024).  
   [https://arxiv.org/abs/2406.11931](https://arxiv.org/abs/2406.11931)   

5. Touvron, H. et al. *LLaMA: Open and Efficient Foundation Language Models* Meta AI Technical Report, arXiv:2302.13971 (2023).
   [https://arxiv.org/abs/2302.13971](https://arxiv.org/abs/2302.13971)

6. Mroueh, Y. et al. *Revisiting Group Relative Policy Optimization.* arXiv:2505.22257v1 (2025).
   [https://arxiv.org/abs/2505.22257](https://arxiv.org/abs/2505.22257)

7. Zhou, C. et al. *Efficient Fine-Tuning of Quantized LLMs via Three-Stage Optimization.* ICLR 2025 submission.
   [https://openreview.net/forum?id=zcx6rIMbbR](https://openreview.net/forum?id=zcx6rIMbbR) 

8. Dettmers, T. et al. *QLoRA: Efficient Finetuning of Quantized LLMs.* NeurIPS (2023).
   [https://arxiv.org/abs/2305.14314](https://arxiv.org/abs/2305.14314)

9. Ouyang, L. et al. *Training Language Models to Follow Instructions with Human Feedback.* OpenAI, NeurIPS (2022).
   [https://arxiv.org/abs/2203.02155](https://arxiv.org/abs/2203.02155)
