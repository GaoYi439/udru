# udru
[IJCAI'24] Unlearning From Weakly Supervised Learning

This code gives the implementation of the paper "Unlearning From Weakly Supervised Learning".

Requirements
- Python >=3.9
- PyTorch >=1.11

---
main.py
  >This is main function. After running the code, you would see a directory with the results saved in the same directory.

appenix.pdf
>The proof of the paper.

  
## Running

python main.py --dataset_name \<dataset name\> --lr \<learning rate\> --data_type \<data type\> --method \<unlearning method\>

**Methods and models**

In main.py, specify the method argument to choose one of the 3 methods available:
- udru
- kpriors
- retrain

Specify the dataset argument:
- mnist
- fashionmnist
- cifar10
