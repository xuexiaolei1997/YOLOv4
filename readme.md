# 环境配置
torch1.9 + cuda11
下载yolo4_voc_weights.pth，放入model_data

链接：https://pan.baidu.com/s/1NNmVvbWZHw3NA71wrkBmkw 
提取码：qzez

# 运行
运行predict.py
输入 img/person.jpg

# 训练
下载VOC2007数据集放到根目录下，运行voc_annotation.py，生成2007_train.txt
运行train.py

借鉴了B站博主的视频，主要是阅读源码使用。
