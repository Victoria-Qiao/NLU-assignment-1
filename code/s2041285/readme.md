For question 5:
Make sure nltk is installed in your environment 
1. Use the following command line to run “part-of-speech” module to generate training and development data files which convert sentences into sequences of tags of part of speech, you can find “tag_train.txt” and “tag_dev.txt” in your data folder after finishing running code.

python rnn.py part-of-speech ../data /wiki-train.txt tag_train.txt
python rnn.py part-of-speech ../data /wiki-dev.txt tag_dev.txt

2. Put the provided “tag.wiki.txt” in the folder which “tag_train.txt” and “tag_dev.txt” locate in
3. Use command line to run “train-np-part-of-speech” module to train the model based on ‘tag_train.txt’ and test the model using ‘tag_dev.txt’

python rnn.py train-np-part-of-speech ../data 50 2 0.5
