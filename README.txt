Note all code in this depended on the file structure being entirely different. Getting the code to function will likely require changing the file paths. 

The folder names should be self-explanatory for the most part. code not original contains code that is not written by me. code original contains code that is at least modified by me.
Federalist Papers contains the Federalist Papers in both unseparated and separated forms. russian short stories contains all original untranslated Russian texts used.
The txt documents are the original downloads. The word documents were used to better accomodate for DeepL's translation limits. deepl translations were the translations from deepl.
google translation was the output translations from Google Translate. init translations were translations from the University of Helsinki's model. 

In code not original:
adjusted translator.ipynb was the code used for generating trnaslations from University of Helsinki's model on Huggingface. The vast majority of the code was not used. 

In code original: 
federalist splitter was the preliminary method of splitting the Federalist Papers as it was downloaded as one document. There were adjustments needed to fix the errors of the outputs.
eng author identification xlmr was an attempt at using xlm-roberta as a classifier. It ultimately did not come to fruitition and is not used.
eng author id used BERT to classify in this document.
eng author id log reg contains the logistic regression and naive bayes classifiers. Code in this will need to change commented sections for all parts.

