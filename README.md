# alexnet_based_malimg
This is an implementation of alexnet based malware image based malware image classification


NOTICE NOTICE NOTICE


THE CODE INCLUDES LINKS TO THE FILES WHERE THEY ARE STORED ON THE CLOUD. THERE ARE ALSO LINKS HERE JUST IN CASE


I WILL BE HAPPY TO ANSWER ANY ISSUES ... OVER mubarik10@gmail.com

THE FILES ARE SEPARATED FOR  IT  WAS DIFFCULT TO WORKING THROUGH IT. I HAD TO MODULARIZE.

:) my laptop and I FOUND OUT THE HARD WAY WHY THEY CALL THEM BOTTLENECK ... 


ONLY 80 FEATURES FROM THE ALEXNET MODEL .. LINK https://mega.nz/file/AEVngSoY#Rve-XEpgY_FRUX3xnDh7IixNZM_KLL4MWRe7UyIcoUw

ORIGINAL DATASET ... LINK https://mega.nz/file/ZN8HDQoI#Shh3gwXYJoB_1HNBoJ1LeQdhe-JZ_2zJjn62MXhObgk


LINK TO THE 1000 FEATURE DATASET CREATED BY ALEXNET https://mega.nz/file/4MMxUIyT#iIk-qFoAdVf-Q-iZFRgbdSe73SzarG6Ae8tE6_Qln4s


link to the features folder: https://mega.nz/file/1EEHAICY#vJb4BBF1qCTHER-NSZe1UJMVgKx7k8pileTgAGe0zu0
the features folder is where the features data extracted from the other four models is stored


link for the 100 dataset created by alexnet
https://mega.nz/file/pE02WZ6L#otu1kbGaUgG-FDffX5QvjC-tt6s8gkigqYU37KqADms
-----------------------------------------------------------------------------------------------------------------------------------------------------------
ABOUT IPYNB NOTE BOOKS
-----------------------------------------------------------------------------------------------------------------------------------------------------------

THIS IS PART OF THE TERM PROJECT. IT WILL REALLY HELP IF ONE READS THE PAPER TO BETTER UNDERSTAND THIS.

IT HAS THE FOLLWING PARTS:


DATA AUGUMENTAION CODE --- THIS IS TO DO THE PRE-PROCESSING STAGE...ACCODIGN TO THE PAPER
    ----- IT CREATES A DATASET OF 1000 SAMPLES IN EACH FOLDER.
  
ALEXNET FEATURE EXRTRACTION:---- IT IS USED TO EXTRACT FEATURES FROM ALEXNET
      ----- IT EXTRACTED FEATRUES OF 1000 SAMPLES FROM THE FILES

ALL FEATURES FILES
        THIS FILE EXTRACTS FEATURES FROM OTHER 4 PRE-TRAINED MODELS
        IT RESULTS FOUR FOLDERS NAMED AFTER THE MODELS..EACH WITH 100 SAMPLE POINTS TENSOR FILESD


RANDOM FOREST ON ALEXNET
      THIS IS THE FILE THAT APPLIES RANDOM FOREST ALGORITHM ON THE FEATURE DATASET CREATED BY ALEXNET...EACH 1000 SAMPLES
      IT GIVE A RESULT OF 97% ACCURACY
        
RANDOM FOREST ON ALL THE FILES
      THIS IS THE ML CLASSIFICATION PART ON THE METHOD, AS DETAILDE ON THE PAPER
      IT SIMPLY APPLIES RANDOM FOREST ON THE SAMPLES EXTRACRTED FROM THE MODELS...ON 100 SAMPLES EACH
