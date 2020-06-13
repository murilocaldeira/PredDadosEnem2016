##  Aplicação "PredDadosEnem2016" é um Data App utilizado para exibir a solução de Machine Learning para a predição de valores da nota de matemática dos alunos participantes do ENEM 2016

Projeto desenvolvido para ingresso no desafio **Acelera DEV de Data Science da CodeNation**, com esse código obtive 93% de acertos e consegui minha vaga. 

Com base nos seguintes datasets, que mostram os dados dos alunos participantes do enem 2016:

def get_data_train():
    return pd.read_csv("model/train_tratado.csv")

def get_data_test():
  return pd.read_csv("model/test.csv")

Foi analisado o dataset e excluídas as colunas com alta correlação entre si e sem relação com a variável alvo assim como as colunas com alta ocorrência de valores faltantes. Após isso, para predição foram testados mais 3 métodos de machine learning, utilizando a métrica RMSE com os valores reais da base. 

## 🛠 Algoritmos testados:

- [Regressão Linear]

- [Árvore de Decisão]

- [Random Forest]

Utilizado então o Random Forest para realizar a predição, pois foi o algoritmo mais preciso.

Nesta solução está o DATASET dentro da pasta modele também o DATASET para testes. 

## 🚀 Para executar, utilizei o Jupyter diretamente no Google Colab, bastando copiar todos arquivos desta solução e rodar os comandos Python na ordem em que estão.

No final, as predições serão armazenadas no arquivo answer.csv





