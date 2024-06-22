---
title: Cálculo Numérico - Interpolação, Fórmula de Newton, Lagrange e Regressão MMQ
---
## Bem-vindo ao Cálculo Numérico!

### O que é Interpolação?
A interpolação é um método de estimar novos pontos de dados dentro do intervalo de um conjunto discreto de pontos conhecidos. Se temos uma série de pontos \( (x_0, y_0), (x_1, y_1), ..., (x_n, y_n) \), a interpolação nos permite encontrar um valor \( y \) correspondente a um novo valor \( x \) que esteja dentro do intervalo dos \( x_i \).

### Fórmula de Interpolação de Newton
A interpolação de Newton é uma forma eficiente de construir um polinômio interpolador através de diferenças divididas. A fórmula geral para o polinômio interpolador de Newton é:

\[ P(x) = y_0 + (x - x_0)f[x_0, x_1] + (x - x_0)(x - x_1)f[x_0, x_1, x_2] + ... + (x - x_0)(x - x_1)...(x - x_{n-1})f[x_0, x_1, ..., x_n] \]

Onde \( f[x_0, x_1] \), \( f[x_0, x_1, x_2] \), etc., são as diferenças divididas calculadas a partir dos pontos dados.

### Fórmula de Interpolação de Lagrange
A interpolação de Lagrange é outra técnica para encontrar o polinômio interpolador. A fórmula do polinômio de Lagrange é:

\[ P(x) = \sum_{i=0}^{n} y_i L_i(x) \]

Onde \( L_i(x) \) são os polinômios de Lagrange definidos como:

formula

### Regressão MMQ (Mínimos Quadrados)
A regressão pelos mínimos quadrados é um método para ajustar uma linha ou uma curva que melhor se aproxima de um conjunto de dados. Este método minimiza a soma dos quadrados das diferenças entre os valores observados e os valores previstos pelo modelo. A fórmula da regressão linear simples é:

\[ y = ax + b \]

Onde os coeficientes \( a \) e \( b \) são calculados para minimizar a soma dos quadrados dos resíduos:

\[S=∑ i=1n(y i−(axi+b))²\]

Para encontrar os valores de \( a \) e \( b \), resolvemos o sistema de equações derivado do critério de minimização da soma dos quadrados dos resíduos.

### Código Interpolação de Newton e Lagrange
![Menu do sistema](images/menusistema.png)
[Código funcionando](https://replit.com/@DAVI-ESTEVES-DE/calculoNumerico)

### Atividade da folha
![Imagem da folha](images/folha.png)
![Newton](images/newton.png)
![Lagrange](images/lagrange.png)

### Lista usando o código
[Lista usando o código](https://docs.google.com/document/d/1a9H8xy_pHW_UF_d9TK2V7cVPpq_pl2I3dU3GJtrCj64/edit?usp=sharing)
