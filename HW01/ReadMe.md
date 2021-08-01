Home Work1的结论

1、我实现了L1和L2 loss function（L1就是Mean Absolute error、L2就是mean squarriel erro）；结论是，L1比L2好，因为模型的loss降得更低，在0.76左右。如果使用L2的话，loss在0.86左右。

2、我完成了挑选特征（Using 40 states & 2 tested_positive features）；结论是使用两个tested_positive后，模型的loss不降低，反而上升了。感觉这个参数target_only=False，对最终的结果影响不大。

3、我尝试了几种不同的网络结构，添加了很多Linear层，和ReLU层，结论：效果没有什么提升。

4、根据Figure 2 "Ground Truth v.s. Prediction"。感觉模型预测的结果在y=x附近，也就是说模型的预测能力还是不错的。但是我使用了浑身解数，也只能将loss降低到0.69，不知道该怎么办了。先这样的。2021年8月1日12:57:11。

5、课程的学习笔记在个人Blog中，有几个知识点：critical point包含了local minimal和saddle point。如何训练神经网络，先看train loss和test loss，然后尝试不同的model（消除model的bias）、然后再尝试不同的loss function。 

