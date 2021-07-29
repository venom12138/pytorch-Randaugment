# pytorch-Randaugment
On cifar100, use
```
CUDA_VISIBLE_DEVICES=0 python3 train_rand.py --no 0 --name Randaug_200ep --dataset cifar100 --model wideresnet --layers 28 --widen-factor 10 --droprate 0.3 --randaugment --cos_lr --N 2 --M 14 --CIFAR_Batch 128 --CIFAR_Norm --drop_last --rcutout 16
```
We achieve 83.38% accuracy on Cifar100.
