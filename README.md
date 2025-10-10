Twelve Years of Evidence: Modelling the Injury Severity of Single-Vehicle Collisions pre- and post-20mph Implementation in Edinburgh and Glasgow

Project Overview
This project models the injury severity of single-vehicle collisions pre- and post-20mph implementation in Edinburgh and Glasgow. The analysis was motivated by recent changes to traffic calming policy in both cities:

Edinburgh: A citywide, blanket 20mph speed limit was introduced on all city center roads from 2016 onwards.
Glasgow: Expanded its network of 20mph roads in 2016, but the approach was less radical than that adopted in Edinburgh.
The distinctness of the 20mph approaches in both cities allows intercity comparisons to be made concerning the efficacy of each 20mph approach. In particular, we were interested in the effect that each approach had on pedestrian safety (hence the focus on single-vehicle collisions—the vast majority of these are vehicle-pedestrian collisions in an urban context).

To assess the effectiveness of each 20mph approach, descriptive and statistical analyses were conducted during four distinct periods/scenarios:

Edinburgh pre-20mph intervention
Edinburgh post-20mph intervention
Glasgow pre-20mph intervention
Glasgow post-20mph intervention
This repository focuses specifically on the statistical analysis phase of the above study (i.e., the estimation of collision severity models across the four scenarios).

Road Safety Data Source:

The relevant road safety data were derived from the Department for Transport's (DfT) centralized database:

DfT Road Accidents and Safety Data (Contains public sector information licensed under the Open Government Licence v3.0).
Note: Significant data preprocessing was required to generate the final model datasets (see model_data), i.e., collision severity data per city per scenario. For more information on the data preprocessing methods used for the DfT's road safety data, please contact me at the address provided below.

Repository Contents
model_code: Contains R Markdown files with the code for the statistical analysis.
Edinburgh:
Edinburgh_models.Rmd: R Markdown file for Edinburgh models.
Glasgow:
Glasgow_models.Rmd: R Markdown file for Glasgow models.
model_data: Contains the processed datasets used for the statistical models. (Note: These are directly readable from the GitHub repository)
Usage
Download: Download the entire contents of the repository.
Access Model Code:
Open the R Markdown files in RStudio or a similar environment:
Edinburgh models: model_code/Edinburgh/Edinburgh_models.Rmd
Glasgow models: model_code/Glasgow/Glasgow_models.Rmd
Run the Code:
The model data are directly readable from the repository. You should not have to change the file pathname (however, if the data do not load, you can load directly from your own PC).
To run the R Markdown files successfully, ensure the following R packages are installed:
car
MASS
Rchoice
lmtest
Install these packages using install.packages(c("car", "MASS", "Rchoice", "lmtest")) in R.
Execute: Run the entire R Markdown file to reproduce the analysis.
Acknowledgments
The authors would like to acknowledge the UK Gov. DfT for their provision of publicly accessible road safety data.

Contact
Feel free to get in touch with questions or feedback.

Email: torran.semple@nottingham.ac.uk
Alternative Email: torranas@gmail.com
