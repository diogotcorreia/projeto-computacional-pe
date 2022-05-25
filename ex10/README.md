# Exercicio 10

Usando o R e fixando a semente em $\textbf{346}$ gere $m = 1100$ amostras de dimensão $n$, onde $n \in \{100, 200, 300, \dots, 2500\}$,
de uma população $X$, com distribuição Exponencial de valor esperado $1 / λ = 1 / 0.45$, i.e. $X~\sim~\operatorname{Exp}(\lambda=0.45)$.

Considere as amostras geradas anteriormente e substitua quaisquer $\epsilon \times 100\% = 20\%$ das observações de cada amostra por
outras geradas de uma população que modela a distribuição dos outliers, $X_c$, tal que $X_c~\sim~\operatorname{Exp}(\lambda_c = 0.01)$`.

Para cada uma das amostras geradas sem contaminação (respetivamente, com contaminação), construa um intervalo de confiança
aproximado para o inverso do valor esperado. Considere o nível de confiança $(1 − \alpha) = 0.999$.

Para cada valor de $n$, calcule a Média da Amplitude dos $m = 1100$ intervalos de confiança: $MA(n)$,
no caso das amostras geradas sem contaminação e $MA^c(n)$, no caso de haver contaminação.

Construa um gráfico colocando no eixo dos $xx$ a dimensão da amostra, $n$, e no eixo dos $yy$ os valores de $MA(n)$ e $MA^c(n)$.
