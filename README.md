# fuzzy_match_reporting

The purpose of this process is to identify exact duplicate entries and fuzzy duplicate entries under the Account object in the Salesforce CRM platform.
The identification of fuzzy duplicates is done through the use of the FuzzyWuzzy library, which utilities the levenshtein distance formula to identify
and quantify the probability that a fuzzy match is present in a dataframe. 

All data used in the example file in this document was created synthetically and there are no real world datapoints included. This was done for 
privacy purposes. The methodology holds with the synthetic data as it would with real world Salesforce data. All code blocks are complete with 
annotation that walks the user step-by-step through the process of identifying and reporting duplicate matches. 
