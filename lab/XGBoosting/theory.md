2. XGBoost (Extreme Gradient Boosting)
O que é:

XGBoost é um algoritmo de boosting que se baseia em árvores de decisão. Diferentemente do Random Forest, que usa bagging, o XGBoost usa boosting, que cria árvores de decisão sequencialmente, cada uma corrigindo os erros das árvores anteriores.
Como Funciona:

Boosting: Ao contrário do bagging, onde as árvores são construídas independentemente, no boosting, as árvores são construídas sequencialmente. Cada nova árvore tenta corrigir os erros cometidos pelas árvores anteriores.

Gradiente Descent: XGBoost usa um método de gradiente descent para minimizar a função de perda, ajustando as predições do modelo para se alinhar melhor aos dados.
Regularização: XGBoost inclui termos de regularização para penalizar modelos complexos, ajudando a evitar overfitting. Essa regularização é uma das razões pelas quais o XGBoost tende a ter um desempenho tão bom em muitas competições de machine learning.
Vantagens:

Alto Desempenho: XGBoost é conhecido por seu desempenho superior em uma ampla variedade de problemas, muitas vezes superando outros algoritmos.

Eficiência Computacional: Implementado de maneira eficiente, aproveitando paralelismo e otimizações de hardware, o que o torna mais rápido que outros métodos de boosting.

Flexibilidade: Suporta customização na função de perda e nos tipos de árvores usadas, o que o torna altamente flexível para diferentes tipos de problemas.
Controle de Overfitting: Oferece controles avançados de overfitting, como a regularização L1 e L2.
Desvantagens:

Complexidade: É mais complexo de entender e ajustar do que algoritmos como Random Forest.
Overfitting: Embora tenha controles de regularização, se não for ajustado corretamente, ainda pode overfitting, especialmente com dados ruidosos.
Interpretação: Como com outros modelos de ensemble, interpretar o modelo completo pode ser difícil.