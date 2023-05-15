# LSTM Neural Network for Time Series Prediction

LSTM built using the Keras Python package to predict time series steps and sequences. Includes sine wave and stock market data.

[Full article write-up for this code](https://www.altumintelligence.com/articles/a/Time-Series-Prediction-Using-LSTM-Deep-Neural-Networks)

[Video on the workings and usage of LSTMs and run-through of this code](https://www.youtube.com/watch?v=2np77NOdnwk)

## Installations

Create python virtual environment for avoiding the version conflictions.

```bash
conda create --prefix ./env python=3.8 -y
conda activate ./env
```

Install requirements.txt file to make sure correct versions of libraries are being used.

* Python 
* TensorFlow 
* Numpy
* Keras 
* Matplotlib 

```bash
pip install -r requirements.txt
```


## Usage

Modify the config.json file to update the parameters or hyper-parameters of the dataset part or for training part.

For training and inferencing execute the below code over terminal.
```bash
python run.py
```

## Output 

Output for sine wave sequential prediction:

![Output for sin wave sequential prediction](https://www.altumintelligence.com/assets/time-series-prediction-using-lstm-deep-neural-networks/sinwave_full_seq.png)

Output for stock market multi-dimensional multi-sequential predictions:

![Output for stock market multiple sequential predictions](https://www.altumintelligence.com/assets/time-series-prediction-using-lstm-deep-neural-networks/sp500_multi_2d.png)

Output for stock market multi-dimensional full sequential predictions:

![Output for stock market multiple sequential predictions](https://www.altumintelligence.com/assets/time-series-prediction-using-lstm-deep-neural-networks/sp500_full.png)

Output for stock market multi-dimensional point by point predictions:

![Output for stock market multiple sequential predictions](https://www.altumintelligence.com/assets/time-series-prediction-using-lstm-deep-neural-networks/sp500_pointbypoint.png)

