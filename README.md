# ssd-pytorch1.8.0
VGG16_reducedfc.pth预训练模型下载地址：<https://s3.amazonaws.com/amdegroot-models/vgg16_reducedfc.pth>

将下载的模型文件放置于ssd源码目录中  wights/vgg16_reducedfc.pth

修改源代码中的错误：源代码地址：<https://github.com/amdegroot/ssd.pytorch> 论文地址：<https://arxiv.org/abs/1512.02325>

由于原作者代码中很多基于Torch1.8版本

!pip install torch==1.8 torchaudio==0.8.0 torchmetrics==0.8.0 torchtext==0.8.0 torchvision==0.9.0

