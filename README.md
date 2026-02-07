# 📄🤖 Desafio — Criando um Chatbot Baseado em Conteúdo de PDFs com Azure AI Foundry

> Projeto desenvolvido como parte de um desafio prático, utilizando Azure AI Foundry, IA Generativa, embeddings e busca vetorial para criação de um chatbot capaz de responder perguntas com base em documentos PDF.

---

## 🚀 Visão Geral

Neste projeto, foi desenvolvido um chat interativo que responde perguntas utilizando como base o conteúdo de arquivos PDF previamente carregados.

A solução foi construída sobre o Azure AI Foundry, explorando serviços de IA generativa e vetorização de conteúdo para implementar uma arquitetura RAG (Retrieval Augmented Generation).

São utilizados conceitos modernos de Inteligência Artificial, como:

- Embeddings
- Busca vetorial (Vector Search)
- Recuperação de contexto (RAG – Retrieval Augmented Generation)
- Modelos de linguagem (LLMs)
- Integração com serviços do Azure

O objetivo é criar um **assistente virtual personalizado**, capaz de interpretar documentos específicos e gerar respostas contextuais, sem depender apenas do conhecimento genérico de modelos pré-treinados.

---

## 🧠 Cenário

Imagine um estudante de Engenharia de Software preparando seu TCC e lidando com diversos artigos científicos em PDF.

Com o aumento da quantidade de documentos, torna-se difícil:

- Localizar informações relevantes  
- Relacionar ideias entre textos  
- Extrair rapidamente conceitos importantes  

Para resolver isso, foi criado um sistema inteligente baseado no Azure AI Foundry que:

✅ Lê PDFs  
✅ Converte o conteúdo em vetores  
✅ Indexa as informações em uma base vetorial  
✅ Responde perguntas usando IA generativa  

Essa abordagem permite criar um modelo de assistência virtual focado em informações proprietárias, utilizando infraestrutura de nuvem e recursos avançados de IA.

---

## 🎯 Objetivo do Projeto

O objetivo deste projeto é permitir que você:

✅ Carregue arquivos PDF contendo informações relevantes para seu estudo ou projeto  
✅ Implemente um sistema de busca vetorial para indexar e recuperar informações dos PDFs  
✅ Utilize inteligência artificial do Azure AI Foundry para gerar respostas baseadas no conteúdo dos documentos carregados  
✅ Desenvolva um chat interativo onde seja possível realizar perguntas e obter respostas contextuais fundamentadas nos arquivos  
✅ Aplique na prática conceitos de RAG, embeddings e integração com modelos de linguagem  

Além disso, o projeto busca demonstrar como conectar IA generativa a dados próprios, criando soluções reais como:

- Assistentes acadêmicos  
- Bots corporativos  
- Sistemas inteligentes de consulta documental  


## ⚙️ Como Funciona

Este projeto foi desenvolvido com base no **Azure AI Foundry**, utilizando serviços de IA generativa e busca vetorial para construir um fluxo completo de RAG (Retrieval Augmented Generation).

Tecnologias envolvidas:

- Azure AI Foundry  
- Azure OpenAI (LLMs e embeddings)  
- Busca vetorial (Vector Search)  
- Python  
- Processamento de documentos (PDF/Text Loader)  
- Chunking de texto  
- Arquitetura RAG  

Fluxo de funcionamento:

1. Os documentos são carregados  
2. O texto é dividido em pequenos blocos  
3. Cada bloco é convertido em embeddings  
4. Os vetores são armazenados em uma base vetorial  
5. Ao fazer uma pergunta:  
   - O sistema busca os trechos mais relevantes  
   - Envia esse contexto ao modelo de IA  
   - Gera uma resposta baseada exclusivamente nos documentos  

Esse processo é conhecido como **RAG (Retrieval Augmented Generation)**.

---

## 🧪 Exemplo de Uso

Pergunta:

> O que é engenharia de software?

Resposta:

> Engenharia de software é uma disciplina que aplica princípios de engenharia ao desenvolvimento, manutenção e evolução de sistemas de software...

*(Resposta gerada exclusivamente a partir dos documentos carregados.)*

---

## 💡 Principais Aprendizados

Durante o desenvolvimento deste projeto:

- Como funcionam embeddings na prática  
- Diferença entre busca tradicional e busca vetorial  
- Como implementar RAG usando Azure AI Foundry  
- Importância do chunking para qualidade das respostas  
- Como conectar IA generativa com dados proprietários  
- Integração entre modelos de linguagem e bases vetoriais  
- Estruturação de projetos voltados para IA aplicada  

---

## 🔮 Possibilidades de Evolução

Algumas melhorias futuras:

- Interface web com Streamlit ou Gradio  
- Suporte a múltiplos PDFs simultaneamente  
- Histórico de conversas  
- Upload direto de arquivos  
- Respostas com referências de páginas  
- Deploy em nuvem  
- Autenticação de usuários  
- Persistência de vetores em serviços gerenciados do Azure  

---

## 🏁 Conclusão

Este projeto demonstra como é possível criar soluções inteligentes capazes de interpretar documentos reais e gerar respostas contextuais utilizando Azure AI Foundry, abrindo caminho para aplicações como:

- Assistentes acadêmicos  
- Bots corporativos  
- Sistemas de FAQ inteligentes  
- Análise documental automatizada  
