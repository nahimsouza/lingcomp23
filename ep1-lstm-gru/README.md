# EP1 - MAC5725 - Linguística Computacional

### RNNs, LSTMs e GRUs

> **IMPORTANTE:**  Este trabalho foi feito **para fins pedagógicos**, os resultados descritos aqui **não** devem ser considerados como referência para outras finalidades, pois **podem conter erros**.

O objetivo deste trabalho é avaliar o desempenho das redes neurais recorrentes LSTM e GRU na classificação de *reviews* em língua portuguesa. A descrição completa do enunciado está em: [ep1.pdf](ep1.pdf).

Um artigo/relatório descrevendo o problema e as etapas do projeto está em: [artigo-relatorio-ep1.pdf](artigo-relatorio-ep1.pdf).

### Sobre a implementação

O código está está disponível no arquivo `src/code_ep1.ipynb`

- Originalmente, ele foi preparado na plataforma Google Colab

- Para executá-lo online, basta importar o arquivo .ipynb e executá-lo

- Para executá-lo localmente, é necessário ter o ambiente preparado com as bibliotecas necessárias: tensorflow, pandas, numpy e matplotlib

Os dados do corpus de treinamento são baixados pelo próprio código e guardados em `data/b2w-full.csv`

- Se necessário, os dados podem ser baixados manualmente e colocados nesse mesmo caminho

- Para salvar os arquivos em outro caminho, basta alterar o caminho para o arquivo, no início do python notebook

Os parâmetros de execução estão definidos no início do python notebook, e podem ser modificados conforme a necessidade:

```python
    # Caminho para download do corpus B2W
    B2W_CORPUS_SRC = "https://raw.githubusercontent.com/americanas-tech/b2w-reviews01/main/B2W-Reviews01.csv"
    B2W_CORPUS_DEST = "data/b2w-full.csv"

    # Proporção de treino, validação e teste.
    TRAIN_SIZE = 0.75
    VALIDATION_SIZE = 0.10
    TEST_SIZE = 0.15

    # Caminho para os arquivos de treino, validação e teste.
    TRAIN_CSV = "data/b2w_train.csv"
    VALIDATION_CSV = "data/b2w_validation.csv"
    TEST_CSV = "data/b2w_test.csv"

    # Tamanho das sentenças.
    BATCH_SIZE = 64

    # Habilita balanceamento dos dados.
    BALANCE_ENABLED = True

    # Tamanho do vocabulário para vetorização (max_tokens).
    VOCAB_SIZE = 600
```



