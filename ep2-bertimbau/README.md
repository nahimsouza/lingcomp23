# EP2 - MAC5725 - Linguística Computacional

### Transformers, Regressão e Quantização

> **IMPORTANTE:**  Este trabalho foi feito **para fins pedagógicos**, os resultados descritos aqui **não** devem ser considerados como referência para outras finalidades, pois **podem conter erros**.

O objetivo deste trabalho é avaliar o desempenho do modelo de linguagem BERTimbau em tarefas de regressão e classificação, a partir de sentenças em língua portuguesa. A descrição completa do enunciado está em: [ep2.pdf](ep2.pdf).

Um artigo/relatório descrevendo o problema e as etapas do projeto está em: [artigo-relatorio-ep2.pdf](artigo-relatorio-ep2.pdf).

### Sobre a implementação

- O código fonte do trabalho está no ipynb em `src/ep2_lingcomp.ipynb`

- Recomenda-se utlilizar o Google Collab ou alguma plataforma semelhante para executá-lo (IMPORTANTE: um ambiente com GPU T4 foi utilizado originalmente)

- O ipynb contém as saídas da última execução no Google Collab

- Todas as etapas: pré-processamento, treinamento e teste estão neste único arquivo ipynb, que contém descrições sobre cada etapa de execução

- O córpus utilizado foi a versão com 10 mil amostras, disponível em: https://github.com/alan-barzilay/NLPortugues/raw/master/Semana%2003/data/b2w-10k.csv (mesmo arquivo que está na pasta `data/b2w-full.csv`)

- Devido ao arquivo ipynb ter sido rodado no Google Collab, há algumas linhas para instalar as bibliotecas necessárias e baixar o base de dados


