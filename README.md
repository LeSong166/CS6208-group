# CS6208 Group Project

## Requirement

We build this project by Python 3.8 with the following packages: 
```
numpy==1.21.2
pandas==1.3.5
PyYAML==6.0
torch==1.10.1
```

## Model training and Evaluation

If the environment is ready, please run the following commands to train model on the specific dataset from `{NYCBike1, NYCBike2, NYCTaxi}`.
```bash
>> cd ST-SSL
>> ./runme 0 NYCBike1   # 0 gives the gpu id
```

## Acknowledgement

The code in this repository is adapted from [ST-SSL](https://github.com/Echo-Ji/ST-SSL).

