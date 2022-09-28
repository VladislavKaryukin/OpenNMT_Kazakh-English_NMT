# OpenNMT_Kazakh-English_NMT

The OpenNMT framework for training parallel Kazakh – English parallel corpora. [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7118550.svg)](https://doi.org/10.5281/zenodo.7118550)

The kk_en_corpora folder contains files with train, valid, test, and predicted texts for the word tokenization and BPE models.

The Configuration folder includes yaml files for RNN, BRNN, and Transformer NMT models.

The quality of the trained model is evaluated with the BLEU, WER, and TER metrics given in the Translation results folder.

Architecture | BLEU | WER | TER | 
| :---:   | :---: | :---: | :---: |
RNN_word_tokenized | 0.45 | 0.55 | 0.48 | 
BRNN_word_tokenized | 0.43 | 0.58 | 0.47 | 
RNN_bpe| 0.37 | 0.62 | 0.55 |
BRNN_bpe | 0.49 | 0.51 | 0.45 |
Transformer_bpe | 0.42 | 0.58 | 0.51 |

The OpenNMT training and translating commands are provided on the official web-site.

https://opennmt.net/OpenNMT-py/quickstart.html
