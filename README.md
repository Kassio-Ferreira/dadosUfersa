# dadosUfersa
Pacote no R com alguns conjuntos de dados do Relatório de Gestão 2017 da Universidade Federal do Semi-Árido (UFERSA).

## Instalação

``` r
library(devtools)
install_github("Kassio-Ferreira/dadosUfersa")
```

## Exemplo

Acessando dados de número de diplomados por curso na UFERSA:

``` r
library(dadosUfersa)
data("diplomados")
diplomados
```

Todos os datasets estão documentados, o comando

``` r
??diplomados
```

abrirá a página de ajuda com as informações sobre o dataset desejado.
