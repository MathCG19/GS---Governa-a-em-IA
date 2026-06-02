# 🌍 Global Solution 2026.1 — Monitoramento de Risco Ambiental com IA

**FIAP · 2TIAP · 1º Semestre de 2026**  
**Disciplina:** Governança em IA e Business Analytics

> Solução integrada de monitoramento de risco ambiental utilizando dados satelitais, sensores locais e múltiplos módulos de inteligência artificial.

---

## 👥 Integrantes

| Nome | RM |
|---|---|
| Matheus Cardoso | 564898 |
| Caique Sousa | 563621 |

---

## 🎥 Vídeo de Apresentação

[![YouTube](https://img.shields.io/badge/YouTube-Assistir-red?logo=youtube)](https://www.youtube.com/watch?v=Kv1LY0qPxwY)

---

## 📌 Sobre o Projeto

Este repositório reúne todos os módulos desenvolvidos ao longo do semestre para o **Global Solution 2026.1**. A solução gira em torno de um problema comum: **monitoramento de risco ambiental com dados satelitais e sensores locais**, conectando diferentes tecnologias de IA em uma pipeline integrada.

O fluxo parte da coleta de dados brutos (sensores de borda e IoT), passa pela classificação de risco (visão computacional e computação quântica), é orquestrado pelo módulo de RPA e apresentado em um dashboard interativo com assistentes RAG de consulta.

---

## 🗂️ Estrutura do Repositório

```
GS2026_GlobalSolution/
├── README.md
├── docs/
│   └── GS2026_Integracao.pdf
├── visao-computacional/
├── computacao-quantica/
├── computacao-neuroморfica/
├── iot-esp32/
├── nlp-rag-espacial/
├── ia-generativa-edificios/
├── ai-for-rpa/
└── dashboard/
```

---

## 🧩 Módulos

### 🔬 Visão Computacional
**Disciplina:** Visão Computacional  
Modelo de classificação de imagens de satélite para identificar áreas com risco de incêndio florestal. Utiliza o Wildfire Prediction Dataset (Kaggle) com ~42 mil imagens nas classes *Wildfire* e *No Wildfire*.  
`📁 visao-computacional/` · **ODS 13**

---

### ⚛️ Computação Quântica e IA
**Disciplina:** Computação Quântica e IA  
Implementação de Quantum Machine Learning (QML) com Qiskit 1.x (QSVC ou VQC) comparado a baselines clássicos (SVM, Random Forest) usando AUC-ROC, F1-score e tempo de treino.  
`📁 computacao-quantica/` · **ODS 9**

---

### 🧠 Computação Neuromórfica
**Disciplina:** Computação Neuromórfica  
Protótipo de sensor neuromórfico de baixo consumo com memória memristiva virtual e limiar de disparo, para detecção de condições críticas (temperatura, radiação, poeira) na camada de borda.  
`📁 computacao-neuroморfica/` · **ODS 9**

---

### 📡 IoT — Physical Computing e Cognitive IoT
**Disciplina:** Physical Computing, Embedded AI, Robotics e Cognitive IoT  
Solução IoT com ESP32, sensores ambientais, protocolo MQTT, dashboard em nuvem e notificações via Telegram.  
`📁 iot-esp32/` · **ODS 11**

---

### 💬 NLP / RAG — Assistente Espacial
**Disciplina:** Inteligência Artificial Generativa  
Assistente inteligente com arquitetura RAG para responder perguntas sobre relatórios da NASA, ESA e dados de monitoramento ambiental, com geração de embeddings e vector store.  
`📁 nlp-rag-espacial/` · **ODS 13**

---

### 🏢 IA Generativa — RAG Edifícios Verdes
**Disciplina:** NLP e Modelos de Linguagem  
Assistente técnico especializado em edifícios verdes e Net Zero (eficiência energética, reúso de água, LEED, AQUA-HQE) com LLM local e banco vetorial persistente.  
`📁 ia-generativa-edificios/` · **ODS 11**

---

### 🤖 AI for RPA
**Disciplina:** AI for RPA — Robotic Process Automation  
Orquestrador da pipeline de dados: coleta dados brutos, aciona os modelos de classificação, consolida resultados e gera outputs estruturados para o dashboard de forma automatizada.  
`📁 ai-for-rpa/` · **ODS 9**

---

### 📊 Dashboard — Front-end
**Disciplina:** Front-end e Mobile Development em Sistemas de IA  
Dashboard interativo em Streamlit com filtros, gráficos Plotly e componente de feedback humano. Interface central que reúne todos os módulos em um único painel.  
`📁 dashboard/` · **ODS 11**

---

## 🌱 ODS da ONU Atendidos

| ODS | Módulos |
|---|---|
| ODS 2 — Fome zero e agricultura sustentável | Visão Computacional, IoT, Front-end |
| ODS 9 — Indústria, inovação e infraestrutura | Computação Quântica, Neuromórfica, RPA |
| ODS 11 — Cidades e comunidades sustentáveis | IoT, IA Generativa, Governança |
| ODS 13 — Ação contra a mudança global do clima | Visão Computacional, NLP/RAG, Front-end |

---

## 📄 Documentação

O documento completo de integração dos módulos está disponível em [`docs/GS2026_Integracao.pdf`](docs/GS2026_Integracao.pdf).
