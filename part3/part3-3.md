## 3.3 SSD Caffe模型转换时遇到不支持的算子
### 问题描述
SSD Caffe模型转换时，提示有不支持的算子，如下图所示。
![图3-5模型转换有不支持算子](./img/3-5.jpg)


### 解决方法
模型转换提示界面中表格拖到最下面，查看不支持的算子，如下图所示。
![图3-6查看不支持算子](./img/3-6.jpg)


提示DetectionOutPut算子不支持，在右边Suggestion一栏点击下拉框选择对应当前网络对应的DetectionOutput算子即可转化成功。

