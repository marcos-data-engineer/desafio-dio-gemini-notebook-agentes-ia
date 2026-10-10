# 🧠 Segundo Cérebro com IA: Agentes de IA e Automação de Conteúdo Técnico

Este repositório documenta a criação do meu **Segundo Cérebro com IA** desenvolvido no **Gemini Notebook** (anteriormente NotebookLM) como parte do desafio prático da **DIO (Digital Innovation One)**.

---

## 🔗 Link do Caderno Compartilhado

- 🎓 [Agentes de IA e Automação de Conteúdo Técnico](https://gemini.google.com/notebook/ee7b447d-3d45-41d4-a6ed-45bd6d722a29)

---

## 🎯 Objetivo

> **Frase de Objetivo:** Construir um ecossistema autônomo de estudo e criação de conteúdo onde um agente de IA em Python cura feeds RSS, consulta o Gemini Notebook como base de conhecimento RAG e gera artigos técnicos fundamentados para blog e LinkedIn.

---

## 📚 Fontes Confiáveis Selecionadas

As fontes foram criteriosamente escolhidas para fundamentar a arquitetura e garantir exatidão técnica:

1. **Arquitetura do Agente Python (`agent.py`)**  
   - *Tipo:* Documentação e Código Fonte (Texto/Markdown)  
   - *Motivo da Escolha:* Define a estrutura de coleta via RSS, filtragem por relevância e geração de posts para o blog Jekyll (Chirpy).
2. **Guia de Integração Python & Gemini Notebook (API & RAG)**  
   - *Tipo:* Guia Técnico e Exemplos de Código (Texto/Markdown)  
   - *Motivo da Escolha:* Detalha como conectar o Gemini SDK via Python para consultar fragmentos do caderno (`retrieve_relevant_chunks`) e eliminar alucinações na geração de artigos.
3. **Documentação Oficial e Tutoriais da Gemini API / NotebookLM**  
   - *Tipo:* Artigo Técnico e Vídeo de Referência (Web/Vídeo)  
   - *Motivo da Escolha:* Garante conformidade com as diretrizes da API do Google Gemini e padrão de citações da ferramenta.

---

## 🤖 Diretriz de Comportamento do Notebook (System Persona)

A seguinte diretriz foi atribuída ao caderno para orientar o modelo:

> *"Comporte-se como um Especialista em Engenharia de Software, Agentes de IA em Python e Automação de Conteúdo Técnico. Suas respostas devem ser estritamente baseadas nas fontes fornecidas, citando trechos e referências exatas. Ajude na revisão de código, na estruturação de artigos técnicos para blog/LinkedIn e no design da arquitetura de agentes."*

---

## 💬 Perguntas, Respostas e Citações de Evidência

### Pergunta:
> **"Como o agente Python se integra ao Gemini Notebook e quais são os principais benefícios dessa abordagem?"**

**Resposta do Gemini Notebook:**  
O agente em Python integra-se ao Gemini Notebook atuando em duas frentes principais:
- **Alimentação Dinâmica:** O script Python envia novos artigos e documentações diretamente para o caderno, mantendo a base de conhecimento atualizada *(Fonte: Guia de Integração Python & Gemini Notebook)*.
- **Consultas RAG de Alta Precisão:** Antes de gerar um artigo para o blog ou post do LinkedIn, o script realiza consultas ao caderno via `retrieve_relevant_chunks` para extrair fatos comprovados e trechos de código *(Fonte: Guia de Integração Python & Gemini Notebook)*.

**Benefícios Identificados:**
- **Eliminação de alucinações:** O conteúdo é gerado estritamente com base em dados verificados no caderno *(Fonte: Guia de Integração Python & Gemini Notebook)*.
- **Rastreabilidade total:** Cada afirmação possui citação direta da fonte primária *(Fonte: Guia de Integração Python & Gemini Notebook)*.
- **Ciclo fechado de aprendizado:** Novos aprendizados do usuário enriquecem o caderno, que por sua vez capacita o agente de IA a criar conteúdos cada vez mais profundos e autênticos *(Fonte: Guia de Integração Python & Gemini Notebook)*.

---

## 🎨 Materiais de Estudo Gerados no Estúdio

Os seguintes artefatos foram gerados pelo caderno e estão armazenados neste repositório na pasta `/assets`:

- 🗺️ `assets/mapa_mental_agentes_ia.png` — Visualização gráfica do fluxo entre RSS, Agente Python, Gemini Notebook e Blog/LinkedIn.
- 📊 `assets/slides_arquitetura_agente.pdf` — Apresentação executiva da arquitetura do projeto.
- 📝 `assets/guia_de_estudos_quiz.md` — Guia interativo contendo perguntas e respostas para testar o aprendizado.
- 📸 `assets/print_chat_citacoes.png` — Captura de tela demonstrando as respostas do chat com as devidas citações de fontes.

---

## 🚀 Como Executar e Reproduzir

1. Acesse o caderno compartilhado: 🎓 [Agentes de IA e Automação de Conteúdo Técnico](https://gemini.google.com/notebook/ee7b447d-3d45-41d4-a6ed-45bd6d722a29).
2. Adicione ou atualize suas fontes de estudo no painel esquerdo.
3. Utilize o script em Python (`agent.py`) configurado com sua `GEMINI_API_KEY` para realizar consultas RAG automáticas via API.
