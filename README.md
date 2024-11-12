# MET
Machine Learning Methods for Predicting Evapotranspiration for Water Management.

# Summary
Ecological functioning in arid and semi-arid river basins is declining due to excessive water extraction by humans and climate change. Whilst environmental water allocations aim to mitigate this, monitoring changes in riverine trees at fine scales remains challenging, especially with fluctuating water availability across diverse climatic zones. To advance monitoring tools relevant to large river basins, we present two new machine learning methods, MET1 and MET2, that employ temporal remote sensing data to directly and accurately predict evapotranspiration in the Murray-Darling Basin for *Eucalyptus camaldulensis* and *E. largiflorens* trees across 23 study locations in the Lower Murray-Darling Basin. The highest performing model was MET2 using Gradient Boosting which obtained an $R^2$ of 0.84, and RMSE of 7.78, considerably improving upon the previously proposed AMLETT model. The results demonstrate the potential of machine learning technology to enhance accurate estimation of evapotranspiration. The MET1 and MET2 methods can be used to aid decision support to improve water management and prioritise environmental water allocations to protect and restore critical ecological assets within river basins and wetland regions worldwide.

# Contents
## Contents
- `Generate Figures/` - Directory to store the code to generate the figures in the paper.
- `MET1/` - Directory to store the code to reproduce the MET1 method.
- `MET2/` - Directory to store the code to reproduce the MET2 method.

## Software requirements
Running the scripts requires the libraries `sklearn`,  `numpy`,  `pandas`,  `matplotlib`, `scipy` and `os`.
\
This workflow is tested with Python 3.9.
