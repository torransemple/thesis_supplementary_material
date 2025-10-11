# The Modern Problematisation of Fuel Poverty in England: Quantification, Obfuscation and Energy Transitions

## Project Overview
This repository contains supplementary files (R code and associated datasets) to reproduce the analyses presented in my PhD thesis (The Modern Problematisation of Fuel Poverty in England: Quantification, Obfuscation and Energy Transitions). This repository is relevant to the analyses in the following chapters:

### Chapter 4: 'An Empirical Critique of the LILEE Definition (Case Study II): Household Energy Security Survey'
This Chapter presents an empirical critique of the LILEE fuel poverty definition via the analysis of London survey data. The R code provided for this chapter concerns the Random Parameters Ordered Probit (RPOP) model (see Thesis: Table 4-4). The survey data have not been published at the request of the funder (Guy’s and St Thomas' NHS Foundation Trust); therefore, the Chapter 4 R code simply serves as an example of the RPOP modelling process. 

### Chapter 7: 'Developing and Validating Fuel Poverty Measurement Approaches using Synthetic Data'
This chapter develops a synthetic set of homes in Nottingham (referred to as 'Synthetic Nottingham Homes') with paired household income and energy costs variables. The aim of this exercise was to develop a realistic sample of homes that could be used to explore various fuel poverty-focused questions. To aid interpretability, the supporting R code for Chapter 7 is divided into two parts (i.e., part 'I' and 'II'): part I concerns the generation of the Synthetic Nottingham Homes (see Thesis: Sections 7.4 and 7.5) and part II describes the subsequent fuel poverty measurement experiments (see Thesis: Section 7.6). 

### Chapter 8: 'Testing the Responsiveness of Fuel Poverty Definitions to Changing Economic Circumstances' 
Chapter 8 presents a sensitivity analysis of competing fuel poverty definitions, including 10%, LIHC, LILEE and the thesis's preferred Two-Step formulation. The R code can be used to reproduce the sensitivity analysis scenarios and all output figures (see Thesis: Figures 8-1, 8-2, 8-3 and 8-4).  


## Data
The majority of data used in this analysis are publicly available and retrievable from UK Government domains (including ONS, DESNZ and DLUHC). Where possible, these data are also available in the "Data" folder of each chapter (for example, see thesis_supplementary_material/Chapter_7/I/Data).


## Repository Contents

### Chapter 4
* **`CH4_energy_security_model.Rmd`:** Is an R Markdown file containing the code for the energy security (RPOP) model estimation. 
* Note: as mentioned previously, the survey data are not included in this repository; therefore, the Chapter 4 code serves as an example of the modelling process only.

### Chapter 7 (Part I)
* **`CH7_I_synthetic_data_generation.Rmd`:** Is an R Markdown file containing the code underlying the synthetic data generation (i.e., the Synthetic Nottingham Homes), as presented in Thesis: Sections 7.4 and 7.5.
* **`Data`:** Is a folder containing a range of datasets used to inform the synthetic data generation process. 

### Chapter 7 (Part II)
* **`CH7_II_measurement_experiments.Rmd`:** Is an R Markdown file containing code to reproduce the fuel poverty measurement experiments, as presented in Thesis: Section 7.6.
* **`Data`:** Is a folder containing the complete data (i.e., a clean version of Synthetic Nottingham Homes) used in the fuel poverty measurement experiments.

### Chapter 8
* **`CH8_sensitivity_analysis.Rmd`:** Is an R Markdown file containing the code underlying the sensitivity analysis of competing fuel poverty definitions, as presented in Thesis: Sections 8.3 and 8.4). 
* **`Data`:** Is a folder containing a further version of the Synthetic Nottingham Homes data (specifically, Synthetic Nottingham Homes paired with the results of the CH7 (II) fuel poverty measurement experiments output).


## Usage

To ensure the code runs successfully and can correctly find the necessary data files, follow these steps:

1.  **Download:** Download the entire repository to your local machine.
2.  **Set Working Directory:** Open RStudio and set the working directory to the **root folder of the downloaded repository** (the folder containing `Chapter_4`, `Chapter_7`, and `Chapter_8`). In RStudio, use: `Session > Set Working Directory > To Source File Location...` (for an open .Rmd) or `Session > Set Working Directory > Choose Directory...`.
3.  **Install Dependencies:** Ensure all required packages (as listed in each Rmd file) are installed.
4.  **Run Code:** Open the desired R Markdown file (e.g., `Chapter_7/I/CH7_I_synthetic_data_generation.Rmd`). The file paths within the code are written to be relative to the repository root and should load the data from the respective `/Data` subfolders automatically.
5.  **Note on Chapter 4:** As a reminder, the Chapter 4 code is provided for demonstration only and **will not execute** without the original, proprietary survey data.

## Acknowledgments

Thanks go to a range of UK Government departments, especially ONS, DESNZ and DLUHC, for the provision of highly valuable, publicly available datasets. Thanks also go to University of Essex’s Institute for Social and Economic Research (for the provision of Understanding Society data) and Loughborough University’s Centre for Research in Social Policy (for the provision of MIS budgets).


## Contact

Feel free to get in touch with questions or feedback.

* **Email:** <torran.semple@nottingham.ac.uk>
* **Alternative Email:** <torranas@gmail.com>
