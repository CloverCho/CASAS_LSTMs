# Overview

This project is a fork of [deep-cases](https://github.com/danielelic/deep-casas/tree/master) which handles Deep learning and LSTM approaches for human activity recognition, which is included in the paper "A Sequential Deep Learning Application for Recognising Human Activities in Smart Homes" accepted for Neurocomputing journal.


## Data

The `data.py` script loads some [CASAS datasets](http://casas.wsu.edu/datasets/) and saves them into NumPy binary format files `.npy` for faster loading later.
```
python data.py
```

## Train

```
python train.py --v LSTM
python train.py --v biLSTM
python train.py --v Ensemble2LSTM
python train.py --v CascadeEnsembleLSTM
python train.py --v CascadeLSTM
```

