# Research year

Hello world!
This is my first attempt at creating something usefull for openly sharing. In my work as a research year student through Aarhus University, Denmark at Aarhus University Hospital, Denmark, I've been introduced to working in the programming language R.
During this work I've come accross a few problems apparently unique for the work with data from the Danish medical databases. To analyse the data in R I've had to rewrite some commands and to write my own, so I thought that I should share them here for others to take advantage of. Nothing fancy, but hopefully you can skip af few steps on your way through data analysis.


For a start I've uploaded five commands for extracting data from cpr-numbers:
- age_calc_function.R
- cpr_check_function.R
- cpr_sex_function.R
- date_convert_function.R
- dob_extract_cpr_function.R

All of these commands are written to work with the Danish Central Person Registry (CPR) numbers of the format ddmmyy-xxxx.


# Further research

In need of a suitable function to perform the chi-squared test of Hardy-Weinberg-equillibrium in my study poppulation, I ended up writing my own. It also contains a few summarise functions. This is actually the function I am most proud of, as it represents an actual universal test for both bi- and triallelic sustems in non-sexcromosome genes.

- hwe_allele.R -- requires input in the form of two vectors with alleles listed

