# Federated-Learning-PyTorch-master_verJy

# 1. Federated Learning with EMG(exponent moving averaging)
- federated learning paper : communication-efficient learning of deep networks from decentralized data
- In Federated learning experments, parameters were used to add exponential moving averages
 
# 2. option
- dataset : MNIST, Fashion MNIST, CIFAR-10
- hyper parameter( in option.py)
     ## EMG option 
    - mode : moving average mode ( on / off ) 
    - alpa : number of start weight value ( 0.1 - 0.99 )
    - alpa_weight : number of alpa weight ( 0.1 - 0.99 )
    ## Federated learning option
    - epoch : client epoch
    - round : server epoch
    - number_users : number of client
    - model : mlp / cnn
    - dataset : mnist / fmnist / cifar
    - gpu : gpu id 
    
    
# 3.runing 
first, You must checked out your options in option.py

    - python federated_main.py 
