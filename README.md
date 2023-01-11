# Dracula: a brief analysis to the most common words in Dracula, by Bram Stoker

This notebook is also available in Dev Community, both [portuguese](https://dev.to/geazi_anc/pyspark-uma-breve-analise-das-palavras-mais-comuns-em-dracula-por-bram-stoker-4an3) and [english](https://dev.to/geazi_anc/pyspark-a-brief-analysis-to-the-most-common-words-in-dracula-by-bram-stoker-1ij4) 🌎.

Check this notebook out in [english](https://github.com/geazi-anc/dracula/blob/main/A%20brief%20analysis%20to%20the%20most%20common%20words%20in%20Dracula%2C%20by%20Bram%20Stoker.ipynb) 😉.

---

Este notebook também está disponível em forma de artigo no Dev Community, tanto em [português](https://dev.to/geazi_anc/pyspark-uma-breve-analise-das-palavras-mais-comuns-em-dracula-por-bram-stoker-4an3) como em [inglês](https://dev.to/geazi_anc/pyspark-a-brief-analysis-to-the-most-common-words-in-dracula-by-bram-stoker-1ij4) 🌎.

Confira esse notebook em [português](https://github.com/geazi-anc/dracula/blob/main/Uma_breve_an%C3%A1lise_das_palavras_mais_comuns_em_Dr%C3%A1cula%2C_por_Bram_Stoker.ipynb) 😉.

---

## 💻 Sobre o projeto

Considerado como um marco da literatura gótica, o icônico livro Drácula, escrito em 1897 por Bram Stoker, desperta até hoje o fascínio das pessoas por todo o mundo. A fim de consolidar os conhecimentos iniciais do Apache Spark, desenvolveu-se este notebook para analisar as principais palavras mais comuns encontradas neste clássico livro.

O processo de análise consiste nas seguintes etapas:

1. Download do livro Drácula, por Bram Stoker;
2. Inicialização do Apache Spark e leitura do livro;
3. Download das stopwords encontradas no idioma inglês;
4. Extração individual das palavras em cada uma das linhas;
5. Explodindo a lista de palavras em colunas no DataFrame;
6. Transformando todas as palavras em minúsculas;
7. Eliminação de pontuação;
8. Remoção de valores nulos;
9. Remoção das stopwords;
10. Análise das palavras mais comuns;

## 🛠 Tecnologias

A análise foi desenvolvida com a linguagem python, utilizando o Jupyter Notebook no Google Colab, assim como a biblioteca PySpark para a limpesa e análise dos dados.
