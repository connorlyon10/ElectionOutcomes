# Forecasting Election Outcomes in Contemporary Democracies

This repository contains the source code and PDF for the paper **“Forecasting Election Outcomes in Contemporary Democracies”**, a group thesis completed as a module of study for MSc Data Science at The University of Birmingham. 

The project achieved a Distinction, and was praised in particular for being ambitious, relevant and technically sound. Feedback confirmed that the project demonstrated “a solid understanding of machine learning, including PCA for dimensionality reduction and clustering for stratified modelling.”

---
## Summary
The project showed that the general state of a country, determined by its social & economic indexes, is a significant indicator in the outcome of an election. In short, we found that "when conditions worsen, people desire a change in government". This seems an obvious statement to make, but by proving it to be true, election outcomes are proven to be predictable.

The biggest issue in predicting election outcomes is data sparsity. Taking the UK as an example, an election is usually every four years, and data quality has only been reliable in the UK for the past 100-200 years. This means that the training data is limited to ~ 25-50 observations, which is not enough to train an adequately complex model.

One workaround for this was to collate the training data for multiple countries, and make a model that predicts each of them. However, the political climate between countries can have high variance, and data quality varies between country to country (many countries only recorded election data from 1990 onwards).

... (it was decided that multiple models would be made based on clustering of countries) (to-do) 

---
## Authors

The project wouldn’t have been possible without significant contributions from each of the following co-authors & collaborators:

- Connor Boyd‑Lyon  
- Evelina Ivanova  
- Matthew Randall  
- Yarkın Yorulmaz  
- Yeni Jung  
- Zehn‑Ul‑Abideen Sharif

---
## Maintenance
This repo, including the readme, aren't complete. The authors are currently completing projects independently. The repo is scheduled to be cleaned up in October 2025 when this work is complete.

This repo isn't actively maintained - it's simply an archive. Questions about the project are welcome.


---
## License & Citation
The project is licensed under the **MIT License** - it is free to use, if it benefits any future work. We ask that you give thanks to the authors:

```
@mastersthesis{electionforecasting2025,
  author       = {Connor Boyd-Lyon and Evelina Ivanova and Matthew Randall and Yarkın Yorulmaz and Yeni Jung and Zehn-Ul-Abideen Sharif},
  title        = {Forecasting Election Outcomes in Contemporary Democracies},
  school       = {University of Birmingham},
  year         = {2025},
  type         = {Group Thesis},
  note         = {MSc Data Science group project}
  url          = {https://github.com/connorlyon10/ElectionOutcomes}
}
```


