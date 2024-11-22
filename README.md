
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Estimativas de saldos migratórios e taxas líquidas de migração das grandes regiões e unidades da federação do Brasil, por sexo, grupo etário e residência urbana/rural, 1960-1970 e 1970-1980

### *Estimates of net migration balances and net migration rates of the major regions and states of Brazil by sex, age group, and urban/rural residence, 1960–1970 and 1970–1980*

------------------------------------------------------------------------

<!-- badges: start -->

[![License: CC BY
4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)

<!-- badges: end -->

------------------------------------------------------------------------

This repository provides the data for the paper *Estimativas de saldos
migratórios e taxas líquidas de migração das grandes regiões e unidades
da federação do Brasil, por sexo, grupo etário e residência
urbana/rural, 1960-1970 e 1970-1980*, by Fernando Fernandes and José
Alberto Magno de Carvalho. The data is provide in one `.csv` file.

------------------------------------------------------------------------

## Citation

Fernandes, Fernando, and José Alberto Magno de Carvalho. 2024.
“Estimativas de saldos migratórios e taxas líquidas de migração das
grandes regiões e unidades da federação do Brasil, por sexo, grupo
etário e residência urbana/rural, 1960-1970 e 1970-1980.” *Revista
Brasileira de Estudos de População*, Notas de Pesquisa, 41 (e0287):
1–12. <https://dx.doi.org/10.20947/S0102-3098a0287>.

------------------------------------------------------------------------

![](output/net_migration_total_age_groups.png)*Saldos migratórios, por
situação de residência e grupos etários, segundo grandes regiões Brasil
– 1960-1980*

------------------------------------------------------------------------

![](output/net_migration_by_net_migration.png)*Taxas líquidas de
migração (%), 1960-1970 versus 1970-1980, por situação de residência,
segundo grandes regiões Brasil – 1960-1980*

------------------------------------------------------------------------

## Data download and variables

The data file
[`fernandes-carvalho-data.csv`](https://github.com/demographyandme/migration-60-70-80/blob/6f9aee4a4b6e3cdfab91012d0ddb68782f7c0c79/output/fernandes_carvalho_data.csv "data file")
has the following variables:

  `decada`: decades = 1960–1970 or 1970–1980  
  `nome_regiao`: region name or Brasil for total  
  `estado`: state’s alpha-code or Brasil for total  
  `nome_estado`: state’s name or Brasil for total  
  `urbano_rural`: residence area = Urbano, Rural or Total  
  `grupo_etario`: 0–4 to 60+ or total  
  `sexid`: sex = Homens, Mulheres or Total  
  `saldo_migratorio`: absolute net migration  
  `saldo_migratorio_indireto`: absolute indirect net migration  
  `populacao_t`: population at the beginning of the decade  
  `populacao_t_10`: population at the end of the decade  
  `taxa_liquida_migracao`: net migration rate  
  `taxa_liquida_migracao_ind`: indirect net migration rate

------------------------------------------------------------------------

## Questions

For any problems or questions, please open an
[issue](https://github.com/demographyandme/migration-60-70-80/issues) or
start a
[discussion](https://github.com/demographyandme/migration-60-70-80/discussions/).

------------------------------------------------------------------------

## Authors

**Fernando Fernandes**, Centro de Desenvolvimento e Planejamento
Regional (Cedeplar), Universidade Federal de Minas Gerais (UFMG)<br>
<img src="icons/x-twitter.svg" width="15"/>
[@demographyandme](https://x.com/demographyandme)

**José Alberto Magno de Carvalho**, In memoriam. Centro de
Desenvolvimento e Planejamento Regional (Cedeplar), Universidade Federal
de Minas Gerais (UFMG)

------------------------------------------------------------------------

## License

This work is licensed under CC BY 4.0. See the
[`LICENSE.md`](https://github.com/demographyandme/migration-60-70-80/blob/428dbe48cf2905c5b7903b841ef1c54c248f9bfc/LICENSE.md)
file for more details.
