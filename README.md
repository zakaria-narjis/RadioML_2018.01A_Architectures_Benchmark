# RadioML_2018.01A_Architectures_Benchmark
📊 Benchmarking Machine Learning Architectures for RadioML (Radio Machine Learning) 📡
The models in this repository were trained on the RadioML 2018 dataset, which consists of a combination of three types of modulation schemes ('OOK,' '4ASK,' 'BPSK') and 26 Signal-to-Noise Ratio (SNR) levels. Each modulation-SNR combination is represented by a set of frames, with 1024 complex time-series samples per frame. In our training setup, we used 1024 frames for training (nf_train), 512 frames for validation (nf_valid), and 256 frames for testing (nf_test). This comprehensive dataset allows us to evaluate and benchmark the performance of different machine learning architectures for Radio Machine Learning tasks across various modulation types and SNR levels.

| Architecture   | Test Accuracy |
|----------------|--------------|
| CNN_NET        | 80.76%       |
| LSTM           | 81.68%       |
| RES_NET        | 78.92%       |
| LSTM_GRU       | 84.84%       |
| Transformer    | 75.47%       |
