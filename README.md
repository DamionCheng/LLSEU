# Lifelong Learning with Searchable Extension Units
## Project Structure
- /src: source code
- /dat: dataset

## Experiment Environment
```
conda env create -f requirements.yml
```

## Command to start experiment

The default is to use the same hyperparameters as in the paper

### run seu on the split CIFAR10
```
source run_cifar10_seu.sh
```
### run seu on the split CIFAR100
```
source run_cifar100_seu.sh
```
### run seu on the PMNIST
```
source run_pmnist_seu.sh
``` 
### run seu on the Mixture Dataset
```
source run_mixture_seu.sh
```