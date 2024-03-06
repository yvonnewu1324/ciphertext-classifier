### Ciphertext Classifier ###
Implemented two methods to classify ciphertext
- main.ipynb: Pretrained DistilBERT custom embeddings + pretrained DistilBERT. This model has a 88% validation accuracy and 87% on testing data.
- final.ipynb: Word2vec + BiLSTM + CNN and FastText + BiLSTM + CNN.  The accuracy hitting around 88% on the dev data.
### Dataset ###
The dataset is split to three categories: train, dev and test. The training and dev data has two columns `label` and `text`. Below is the data format:
| label | text| 
| ------------- | ------------- |
| 0	  | lkêcê yoúc cêêö y#êjl lw mówám Újám j Úêê# ütlk Úol lkêú z#ê ctöé8ú ówl xoóóú éê#xw#öê#c .  | 
| 1	 | yt2ê á#ê6tl lw ê2ê#úwóê x#wö #wÚtócwó 6wüó lw lkê mêú y#té lkjl lktc Úw86 öw2ê üw#mc . | 

The test data is unlabeled.
### Implement Detail ###
More detail can be find at `upload_document.txt`.