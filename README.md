# Populism Scores from Party Manifestos

This repository provides party-level populism scores constructed from political party manifestos using supervised machine learning and text analysis.

The scores are based on the Manifesto Project Database and combine Comparative Manifesto Project (CMP) policy components with sentiment and emotion measures. The resulting indices quantify populist rhetoric on a continuous scale and are available for:
- Overall populism
- Left-wing populism
- Right-wing populism

The dataset is designed for longitudinal and cross-national research in political economy, comparative politics, political communication, and electoral studies.

## Methodology overview

Populism scores are derived using a supervised learning framework trained on a curated sample of populist and non-populist parties. The approach integrates:
- CMP policy categories
- AI-based sentiment measures
- Dictionary-based sentiment and emotion indicators

Random forest models are estimated repeatedly to ensure stability of variable importance and predictions. Final populism scores are obtained by aggregating predictions across model runs and combining complementary importance metrics.

Full methodological details are provided in the associated working paper.

## Citation

If you use these data, please cite:

Nikolakakis, Nikolaos and Polyzos, Efstathios and Arin, Kerim Peren (2025).  
*Go Big or Go Home: How Populist Rhetoric in Party Manifestos Shapes Electoral Outcomes*.  
Available at SSRN: https://ssrn.com/abstract=5296231  
http://dx.doi.org/10.2139/ssrn.5296231

## Updates

This repository will be updated periodically to reflect new releases of the Manifesto Project Database and corresponding recalculations of the populism scores.

## License

This repository is released under the **MIT License**.

You are free to use, copy, modify, merge, publish, distribute, and adapt the contents of this repository for academic, policy, and non-commercial purposes, subject to the terms of the MIT License.

While the MIT License does not legally require citation, **academic use of these data requires appropriate citation**. If you use the populism scores, derived measures, or any outputs from this repository in academic work, policy reports, or related research, please cite:

Nikolakakis, Nikolaos and Polyzos, Efstathios and Arin, Kerim Peren,  
*Go Big or Go Home: How Populist Rhetoric in Party Manifestos Shapes Electoral Outcomes*  
Working Paper, June 15, 2025.  
Available at SSRN: https://ssrn.com/abstract=5296231  
DOI: http://dx.doi.org/10.2139/ssrn.5296231

The data provided here are **research outputs derived from the Manifesto Project Database** and related text-processing pipelines. They do not represent official positions or classifications of the Manifesto Project or its contributors.

This repository may be updated periodically to reflect new releases or revisions of manifesto data.

## Disclaimer

This repository uses data from the Manifesto Project Database. Responsibility for all interpretations, transformations, and derived measures lies solely with the authors.  
The Manifesto Project bears no responsibility for the analyses or conclusions presented here.

The populism scores provided in this repository are research outputs intended for scholarly use. They should not be interpreted as definitive classifications or endorsements of political actors.
