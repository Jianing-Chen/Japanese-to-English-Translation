# Japanese-to-English-Translation

To reproduce the project necessary setup needs to be installed in a Colab environment. 


The whole project is constructed using the d2l package which was generated from the Amazon team leadered by professor Li. Before reproducing the project you need to install the d2l package. 


pip install -U d2l 


However, the d2l package only supports matplotlib version 3.0.0, you may need to replace your matplotlib by pip install matplotlib==3.0.0


To download the dataset of Japanese to English, we install the datasets from pytorch.


pip install datasets.


To tokenize the Japanese sentences, we utilize the fugashi tokenization tool with pip install fugashi[unidic-lite].
