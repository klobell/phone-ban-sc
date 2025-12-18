# The Effect of Cell Phone Bans on Test Scores: A Synthetic Control Analysis of San Mateo High School

## Motivation

In July 2024, California passed AB 3216 requiring all school districts to develop cellphone use policies by July 2026. San Mateo High School implemented a phone ban in 2019, making it one of the few schools with multi-year post-treatment data. Its similarity to other high schools in the district makes it an ideal case for synthetic control analysis to estimate causal effects before widespread policy adoption.

## Key Findings

**Math:**
- p = 0.182
- Treatment effect: -2.18 percentage points
- Pre-treatment fit: RMSPE = 4.2% 

**ELA:**
- p = 0.091
- Treatment effect: -5.36 percentage points 
- Pre-treatment fit: RMSPE = 10.2%
- Note: Scores declined 2022-2024 but recovered to baseline by 2025

## COVID-19 Note

The phone ban at San Mateo High was implemented in 2019, shortly before the COVID-19 pandemic disrupted schools in spring 2020. All schools in the study—San Mateo High and its donor pool (Burlingame, Hillsdale, Aragon, Mills, Capuchino, Sequoia, Menlo-Atherton, Carlmont, Henry M. Gunn, and Palo Alto High)—followed similar closure and reopening timelines under shared county and state public health orders. Because pandemic-related disruptions were comparable across all schools, the synthetic control design accounts for these common shocks, mitigating concerns that differential COVID-19 responses confound the estimated treatment effects.

## Data Source

California Assessment of Student Performance and Progress (CAASPP) Research Files, available [here](https://caaspp-elpac.ets.org/caaspp/ResearchFileListSB?ps=true&lstTestYear=2025&lstTestType=B&lstCounty=00&lstDistrict=00000#dl).
