# The Modern Problematisation of Fuel Poverty in England: Quantification, Obfuscation and Energy Transitions

## Project Overview
This repository contains supplementary files (R code and associated datasets) to reproduce the analyses presented in my PhD thesis (The Modern Problematisation of Fuel Poverty in England: Quantification, Obfuscation and Energy Transitions). This repository concerns the following chapters:

### Chapter 4: 'An Empirical Critique of the LILEE Definition (Case Study II): Household Energy Security Survey'
This Chapter presents an empirical ciritque of the LILEE fuel poverty definition via the analysis of London survey data. The R code provided for this chapter concerns the Random Parameters Ordered Probit (RPOP) model (see Thesis: Table 4-4). 

### Chapter 7: 'Developing and Validating Fuel Poverty Measurement Approaches using Synthetic Data'
This chapter... To aid interpretability, the supporting R code for Chapter 7 is divided into two parts (i.e., part 'I' and 'II'), where part I concerns the generation of the Synthetic Nottingham Homes (see Thesis: Sections 7.4 and 7.5) and part II describes the subsequent fuel poverty measurement experiments (see Thesis: Section 7.6). 

### Chapter 8: 'Testing the Responsiveness of Fuel Poverty Definitions to Changing Economic Circumstances' 



## Data




## Repository Contents

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
