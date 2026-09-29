# 🧠 Miniguia de Estudos: Professor Particular de Python (Back-end e Dados)

> Projeto desenvolvido como parte do Desafio de Projeto: **Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM** na [DIO](https://dio.me).

---

## 📌 Contexto e Objetivos

Este projeto utiliza o **NotebookLM** como um mentor e assistente técnico ("professor particular") para acelerar o aprendizado em Python, conectando a construção de APIs back-end com a manipulação e análise de dados.

- **Tema de interesse:** Desenvolvimento Python Back-end e Análise de Dados.
- **Objetivos de estudo:**
  - Compreender os fundamentos de APIs RESTful em Python.
  - Aprender a limpar, transformar e estruturar conjuntos de dados com Pandas.
  - Usar o NotebookLM para gerar resumos, analogias didáticas e perguntas de fixação.

---

## 📚 Curadoria de Fontes
Fontes abertas e oficiais selecionadas e enviadas ao NotebookLM como base de conhecimento:

1. [Python.org - Tutorial Oficial](https://docs.python.org/pt-br/3/tutorial/): Fundamentos da linguagem, tipos de dados e controle de fluxo.
2. [FastAPI Documentation - First Steps](https://fastapi.tiangolo.com/tutorial/first-steps/): Criação de endpoints, roteamento e requisições HTTP no back-end.
3. [Pandas Getting Started Tutorials](https://pandas.pydata.org/docs/getting_started/intro_tutorials/): Leitura, filtros e manipulação básica de DataFrames para análise de dados.

---

## 🧪 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

### Perguntas Estratégicas
- *"Explique como um endpoint FastAPI recebe um JSON de entrada e converte para um DataFrame do Pandas, usando uma analogia simples."*
- *"Quais são os erros mais comuns de iniciantes ao manipular colunas no Pandas e como evitá-los?"*

### Dificuldades e Ajustes (Troubleshooting / Cicatrizes)
- **Problema encontrado:** Ao pedir explicações de código muito longas, as respostas ficavam genéricas demais.
- **Ajuste realizado:** Refinei o prompt exigindo: *"Foque em apenas um exemplo de no máximo 15 linhas, explicando cada linha comentada"*. Isso tornou a explicação muito mais didática e fácil de fixar.

---

## 📖 Miniguia de Estudo (Entrega Final)

### 1. Resumos Estruturados
- **Back-end em Python:** Focado em criar servidores web que recebem requisições (GET, POST), processam a regra de negócio e retornam respostas estruturadas (geralmente JSON).
- **Análise de Dados:** Focada em coletar dados dispersos, realizar limpeza (tratar valores nulos) e extrair métricas ou estatísticas relevantes através de DataFrames.
- **A Conexão:** No mercado, o back-end frequentemente serve como a ponte para disponibilizar os modelos ou relatórios de dados para usuários e aplicações.

### 2. Glossário de Conceitos
- **API (Interface de Programação de Aplicações):** Conjunto de regras que permite que diferentes sistemas conversem entre si.
- **Endpoint:** O endereço/URL específico no back-end onde uma função ou recurso pode ser acessado.
- **DataFrame:** Estrutura bidimensional de dados em formato de tabela (linhas e colunas), amplamente usada no Pandas.
- **Grounding (Ancoragem):** Capacidade do NotebookLM de responder baseado estritamente nos documentos que você enviou, reduzindo alucinações.

### 3. Prompts Reutilizáveis para Revisão
- **Revisão rápida:** *"Faça um quiz de 3 perguntas de múltipla escolha sobre o uso do Pandas para testar meus conhecimentos."*
- **Explicação de erros:** *"Estou com o erro [nome do erro]. Com base nas fontes do caderno, qual é a provável causa e como resolvo?"*
- **Analogias:** *"Explique o conceito de [conceito] como se eu fosse um iniciante de 12 anos."*
