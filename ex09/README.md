# Exercicio 9

Usando o R e fixando a semente em **992**, gere `m = 900` amostras de dimensão `n`, onde `n ∈ {100, 200, 300, …, 5000}`,
de uma população `X`, com distribuição Exponencial de valor esperado `1 / λ = 1 / 0.98`, i.e. `X ∼ Exp(λ = 0.98)`.

Para cada uma das amostras geradas, construa um intervalo de confiança aproximado para λ.
Considere o nível de confiança `1 − α = 0.93`.

Para cada valor de n, calcule a Média da Amplitude dos `m = 900` intervalos de confiança obtidos, `MA(n)`.

Construa um gráfico colocando no eixo dos _xx_ a dimensão da amostra, `n`, e no eixo dos _yy_ o valor de `MA(n)`.
