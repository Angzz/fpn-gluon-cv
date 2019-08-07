# Feature Pyramid Network for Object Detection
Paper Link : https://arxiv.org/pdf/1612.03144.pdf

### Note : Our code has been merged into official [gluon-cv](https://github.com/dmlc/gluon-cv), we recommend the official version, details can be found: https://github.com/dmlc/gluon-cv/pull/494

This repo is an unofficial implementation of FPN in a [gluon-cv](https://github.com/dmlc/gluon-cv) style, we will follow up with the official code and please refer to the official tutorials for more information.

# Usage
1.Install the mxnet 
* pip install mxnet-cu92 --pre --upgrade

2.Clone this code and run the script
* 


# Results
### VOC07
* **e2e_fastercnn_fpn_resnet50_v1b_1x_voc0712** : mAP=0.8035 on VOC07 Test.
  * train-log : https://drive.google.com/open?id=1obMRJedBHXrNPZLsahiR6WMQyYJFnli0
  * models : https://pan.baidu.com/s/1JrQYMLCPXuWGViSokS1LLg
* **e2e_fastercnn_fpn_resnet101_v1d_1x_voc0712** : mAP=0.8301 on VOC07 Test.
  * train-log : https://drive.google.com/open?id=1Z7FeZ7fEuhYi1d4ExBlaLcJLl8RBSfFG
### VOC12
* **e2e_fastercnn_fpn_resnet50_v1d_1x_voc07++12** : Stay tuned!
  * train-log : https://drive.google.com/open?id=18NFrME-TM_8cvYTkKwtrqvcPCmZ5L-MG
### COCO17
* **e2e_fastercnn_fpn_resnet50_v1d_2x_coco17** : Stay tuned!

# Acknowledgements
Below repos give me a lot of inspiration
* https://github.com/msracver/Deformable-ConvNets
* https://github.com/guoruoqian/FPN_Pytorch
* https://github.com/facebookresearch/Detectron
