# KSUaravec

Here you can fine the genertaed word embeddings for KSUAravec from King Saud University Corpus of Classical Arabic (KSUCCA) :
https://mahaalrabiah.wordpress.com/2012/07/20/king-saud-university-corpus-of-classical-arabic-ksucca/

### We trained KSUCCA with word2vec models ( CBOW and SG) twice, the first time with row text and the second time with weaksupervision using POS tags.
### The used hyperparameters were ( 5 for window size) and ( 300 for dimentions) as defalte settings and we trained with range of epoches from 5 to 50)

# Unsupervised models (row text):


## KSUCCA - CBOW 
#### Epochs = 5


Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
CBOW        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/sh/1tvz8je9goebjq9/AAD1emSabZ5xO4wNngJWGm6va?dl=0) |
CBOW         | 10 | **300**          | 5        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_twitter.zip) |
CBOW        | 20 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_300_twitter.zip) |
CBOW        | 30  | **300**           | 5	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_100_twitter.zip) |
CBOW        | 40 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_300_wiki.zip) |
CBOW        | 50 | **300**           | 5         | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_wiki.zip) |




## KSUCCA - SG - Round(A)
#### Epochs = 5
Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
SG        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/sh/1tvz8je9goebjq9/AAD1emSabZ5xO4wNngJWGm6va?dl=0) |
SG         | 10 | **300**          | 5        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_twitter.zip) |
SG        | 20 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_300_twitter.zip) |
SG        | 30  | **300**           | 5	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_100_twitter.zip) |
SG        | 40 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_300_wiki.zip) |
SG        | 50 | **300**           | 5         | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_wiki.zip) |


***

## POS weak supervision


## KSUCCA-POS - CBOW 
#### Epochs = 5


## KSUCCA - CBOW 
#### Epochs = 5


Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
CBOW        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/sh/1tvz8je9goebjq9/AAD1emSabZ5xO4wNngJWGm6va?dl=0) |
CBOW         | 10 | **300**          | 5        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_twitter.zip) |
CBOW        | 20 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_300_twitter.zip) |
CBOW        | 30  | **300**           | 5	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_100_twitter.zip) |
CBOW        | 40 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_300_wiki.zip) |
CBOW        | 50 | **300**           | 5         | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_wiki.zip) |




## KSUCCA - SG 

Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
SG        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/sh/1tvz8je9goebjq9/AAD1emSabZ5xO4wNngJWGm6va?dl=0) |
SG         | 10 | **300**          | 5        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_twitter.zip) |
SG        | 20 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_300_twitter.zip) |
SG        | 30  | **300**           | 5	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_sg_100_twitter.zip) |
SG        | 40 | **300**           | 5 	        | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_300_wiki.zip) |
SG        | 50 | **300**           | 5         | [Download](https://bakrianoo.sfo2.digitaloceanspaces.com/aravec/full_grams_cbow_100_wiki.zip) |



