# dadosUfersa
Pacote no R com alguns conjuntos de dados do Relatório de Gestão 2017 da Universidade Federal do Semi-Árido (UFERSA).
Os Relatórios de Gestão da UFERSA podem ser baixados [aqui](https://documentos.ufersa.edu.br/relatorios/gestao/).
Basicamente, são disponibilizados indicadores do Tribunal de Contas da União (TCU) e do Fórum Nacional de Pró-Reitores de Planejamento e de Administração das Instituições Federais de Ensino Superior (Forplad).

## Instalação

``` r
library(devtools)
install_github("Kassio-Ferreira/dadosUfersa")
```

## Dados disponíveis

1.  "AGTI_curso": Aluno de graduação em Tempo Integral por curso, UFERSA (2013-2017).
2.  "capes": Conceito capes para programas de pós-graduação da UFERSA - 2017.
3.  "diplomados": Número de diplomados e ingressantes na graduação - UFERSA.
4.  "forplad_assist": Indicadores de Assistência Estudantil UFERSA (2013-2017) - Forplad.
5.  "forplad_ext": Indicadores de Extensão UFERSA (2013-2017) - Forplad.
6.  "forplad_grad": Indicadores de Graduação UFERSA (2013-2017) - Forplad.
7.  "forplad_pesqPos": Indicadores de Pesquisa e Pós-graduação UFERSA (2013-2017) - Forplad.
8.  "ouvidoria": Quantitativo de chamadas realizadas junto à Ouvidoria na UFERSA no período 2013-2017 por tipo de chamada. 
9.  "Qalunos": Quantidade de alunos matriculados nos cursos de graduação da UFERSA (2013-2017).
10. "Qalunos_pos": Quantidade de alunos dos programas de (Mestrado) na UFERSA (2013-2017)
11. "tcu_AG": Indicadores do número de alunos de graduação, por curso, da UFERSA para 2016.2 e 2017.1 e a média.
12. "tcu_AGE": Números do indicador Aluno equivalente da graduação, por curso, da UFERSA - 2017. 
13. "tcu_AGTI": Aluno da Graduação em Tempo Integral da UFERSA (2016.2-2017.1).
14. "tcu_APG": Número de Alunos da Pós-Graduação da UFERSA (2017.1-2017.2).
15. "tcu_gestao": Indicadores de gestão da UFERSA (2013-2017).
16. "tcu_NFE": Número de Funcionários Equivalentes da UFERSA (2017).
17. "tcu_NPE": Número de Professores Equivalentes da UFERSA (2017).
18. "tcu_primario": Indicadores Primários da UFERSA (2017).

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
