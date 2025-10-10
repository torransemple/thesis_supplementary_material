# The Modern Problematisation of Fuel Poverty in England: Quantification, Obfuscation and Energy Transitions

## Project Overview
This repository contains supplementary files (R code and associated datasets) to reproduce the analyses presented in my PhD thesis (The Modern Problematisation of Fuel Poverty in England: Quantification, Obfuscation and Energy Transitions). This repository is relevant to the analyses in the following chapters:

### Chapter 4: 'An Empirical Critique of the LILEE Definition (Case Study II): Household Energy Security Survey'
This Chapter presents an empirical ciritque of the LILEE fuel poverty definition via the analysis of London survey data. The R code provided for this chapter concerns the Random Parameters Ordered Probit (RPOP) model (see Thesis: Table 4-4). The survey data have not been published at the request of the funder (Guy’s and St Thomas' NHS Foundation Trust); therefore, the Chapter 4 R code simply serves as an example of the RPOP modelling process. 

### Chapter 7: 'Developing and Validating Fuel Poverty Measurement Approaches using Synthetic Data'
This chapter develops a synthetic set of homes in Nottingham (referred to as 'Synthetic Nottingham Homes') with paired household income and energy costs variables. The aim of this exercise was to develop a realistic sample of homes that could be used to explore various fuel poverty-focused questions. To aid interpretability, the supporting R code for Chapter 7 is divided into two parts (i.e., part 'I' and 'II'): part I concerns the generation of the Synthetic Nottingham Homes (see Thesis: Sections 7.4 and 7.5) and part II describes the subsequent fuel poverty measurement experiments (see Thesis: Section 7.6). 

### Chapter 8: 'Testing the Responsiveness of Fuel Poverty Definitions to Changing Economic Circumstances' 
Chapter 8 presents a sensitivity analysis of competing fuel poverty definitions, including 10%, LIHC, LILEE and the thesis's preferred Two-Step formulation. The R code can be used to reproduce the sensitivity analysis secanrios and all ouput figures (see Thesis: Figures 8-1, 8-2, 8-3 and 8-4).  

## Data
The majority of data used in this analysis are publicly available and retrievable from Government domains (including ONS, DESNZ, DLUHC). Where possible, these data are also available in the "Data" folder of each chapter (for example, see thesis_supplementary_material/Chapter_7/I/Data)


## Repository Contents

### Chapter 4
* **`model_code`:** Contains R Markdown files with the code for the statistical analysis.
    * `Edinburgh`:
        * `Edinburgh_models.Rmd`: R Markdown file for Edinburgh models.
    * `Glasgow`:
        * `Glasgow_models.Rmd`: R Markdown file for Glasgow models.
* **`model_data`:** Contains the processed datasets used for the statistical models. (Note: These are directly readable from the GitHub repository)

## Usage

1.  **Download:** Download the entire contents of the repository.
2.  **Access Model Code:**
    * Open the R Markdown files in RStudio or a similar environment:
        * Edinburgh models: `model_code/Edinburgh/Edinburgh_models.Rmd`
        * Glasgow models: `model_code/Glasgow/Glasgow_models.Rmd`
3.  **Run the Code:**
    * The model data are directly readable from the repository. You should not have to change the file pathname (however, if the data do not load, you can load directly from your own PC).
    * To run the R Markdown files successfully, ensure the following R packages are installed:
        * `car`
        * `MASS`
        * `Rchoice`
        * `lmtest`
    * Install these packages using `install.packages(c("car", "MASS", "Rchoice", "lmtest"))` in R.
4.  **Execute:** Run the entire R Markdown file to reproduce the analysis.

## Acknowledgments

The authors would like to acknowledge the UK Gov. DfT for their provision of publicly accessible road safety data.

## Contact

Feel free to get in touch with questions or feedback.

* **Email:** <torran.semple@nottingham.ac.uk>
* **Alternative Email:** <torranas@gmail.com>
