# RA-survey-analysis

Author: Thorid Wagenblast

# Survey Analysis Repository

This repository contains the Python notebooks used for the data analysis for 'Who talks about flood risks and climate change adaptation? Analysis of social interactions in three countries' by Wagenblast et al. 2025 [https://doi.org/10.1111/risa.70213]. The repository also contains the data underlying the figures.

## Repository Structure

```
├── data_minibatch                      # folder containing the data used
    ├── processed                       
    ├── raw                             # minibatch of the data used            
├── notebooks                           # Stata do-file with econometric models
    ├── 0_Data_preparaption.ipynb       # Data preparation to generate processed from raw data files
    ├── 1_Analysis.ipynb                # Data analysis and outputs for paper
├── reports                             # outputs used in the article
    ├── figures                         # figures   
├── requirements.txt                    # packages used to run the code
└── README.md                           # This file

```

## Note on the Data
We used the SCALAR survey data for this analysis. In this repository, we provide a minibatch (subset) of the data. For more information on the full data, see [https://doi.org/10.17026/DANS-X9H-NJ3W].

## Citation

If you use this analysis, please cite:

Wagenblast, T., Ghorbani, A., Warnier, M., & Filatova, T. (2026). Who Talks About Flood Risks and Climate Change Adaptation? Analysis of Social Interactions in Three Countries. Risk Analysis. https://doi.org/10.1111/risa.70213

## Acknowledgements
This work was supported by the Dutch Research Council NWO VIDI grant number 191015. The survey data collection was supported by the European Research Council (ERC) under the European Union’s Horizon 2020 Research and Innovation Program (grant agreement number: 758014). 

## Contact
t.wagenblast@tudelft.nl, t.filatova@tudelft.nl
