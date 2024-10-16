# 基于深度学习的验证码识别系统

本项目将使用多种 `降噪算法` `分割算法` `神经网络` 来对不同的验证码进行识别

</br>

## 验证码类别

- [x] 分离数字验证码

![0001](assets/0001.png)

降噪算法: **灰度峰值滤波**

分割算法: **列扫描断点分割**

训练集: 约3000张

测试集: 约7000张

神经网络架构:

* `CustomNet`
    * Epoch: 100
    * Accuracy: 0.86112
* `AlexNet`
    * Epoch: 50
    * Accuracy: 0.89516

</br>

</br>

- [ ] 贴合数字验证码

![0007](assets/0007.png)



</br>

</br>

- [ ] 紧凑数字字母验证码

<img src="assets/556wd.png" alt="556wd" style="zoom:150%;" />

</br>

</br>

- [ ] 会赢吗? 会赢的。

<img src="assets/image-20241016171416571.png" alt="image-20241016171416571" style="zoom:15%;" />



