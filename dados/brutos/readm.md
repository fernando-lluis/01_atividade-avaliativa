Atividade Avaliativa I
================
Luis Fernando dos Santos de Brito </br>
Estat 28/07/2020.2

------------------------------------------------------------------------

**Questão 01** Box Plot

1.  O erro foi não ter calculado o intervalo fora do Box Plot, é sim
    50%, o equivalente ao Q1 e Q3.
2.  17
3.  13

<!-- -->

4.  

**Questão 2** Uma prova foi aplicada em duas turmas distintas. Na
primeira, com 30 alunos, a média aritmética das notas foi 6.40. Na
segunda, com 50 alunos, foi 5.20. A média aritmética das notas dos 80
alunos foi:

Letra A: 5,65

30 \* 6,40 + 50 \* 5,20/80 = 192+260/80 = 452/80 = 5,65

**Questão 3** Considere os dados abaixo, onde a variável de interesse,
X, é batimentos cardíacos por minuto (BAT/min). 68 70 72 58 90 110 68 70
72 80 80 67 90 94 100 80 75 79 84 90

1.  

``` r
x <- c(68,70,72,58,90,110,68,70,72,80
,80,67,90,94,100,80,75,79,84,90)
110:58
```

    ##  [1] 110 109 108 107 106 105 104 103 102 101 100  99  98  97  96  95  94  93  92
    ## [20]  91  90  89  88  87  86  85  84  83  82  81  80  79  78  77  76  75  74  73
    ## [39]  72  71  70  69  68  67  66  65  64  63  62  61  60  59  58

2.  

Média = 79,85

Mediana = 79,5

Primeiro Quartil = 70

Teceiro Quartil = 90

Desvio Padrão = 4,46

3.  

``` r
hist(x)
```

![](readm_files/figure-gfm/unnamed-chunk-2-1.png)<!-- -->

``` r
hist(x, ylab = "Frequência Absoluta", xlab = "BAT/min", col = "blue",bolder = FALSE, main = "Batimentos Cardíacos")
```

    ## Warning in plot.window(xlim, ylim, "", ...): "bolder" não é um parâmetro gráfico

    ## Warning in title(main = main, sub = sub, xlab = xlab, ylab = ylab, ...):
    ## "bolder" não é um parâmetro gráfico

    ## Warning in axis(1, ...): "bolder" não é um parâmetro gráfico

    ## Warning in axis(2, ...): "bolder" não é um parâmetro gráfico

![](readm_files/figure-gfm/unnamed-chunk-2-2.png)<!-- -->

**Questão 4**
