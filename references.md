## References: 
— Page 92, Neural Network Methods in Natural Language Processing, 2017.
- Jeffrey Pennington, Richard Socher, and Christopher D. Manning. 2014. GloVe: Global Vectors for Word Representation. [pdf] [bib]


## Model Genomes

### Text to Emoji
"LSTM 128; Dropout 0.3; LSTM 64; Dropout 0.2; Dense 32 relu; Dense 20 relu; Dense 5 softmax;"
"LSTM 128; Dropout 0.3; LSTM 64; Dropout 0.2; Dense 32 relu; Dense 20 relu; Dense 5 relu;"
"LSTM 64; Dropout 0.3; LSTM 32; Dropout 0.2; Dense 10 relu; Dense 5 softmax;"
### Twitter Emoji Prediction
"LSTM 256; Dropout 0.3; LSTM 128; Dropout 0.3; Dense 128 relu; Dense 64 relu; Dense 32 relu; Dense 20 softmax;"