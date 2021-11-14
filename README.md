# 1. Describe
## 1.1 Network Architecture
The architecture of our multi-branch Transformer network.
![architecture ](resources/AGMB.pn)
# 2. How to reproduce
## 2.1 Environmental preparation
Install dependency package
```
pip install -r requirements.txt -i https://pypi.mirrors.ustc.edu.cn/simple
```

## 2.2 Run the code
Step-1 : The training model was verified by three fold cross test.
```terminal
python train.py --train_batch_size 32 --gpus 0 1 2 3
```


## More details and complete code will be released once our paper is accepted.
