设计并训练一个卷积神经网络（CNN）来分析狗狗图像，并据此准确区分它们的品种。当将一只狗狗的图像输入你的算法，它将被识别并估计为狗的品种，如果输入的图像是人，模型将识别为最相近的狗的品种。使用迁移学习来优化这一模型。



**下载数据集**



1、克隆存储库并打开下载的文件夹。

```
git clone https://github.com/udacity/cn-deep-learning.git
cd cn-deep-learning/dog-project
```



2、下载[狗狗数据集](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd101/v4-dataset/dogImages.zip) ，并将数据集解压大存储库中，地点为`项目路径/dogImages`. 

```
wget https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
unzip dogImages.zip
rm dogImages.zip
```



3、下载[人类数据集](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd101/v4-dataset/lfw.zip)。并将数据集解压大存储库中，位置为`项目路径/lfw `。

```
wget http://vis-www.cs.umass.edu/lfw/lfw.tgz
tar -xvzf lfw.tgz
rm lfw.tgz
```



4、为狗狗数据集下载 [VGG-16关键特征](https://s3.cn-north-1.amazonaws.com.cn/static-documents/nd101/v4-dataset/DogVGG16Data.npz) 并将其放置于存储库中，位置为`项目路径/bottleneck_features `。





