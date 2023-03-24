
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Estimativas de saldos migratórios e taxas líquidas de migração das unidades da federação e grandes regiões do Brasil, por sexo, idade e setores rural e urbano, 1960–1970 e 1970–1980

### *Estimates of net migration and net migration rates for Brazil’s states and regions by sex, age, and rural and urban residence, 1960–1970 and 1970–1980*

------------------------------------------------------------------------

<!-- badges: start -->

[![License: CC BY
4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

<!-- badges: end -->

------------------------------------------------------------------------

This repository provides the data of the Cedeplar/UFMG paper
*Estimativas de saldos migratórios e taxas líquidas de migração das
unidades da federação e grandes regiões do Brasil por sexo, idade e
setores rural e urbano, 1960–1970 e 1970–1980*, by José Alberto Magno de
Carvalho and Fernando Fernandes, initially “published” in 1996.
Published is between quotes because the paper is in *mimeo* format and,
unfortunately, has never been formally published.

Currently, the UFMG library only has one copy of this paper. Given the
continuous demand for these estimates, especially in digital format, I
have decided to prepare and compile all the data dispersed in different
original spreadsheets and provide it in one `.csv` file.

------------------------------------------------------------------------

## Citation

Please, cite the paper or its data as follows:

Carvalho, José Alberto Magno de, and Fernando Fernandes. 1996.
*Estimativas de saldos migratorios e taxas liquidas de migração das
unidades da federação e grandes regiões do Brasil por sexo, idade e
setores rural e urbano, 1960–1970 e 1970–1980*. Belo Horizonte:
Cedeplar, UFMG.

If you prefer, download the
[`.bib file`](output/carvalho-fernandes-1996.bib).

------------------------------------------------------------------------

![](output/net_migration_total_age_groups.png)*Net migration by decade,
urban/rural residence, region, and age group. Brazil, both sexes.*

------------------------------------------------------------------------

## Technical Observations (from the original in Portuguese)

## Observações Técnicas

José Alberto Magno de Carvalho<br> Fernando Fernandes

As estimativas ora apresentadas referem-se aos saldos migratórios e
taxas líquidas de migração das Grande Regiões brasileiras e Unidades da
Federação (UF), segundo situação do domicílio, por sexo e grupo etário,
referentes aos períodos de 1960/1970 e 1970/1980. Os atuais estados do
Mato Grosso do Sul e Mato Grosso estão englobados em Mato Grosso e
Tocantins está incluído em Goiás.

Os saldos migratórios para as idades de 10 anos ou mais da população
total de cada Unidade da Federação deveriam corresponder à soma daqueles
das populações rural e urbana o que nem sempre acontece nas estimativas
apresentadas. Como as diferenças são pequenas, decidiu-se por não fazer
nenhum ajuste.

O saldo migratório ao final da década da população já nascida quando da
realização do Censo anterior, isto é, aquela com 10 anos ou mais em 1970
e 1980, foi obtido através da técnica das relações intercensitárias de
sobrevivência ajustadas ao nível de mortalidade da população em estudo
(Carvalho, 1980). Para os níveis de mortalidade da população em estudo
foram usadas tabelas de sobrevivência de (Carvalho, 1978) e (Carvalho &
Pinheiro, 1986).

Os saldos migratórios relativos à população nascida no período
intercensitário foram calculados conforme procedimento proposto por Lee
et al. (1957).

1.  Para a população com idade entre 0 e 4 anos completos:

![\begin{aligned}
\_5^{\~} SM_0^h \~=\~ \_5^{\~} RCM_0^h \~ \times \~ &\_{30}^{\~} SM\_{15}^m\\\\
\\\\
\_5^{\~} SM_0^m \~=\~ \_5^{\~} RCM_0^m \~ \times \~ &\_{30}^{\~} SM\_{15}^m
\end{aligned}](https://latex.codecogs.com/svg.image?%5Cbegin%7Baligned%7D%0A_5%5E%7B~%7D%20SM_0%5Eh%20~%3D~%20_5%5E%7B~%7D%20RCM_0%5Eh%20~%20%5Ctimes%20~%20%26_%7B30%7D%5E%7B~%7D%20SM_%7B15%7D%5Em%5C%5C%0A%5C%5C%0A_5%5E%7B~%7D%20SM_0%5Em%20~%3D~%20_5%5E%7B~%7D%20RCM_0%5Em%20~%20%5Ctimes%20~%20%26_%7B30%7D%5E%7B~%7D%20SM_%7B15%7D%5Em%0A%5Cend%7Baligned%7D "\begin{aligned}
_5^{~} SM_0^h ~=~ _5^{~} RCM_0^h ~ \times ~ &_{30}^{~} SM_{15}^m\\
\\
_5^{~} SM_0^m ~=~ _5^{~} RCM_0^m ~ \times ~ &_{30}^{~} SM_{15}^m
\end{aligned}")

  

> onde:
>
> ![\_5^{\~} SM_0^h](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20SM_0%5Eh "_5^{~} SM_0^h")
> e
> ![\_5^{\~} SM_0^m](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20SM_0%5Em "_5^{~} SM_0^m"):
> saldos migratórios de homens (h) e mulheres (m) com idade entre 0 e 4
> anos completos;
>
> ![\_5^{\~} RCM_0^h](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20RCM_0%5Eh "_5^{~} RCM_0^h")
> e
> ![\_5^{\~} RCM_0^m](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20RCM_0%5Em "_5^{~} RCM_0^m"):
> relações, ao final da década, entre crianças (homens e mulheres
> respectivamente) com 0 a 4 anos de idade completos e mulheres de 15 a
> 44 anos de idade completos;
>
> ![\_{30}^{\~} SM\_{15}^m](https://latex.codecogs.com/svg.image?_%7B30%7D%5E%7B~%7D%20SM_%7B15%7D%5Em "_{30}^{~} SM_{15}^m"):
> saldo migratório de mulheres de 15 a 44 anos de idade;

2.  Para a população com idade entre 5 e 9 anos completos:

![\begin{aligned}
\_5^{\~} SM_5^h \~=\~ \_5^{\~} RCM_5^h \~ \times \~ &\_{30}^{\~} SM\_{20}^m\\\\
\\\\
\_5^{\~} SM_5^m \~=\~ \_5^{\~} RCM_5^m \~ \times \~ &\_{30}^{\~} SM\_{20}^m
\end{aligned}](https://latex.codecogs.com/svg.image?%5Cbegin%7Baligned%7D%0A_5%5E%7B~%7D%20SM_5%5Eh%20~%3D~%20_5%5E%7B~%7D%20RCM_5%5Eh%20~%20%5Ctimes%20~%20%26_%7B30%7D%5E%7B~%7D%20SM_%7B20%7D%5Em%5C%5C%0A%5C%5C%0A_5%5E%7B~%7D%20SM_5%5Em%20~%3D~%20_5%5E%7B~%7D%20RCM_5%5Em%20~%20%5Ctimes%20~%20%26_%7B30%7D%5E%7B~%7D%20SM_%7B20%7D%5Em%0A%5Cend%7Baligned%7D "\begin{aligned}
_5^{~} SM_5^h ~=~ _5^{~} RCM_5^h ~ \times ~ &_{30}^{~} SM_{20}^m\\
\\
_5^{~} SM_5^m ~=~ _5^{~} RCM_5^m ~ \times ~ &_{30}^{~} SM_{20}^m
\end{aligned}")

  

> onde:
>
> ![\_5^{\~} SM_5^h](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20SM_5%5Eh "_5^{~} SM_5^h")
> e
> ![\_5^{\~} SM_5^m](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20SM_5%5Em "_5^{~} SM_5^m"):
> saldos migratórios de homens (h) e mulheres (m) com idade entre 5 e 9
> anos completos;
>
> ![\_5^{\~} RCM_5^h](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20RCM_5%5Eh "_5^{~} RCM_5^h")
> e
> ![\_5^{\~} RCM_5^m](https://latex.codecogs.com/svg.image?_5%5E%7B~%7D%20RCM_5%5Em "_5^{~} RCM_5^m"):
> relações, ao final da década, entre crianças (homens e mulheres
> respectivamente) com 5 a 9 anos de idade completos e mulheres de 20 a
> 49 anos de idade completos;
>
> ![\_{30}^{\~} SM\_{20}^m](https://latex.codecogs.com/svg.image?_%7B30%7D%5E%7B~%7D%20SM_%7B20%7D%5Em "_{30}^{~} SM_{20}^m"):
> saldo migratório de mulheres de 20 a 49 anos de idade.

Os saldos migratórios para os dois primeiros grupos quinqüenais seriam
explicados pelos efeitos diretos e indiretos da migração. Ainda segundo
a proposta de Lee et al. (1957), supôs-se que no grupo de 0 a 4 anos,
![1/4](https://latex.codecogs.com/svg.image?1%2F4 "1/4") seria devido
aos efeitos diretos e
![3/4](https://latex.codecogs.com/svg.image?3%2F4 "3/4") aos indiretos.
No grupo de 5 a 9 anos, os coeficientes de separação seriam,
respectivamente,
![3/4](https://latex.codecogs.com/svg.image?3%2F4 "3/4") e
![1/4](https://latex.codecogs.com/svg.image?1%2F4 "1/4").

Em cada UF, os saldos migratórios foram estimados, de maneira
independente, para as populações urbana, rural e total. Como já
referido, usou-se em cada população a relação crianças/mulheres para se
estimar os saldos migratórios, neles incluídos também os efeitos
indiretos, nos dois primeiros grupos etários quinquenais. As relações
crianças/mulheres observadas em uma determinada população dependem dos
níveis de fecundidade e mortalidade infanto-juvenil, além da
distribuição etária das mulheres em idade reprodutiva experimentados por
cada população nos 10 anos anteriores à data do censo. A população rural
de todas as UFs, assim como, de modo geral, a população total das UFs
mais pobres tiveram saldo migratório negativo entre as mulheres em idade
reprodutiva, o que levou também a estimativas de saldo migratório
negativo para a população abaixo de 10 anos. O oposto se deu para as
populações urbanas das UFs e totais de várias UFs, por terem saldos
migratórios positivos na população feminina em idade reprodutiva.

Como as áreas rurais têm maior fecundidade que as urbanas, assim como,
de modo geral, as UFs perdedoras líquidas de população vis-a-vis as
ganhadoras líquidas, suas relações crianças/mulheres são, com raras
exceções, maiores do que nas populações urbanas e nas UF receptoras
líquidas. Conseqüentemente, espera-se que, dado o procedimento de
estimação adotado, os saldos migratórios negativos entre as pessoas
abaixo de 10 anos não sejam compensados pelos saldos positivos, mesmo em
uma situação de população fechada no País como um todo. Isto explica
porque nas Tabelas a serem apresentadas referentes ao Brasil como um
todo, correspondentes à soma dos resultados das UFs, os valores
absolutos dos saldos migratórios negativos abaixo de 10 anos da
população rural sejam significativamente maiores do que os positivos da
população urbana. A explicação é a mesma para o fato observado nas
tabelas referentes à população total do Brasil: em 1960/1970, há saldo
negativo abaixo de 10 anos, apesar do saldo levemente positivo entre as
mulheres em idade reprodutiva; em 1970/1980, apesar dos saldos serem
negativos para mulheres e crianças, nestas últimas são desproporcionais
aos saldos femininos.

Na verdade, deve-se interpretar o saldo migratório negativo abaixo de 10
anos de idade como o número de pessoas que se teria a mais ao final da
década, caso a população em questão tivesse permanecido fechada na
década. Não necessariamente essas crianças estarão presentes nas
populações receptoras, pois provavelmente parte delas não nasceu, como
conseqüência do impacto da migração sobre a fecundidade das emigrantes.

Os saldos migratórios das Grandes Regiões foram obtidos a partir da soma
dos saldos migratórios das suas respectivas UFs, e os do Brasil,
analogamente, tomando-se a soma dos saldos migratórios das Grandes
Regiões.

Já para a população total do Brasil, supondo-se que a metodologia
adotada tenha minimizado os problemas oriundos de deficiência de
cobertura censitária e que as tabelas de sobrevivência utilizadas
correspondam exatamente à mortalidade ocorrida durante as décadas de
1960/1970 e 1970/1980, os saldos migratórios apresentados, referentes à
população com 10 ou mais anos, podem ser interpretados como saldo
migratório internacional.

A taxa líquida de migração foi obtida dividindo-se o saldo migratório
pela população enumerada nos Censos de 1970 e 1980. Se positiva, deve
ser interpretada como a proporção da população recenseada conseqüência
dos fluxos migratórios. Se negativa, como a proporção que se teria a
mais na ausência de fluxos migratórios.

### Referências (References)

<div id="refs" class="references csl-bib-body hanging-indent"
line-spacing="2">

<div id="ref-Carvalho1978" class="csl-entry">

Carvalho, José Alberto Magno de. (1978). *Fecundidade e mortalidade no
Brasil, 1960-1970*. Cedeplar, UFMG.

</div>

<div id="ref-Carvalho1980" class="csl-entry">

Carvalho, José Alberto Magno de. (1980). Migrações internas: mensuração
direta e indireta. *Anais do II Encontro Nacional de Estudos
Populacionais*, 532–577.
<http://www.abep.org.br/publicacoes/index.php/anais/article/view/199>

</div>

<div id="ref-Carvalho1986" class="csl-entry">

Carvalho, José Alberto Magno de, & Pinheiro, Sílvia de Menezes Gama.
(1986). *Fecundidade e mortalidade no Brasil, 1970-1980*. Cedeplar,
UFMG.

</div>

<div id="ref-Lee1957" class="csl-entry">

Lee, Everett S., Miller, Ann Ratner, Brainerd, Carol P., & Easterlin,
Richard A. (1957). *Population Redistribution and Economic Growth United
States, 1870-1950: Methodological Considerations and Reference Tables*
(Simon Kuznets & Dorothy Swaine Thomas, Eds.; Vol. 1). The American
Philosophical Society.

</div>

</div>

------------------------------------------------------------------------

## Estimates of net migration and indirect net migration, both sexes, totals

<table class="gmisc_table" style="border-collapse: collapse; margin-top: 1em; margin-bottom: 1em;">
<thead>
<tr>
<td colspan="13" style="text-align: left;">
Net migration by decade, urban/rural residence, and region. Brazil, both
sexes.
</td>
</tr>
<tr>
<th style="border-top: 2px solid grey;">
</th>
<th colspan="4" style="font-weight: 900; border-top: 2px solid grey; text-align: center;">
</th>
<th style="border-bottom: none; border-top: 2px solid grey;" colspan="1">
 
</th>
<th colspan="7" style="font-weight: 900; border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
 Decade 
</th>
</tr>
<tr>
<th style>
</th>
<th colspan="4" style="font-weight: 900; text-align: center;">
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 1960-1970 
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 1970-1980 
</th>
</tr>
<tr>
<th style>
</th>
<th colspan="4" style="font-weight: 900; text-align: center;">
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban / Rural Residence 
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban / Rural Residence 
</th>
</tr>
<tr>
<th style="border-bottom: 1px solid grey; font-weight: 900; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;" colspan="1">
 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Rural 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Total 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;" colspan="1">
 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Rural 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Total 
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="13" style="font-weight: 900;">
 Region 
</td>
</tr>
<tr>
<td style="text-align: left;">
   North 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Acre 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
11,307 
</td>
<td style="text-align: right;">
-31,058 
</td>
<td style="text-align: right;">
-18,176 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
42,202 
</td>
<td style="text-align: right;">
-59,458 
</td>
<td style="text-align: right;">
-13,383 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Amazonas 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
64,523 
</td>
<td style="text-align: right;">
-142,929 
</td>
<td style="text-align: right;">
-71,356 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
232,612 
</td>
<td style="text-align: right;">
-235,684 
</td>
<td style="text-align: right;">
16,072 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Amapá 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
8,397 
</td>
<td style="text-align: right;">
1,843 
</td>
<td style="text-align: right;">
10,290 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
10,245 
</td>
<td style="text-align: right;">
-8,482 
</td>
<td style="text-align: right;">
2,001 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Pará 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
140,876 
</td>
<td style="text-align: right;">
-162,084 
</td>
<td style="text-align: right;">
-15,546 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
229,717 
</td>
<td style="text-align: right;">
25,380 
</td>
<td style="text-align: right;">
257,829 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rondônia 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
13,182 
</td>
<td style="text-align: right;">
-4,194 
</td>
<td style="text-align: right;">
8,922 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
120,364 
</td>
<td style="text-align: right;">
155,654 
</td>
<td style="text-align: right;">
275,699 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Roraima 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
27 
</td>
<td style="text-align: right;">
-1,100 
</td>
<td style="text-align: right;">
-1,002 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
19,277 
</td>
<td style="text-align: right;">
-3,744 
</td>
<td style="text-align: right;">
15,776 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
238,312 
</td>
<td style="text-align: right;">
-339,522 
</td>
<td style="text-align: right;">
-86,869 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
654,416 
</td>
<td style="text-align: right;">
-126,333 
</td>
<td style="text-align: right;">
553,994 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Northeast 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Alagoas 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
65,949 
</td>
<td style="text-align: right;">
-175,344 
</td>
<td style="text-align: right;">
-105,193 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
134,047 
</td>
<td style="text-align: right;">
-298,379 
</td>
<td style="text-align: right;">
-151,490 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Bahia 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
295,366 
</td>
<td style="text-align: right;">
-942,173 
</td>
<td style="text-align: right;">
-620,258 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
452,742 
</td>
<td style="text-align: right;">
-1,097,987 
</td>
<td style="text-align: right;">
-765,245 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Ceará 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
288,087 
</td>
<td style="text-align: right;">
-439,541 
</td>
<td style="text-align: right;">
-126,233 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
475,553 
</td>
<td style="text-align: right;">
-915,248 
</td>
<td style="text-align: right;">
-392,044 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Maranhão 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
126,023 
</td>
<td style="text-align: right;">
-496,392 
</td>
<td style="text-align: right;">
-350,249 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
191,786 
</td>
<td style="text-align: right;">
-404,140 
</td>
<td style="text-align: right;">
-207,656 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Paraíba 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
76,924 
</td>
<td style="text-align: right;">
-347,074 
</td>
<td style="text-align: right;">
-259,859 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
163,814 
</td>
<td style="text-align: right;">
-468,686 
</td>
<td style="text-align: right;">
-283,629 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Pernambuco 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
359,777 
</td>
<td style="text-align: right;">
-633,495 
</td>
<td style="text-align: right;">
-248,788 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
204,701 
</td>
<td style="text-align: right;">
-713,706 
</td>
<td style="text-align: right;">
-483,007 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Piauí 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
117,959 
</td>
<td style="text-align: right;">
-197,296 
</td>
<td style="text-align: right;">
-73,056 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
149,705 
</td>
<td style="text-align: right;">
-344,227 
</td>
<td style="text-align: right;">
-182,160 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rio Grande do Norte 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
147,642 
</td>
<td style="text-align: right;">
-146,588 
</td>
<td style="text-align: right;">
9,870 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
162,364 
</td>
<td style="text-align: right;">
-265,161 
</td>
<td style="text-align: right;">
-90,109 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Sergipe 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
25,117 
</td>
<td style="text-align: right;">
-141,833 
</td>
<td style="text-align: right;">
-112,540 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
65,048 
</td>
<td style="text-align: right;">
-147,333 
</td>
<td style="text-align: right;">
-74,053 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,502,843 
</td>
<td style="text-align: right;">
-3,519,737 
</td>
<td style="text-align: right;">
-1,886,306 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
1,999,760 
</td>
<td style="text-align: right;">
-4,654,867 
</td>
<td style="text-align: right;">
-2,629,394 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Midwest 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Distrito Federal 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
334,960 
</td>
<td style="text-align: right;">
-46,941 
</td>
<td style="text-align: right;">
292,445 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
392,551 
</td>
<td style="text-align: right;">
5,704 
</td>
<td style="text-align: right;">
398,936 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Goiás 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
388,682 
</td>
<td style="text-align: right;">
-223,432 
</td>
<td style="text-align: right;">
184,592 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
683,700 
</td>
<td style="text-align: right;">
-789,871 
</td>
<td style="text-align: right;">
-73,278 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Mato Grosso 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
186,364 
</td>
<td style="text-align: right;">
93,540 
</td>
<td style="text-align: right;">
284,144 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
569,108 
</td>
<td style="text-align: right;">
-291,911 
</td>
<td style="text-align: right;">
290,576 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
910,006 
</td>
<td style="text-align: right;">
-176,832 
</td>
<td style="text-align: right;">
761,180 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
1,645,359 
</td>
<td style="text-align: right;">
-1,076,077 
</td>
<td style="text-align: right;">
616,235 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Southeast 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Espírito Santo 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
202,595 
</td>
<td style="text-align: right;">
-234,355 
</td>
<td style="text-align: right;">
-15,119 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
314,274 
</td>
<td style="text-align: right;">
-406,900 
</td>
<td style="text-align: right;">
-74,982 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Minas Gerais 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
951,708 
</td>
<td style="text-align: right;">
-2,404,373 
</td>
<td style="text-align: right;">
-1,330,010 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
1,175,758 
</td>
<td style="text-align: right;">
-2,583,004 
</td>
<td style="text-align: right;">
-1,288,558 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rio de Janeiro 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,370,716 
</td>
<td style="text-align: right;">
-708,349 
</td>
<td style="text-align: right;">
725,816 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
871,786 
</td>
<td style="text-align: right;">
-430,395 
</td>
<td style="text-align: right;">
465,088 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 São Paulo 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
3,892,404 
</td>
<td style="text-align: right;">
-2,575,325 
</td>
<td style="text-align: right;">
1,509,831 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
4,296,419 
</td>
<td style="text-align: right;">
-1,478,811 
</td>
<td style="text-align: right;">
2,890,547 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
6,417,423 
</td>
<td style="text-align: right;">
-5,922,403 
</td>
<td style="text-align: right;">
890,517 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
6,658,237 
</td>
<td style="text-align: right;">
-4,899,111 
</td>
<td style="text-align: right;">
1,992,096 
</td>
</tr>
<tr>
<td style="text-align: left;">
   South 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Paraná 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
671,824 
</td>
<td style="text-align: right;">
85,115 
</td>
<td style="text-align: right;">
792,361 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
1,132,261 
</td>
<td style="text-align: right;">
-2,440,122 
</td>
<td style="text-align: right;">
-1,222,683 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rio Grande do Sul 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
526,065 
</td>
<td style="text-align: right;">
-810,858 
</td>
<td style="text-align: right;">
-243,792 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
817,229 
</td>
<td style="text-align: right;">
-1,236,764 
</td>
<td style="text-align: right;">
-391,762 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Santa Catarina 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
300,714 
</td>
<td style="text-align: right;">
-350,830 
</td>
<td style="text-align: right;">
-28,631 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
507,262 
</td>
<td style="text-align: right;">
-614,229 
</td>
<td style="text-align: right;">
-87,539 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,498,602 
</td>
<td style="text-align: right;">
-1,076,573 
</td>
<td style="text-align: right;">
519,938 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
2,456,752 
</td>
<td style="text-align: right;">
-4,291,115 
</td>
<td style="text-align: right;">
-1,701,983 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Brazil 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Brazil 
</td>
<td style="text-align: left;">
 Net migration 
</td>
<td style="text-align: left;">
 Total 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
10,567,187 
</td>
<td style="text-align: right;">
-11,035,067 
</td>
<td style="text-align: right;">
198,461 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
13,414,523 
</td>
<td style="text-align: right;">
-15,047,503 
</td>
<td style="text-align: right;">
-1,169,053 
</td>
</tr>
<tr>
<td style="border-bottom: 2px solid grey; text-align: left;">
  
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
 #Total 
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
 Net migration 
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
 Total 
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
</td>
<td style="border-bottom: 2px solid grey; text-align: left;" colspan="1">
 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
10,567,187 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-11,035,067 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
198,461 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;" colspan="1">
 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
13,414,523 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-15,047,503 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-1,169,053 
</td>
</tr>
</tbody>
</table>
<table class="gmisc_table" style="border-collapse: collapse; margin-top: 1em; margin-bottom: 1em;">
<thead>
<tr>
<td colspan="12" style="text-align: left;">
Indirect net migration by decade, urban/rural residence, and region.
Brazil, both sexes.
</td>
</tr>
<tr>
<th style="border-top: 2px solid grey;">
</th>
<th colspan="3" style="font-weight: 900; border-top: 2px solid grey; text-align: center;">
</th>
<th style="border-bottom: none; border-top: 2px solid grey;" colspan="1">
 
</th>
<th colspan="7" style="font-weight: 900; border-bottom: 1px solid grey; border-top: 2px solid grey; text-align: center;">
 Decade 
</th>
</tr>
<tr>
<th style>
</th>
<th colspan="3" style="font-weight: 900; text-align: center;">
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 1960-1970 
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 1970-1980 
</th>
</tr>
<tr>
<th style>
</th>
<th colspan="3" style="font-weight: 900; text-align: center;">
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban / Rural Residence 
</th>
<th style="border-bottom: none;" colspan="1">
 
</th>
<th colspan="3" style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban / Rural Residence 
</th>
</tr>
<tr>
<th style="border-bottom: 1px solid grey; font-weight: 900; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;" colspan="1">
 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Rural 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Total 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;" colspan="1">
 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Urban 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Rural 
</th>
<th style="font-weight: 900; border-bottom: 1px solid grey; text-align: center;">
 Total 
</th>
</tr>
</thead>
<tbody>
<tr>
<td colspan="12" style="font-weight: 900;">
 Region 
</td>
</tr>
<tr>
<td style="text-align: left;">
   North 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Acre 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,125 
</td>
<td style="text-align: right;">
-11,143 
</td>
<td style="text-align: right;">
-7,696 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
6,603 
</td>
<td style="text-align: right;">
-17,583 
</td>
<td style="text-align: right;">
-5,350 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Amazonas 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
7,013 
</td>
<td style="text-align: right;">
-50,642 
</td>
<td style="text-align: right;">
-33,107 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
44,825 
</td>
<td style="text-align: right;">
-74,954 
</td>
<td style="text-align: right;">
-3,154 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Amapá 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,268 
</td>
<td style="text-align: right;">
659 
</td>
<td style="text-align: right;">
1,963 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
2,051 
</td>
<td style="text-align: right;">
-2,898 
</td>
<td style="text-align: right;">
-377 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Pará 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
14,710 
</td>
<td style="text-align: right;">
-55,588 
</td>
<td style="text-align: right;">
-32,972 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
27,250 
</td>
<td style="text-align: right;">
-6,946 
</td>
<td style="text-align: right;">
25,809 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rondônia 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
2,286 
</td>
<td style="text-align: right;">
-1,058 
</td>
<td style="text-align: right;">
1,230 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
23,204 
</td>
<td style="text-align: right;">
32,600 
</td>
<td style="text-align: right;">
55,482 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Roraima 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
-546 
</td>
<td style="text-align: right;">
-312 
</td>
<td style="text-align: right;">
-777 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
3,372 
</td>
<td style="text-align: right;">
-589 
</td>
<td style="text-align: right;">
3,043 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
25,857 
</td>
<td style="text-align: right;">
-118,085 
</td>
<td style="text-align: right;">
-71,360 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
107,305 
</td>
<td style="text-align: right;">
-70,370 
</td>
<td style="text-align: right;">
75,453 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Northeast 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Alagoas 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
2,817 
</td>
<td style="text-align: right;">
-60,309 
</td>
<td style="text-align: right;">
-47,951 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
12,423 
</td>
<td style="text-align: right;">
-95,649 
</td>
<td style="text-align: right;">
-63,880 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Bahia 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
3,248 
</td>
<td style="text-align: right;">
-314,152 
</td>
<td style="text-align: right;">
-274,393 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
29,718 
</td>
<td style="text-align: right;">
-319,241 
</td>
<td style="text-align: right;">
-292,413 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Ceará 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
26,155 
</td>
<td style="text-align: right;">
-138,755 
</td>
<td style="text-align: right;">
-81,324 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
39,941 
</td>
<td style="text-align: right;">
-249,722 
</td>
<td style="text-align: right;">
-147,149 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Maranhão 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,035 
</td>
<td style="text-align: right;">
-128,533 
</td>
<td style="text-align: right;">
-89,664 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
7,113 
</td>
<td style="text-align: right;">
-126,051 
</td>
<td style="text-align: right;">
-111,113 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Paraíba 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
-2,453 
</td>
<td style="text-align: right;">
-107,555 
</td>
<td style="text-align: right;">
-96,560 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
8,805 
</td>
<td style="text-align: right;">
-125,385 
</td>
<td style="text-align: right;">
-90,786 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Pernambuco 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
32,484 
</td>
<td style="text-align: right;">
-193,419 
</td>
<td style="text-align: right;">
-123,987 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
15,082 
</td>
<td style="text-align: right;">
-194,991 
</td>
<td style="text-align: right;">
-134,839 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Piauí 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
14,053 
</td>
<td style="text-align: right;">
-56,728 
</td>
<td style="text-align: right;">
-34,422 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
16,601 
</td>
<td style="text-align: right;">
-99,771 
</td>
<td style="text-align: right;">
-64,939 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rio Grande do Norte 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
15,895 
</td>
<td style="text-align: right;">
-51,004 
</td>
<td style="text-align: right;">
-22,967 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
12,763 
</td>
<td style="text-align: right;">
-67,389 
</td>
<td style="text-align: right;">
-36,586 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Sergipe 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
-1,121 
</td>
<td style="text-align: right;">
-45,045 
</td>
<td style="text-align: right;">
-39,830 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
8,564 
</td>
<td style="text-align: right;">
-47,186 
</td>
<td style="text-align: right;">
-26,584 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
92,113 
</td>
<td style="text-align: right;">
-1,095,501 
</td>
<td style="text-align: right;">
-811,098 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
151,012 
</td>
<td style="text-align: right;">
-1,325,385 
</td>
<td style="text-align: right;">
-968,288 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Midwest 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Distrito Federal 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
70,874 
</td>
<td style="text-align: right;">
-11,453 
</td>
<td style="text-align: right;">
64,476 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
73,227 
</td>
<td style="text-align: right;">
1,214 
</td>
<td style="text-align: right;">
75,311 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Goiás 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
52,121 
</td>
<td style="text-align: right;">
-62,550 
</td>
<td style="text-align: right;">
14,851 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
88,557 
</td>
<td style="text-align: right;">
-170,408 
</td>
<td style="text-align: right;">
-29,629 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Mato Grosso 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
25,543 
</td>
<td style="text-align: right;">
13,329 
</td>
<td style="text-align: right;">
44,967 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
87,848 
</td>
<td style="text-align: right;">
-57,795 
</td>
<td style="text-align: right;">
49,085 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
148,538 
</td>
<td style="text-align: right;">
-60,673 
</td>
<td style="text-align: right;">
124,294 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
249,631 
</td>
<td style="text-align: right;">
-226,988 
</td>
<td style="text-align: right;">
94,767 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Southeast 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Espírito Santo 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
26,755 
</td>
<td style="text-align: right;">
-63,057 
</td>
<td style="text-align: right;">
-16,669 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
41,245 
</td>
<td style="text-align: right;">
-82,554 
</td>
<td style="text-align: right;">
-18,497 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Minas Gerais 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
77,308 
</td>
<td style="text-align: right;">
-624,015 
</td>
<td style="text-align: right;">
-394,530 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
121,162 
</td>
<td style="text-align: right;">
-568,399 
</td>
<td style="text-align: right;">
-289,649 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rio de Janeiro 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
166,610 
</td>
<td style="text-align: right;">
-151,320 
</td>
<td style="text-align: right;">
89,591 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
121,113 
</td>
<td style="text-align: right;">
-76,592 
</td>
<td style="text-align: right;">
78,392 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 São Paulo 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
495,137 
</td>
<td style="text-align: right;">
-510,372 
</td>
<td style="text-align: right;">
206,658 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
646,479 
</td>
<td style="text-align: right;">
-246,548 
</td>
<td style="text-align: right;">
499,015 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
765,809 
</td>
<td style="text-align: right;">
-1,348,764 
</td>
<td style="text-align: right;">
-114,948 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
929,998 
</td>
<td style="text-align: right;">
-974,092 
</td>
<td style="text-align: right;">
269,262 
</td>
</tr>
<tr>
<td style="text-align: left;">
   South 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Paraná 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
102,156 
</td>
<td style="text-align: right;">
16,751 
</td>
<td style="text-align: right;">
166,877 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
152,194 
</td>
<td style="text-align: right;">
-458,827 
</td>
<td style="text-align: right;">
-198,079 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Rio Grande do Sul 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
61,232 
</td>
<td style="text-align: right;">
-149,247 
</td>
<td style="text-align: right;">
-43,244 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
101,552 
</td>
<td style="text-align: right;">
-195,281 
</td>
<td style="text-align: right;">
-60,312 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;">
 Santa Catarina 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
48,434 
</td>
<td style="text-align: right;">
-77,619 
</td>
<td style="text-align: right;">
-5,404 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
70,732 
</td>
<td style="text-align: right;">
-107,604 
</td>
<td style="text-align: right;">
-14,382 
</td>
</tr>
<tr>
<td style="text-align: left;">
  
</td>
<td style="text-align: left;">
 #Total 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;">
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
211,822 
</td>
<td style="text-align: right;">
-210,115 
</td>
<td style="text-align: right;">
118,229 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
324,478 
</td>
<td style="text-align: right;">
-761,712 
</td>
<td style="text-align: right;">
-272,773 
</td>
</tr>
<tr>
<td style="text-align: left;">
   Brazil 
</td>
<td style="text-align: left;">
 State 
</td>
<td style="text-align: left;">
 Brazil 
</td>
<td style="text-align: left;">
 Indirect net migration 
</td>
<td style="text-align: left;" colspan="1">
 
</td>
<td style="text-align: right;">
1,244,138 
</td>
<td style="text-align: right;">
-2,833,137 
</td>
<td style="text-align: right;">
-754,884 
</td>
<td style="text-align: right;" colspan="1">
 
</td>
<td style="text-align: right;">
1,762,425 
</td>
<td style="text-align: right;">
-3,358,547 
</td>
<td style="text-align: right;">
-801,579 
</td>
</tr>
<tr>
<td style="border-bottom: 2px solid grey; text-align: left;">
  
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
 #Total 
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
 Indirect net migration 
</td>
<td style="border-bottom: 2px solid grey; text-align: left;">
</td>
<td style="border-bottom: 2px solid grey; text-align: left;" colspan="1">
 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
1,244,138 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-2,833,137 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-754,884 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;" colspan="1">
 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
1,762,425 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-3,358,547 
</td>
<td style="border-bottom: 2px solid grey; text-align: right;">
-801,579 
</td>
</tr>
</tbody>
</table>

------------------------------------------------------------------------

## Data download and variables

The data file
[`carvalho-fernandes-1996.csv`](https://github.com/demographyandme/migration-60-70-80/blob/428dbe48cf2905c5b7903b841ef1c54c248f9bfc/output/carvalho-fernandes-data.csv "data file")
has the following variables:

  `decade`: decades = 1960–1970 or 1970–1980  
  `region_name`: region name or Brazil for total  
  `state`: state’s alpha-code or Brazil for total  
  `state_name`: state’s name or Brazil for total  
  `urban_rural`: residence area = Urban, Rural or Total  
  `age_group`: 0–4 to 60+ or total  
  `sexid`: sex = Male, Female or Total  
  `net_migration`: absolute net migration  
  `indirect_net_migration`: absolute indirect net migration  
  `population_t`: population at the beginning of the decade  
  `population_t_10`: population at the end of the decade  
  `migration_rate`: net migration rate  
  `ind_migration_rate`: indirect net migration rate

------------------------------------------------------------------------

## Questions

For any problems or questions, please open an
[issue](https://github.com/demographyandme/migration-60-70-80/issues) or
start a
[discussion](https://github.com/demographyandme/migration-60-70-80/discussions/).

------------------------------------------------------------------------

## Authors

**José Alberto Magno de Carvalho**, Demography Department, Cedeplar,
Universidade Federal de Minas Gerais, Brazil

**Fernando Fernandes**, Demography Department, Cedeplar, Universidade
Federal de Minas Gerais <img src="icons/twitter-brands.svg" width="15"/>
[@demographyandme](https://twitter.com/demographyandme)

------------------------------------------------------------------------

## License

This work is licensed under CC BY 4.0. See the
[`LICENSE.md`](https://github.com/demographyandme/migration-60-70-80/blob/428dbe48cf2905c5b7903b841ef1c54c248f9bfc/LICENSE.md)
file for more details.
