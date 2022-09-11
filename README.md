# Overview
Based on nlp (tf-idf), you give the machine key words that you want to search
and machine gives you names of the most relevant n number of papers and n number of sentences in those papers

# Libraries
PyPDF2, 
os, 
nltk, 
numpy

# Usage
Relocate the directory that contains papers to the working directory.
Your papers must be in txt format if they are not I wrote function that convert pdfs to txts
If your papers are in pdf format then execute the first cell that contains convert_pdfs_to_txt() function once

In the second cell that containt main(), you can choose how many top relevant documents or sentences you want to expect by changing following variables
By default their values are:
FILE_MATCHES = 5
SENTENCE_MATCHES = 10

When you have the directory in the right place execute all of the cells except the cell contains convert_pdfs_to_txt() function
Program will ask you the words that you want to search then it will find the most relevant papers and sentences in those papers
Program will create a Query_result.txt file in which there are the results of the query

There are several things you might want to print, you can choose things whether you like to print or not by playing with write_query_result_2txt():

If you want to quit the program enter "quit" as input
