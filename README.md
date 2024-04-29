# Depression-In-Tweets

## Prerequisites
* Python 3
* CPU or NVIDIA GPU + CUDA CuDNN

##Getting started
* Please Install PyTorch and the other relevant dependencies.
* Please run the command `pip install -r requirements.txt.`

##Dataset
The data folder contains tweet IDs corresponding to severities of depression collected from Twitter. Owing to Twitter's policy on data sharing, we can not directly upload the dataset and are only restricted to sharing tweet-id's here. 


* Go to the Scripts directory:
```cd Scripts```

* Place the dataset in the ../Dataset/ folder and run the command:
```python dataset.py```

##Training and Evaluation

* Go to the Scripts directory:
```cd Scripts```

* Train stand-alone model (BERT-base-uncased) with GPU support:
```python train.py```


