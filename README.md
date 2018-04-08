# Neural Machine Translation with Attention
This project implements Neural Machine Translation with Attention to translate Vietnamese sentences to English. It explores an LSTM seq2seq model with no attention, Dot Product Attention, Bilinear Attention and Feedforward Attention. Achieved a BLEU score of 20 after 20,000 epochs on the [IWSLT'15 English-Vietnamese dataset](https://nlp.stanford.edu/projects/nmt/).

<img src="images/attention_mechanism.jpg" width="500"/> <br />

**Sample Translation:** </br>
src: Thật là vinh hạnh cho tôi khi được đứng đây và cùng chia sẻ với mọi người </br>
ref: Well this is a really extraordinary honor for me . </br>
nmt: This is a really extraordinary honor for me

## Installation: ##
```
cd nmt-with-attention
sudo pip install virtualenv
virtualenv -p python3 .env          # Create environment
source .env/bin/activate            # Activate environment
pip install -r requirements.txt     # Install tf packages
pip install -r requirements_tf.txt  # Install python packages
jupyter notebook machine_translation_and_attention_tf.ipynb

deactivate                          # Deactivate environnment
```
