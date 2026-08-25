# Diego Nunes de Morais

**AI & Data Engineer** — Brasília, DF · [diegonmorais.com](https://www.diegonmorais.com)

Construo sistemas de dados e de IA que chegam até a produção: da ingestão e do
processamento distribuído ao modelo servido, versionado e monitorado. Interesse
particular em **IA agêntica, LLMs, RAG e MCP**, e em decisões de projeto que sobrevivem
ao contato com a operação real. Fundador da **Mundo dos Dados BR**.

## Projetos em destaque

### [fraud-triage](https://github.com/diegoedataengineer/fraud-triage)
Triagem de fraude em transações de cartão de crédito. Em vez do classificador binário
usual, o modelo alimenta uma **política de três faixas** — aprovar, revisar, bloquear —
sujeita à capacidade real de revisão manual e construída sobre probabilidades
**explicitamente calibradas**. Traz a esteira completa: treino, versionamento,
API, console de operação e monitoramento, tudo em pé com um `docker compose up`.

`Python` · `scikit-learn` · `XGBoost` · `FastAPI` · `Docker` · `PostgreSQL`

### [atelie-generativo-lambe-lambe](https://github.com/diegoedataengineer/atelie-generativo-lambe-lambe)
Especialização do **Stable Diffusion v1-5** em um estilo visual próprio — a fotografia
lambe-lambe, o retrato vintage de estúdio — via **LoRA**, integrada a um pipeline
multimodal (LLM expande o prompt → difusor gera a imagem → TTS narra a descrição) e
publicada na web com Gradio.

`diffusers` · `peft` · `transformers` · `Gradio` · `Hugging Face`
· [Testar a aplicação](https://huggingface.co/spaces/lamble-lambe/atelie)

## Stack

| | |
|---|---|
| **IA / ML** | LLMs, RAG, MCP, agentes · scikit-learn, XGBoost, PyTorch, Hugging Face |
| **Dados** | Spark, Airflow, Iceberg · SQL, Python |
| **Plataforma** | AWS · Docker, CI/CD, MLOps · PostgreSQL |

## Contato

- Site: [diegonmorais.com](https://www.diegonmorais.com)
- GitHub: [@diegoedataengineer](https://github.com/diegoedataengineer)
