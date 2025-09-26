# 📖 Projeto Oráculo – Chat com Meus Dados  

🔗 **Acesse o aplicativo aqui:** [oraculochatbot.streamlit.app](https://oraculochatbot.streamlit.app/)  

O **Oráculo** é um projeto de inteligência artificial que permite criar uma interface de conversação interativa capaz de **conversar com seus próprios dados**.  
Com ele, você pode fazer perguntas e obter respostas baseadas em informações extraídas de **vídeos do YouTube, arquivos CSV, PDFs e TXT**, de forma simples e intuitiva.  

A proposta nasceu como uma pequena aplicação apresentada em redes sociais pelo professor Rodrigo e, devido ao grande interesse, foi expandida com novas funcionalidades e flexibilidade.  

---

## 🎯 Objetivo do Projeto

O **Oráculo** tem como objetivo mostrar, na prática, como construir um **chat inteligente** que não só responde perguntas, mas também **extrai informações úteis de diferentes fontes de dados**, utilizando modelos de linguagem (LLMs).  

Você pode escolher entre:  
- **Grok** (gratuito)  
- **OpenAI** (pago)  

Dessa forma, é possível personalizar a experiência de conversação de acordo com sua necessidade.  

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.11+**  
- **Streamlit** → Criação da interface web  
- **LangChain** → Conexão e orquestração de modelos de linguagem  
- **Document Loaders** → Carregamento de diferentes tipos de dados (CSV, PDF, TXT, YouTube)  
- **Modelos de Linguagem** (Grok ou OpenAI GPT)  

---

## 📚 O que foi desenvolvido passo a passo

### 1. Configuração do Ambiente  
Organizamos o ambiente de desenvolvimento com todas as dependências necessárias para rodar o projeto sem complicações.  

### 2. Desenvolvimento do WebApp em Streamlit  
Criamos uma interface simples e intuitiva com **sidebar**, onde o usuário pode:  
- Selecionar qual modelo de linguagem deseja utilizar (Grok ou OpenAI).  
- Carregar seus próprios arquivos (CSV, PDF, TXT).  
- Inserir links de vídeos do YouTube para análise.  

### 3. Integração com LangChain  
Conectamos os **LLMs** via LangChain, que faz o trabalho de manipular dados, criar embeddings e possibilitar uma conversação natural com as fontes carregadas.  

### 4. Document Loaders  
Implementamos loaders específicos para cada tipo de dado:  
- **YouTube** → Transcrição automática dos vídeos.  
- **CSV** → Interação com planilhas e tabelas.  
- **PDF** → Extração de texto de documentos.  
- **TXT** → Leitura e análise de arquivos simples.  

### 5. Construção da Chain de Conversação  
Criamos a lógica responsável por:  
- Receber as perguntas do usuário.  
- Processar os dados carregados.  
- Retornar respostas relevantes e contextuais.  

### 6. Finalização do Projeto  
Integramos todos os componentes, resultando em um **chat funcional** que conversa com diferentes tipos de dados.  

---

## 🚀 Deploy na Nuvem  
O projeto também foi publicado na **Streamlit Cloud**, permitindo que qualquer pessoa possa acessá-lo e utilizá-lo diretamente do navegador, sem precisar instalar nada localmente.  

---

## 🌟 Aprendizados

Com o **Projeto Oráculo**, aprendi/pratiquei:

✅ Criar aplicações de IA práticas e funcionais.  
✅ Usar o Streamlit para desenvolver interfaces simples e poderosas.  
✅ Integrar modelos de linguagem via LangChain.  
✅ Carregar e processar diferentes tipos de dados com document loaders.  
✅ Construir um fluxo completo de conversação com dados reais.  
✅ Fazer deploy de aplicações na **Streamlit Cloud**.  
