# resnet_dilate test
compare resnet with dilation using imagenet 1k  

using dilation, resnet18 top1 acc 70.2%


python main_dilate.py -a resnet18 ILSVRC/Data/CLS-LOC  
outputs/resnet_dilate.log  
maximum top1 acc : 70.2 % (0.5% more)  

python main.py -a resnet18 ILSVRC/Data/CLS-LOC
