# Análise de Sazonalidade e Regressão

Este repositório contém códigos em Python para análise de sazonalidade e regressão em séries temporais. Os códigos estão organizados em diferentes notebooks para cada tarefa específica. A seguir, uma descrição de cada notebook presente neste repositório:

## Modo de usar:

1. Faça o download ou clone o repositório em seu ambiente local.
2. Certifique-se de ter o Python instalado em seu sistema.
3. Instale as bibliotecas necessárias mencionadas nos notebooks, como numpy, pandas, matplotlib, statsmodels, sklearn e seaborn. Você pode usar o gerenciador de pacotes pip para instalá-las. Por exemplo:
   
    ```
    pip install numpy pandas matplotlib statsmodels sklearn seaborn
    ```
    
5. Abra o ambiente Python de sua escolha, como Jupyter Notebook ou Google Colab.
6. Navegue até o diretório onde você baixou ou clonou o repositório.
7. Abra o notebook específico que deseja executar, por exemplo, "Sazonalidade.ipynb".
8. Antes de executar o código, certifique-se de ter os dados em uma planilha em formato Excel. Faça o upload do arquivo de dados no ambiente Python.
9. Siga as instruções detalhadas fornecidas no próprio notebook para realizar as análises de sazonalidade ou regressão.

## Dependências:

Certifique-se de ter as seguintes bibliotecas instaladas em seu ambiente Python:

- numpy
- pandas
- matplotlib
- statsmodels
- sklearn
- seaborn

Você pode instalá-las usando o comando pip install <nome_da_biblioteca>. Certifique-se de ter as versões mais recentes das bibliotecas para garantir a compatibilidade com os códigos fornecidos nos notebooks.

Além disso, os notebooks utilizam planilhas em formato Excel como fonte de dados. Certifique-se de ter os arquivos de dados em formato Excel prontos para serem carregados pelos notebooks.

## Sazonalidade.ipynb

Este notebook contém códigos para realizar a análise de sazonalidade em uma série temporal. Ele utiliza bibliotecas como numpy, pandas, matplotlib, statsmodels e sklearn para realizar as seguintes tarefas:

1. Carregar os dados de uma planilha em formato Excel.
2. Visualizar os dados e plotar gráficos.
3. Realizar decomposição da série temporal.
4. Verificar a estacionariedade dos dados.
5. Calcular a primeira diferença e verificar a estacionariedade novamente.
6. Plotar a função de autocorrelação.
7. Treinar e testar modelos de previsão usando regressão linear.
8. Avaliar o desempenho dos modelos.

## Sazonalidade_Proteina_Updated.ipynb

Este notebook também trata da análise de sazonalidade em séries temporais. Ele utiliza bibliotecas como numpy, pandas, matplotlib, seaborn e statsmodels para realizar as seguintes tarefas:

1. Carregar os dados de uma planilha em formato Excel.
2. Visualizar os dados e plotar gráficos.
3. Realizar decomposição da série temporal.
4. Verificar a estacionariedade dos dados.
5. Calcular a primeira diferença e verificar a estacionariedade novamente.
6. Plotar a função de autocorrelação.
7. Realizar previsões usando o método de Holt-Winters.

## Sazonalidade_Gordura_Updated.ipynb

Este notebook é semelhante ao anterior, mas analisa a sazonalidade em uma série temporal específica relacionada ao percentual de gordura. Ele utiliza as mesmas bibliotecas e métodos descritos no notebook anterior.

## Regressão_Linear_Updated.ipynb

Este notebook aborda o tema da regressão linear em séries temporais. Ele utiliza bibliotecas como numpy, pandas, matplotlib e seaborn para realizar as seguintes tarefas:

1. Carregar os dados de uma planilha em formato Excel.
2. Verificar os tipos de dados e tratar eventuais problemas.
3. Verificar a presença de valores nulos nos dados.
4. Calcular a matriz de correlação entre os atributos.
5. Dividir os dados em conjuntos de treinamento e teste.
6. Treinar um modelo de regressão linear e fazer previsões.
7. Avaliar o desempenho do modelo usando métricas como R², MAE, MSE e MAPE.

## Regressão_Updated.ipynb

Este notebook é semelhante ao anterior e também aborda o tema da regressão linear em séries temporais. Ele utiliza as mesmas bibliotecas e métodos descritos no notebook anterior.


Cada notebook contém uma descrição detalhada dos passos realizados em cada tarefa, bem como a visualização de gráficos e resultados. Os dados utilizados nos notebooks são carregados a partir de planilhas em formato Excel, sendo necessário fazer o upload dos arquivos antes de executar os códigos.
