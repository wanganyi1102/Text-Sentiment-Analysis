
Our implementations for existing methods and our proposed models are flled in their respective folders. 

Existing models:
- CNN
- BERT
- Bi RNN-CNN
- BLSTM
- Bi RNN

Proposed models:
BLSTM-CNN (BERT embedding)
BLSTM-CNN (GloVe embedding)

To run the models, replace the file paths with your own file paths. 

NNDL Project
├── 11000-14000.pickle
├── 14000-16000.pickle
├── 5000-8000.pickle
├── 8000-11000.pickle
├── CZ4042_video.MP4
├── data
│   ├── crowdflower
│   │   └── text_emotion.csv
│   ├── emotion
│   │   ├── test.txt
│   │   ├── train.txt
│   │   └── val.txt
│   ├── glove.6B.300d.txt
│   └── wassa
│       └── data
│           ├── testing
│           │   ├── anger-ratings-0to1.test.target.txt
│           │   ├── fear-ratings-0to1.test.target.txt
│           │   ├── joy-ratings-0to1.test.target.txt
│           │   └── sadness-ratings-0to1.test.target.txt
│           ├── training
│           │   ├── anger-ratings-0to1.train.txt
│           │   ├── fear-ratings-0to1.train.txt
│           │   ├── joy-ratings-0to1.train.txt
│           │   └── sadness-ratings-0to1.train.txt
│           └── validation
│               ├── anger-ratings-0to1.dev.gold.txt
│               ├── fear-ratings-0to1.dev.gold.txt
│               ├── joy-ratings-0to1.dev.gold.txt
│               └── sadness-ratings-0to1.dev.gold.txt
├── data10000_14999.pkl
├── data1_4999.pkl
├── data15000_20000.pkl
├── data5000_9999.pkl
├── existing models
│   ├── BERT
│   │   └── CZ4042_BERT (1).ipynb
│   ├── BiRNN
│   │   ├── birnn-crowdflower.ipynb
│   │   ├── birnn-emotion.ipynb
│   │   └── birnn-wassa.ipynb
│   ├── BiRNN-CNN
│   │   ├── crowdflower_brnn_cnn.ipynb
│   │   ├── emotion_brnn_cnn.ipynb
│   │   └── wassa_brnn_cnn.ipynb
│   ├── BLSTM
│   │   ├── Bi LSTM_emotions.ipynb
│   │   ├── BiLSTM_wassa.ipynb
│   │   └── blstm-crowdflower.ipynb
│   └── CNN
│       └── CZ4042_CNN.ipynb
├── our models
│   ├── BLSTM-CNN(BERT)
│   │   └── CZ4042_Bi_LSTM_CNN(BERT).ipynb
│   ├── BLSTM-CNN(glove)
│   │   ├── bilstm-cnn-glove-emotions.ipynb
│   │   ├── BLSTM_CNN(glove)_wassa.ipynb
│   │   └── k-fold-blstm-cnn-crowdflower.ipynb
│   └── BLSTM-CNN(glove)+attention
│       ├── bilstm-cnn-glove-att-crowdflower.ipynb
│       ├── bilstm-cnn-glove-att-emotions-predictions.ipynb
│       └── bilstm-cnn-glove-att-wassa.ipynb
├── PPT.gslides
├── Report.gdoc