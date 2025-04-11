## 📘 Sobre o repositório `llm-testes`

Este repositório contém notebooks desenvolvidos para estudos e experimentações com modelos de linguagem (LLMs) e agentes inteligentes.

### 🤖 Destaque: `Agents.ipynb`

O notebook `Agents.ipynb` explora o uso de agentes com o framework [LangChain](https://www.langchain.com/), aplicando conceitos avançados de RAG (Retrieval-Augmented Generation). O agente é configurado com duas ferramentas personalizadas, ambas implementadas como RAGs:

- **RAG 1**: Responsável por buscar informações sobre o Grande Prêmio de Abu Dhabi de 2024 no site [StatsF1](https://www.statsf1.com).
- **RAG 2**: Realiza a recuperação de dados sobre o circuito de Yas Marina no site [Racing Circuits](https://www.racingcircuits.info).

Ao final do notebook, são apresentados exemplos de perguntas para avaliar a performance do agente, analisando sua capacidade de identificar a fonte de informação mais adequada para cada requisição do usuário.

### 🎯 Objetivo

Este projeto demonstra habilidades práticas na integração de LLMs com pipelines de recuperação de informação, além de reforçar conhecimentos em:

- Construção de agentes inteligentes com LangChain  
- Implementação de RAGs personalizados  
- Engenharia de prompts para testes controlados  
- Aplicação de conceitos de NLP e IA em cenários reais
