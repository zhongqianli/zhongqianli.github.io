# github项目列表 https://zhongqianli.github.io

## CSDN博客: [https://blog.csdn.net/zhongqianli](https://blog.csdn.net/zhongqianli)

## github地址: [https://github.com/zhongqianli](https://github.com/zhongqianli)

**PS: 点击项目名称可以跳转到相应的repository**

### [**keras-retinanet**](https://github.com/zhongqianli/keras-retinanet)
Trainning a face detector by transfer learning based on keras-retinanet.

### [**iris_detection-resnet10_ssd**](https://github.com/zhongqianli/iris_detection-resnet10_ssd)
基于resnet10+ssd的虹膜检测，利用迁移学习技术，用opencv dnn的face detector模型训练iris detector。

### [**iris_detection-adaboost_lbp**](https://github.com/zhongqianli/iris_detection-adaboost_lbp)
基于adaboost + lbp的虹膜检测。

### [**caffe_vgg**](https://github.com/zhongqianli/caffe_vgg)
用pycaffe实现了《Very Deep Convolutional Networks for Large-Scale Image Recognition》提出的VGG网络

### [**caffe_googlenet**](https://github.com/zhongqianli/caffe_googlenet)
用pycaffe实现了《Going Deeper with Convolutions》提出的GoogleNet，并在cifar10数据集上训练模型。 该作者受到NiN网络的启发，提出了一种高效的深度学习框架。使用了1x1卷积（bottleneck），用于增加网络的宽度和深度，以及减少计算量。Inception模块是在naive inception的基础上加入了1x1卷积，可以有效降低计算复杂度。最后使用了avg pool。 网络的设计遵循了这样的规则：视觉信息应该在不同尺寸进行处理，然后将它们合并在一起供下一阶段使用。

### [**caffe_resnet**](https://github.com/zhongqianli/caffe_resnet)
用pycaffe实现了《Deep Residual Learning for Image Recognition》提出的ResNet，并在cifar10数据集上训练模型。

### [**caffe_python_layer**](https://github.com/zhongqianli/caffe_python_layer)
使用python layer自定义数据增强层，对于准确率的提升有一定的效果。

### [**cifar10_classification**](https://github.com/zhongqianli/cifar10_classification)
opencv的dnn模块使用caffe训练的cifar10分类模型进行图像识别

### [**transfer_learning**](https://github.com/zhongqianli/transfer_learning)
使用keras实现transfer learning，使用了cifar10数据库和vgg16模型。

### [**image_focus_assessment**](https://github.com/zhongqianli/image_focus_assessment)
虹膜图像清晰度评估

### [**morph_snakes(C++版本)**](https://github.com/zhongqianli/morph_snakes) 和  [**MorphGAC（matlab版本）**](https://github.com/zhongqianli/morph_snakes)
根据论文《A Morphological Approach to Curvature-Based Evolution of Curves and Surfaces》实现了MorphGAC

### [**local_binary_pattern**](https://github.com/zhongqianli/local_binary_pattern)
用python和c++实现了原始的LBP、圆形LBP、旋转不变的圆形LBP、等价模式的圆形LBP、旋转不变的等价模式的圆形LBP。python版本LBP用于模型训练，c++版本LBP用于模型部署。

### [**svm_classification**](https://github.com/zhongqianli/svm_classification)
svm_classification是一个通用的svm模型训练框架，稍加修改即可变成一个通用的机器学习模型训练框架。方便快速训练机器学习模型，可重复使用，避免重复写代码。
