# 🧠 Segundo Cérebro com IA: Agentes de IA e Automação de Conteúdo Técnico

Este repositório documenta a criação do meu **Segundo Cérebro com IA** desenvolvido no **Gemini Notebook** (anteriormente NotebookLM) como projeto prático para o desafio da **DIO (Digital Innovation One)**. 

O projeto une pesquisa avançada em Inteligência Artificial, curadoria de fontes de alta confiabilidade e geração de conteúdo técnico totalmente fundamentado e livre de alucinações.

---

## 🔗 Link do Caderno Compartilhado

- 🎓 **Gemini Notebook:** [Agentes de IA e Automação de Conteúdo Técnico](https://gemini.google.com/notebook/ee7b447d-3d45-41d4-a6ed-45bd6d722a29)

---

## 🎯 Objetivo

> **Objetivo:** Construir um ecossistema autônomo de estudo e criação de conteúdo onde um agente de IA em Python cura feeds RSS, consulta o Gemini Notebook como base de conhecimento RAG e gera artigos técnicos fundamentados para blog e LinkedIn.

---

## 📚 Fontes Confiáveis Selecionadas

As fontes inseridas no caderno foram selecionadas com base em rigor científico, autoridade técnica e diversidade de formatos:

1. **OpenAI — Planning for AGI and Beyond (Artigo / Documentação)**  
   - *Motivo:* Define o panorama e as visões estratégicas sobre a evolução e governança da AGI.
2. **Yann LeCun / Meta AI — World Models & JEPA (Palestras & Artigos Técnicos)**  
   - *Motivo:* Apresenta a crítica fundamentada ao *scaling laws* em LLMs e introduz as arquiteturas baseadas em modelos de mundo (*Joint Embedding Predictive Architecture*).
3. **ArXiv AI / Feeds de Pesquisa (Artigos Científicos em RSS)**  
   - *Motivo:* Prover dados atualizados sobre aprendizado por reforço, otimização e robótica.
4. **Arquitetura do Agente Python (`agent.py`) & Guia RAG com Gemini SDK (Código & Markdown)**  
   - *Motivo:* Documentação interna do pipeline que integra o script Python ao Gemini Notebook via chamadas de API (`retrieve_relevant_chunks`).

---

## 🤖 Diretriz de Comportamento do Notebook (System Persona)

> *"Comporte-se como um Engenheiro de Dados e Pesquisador Especialista em Inteligência Artificial. Suas respostas devem ser estritamente baseadas nas fontes fornecidas, citando trechos e referências exatas. Ajude na revisão de código, na estruturação de artigos técnicos para blog/LinkedIn e no design de arquiteturas de agentes autônomos."*

---

## 📝 Prompt Utilizado para Geração do Artigo Técnico

```text
Atue como um Engenheiro de Dados e Pesquisador Especialista em Inteligência Artificial. Elabore um artigo técnico completo, aprofundado e visualmente atraente sobre o tema: "A Ilusão da Inteligência: O Que Realmente Separa os LLMs da AGI Real?".

Gere todo o conteúdo formatado em Markdown, estruturado exatamente como deve ser salvo no arquivo `LLMtoAGI.md`.

Instruções e Estrutura para o Arquivo `LLMtoAGI.md`:

1. Front Matter / Cabeçalho YAML (Compatível com Jekyll/Chirpy):
   - Inclua título, data no formato YYYY-MM-DD, autor, categorias, tags e um resumo executivo chamativo com emojis.

2. Recursos Visuais e Formatação:
   - Utilize emojis estratégicos nos títulos e tópicos para enriquecer a leitura.
   - Insira placeholders de imagens e diagramas em sintaxe Markdown.
   - Crie uma tabela comparativa detalhada confrontando "LLMs Atuais (Predictive Text)" vs. "Sistemas AGI Reais".

3. Seções Obrigatórias do Artigo:
   - 📌 Introdução: A febre dos LLMs e a falsa percepção de que o aumento de escala (scaling laws) por si só nos levará à AGI.
   - 🎲 O Papagaio Estocástico: Como a previsão de próximo token cria a "ilusão de raciocínio" sem real compreensão conceitual.
   - 🏗️ Os Pilares Faltantes para a AGI: Raciocínio Causal, World Models (JEPA), Aprendizado Contínuo e Eficiência Energética.
   - 🚀 Caminhos Promissores: Arquiteturas Neuro-Simbólicas, Raciocínio do Tipo "Sistema 2" e Orquestração por Agentes (Harness & RAG).
   - 🏁 Conclusão: O horizonte real para a AGI e o impacto esperado na engenharia de software.

4. Citações e Fundamentação:
   - Insira citações explícitas entre colchetes [Fonte: Nome da Fonte / Pesquisa] ao longo dos tópicos para demonstrar fundamentação nas fontes.
