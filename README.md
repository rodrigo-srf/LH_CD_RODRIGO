## 🎬 Desafio Indicium Hollywood Data Analytics - Análise Cinematográfica para a PProductions

-----

### **📋 Sobre o Projeto**

Este projeto é um desafio técnico para a vaga de Cientista de Dados na Indicium. O objetivo principal é atuar como consultor(a) para a PProductions, um estúdio de Hollywood, e utilizar análise de dados e machine learning para orientar a empresa sobre qual tipo de filme deve ser desenvolvido em seguida para alcançar um alto faturamento.

### **🎯 Objetivo Principal**

Realizar uma análise aprofundada de um banco de dados cinematográfico, identificando os principais fatores de sucesso para a criação de um modelo preditivo e fornecendo uma recomendação de negócio detalhada e bem fundamentada.

### **🏆 Contexto do Desafio**

  * **Empresa Contratante:** Indicium
  * **Cliente:** Estúdio PProductions (Hollywood)
  * **Desafio:** Análise e Recomendação de Filme
  * **Carreira:** Cientista de Dados
  * **Requisito:** Aptidão para resolução de problemas e aplicação de modelos preditivos.

-----

### **✨ Entregas e Características Principais**

  * **Análise Exploratória de Dados (EDA):** Demonstrar as principais características das variáveis, identificar correlações e apresentar hipóteses.
  * **Recomendação de Filme:** Sugerir um filme com base na análise.
  * **Fatores de Faturamento:** Identificar os principais elementos que levam a um alto faturamento (`Gross`).
  * **Análise de Texto (`Overview`):** Explorar a coluna de sinopse para extrair insights e inferir o gênero do filme.
  * **Previsão do `IMDB_Rating`:** Construir um modelo preditivo para estimar a nota do IMDB com base nas outras variáveis.
  * **Boas Práticas:** Seguir boas práticas de codificação e estruturação de projetos.

### **🏗️ Arquitetura Técnica**

**Tecnologias Utilizadas**

  * **Linguagem:** Python
  * **Notebooks:** Jupyter Notebook ou Google Colab
  * **Bibliotecas:** Pandas, Scikit-learn, Matplotlib/Seaborn, NLTK (para análise de texto)
  * **Armazenamento de Modelo:** Formato `.pkl`

**Estrutura do Projeto**

```
PProductions_Data_Analytics/
├── README.md              # Documentação do projeto
├── requirements.txt       # Dependências Python
├── analysis/              # Relatórios das análises (PDF, Notebooks)
│   └── eda_report.ipynb
│   └── model_report.ipynb
├── model/                 # Arquivos de modelo
│   └── predictive_model.pkl
└── src/                   # Códigos auxiliares (se houver)
    └── data_preprocessing.py
```

-----

### **🚀 Como Executar**

1.  **Pré-requisitos:**
      * Python 3.8+ instalado.
      * Acesso a um ambiente de execução de notebooks (Jupyter, Colab).
2.  **Instalação:**
      * Clone o repositório.
      * Instale as dependências: `pip install -r requirements.txt`.
3.  **Execução:**
      * Abra o Jupyter Notebook ou Colab e execute os arquivos de análise na pasta `analysis/`.

-----

### **⚠️ Aviso Legal**

Este projeto é uma avaliação de habilidades técnicas. A utilização de **Inteligência Artificial (IA)** ou **Plágio** para a resolução do desafio implica desclassificação imediata, pois a Indicium valoriza a autenticidade e o raciocínio individual.

### **📄 Dicionário dos Dados**

A base de dados de treinamento contém 15 colunas, com os seguintes dados:

  * `Series_Title` – Nome do filme
  * `Released_Year` - Ano de lançamento
  * `Certificate` - Classificação etária
  * `Runtime` – Tempo de duração
  * `Genre` - Gênero
  * `IMDB_Rating` - Nota do IMDB
  * `Overview` - Overview do filme
  * `Meta_score` - Média ponderada de todas as críticas
  * `Director` – Diretor
  * `Star1` - Ator/atriz \#1
  * `Star2` - Ator/atriz \#2
  * `Star3` - Ator/atriz \#3
  * `Star4` - Ator/atriz \#4
  * `No_of_Votes` - Número de votos
  * `Gross` - Faturamento
