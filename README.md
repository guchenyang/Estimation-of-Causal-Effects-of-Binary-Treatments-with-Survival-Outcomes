# Estimation of causal effects of binary treatments with survival outcomes

Comparing the performance of propensity score matching and SurvBART for binary treatments and survival outcomes

Propensity score matching:
(1) Greedy nearest neighbor matching;
(2) Nearest neighbor caliper matching (disallowing matching between units which differ by more than 2 standard deviations);
(3) Optimal full matchings (possible with a caliper).

Survival BART:
(1) BART and Cox proportional hazards regression;
(2) BART and Weibull regression;
(3) BART and accelerated failure time model.

