# Education Policies and Wage Inequality in Spain

## Research question

How do educational expansion and schooling resources relate to wage differences across education groups and generations?

Education can affect wages through two connected channels: the skills workers acquire and the market price of those skills. Expanding access can increase educational attainment and the supply of educated workers, while changes in teaching resources can affect human capital. Goal: study both channels in Spain by linking historical education indicators to individual wage data.

## Data and contribution

- **Historical education series, 1900–2022:** enrolment, graduation, student–teacher ratios, and public expenditure by education stage, assembled and harmonised from Spanish statistical yearbooks, censuses, ministry publications, and public expenditure accounts. The overview figure shows decadal averages.
- **Spanish Wage Structure Survey (EES), INE:** seven survey waves—1995, 2002, 2006, 2010, 2014, 2018, and 2022—with harmonised education, wage, hours, and demographic variables.
- **Real hourly wages:** constructed from gross annual earnings and contracted annual hours, with CPI adjustment to a 2022 price base.

The contribution combines historical data construction, survey harmonisation, and a framework connecting education conditions to wage outcomes.

## Empirical approach

1. **Construct education indicators.** Gross enrolment rates proxy educational expansion. Reversed student–teacher ratios and expenditure per student proxy schooling resources. Resource measures are considered separately and as a composite.
2. **Link schooling environments to workers.** Approximate schooling periods are constructed from age categories and assumed school-leaving ages. Five-year exposure periods link historical indicators to the wage survey.
3. **Estimate cell-level wage relationships.** Survey-weighted means form education–cohort–year cells. Regressions include education-by-year fixed effects and examine sensitivity to age and gender composition. The thesis reports 149 cells in the main dataset.
4. **Apply nested CES accounting.** Compare baseline labour supplies with supplies adjusted for cohort-specific schooling resources, and recover the relative demand shifts implied by each specification.

The CES model groups workers into primary-or-less, secondary, and a broad vocational/tertiary category. Its original “dropout”, “high school”, and “college” labels refer to these operational groups; “college” is not limited to university graduates.

## Selected findings

- **Expansion and wages:** greater expansion is associated with lower wages for secondary and higher-education groups in the main within-education-year specification. Adding demographic composition controls changes these relationships substantially, so the coefficients require a cautious interpretation.
- **Measuring schooling resources matters:** student–teacher ratios and expenditure per student produce different patterns. The estimated quality relationships are sensitive to the proxy and to cohort composition.
- **Quality adjustment leaves the CES demand paths broadly similar:** under the thesis calibration, adjusting labour supplies for the student–teacher quality index slightly increases the variance of implied relative demand shifters.

| Implied demand shifter | Baseline variance | Quality-adjusted variance |
| --- | ---: | ---: |
| Secondary relative to primary-or-less: ln(B_H/B_D) | 0.0484 | 0.0534 |
| Broad vocational/tertiary group relative to the lower-skill composite: ln(B_C/B_N) | 0.5797 | 0.5911 |

*Source: Table 5.4. Substitution elasticities are calibrated at 2.8 for the lower nest and 1.4 for the upper nest. The resource adjustment assumes a 5% productivity change per standard deviation of the quality index; it is not an estimated productivity effect.*

## Selected figures

### 1. A century of educational change

![Long-run education trends in Spain](figures/01_education_trends.png)

Enrolment, students per teacher, graduation indicators, and expenditure per student show different dimensions of Spain's educational development. These are gross enrolment and graduation indicators; enrolment rates can exceed 100%. Students per teacher measure resource intensity, rather than classroom size directly.

### 2. Wage differences across education levels

![Mean log real hourly wages by education level](figures/02_wages_by_education.png)

Survey-weighted mean **log real hourly wages** for seven harmonised education categories. The vertical axis is in log units, not euros. The chart describes wage differences across groups and survey waves; it does not estimate causal returns to schooling.

### 3. Resource adjustment in the lower CES nest

![Implied demand shifts in the lower CES nest](figures/03_ces_lower_nest.png)

Baseline and quality-adjusted implied demand shifters for secondary education relative to primary-or-less. The two paths remain close under the calibration. H and D are the model's secondary and primary-or-less groups.

### 4. Resource adjustment in the upper CES nest

![Implied demand shifts in the upper CES nest](figures/04_ces_upper_nest.png)

The corresponding comparison for the broad vocational/tertiary group C relative to the lower-skill composite N. These demand shifters absorb factors beyond measured labour supplies, including institutions and measurement error; they do not identify technological change separately.

## Interpretation and scope

This is an observational analysis and calibrated accounting exercise. It does not identify the causal effect of a particular education reform. Schooling exposure is approximated from age bins, resource inputs are imperfect proxies for learning, and CES conclusions depend on assumed elasticities and productivity scaling. Changes in survey coverage also matter for comparisons across waves.

## Sources

- Instituto Nacional de Estadística (INE), [Encuestas de estructura salarial: results and microdata](https://www.ine.es/dyngs/INEbase/operacion.htm?c=Estadistica_C&cid=1254736177025&idp=1254735976596&menu=resultados). Wage figures are the author's calculations using INE data.
