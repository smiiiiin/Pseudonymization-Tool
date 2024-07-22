# Pseudonymization Tool for Data Privacy

Developed a pseudonymization tool designed to protect personal data from being exposed during the collection and analysis processes for marketing or market research purposes. This tool aims to prevent privacy breaches by substituting or generalizing outliers at the extremes of the normal distribution, thereby minimizing the risk of sensitive information exposure such as identification details or medical records. The core goal was to maximize data utility while minimizing potential damages from the disclosure of identifiable information. The program comprises a main window and 11 modules, processing data through pre-processing, pseudonymization, and post-processing stages.

## Key Contributions:

Pre-processing: Implemented modules for handling missing values by replacing them with data such as 0, Null, or NaN to facilitate subsequent pseudonymization.

### Pseudonymization Modules: Focused on the following key functions:
Aggregation: Replaced entire column values with statistical measures such as mean, minimum, maximum, median, or mode. <br>
Generalization: Rounded, random-rounded, or truncated numerical data to reduce granularity. <br>
Randomization: Added noise or errors to data to lower the degree of identification and prevent privacy breaches. <br>
Deletion: Assisted in pseudonymization by deleting rows or columns, and performing string trimming or masking. <br>
Additionally, authored a user manual to ensure that the developed program could be easily utilized by end users. 

