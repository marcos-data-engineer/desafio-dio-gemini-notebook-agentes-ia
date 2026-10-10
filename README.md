# 🧠 Segundo Cérebro com IA: Agentes de IA e Automação de Conteúdo Técnico

Este repositório documenta a criação do meu **Segundo Cérebro com IA** desenvolvido no **Gemini Notebook** (anteriormente NotebookLM) como parte do desafio prático da **DIO (Digital Innovation One)**.

---

## 🎯 Objetivo

> **Frase de Objetivo:** Construir um ecossistema autônomo de estudo e criação de conteúdo onde um agente de IA em Python cura feeds RSS, consulta o Gemini Notebook como base de conhecimento RAG e gera artigos técnicos fundamentados para blog e LinkedIn.

---

## 📚 Fontes Confiáveis Selecionadas

As fontes foram criteriosamente escolhidas para fundamentar a arquitetura e garantir exatidão técnica:

1. **Arquitetura do Agente Python (`agent.py`)**  
   - *Tipo:* Documentação e Código Fonte (Texto/Markdown)[cite: 1]  
   - *Motivo da Escolha:* Define a estrutura de coleta via RSS, filtragem por relevância e geração de posts para o blog Jekyll (Chirpy)[cite: 1].
2. **Guia de Integração Python & Gemini Notebook (API & RAG)**  
   - *Tipo:* Guia Técnico e Exemplos de Código (Texto/Markdown)[cite: 2]  
   - *Motivo da Escolha:* Detalha como conectar o Gemini SDK via Python para consultar fragmentos do caderno (`retrieve_relevant_chunks`) e eliminar alucinações na geração de artigos[cite: 2].
3. **Documentação Oficial e Tutoriais da Gemini API / NotebookLM**  
   - *Tipo:* Artigo Técnico e Vídeo de Referência (Web/Vídeo)  
   - *Motivo da Escolha:* Garante conformidade com as diretrizes da API do Google Gemini e padrão de citações da ferramenta.

---

## 🤖 Diretriz de Comportamento do Notebook (System Persona)

A seguinte diretriz foi atribuída ao caderno para orientar o modelo:

> *"Comporte-se como um Especialista em Engenharia de Software, Agentes de IA em Python e Automação de Conteúdo Técnico. Suas respostas devem ser estritamente baseadas nas fontes fornecidas, citando trechos e referências exatas. Ajude na revisão de código, na estruturação de artigos técnicos para blog/LinkedIn e no design da arquitetura de agentes."*

---

## 💬 Perguntas, Respostas e Citações de Evidência

### Pergunta 1:
> **"Como o agente Python se integra ao Gemini Notebook e quais são os principais benefícios dessa abordagem?"**

**Resposta do Gemini Notebook:**  
O agente em Python integra-se ao Gemini Notebook atuando em duas frentes principais[cite: 2]:
- **Alimentação Dinâmica:** O script Python envia novos artigos e documentações diretamente para o caderno mantendo a base de conhecimento atualizada[cite: 2].
- **Consultas RAG de Alta Precisão:** Antes de gerar um artigo para o blog ou post do LinkedIn, o script realiza consultas ao caderno (`retrieve_relevant_chunks`) para extrair fatos comprovados e trechos de código[cite: 2].

Os principais benefícios incluem a **eliminação de alucinações** (conteúdo gerado estritamente com base nos dados verificados)[cite: 2], **rastreabilidade total** com citação das fontes originais[cite: 2] e um **ciclo fechado de aprendizado**, onde novos conhecimentos enriquecem a base de dados do agente[cite: 2].

---

## 🎨 Materiais de Estudo Gerados no Estúdio

Os seguintes artefatos foram gerados pelo caderno e estão armazenados neste repositório na pasta `/assets`:

- 🗺️ `mapa_mental_agentes_ia.png` — Visualização gráfica do fluxo entre RSS, Agente Python, Gemini Notebook e Blog/LinkedIn.
- 📊 `slides_arquitetura_agente.pdf` — Apresentação executiva da arquitetura do projeto.
- 📝 `guia_de_estudos_quiz.md` — Guia interativo contendo perguntas e respostas para testar o aprendizado.
- 🎧 `podcast_resumo_executivo.mp3` — Resumo em áudio sobre o papel dos agentes de IA na automação de conteúdo.

---

## 🔗 Link do Caderno Compartilhado

- 🎓 **Gemini Notebook:** [Acessar Caderno Especialista](https://gemini.google.com/notebook/ee7b447d-3d45-41d4-a6ed-45bd6d722a29)
