# FinalProject_IR
There is 2 ipynb file:
- ScrappingDatee: Use to srapping dates from the tweets and save to file ../other-outputs/output.json. 
					but output.json only have around 4600 tweets, because 100000 tweets can't upload to github. 

- Search Engine.ipynb: Preprocess collection, build index, consult collection information, ranking and search. 
To use this file: 
 
 Step 0: Import library. 
 Step 1: Execute code block 1. lodad data from json. and take the original tweets 	
 Step 2: Block 2 is used to see the information about the collection. 
 Step 3: Function to update the collection and save to Tweets.tsv file. 
			this process takes a very long time to process, to save time, it's already done.  
			And don't execute this block, you can jump to steo 4. 
Step 4:	Load data from TSV in block 4. 
Step 5: Pre-processing the tweets, generate tokens and index by execute the block 6 and 7. 
Step 6: Execute block 8 to print the output. 
Step 7: Execute block 9  and 10 to see ranking score from tf-idf.
Step 8: Execute block 11 and 12 to see ranking from my score. 
 	
		