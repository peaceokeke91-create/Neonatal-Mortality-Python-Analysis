Neonatal Mortality Determinants in Nigeria

Analysis code for the manuscript:

"Socioeconomic and Geographic Determinants of Neonatal Mortality in Nigeria: A Cross-Sectional Analysis of the 2024 Nigeria Demographic and Health Survey"

Peace Chinenye Okeke and Precious Ifeoma Ugwu


Overview

This repository contains the complete Python analysis code used to produce all results, tables, and figures in the manuscript. The analysis uses survey-weighted logistic regression and concentration index methods to identify socioeconomic and geographic determinants of neonatal mortality in Nigeria.


Repository Contents

File Description
NEONATAL_MORTALITY_updated.ipynb Main Jupyter notebook with all analysis code
Figure1_NMR_by_zone.png Bar chart: Neonatal mortality rate by geopolitical zone
Figure2_concentration_curve.png Concentration curve showing wealth-related inequality
requirements.txt Python package dependencies


Requirements

· Python 3.14.6
· Packages listed in requirements.txt

Install dependencies:

pip install -r requirements.txt




Data Source and Access

This analysis uses the 2024 Nigeria Demographic and Health Survey (NDHS) Birth Recode file. The data are not included in this repository per the DHS Program data use agreement.

To reproduce this analysis:

1. Register at https://dhsprogram.com
2. Submit a data access request for the 2024 Nigeria DHS
3. Download the Birth Recode file (.dta format)
4. Place the file in your working directory
5. Update the data_path variable in the notebook to point to your file

Data Access Authorization: AuthLetter_230883



Usage

1. Clone this repository:
   
   git clone https://github.com/peaceokeke91-create/Neonatal-Mortality-Python-Analysis.git
   
2. Install dependencies:
   
   pip install -r requirements.txt
   
3. Obtain the NDHS data file from the DHS Program (see above)
4. Open the Jupyter notebook:
   
   jupyter notebook "Neonatal Mortality 2024.ipynb"
   ```
5. Update the data_path variable in Cell [2] to point to your NDHS .dta file
6. Run all cells to reproduce the analysis



Results Summary

The analysis produces:

· Table 1: Sociodemographic characteristics of the study population (n = 25,872)
· Table 2: Distribution of explanatory variables by neonatal death outcome
· Table 3: Neonatal mortality rate by geopolitical zone and place of residence
· Table 4: Bivariable survey-weighted logistic regression (crude odds ratios)
· Table 5: Multivariable survey-weighted logistic regression (adjusted odds ratios)
. Table 6: Decomposition of the gap in neonatal mortality between North West and South South
. Table 7: Decomposition of the gap in neonatal mortality between rural and urban areas
· Figure 1: Bar chart of NMR by geopolitical zone and place of residence
· Figure 2: Concentration curve showing wealth-related inequality
. Figure 3: Decomposition of the gap in neonatal mortality between North West and South South zones



License

This code is licensed under the MIT License. See the LICENSE file for details.



Citation

If you use this code in your research, please cite the associated manuscript.

Contact

Peace Chinenye Okeke
Email: peaceokeke91@gmail.com
ORCID: 0009-0006-2943-113X
