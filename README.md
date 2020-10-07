# AraKSUvec

Here you can fine the genertaed word embeddings for AraKSUvec from King Saud University Corpus of Classical Arabic (KSUCCA) :
https://mahaalrabiah.wordpress.com/2012/07/20/king-saud-university-corpus-of-classical-arabic-ksucca/

### We trained KSUCCA with word2vec models ( CBOW and SG) twice, the first time with row text and the second time with weaksupervision using POS tags.
### The used hyperparameters were ( 5 for window size) and ( 300 for dimentions) as defalte settings and we trained with range of epoches from 5 to 50)

# Unsupervised models (row text):


## KSUCCA - CBOW 


Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
CBOW        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/pm2d6rx0axt48o3/KSU_CBOW_300_5.zip?dl=0) |
CBOW         | 10 | **300**          | 5        | [Download](https://www.dropbox.com/s/pm2d6rx0axt48o3/KSU_CBOW_300_5.zip?dl=0) |
CBOW        | 20 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/pe1n3qq11lsv9fy/KSU_CBOW_300_20.zip?dl=0) |
CBOW        | 30  | **300**           | 5	        | [Download](https://www.dropbox.com/s/pe1n3qq11lsv9fy/KSU_CBOW_300_20.zip?dl=0) |
CBOW        | 40 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/pe1n3qq11lsv9fy/KSU_CBOW_300_20.zip?dl=0) |
CBOW        | 50 | **300**           | 5         | [Download](https://www.dropbox.com/s/cfffboh0hjp1ahl/KSU_CBOW_300_40.zip?dl=0) |

## KSUCCA - SG 

Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
SG        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/cfffboh0hjp1ahl/KSU_CBOW_300_40.zip?dl=0) |
SG         | 10 | **300**          | 5        | [Download](https://www.dropbox.com/s/cfffboh0hjp1ahl/KSU_CBOW_300_40.zip?dl=0) |
SG        | 20 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/exnrjl5cuvry6k4/KSU_SG_300_20.zip?dl=0) |
SG        | 30  | **300**           | 5	        | [Download](https://www.dropbox.com/s/exnrjl5cuvry6k4/KSU_SG_300_20.zip?dl=0) |
SG        | 40 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/exnrjl5cuvry6k4/KSU_SG_300_20.zip?dl=0) |
SG        | 50 | **300**           | 5         | [Download](https://www.dropbox.com/s/fdg4jje3v7um5lz/KSU_SG_300_50.zip?dl=0) |

***

## POS weak supervision

## KSUCCA-POS - CBOW 

Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
CBOW        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/fdg4jje3v7um5lz/KSU_SG_300_50.zip?dl=0) |
CBOW         | 10 | **300**          | 5        | [Download](https://www.dropbox.com/s/18vpp1wb1ekvl4g/KSU_POS_CBOW_300_10.zip?dl=0) |
CBOW        | 20 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/18vpp1wb1ekvl4g/KSU_POS_CBOW_300_10.zip?dl=0) |
CBOW        | 30  | **300**           | 5	        | [Download](https://www.dropbox.com/s/18vpp1wb1ekvl4g/KSU_POS_CBOW_300_10.zip?dl=0) |
CBOW        | 40 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |
CBOW        | 50 | **300**           | 5         | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |


## KSUCCA-POS - SG

Model     | Epochs.   	  | Dim No.              | wnidow size.        		| Download      |
-----     | --------   	  | --------             | ----------          	    | --------- 	|
CBOW        | 5 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |
CBOW         | 10 | **300**          | 5        | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |
CBOW        | 20 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |
CBOW        | 30  | **300**           | 5	        | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |
CBOW        | 40 | **300**           | 5 	        | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |
CBOW        | 50 | **300**           | 5         | [Download](https://www.dropbox.com/s/0ko496zkh8qkql2/KSU_POS_CBOW_300_40.zip?dl=0) |



