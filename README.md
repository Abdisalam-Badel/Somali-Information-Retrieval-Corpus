# Somali Information Retrieval Corpus: Bridging the Gap between Query Translation and Dedicated Language Resources

# This is the official GitHub for the paper: Somali Information Retrieval Corpus: Bridging the Gap between Query Translation and Dedicated Language Resources 
# The Repository contains:



1) Somali IR Evaluation Corpus: holds the documents, it has 2335 Somali text documents
2) Judgements: the number of documents judged against the total documents concerning the queries.
3) queries.txt: holds the queries used 16 in total.
4) Somali_Stop_Words.txt: the number of Somali stop words identified are in this file
5) Som_PRF_IR.py: this file contains the Psuedo relevance feedback technique implementation
6) Som_TF-IDF.py: the TF-IDF python file is in this file
===============================================================================================================



To use this file please first run the Som_index_creator.py, after that, you can 
either run the Som_TF-IDF.py or Som_PRF_IR.py, to see the performance of the system after you run one of these files,
you can run evaluation.py and change them with open('TF-IDF-Evaluation', 'r') as retrieved_file, this file based on your requirement
use the TF-IDF-Evaluation text file if you have run the Som_TF-IDF.py or PRF-Evaluation if you run the Som_PRF_IR.py.

# Please rename the corpus as Somali_IR_Evaluation_Corpus if you want to create an index by yourself, find the corpus name in the file: Som_index_creator.py.

Will update the Repository, and add more explanations about the use, near time.
