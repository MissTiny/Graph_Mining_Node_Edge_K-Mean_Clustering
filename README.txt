Following are the two python files, that are needed to run the experiment:

1. embeddings-generator.py
2. social-circles-discovery.py

Place both of these files in the same location for ease and then perform the following steps.

1. First we need to generate datasets and prepocess them in order to make them feasible for our approach 
   and for this purpose you need to run embeddings-generator.py file.
   
   a. Install node2vec package before running this script You can install it using following command:
      pip install node2vec or pip3 install node2vec

   b. Then run embeddings-generator.py file using following command:
      python embeddings-generator.py or python3 embeddings-generator.py

   c. After running this script, following two data files are generated:
      
      i. embedded-soc-sign-slashdot
      ii. soc-sign-Slashdot090221.txt.gz

2. The dataset files generated in previous step will be used as an input to social-circles-discovery.py file.
   Finally, to run the experiments using our approach you need to run social-circles-discovery.py script using
   following command:
   
   python social-circles-discovery.py or python3 social-circles-discovery.py

   Progress and results of the experiment will be printed on the console.
 