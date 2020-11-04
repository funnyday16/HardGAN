# HardGAN: A Haze-Aware Representation Distillation GAN for Single Image Dehazing

## News

[2020/11/05] Our code released.

## Reuqirements

Pytorch >= 1.1.0

numpy >=  1.6.0

tensorboardX

## Quick start

+ 'mkdir checkpoint data NH_results training_log'
+ Download datasets into ./data folder
+ Use `bash run.sh`
+ If you train on REDIES datasets, please use train_phrase 1.
+ If you train on NTIRE2020， please train train_phrase 1 first. Then, copy trained trained parameter to G1 and G2(crop_size is [240, 240]).  Finetune G2.  Train G3 finally(crop_size is [960, 960]). You can choose whether to do data augmentation by aug_fog.py.

## Citation

If your find our research is helpful for you, please cite our paper.











