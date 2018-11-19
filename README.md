# kaggle_criteo_ctr_challenge-
This is a kaggle challenge project called Display Advertising Challenge by CriteoLabs at 2014.
这是2014年由CriteoLabs在kaggle上发起的广告点击率预估挑战项目。
使用TensorFlow1.0和Python 3.5开发。

代码详解请参见[jupyter notebook](https://nbviewer.jupyter.org/github/classtag/kaggle_criteo_ctr_challenge/blob/master/ctr.ipynb)


本文使用GBDT、FM、FFM和神经网络构建了点击率预估模型。

## 网络模型
![image](https://raw.githubusercontent.com/classtag/kaggle_criteo_ctr_challenge/master/model.png)

## LogLoss曲线
![image](https://raw.githubusercontent.com/classtag/kaggle_criteo_ctr_challenge/master/tensorboard.png)

## 验证集上的训练信息
 - 平均准确率
 - 平均损失
 - 平均Auc
 - 预测的平均点击率
 - 精确率、召回率、F1 Score等信息

![image](https://raw.githubusercontent.com/classtag/kaggle_criteo_ctr_challenge/master/train_info.png)

更多内容请参考代码，Enjoy！
