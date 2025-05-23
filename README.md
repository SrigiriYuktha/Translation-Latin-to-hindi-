# Translation-Latin-to-hindi-
For this , we have an input embedding size m=256, hidden state size k= 256 for both the encoder and decoder, input and output sequence length 𝑇=20, and vocabulary v=60. We use a single-layer LSTM for both the encoder and decoder, with greedy decoding during inference and no attention mechanism. The total number of computations performed by the network can be calculated using the formula 𝑇×[8𝑘(𝑚+𝑘)+𝑘𝑉].Substituting the values, we get 20×[8×256×(256+256)+256×60]=21,278,72020.Therefore, the total number of computations done by the network is approximately 21.28 million operations.


The total number of parameters in the network is calculated using the formula 2Vm+8k(m+k+1)+kV+V.Plugging in the values, we get 
2×60×256+8×256×(256+256+1)+256×60+60=1,100,4642×60×256+8×256×(256+256+1)+256×60+60=1,100,464 .Hence, the total number of parameters in the model is approximately 1.10 million.
