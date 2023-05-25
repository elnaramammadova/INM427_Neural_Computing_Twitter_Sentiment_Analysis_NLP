# INM427_Neural_Computing_Twitter_Sentiment_Analysis_NLP

The code was written in a Google Colab (due to limitations of GPU in M1 MacBook Pro), running  Python 3.7.13. 
</br>
</br>
Code files: 
</br>PART1_PreProcessing.ipynb – codes for text preprocessing prior to feeding into the network. 
</br>PART2_BiLSTM.ipynb – all the codes for building and training BiLSTM model
</br>PART3.CNN.ipynb – all the codes used for building and training CNN model 

</br>
</br>
Please open files below and RUN ALL for testing. Since the way the dataset is shaped we have to run training and testing in one notebook. The training takes 2 minutes, so it won’t take too much time to run all the notebook. However, the downloading for glove embedding takes about 11 minutes. No need to run cells with !wget http://nlp.stanford.edu/data/glove.twitter.27B.zip and !unzip glove*.zip if it was run once prior. The Code was tested on Anaconda Jupiter notebooks to make sure everything is in running order. Additionally all the dependencies required to run the notebook will be downloaded at the beginning of the notebooks. 
</br>
TEST_CNN.ipynb
</br>
TEST_BiLSTM.ipynb

</br></br>
The full file list with the codes and the data can be found here: It is public to anyone with the link: 
https://drive.google.com/drive/folders/1l5kbVayw81EVSTGXUXhwo2UFe7w_88U7?usp=sharing

</br></br>
I could not include glove vectors in the submission section due to its size being too huge for the TurnitIn to accept. The link to the GloVe file can be found found here: 
https://drive.google.com/drive/folders/1i76rVQG4Mpit9CDcrVCCo3hF0NDV_nOd?usp=sharing

</br></br>
Original dataset could not be submitted either due to size limitation. Therefore only the preprocessed data with 50K samples were included in the submission which you can use to run both notebooks for testing. 
