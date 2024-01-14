# CNN-Hyperparameter-optimization
## Designing, training and optimizing MLP NN

This project is an assignment made in the context of my Master studies

### Technologies

* Python
* Pytorch
* Numpy
* Matplolib
* Pandas
* Google colab

### Dataset

Fashion-MNIST dataset (source : https://github.com/zalandoresearch/fashion-mnist)
* 10 clothes' categories
* Training set : 55000 images
* Validation set : 5000
* Test set : 1000


### Roadmap

1) Data preprocessing
2) Data augmentation
3) Make the NN flexible to efficiently swipe hyper parameters
4) Searching for the best Hyper-parameters
      - Preprocess Wandb
      - Run four times Wandb. At each run, re adjust Hyper-parameters according to last run results
5) Evaluate the final model
