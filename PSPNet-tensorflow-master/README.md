# PSPNet_tensorflow
## Introduction
  This is an implementation of PSPNet in TensorFlow for semantic segmentation on the [cityscapes](https://www.cityscapes-dataset.com/) dataset. We first convert weight from [Original Code](https://github.com/hszhao/PSPNet) by using [caffe-tensorflow](https://github.com/ethereon/caffe-tensorflow) framework.

## Inference
To get result on your own images, use the following command:
```
python inference.py --img-path=./input/test.png --dataset cityscapes  
```
Inference CPU time:  ~6s 

Options:
```
--flipped-eval 
--checkpoints /PATH/TO/CHECKPOINT_DIR
```

## References:
