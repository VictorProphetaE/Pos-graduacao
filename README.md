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

Este notebook demonstra a aplicação da regressão linear simples em um conjunto de dados. Ele contém os seguintes passos:

1. Carregamento dos dados de um arquivo Excel.
2. Análise exploratória dos dados, incluindo a visualização de histogramas e a matriz de correlação.
3. Pré-processamento dos dados, incluindo a transformação de atributos e normalização.
4. Divisão dos dados em conjuntos de treinamento e teste.
5. Treinamento do modelo de regressão linear.
6. Avaliação do modelo usando métricas de desempenho, como erro médio absoluto, erro quadrático médio e acurácia.

## Regressão_Updated.ipynb

Este notebook mostra a aplicação da regressão linear múltipla em um conjunto de dados com múltiplos atributos. Ele segue uma abordagem semelhante ao notebook anterior e inclui os seguintes passos:

1. Carregamento dos dados de um arquivo Excel.
2. Manipulação de dados ausentes usando a estratégia da média.
3. Normalização dos dados usando a escala mínima-máxima.
4. Divisão dos dados em conjuntos de treinamento e teste.
5. Treinamento do modelo de regressão linear para prever diferentes variáveis dependentes.
6. Avaliação do modelo usando métricas de desempenho, como erro médio absoluto, erro quadrático médio e validação cruzada.

Os notebooks também incluem visualizações gráficas para ajudar na compreensão dos dados e resultados.

Cada notebook contém uma descrição detalhada dos passos realizados em cada tarefa, bem como a visualização de gráficos e resultados. Os dados utilizados nos notebooks são carregados a partir de planilhas em formato Excel, sendo necessário fazer o upload dos arquivos antes de executar os códigos.
