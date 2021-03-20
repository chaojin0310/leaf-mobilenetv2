# LEAF: A Benchmark for Federated Settings

## Resources

  * **Homepage:** [leaf.cmu.edu](https://leaf.cmu.edu)
  * **Paper:** ["LEAF: A Benchmark for Federated Settings"](https://arxiv.org/abs/1812.01097)

## Datasets

CIFAR-100

  * **Overview:** Image Dataset
  * **Details:** 100 different classes 20 different super classes, images are 3072 pixels(32 * 32 * 3 and preprocess to make them all 224 by 224 pixels), 600 users
  * **Task:** Image Classification

## Notes

- Install the libraries listed in ```requirements.txt```
    - I.e. with pip: run ```pip3 install -r requirements.txt```
- Go to directory of respective dataset for instructions on generating data
    - in MacOS check if ```wget``` is installed and working
- ```models``` directory contains instructions on running baseline reference implementations
