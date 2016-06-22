# Reccurent Attention Model

## Reccurent Attention Model
Reccurent Attention Model with Chainer based on the following paper  
[arXiv:1406.6247](http://arxiv.org/abs/1406.6247): Recurrent Models of Visual Attention [Volodymyr Mnih+ 2014]  

## Dependencies  
Python, Chainer, scikit-learn, tqdm  

## Usage  

```shellsession
➜ python train_wolstm.py -g -1  
```

![loss and accuracy](figure/ram_wolstm_log.png)

## Not implemetnted yet...  
* visualize the locations which the model predicted    
* multi-scale glimpse  
* models to solve "Translated MNIST" task  
