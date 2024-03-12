# Q-rung orthopair fuzzy three-way multi-criteria decision-making model for fuzzy concepts
These data sets are named Computer Hardware (Z1), Quality of red wine (Z2), Quality of white wine (Z3), Travel Reviews (Z4), Basketball Player (Z5), and Stock Price (Z6). Among them, Z1-Z4 are obtained from the UCI Machine Learning Repository (http://archive.ics.uci.edu/ml/datasets.php), and Z5 and Z6 are obtained from the KEEL-dataset repository (https://sci2s.ugr.es/keel/datasets.php). The data set Z1 contains 209 alternatives with six criteria: machine cycle unit (C1), minimum main memory (C2), maximum main memory (C3), cache (C4), minimum number of channels (C5), and maximum number of channels (C6). Among these, C1 is a cost criterion, while the others are benefit criteria. Z2 consists of 1599 alternatives with six criteria: volatile acidity (C1), citric acid (C2), density (C3), pH (C4), sulphates (C5), and alcohol (C6). Among these, C1, C3, and C4 are cost criteria, while the others are benefit criteria. Z3 includes 4898 alternatives with four criteria: density (C1), pH (C2), chlorides (C3), and alcohol (C4). Here, C1 and C3 are cost criteria, while the others are benefit criteria. Z4 has 980 alternatives with ten criteria: comments on the art galleries (C1), comments on dance clubs (C2), comments on juice bars (C3), comments on restaurants (C4), comments on museums (C5), comments on resorts (C6), comments on parks/picnic spots (C7), comments on beaches (C8), comments on theaters (C9), comments on religious institutions (C10). All ten criteria are benefit criteria. Z5 comprises 96 alternatives with five criteria: assists per minute (C1), height (C2), playing time (C3), age (C4), and points per minute (C5). All five criteria are benefit criteria. Z6 consists of 950 alternatives with ten criteria: Company1 (C1), Company2 (C2), Company3 (C3), Company4 (C4), Company5 (C5), Company6 (C6), Company7 (C7), Company8 (C8), Company9 (C9), Company10 (C10).

<div align="center">
  
| Data set | Cost criteria | Benefit criteria |
| :---: | :---: | :---: |
| Z1 | C1 | C2-C6 |
| Z2 | C1,C3,C4 | C2,C5,C6 |
| Z3 | C1,C3 | C2,C4 |
| Z4 | None | C1-C10 |
| Z5 | None | C1-C5 |
| Z6 | None | C1-C10 |

</div>

| Data set | Re | Ri | $\xi$ | W |
|----------|------|------|-------|-----|
| Z1       | $\{(0.93, 0.07), (0.07, 0.93), (0.13, 0.87),(0.04, 0.96),$ $ (0.05, 0.95), (0.05, 0.95)\}$ | $\{0.45,0.4,0.47,0.44,0.39,0.4\}$ | 0.5 | $\{0.18,0.15,0.23,0.13,0.15,0.16\}$ |
| Z2       | $\{(0.72, 0.28), (0.26, 0.74), (0.51, 0.49),(0.55, 0.45),$ $ (0.18, 0.82), (0.28, 0.72)\}$ | $\{0.45,0.4,0.47,0.44,0.39,0.4\}$ | 0.7 | $\{0.17,0.14,0.19,0.19,0.14,0.17\}$ |
| Z3       | $\{(0.86, 0.14), (0.42, 0.58), (0.89, 0.11),(0.39, 0.61)\}$ | $\{0.45,0.4,0.47,0.44\}$ | 0.6 | $\{0.2,0.32,0.18,0.3\}$ |
| Z4       | $\{(0.18, 0.82), (0.35, 0.65), (0.20, 0.80),(0.11, 0.89),$ $ (0.26, 0.74), (0.46, 0.54), (0.40, 0.60),(0.41, 0.59),$ $ (0.33, 0.67), (0.42, 0.58)\}$ | $\{0.45,0.4,0.47,0.44,0.39,$ $0.4,0.35,0.38,0.43,0.41\}$ | 0.8 | $\{0.08,0.11,0.08,0.06,0.1,$ $0.12,0.11,0.12,0.11,0.11\}$ |
| Z5       | $\{(0.37, 0.63), (0.72, 0.28), (0.51, 0.49),(0.34, 0.66),$ $ (0.40, 0.60)\}$ | $\{0.45,0.4,0.47,0.44,0.39\}$ | 0.9 | $\{0.2,0.2,0.18,0.2,0.22\}$ |
| Z6       | $\{(0.49,0.51), (0.72,0.28), (0.53,0.47),(0.37,0.63),$ $ (0.51,0.49), (0.55,0.45), (0.37,0.63),(0.48,0.52),$ $ (0.61,0.39), (0.45,0.55)\}$ | $\{0.45,0.4,0.47,0.44,0.39,$ $0.4,0.35,0.38,0.43,0.41\}$ | 0.9 | $\{0.1,0.09,0.1,0.1,0.11,$ $0.09,0.1,0.1,0.11,0.1\}$ |

