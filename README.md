# DARTS_Changes
To carry out architecture search OR architecture evaluation on other datasets:
  Replace DARTS files in cnn folder with the files in this repository.
  Then follow DARTS instructions.


Architecture Search - datasets = fashion_mnist, cifar10, SVHN:

```python 
   cd cnn && python train_search.py --unrolled --dataset='fashion_mnist' 
```
  
Architecture Evaluation - datasets = fashion_mnist, cifar10, SVHN:

  cd cnn && python train.py --auxiliary --cutout --dataset='fashion_mnist'
