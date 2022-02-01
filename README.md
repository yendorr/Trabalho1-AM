# _Adult Data Set_
## Etapas do projeto
Análise exploratória da base de dados _Adult Data Set_ (https://archive.ics.uci.edu/ml/datasets/Adult), procurando por correlções entre os atributos. 

Verificação das distribuições destes atributos com dois histogramas sobrepostos por atributo, onde ambos os histogramas dizem respeito a uma das duas faixas salariais. 

Verificação das distribuições de idade utilizando _blox-plots_, dividindo as pessoas por sua faixa salarial e diversos outros atributos.

Remoção de atributos redundantes.

Criação de um _colum tansformer_ que pré-processa os dados, aplicando _one hot encode_ nos atributos categórico e _stantard scale_ em atributos numéricos

A base de dados é dividida por padrão em dois arquivos, um contendo 66% dos registros e o outro contendo os 33% restantes.

Construção de 3 modelos de aprendizado de máquina (árvore de decisão, SVM, regressão logistica) para a previsão Previsão da faixa salárial de uma pessoa. São criados outros dois modelos com _grid search_ com o intuito de otimizar os parametros dos modelos SVM e árvore de regressão e comparar os resultados.

Visualização de uma das árvores de decisão

## Métricas dos modelos
![Resultados](https://github.com/yendorr/Trabalho1-AM/blob/main/imgs/resultados.png)
