### Hi there 👋

This is Bin Li from Zhejiang University.

A photographer and a programmer!

一周工作安排，

周一完成，吃东西完成，测试完成，v1，v2数据集做完，得到coco格式的结果。

对齐各个部分的结果，比如python接口结果，SDK的结果，还有AGX的结果。

测试batch_test，并进行一个大致的分析。问一下写词关于ONNX如何进行转换的。

周二，开始思考，下一步要如何改进玩手机和吃东西两个模型。

玩手机应该重新标注玩手机部分，不玩手机的标出来手持物，这样可以极大地解决该问题。

此外，吃东西应该把batch_test中的负样本加上，重新看一下，关于不清楚和质量差的图片，到底是怎么一回事。

建立一个，完全体的数据格式，满足自己的各种需求。如果可以，就把玩手机给暂时放在disk1或者algo2里面，做好记录。

认真阅读HOI的方式，问一下远拧他是怎么做HOI的，把这个当做自己的一个基本工作。

吃东西建立基本数据集以后，测试yolo模型和resnet模型之间的性能差异。给云涛一个参考。









