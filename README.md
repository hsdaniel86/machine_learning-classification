# Student classification

## classifição de alunos


This work consists of classifying students into five categories. More information can be found in the data dictionary in the notebook header with "Exploratory_Analysis"

Este trabalho consiste em classificar alunos em cinco categorias. Maiores informações pode ser encontrada no dicionário de dados no cabeçalho do notebook com no "Exploratory_Analisys"

# Exploratory_Analysys

## Análise Exploratoria

This notebook contains data dictionary and an analysis of how the data is divided, if there are missing values, balancing, graphs with data distribution, correlation analysis.

Este notebook contém dicionário de dados e uma análise de como os dados estão divididos, se existem valores faltantes, balanceamento, gráficos com distribuição dos dados, análise de correlação.

# PreProcessing

## Pré Processamento

Notebook with transformations aiming a better generalization of data such as transforming target variable from object to numerical, treatment of missing values, categorization of variables, balancing, standardization and dimension reduction

Notebook com transformações visando uma melhor generalização dos dados, como trnsformar variavel alvo de object para numerical, tratamento de valores faltantes, categorização de variáveis, balanceamento, padronização e redução de dimensinalidade

# PreProcessing_2

## Pré Processamento 2

After the creation of some decision tree models, it was diagnosed that some more transformations could be performed for better performance of the CLASSIFICATION ALGORITHM as a categorical variable generated in the first pre-processing notebook, it was not accepted because the algorithm does not accept object value, a transformation was performed for convert it into a numerical variable, comparisons were also carried out between variables and generating a new variable, as well as a feature selection, in this notebook there is no accounting and standardization of the new datasets generated after processing.

Apos a criação de alguns modelos de árvore de decisão, foi diagnosticado que poderiam ser realizadas mais algumas tranformações para melhor desempenho do algoritmo de classificação como variável categórica gerado no primeiro notebook de pré processamento não foi aceita pois o algoritmo nao aceita valor object foi realizado tranformação para convertê-lo em variável numerical, também foi realizado comparações entre variáveis e gerando uma nova variável, bem como foi realizado uma feature selection, neste notebook não tem balanceamento e padronização dos novos datasets gerados apos o processamento.

# Creating_model_Decision_Tree

# Criação do modelo de Árvore de Decisão

After exploratory analysis and pre-processing this notebook was started with the creation of decision tree models with the SKLEARN framework, after testing some models was performed but some processing to generalize and optimize the model in this notebook has data balancing and standardization , something very important to mention and that GridsearchCV algorithm was used to search for better optimization of hyper parameters

Apos a analise exploratoria e o pré processamento foi dado inicio a este notebook com a criação de modelos de arvore de decisão com o framework SKLEARN, apos testar alguns modelos foi realizado mas alguns processamentos para generalizar e otimizar o modelo neste notebook tem balanceamento de dados e padronização, algo muito importante de se mencionar e que foi usado algoritmo GridsearchCV para buscar melhor otimiação de hiper parametros

# Ceate_model_RandomForest

## Criar modelo RandomForest

as in the decision tree models it was not possible to obtain satisfactory values, new tests were carried out with sklearn's ensemble methods in order to improve the model's performance and with the random forest, since the first model the algorithm showed a much better performance 

Como nos modelos de árvore de decisão nao foi possivel conseguir valores satisfatorios, foi feito novos testes com metodos ensemble do sklearn com objetivo de melhorar o desenpenho do modelo e com o random forest,  desde o primeiro modelo o algoritmo mostrou um desempenho muito melhor.
