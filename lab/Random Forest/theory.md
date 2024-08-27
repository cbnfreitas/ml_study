1. Random Forest
O que é:

Random Forest é um algoritmo de ensemble learning que cria um "conjunto" (ou floresta) de árvores de decisão, onde cada árvore é treinada em um subconjunto diferente dos dados e das features (variáveis). A predição final do modelo é obtida pela média (para regressão) ou pela votação da maioria (para classificação) das predições de todas as árvores.
Como Funciona:

Bagging (Bootstrap Aggregating): O Random Forest usa uma técnica chamada bagging, onde múltiplos subconjuntos de dados são gerados aleatoriamente (com reposição) a partir do conjunto de dados original. Cada árvore de decisão é treinada em um desses subconjuntos.
Seleção Aleatória de Features: Para cada divisão em uma árvore, um subconjunto aleatório de features é selecionado, o que reduz a correlação entre as árvores e melhora a generalização do modelo.

Vantagens:

Redução de Overfitting: Como o modelo é composto por muitas árvores de decisão independentes, o risco de overfitting é significativamente reduzido em comparação com uma única árvore de decisão.
Robustez: O Random Forest é robusto a outliers e dados ruidosos.
Simplicidade de Uso: Requer pouca parametrização e tende a funcionar bem com a configuração padrão.
Interpretação: Embora não seja tão simples de interpretar quanto uma única árvore de decisão, ainda é possível obter insights, como a importância das features, o que é valioso em muitos casos.
Desvantagens:

Complexidade e Lento em Predição: Como há muitas árvores para processar, pode ser mais lento para fazer predições em comparação com algoritmos mais simples.
Menor Interpretabilidade: Embora ainda seja mais interpretável que redes neurais, o modelo completo é menos transparente que uma única árvore de decisão.
Quando Usar:

Dados Complexos e Não Lineares: Quando há muitas variáveis e interações complexas entre elas.
Quando se Busca Robustez: Se você quer um modelo que seja robusto a outliers e que reduza o overfitting.
Quando Não se Exige Alta Interpretabilidade: Se a interpretabilidade não é a principal prioridade.