
<!-- README.md is generated from README.Rmd. Please edit that file -->

## Estimativas de saldos migratórios e taxas líquidas de migração das grandes regiões e unidades da federação do Brasil, por sexo, grupo etário e residência urbana/rural, 1960-1970 e 1970-1980

### *Estimates of net migration balances and net migration rates of the major regions and states of Brazil by sex, age group, and urban/rural residence, 1960–1970 and 1970–1980*

------------------------------------------------------------------------

<!-- badges: start -->

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-blue.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://img.shields.io/badge/DOI-10.20947%2FS0102--3098a0287-blue)](https://dx.doi.org/10.20947/S0102-3098a0287)
[![Project Status: Active](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
[![Lifecycle: stable](https://img.shields.io/badge/lifecycle-stable-brightgreen.svg)](https://lifecycle.r-lib.org/articles/stages.html#stable)

<!-- badges: end -->

------------------------------------------------------------------------

This repository provides the data for the paper *Estimativas de saldos migratórios e taxas líquidas de migração das grandes regiões e unidades da federação do Brasil, por sexo, grupo etário e residência urbana/rural, 1960-1970 e 1970-1980*, by Fernando Fernandes and José Alberto Magno de Carvalho. The data is provide in one `.csv` file.

------------------------------------------------------------------------

## Citation

Fernandes, Fernando, and José Alberto Magno de Carvalho. 2024. “Estimativas de saldos migratórios e taxas líquidas de migração das grandes regiões e unidades da federação do Brasil, por sexo, grupo etário e residência urbana/rural, 1960-1970 e 1970-1980.” *Revista Brasileira de Estudos de População*, Notas de Pesquisa, 41 (e0287): 1–12. <https://dx.doi.org/10.20947/S0102-3098a0287>.

------------------------------------------------------------------------

## Figures

### Net Migration by Age Groups

<figure>
<img src="output/net_migration_total_age_groups.png" alt="Net migration by residence area and age groups, by major regions Brazil – 1960-1980" />
<figcaption aria-hidden="true">Net migration by residence area and age groups, by major regions Brazil – 1960-1980</figcaption>
</figure>

### Net Migration Rates

<figure>
<img src="output/net_migration_by_net_migration.png" alt="Net migration rates (%), 1960-1970 versus 1970-1980, by residence area, by major regions Brazil – 1960-1980" />
<figcaption aria-hidden="true">Net migration rates (%), 1960-1970 versus 1970-1980, by residence area, by major regions Brazil – 1960-1980</figcaption>
</figure>

------------------------------------------------------------------------

## Data download and variables

The data file [`fernandes-carvalho-data.csv`](https://github.com/demographyandme/migration-60-70-80/blob/be822254ecdde660082483a7b323fb49347ab353/output/fernandes_carvalho_data.csv "data file") has the following variables:

| Variable                    | Description                               |
|-----------------------------|-------------------------------------------|
| `decada`                    | Decades = 1960–1970 or 1970–1980          |
| `nome_regiao`               | Region name or Brasil for total           |
| `estado`                    | State’s alpha-code or Brasil for total    |
| `nome_estado`               | State’s name or Brasil for total          |
| `urbano_rural`              | Residence area = Urbano, Rural or Total   |
| `grupo_etario`              | 0–4 to 60+ or total                       |
| `sexid`                     | Sex = Homens, Mulheres or Total           |
| `saldo_migratorio`          | Absolute net migration                    |
| `saldo_migratorio_indireto` | Absolute indirect net migration           |
| `populacao_t`               | Population at the beginning of the decade |
| `populacao_t_10`            | Population at the end of the decade       |
| `taxa_liquida_migracao`     | Net migration rate                        |
| `taxa_liquida_migracao_ind` | Indirect net migration rate               |

------------------------------------------------------------------------

## Questions

For any problems or questions, please open an [issue](https://github.com/demographyandme/migration-60-70-80/issues) or start a [discussion](https://github.com/demographyandme/migration-60-70-80/discussions/).

------------------------------------------------------------------------

## Authors

**Fernando Fernandes**, Centro de Desenvolvimento e Planejamento Regional (Cedeplar), Universidade Federal de Minas Gerais (UFMG)<br> <img src="icons/x-twitter.svg" width="15"/> [@demographyandme](https://x.com/demographyandme)

**José Alberto Magno de Carvalho**, In memoriam. Centro de Desenvolvimento e Planejamento Regional (Cedeplar), Universidade Federal de Minas Gerais (UFMG)

------------------------------------------------------------------------

## License

This work is licensed under CC BY 4.0. See the [`LICENSE.md`](https://github.com/demographyandme/migration-60-70-80/blob/428dbe48cf2905c5b7903b841ef1c54c248f9bfc/LICENSE.md) file for more details.
