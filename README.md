# Implementation of seq2seq model for English to Mongolian translation

Deep neural network, sequence-to-sequence module is built using PyTorch library, with encoder, decoder and attention.

English sentences were translated manually by four people within a month period since there is no training data for English Mongolian sentence pair. The network model architecture is implementation of 'Neural Machine Translation by Jointly Learning to Align and Translate' by Bahdanau et al. 2014 paper. Encoder layer is bidirectional GRU cells with Embedding and Dropout, Decoder layer is GRU cells with Dropout and also contains Attention layer which is Linear module.
