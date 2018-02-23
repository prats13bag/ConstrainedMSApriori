_About the project_
===================

A python implementation for MS Apriori algorithm to find frequent itemsets from a given set of transaction data and parameters with following two constraints - 1. certain items can not be together in frequent itemset
2. frequent itemset must have certain items otherwise those itemsets without one of these items becomes infrequent

'input-data.txt' file contains only the transaction data
'parameter-file.txt" file contains MIS values of each of the items, SDC value, items which can not be together in usual set form, and a list of items among which one or more items must be in frequent itemset


_Steps to run the Program_
===========================

1. Please install python 3.6 interpreter from https://www.python.org/
2. Make sure that ConstrainedMSApriori.py file is at same directory as it is for "input-data.txt" and "parameter-file.txt" files
3. Please do not change names of "input-data.txt" and "parameter-file.txt" files, however their data can be changed inside
4. In windows machine, please open command prompt and navigate to the current working directory. Current working directory is the directory where all these 3 files are kept
5. Give the following command "ConstrainedMSApriori.py" or "python ConstrainedMSApriori.py"
6. A new file will be generated with name "output-data.txt" which will have the required result in the current working directory itself