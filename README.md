# Loading-status-recognition-of-heavy-trucks-via-image-classification-algorithm

甲方消失第二弹：基于图像分类算法的空盘车载货状态识别

这次是在2022年下半年的一天,甲方打电话说有个挺急的项目需要我做。我说可以，他们下午就开车到我家附近的一个麦当劳见面。甲方的需求是要识别出通过关口的大货车上是否有集装箱等货物，并且模型要部署在他们现在使用的工控机上。对于这个项目我的想法是：1.大货车在通过关口时是一辆一辆分开通过的。就是每次都会只有一辆车停留在摄像机的视场内。这种情况用图像分类算法就可以了，没有必要动用目标检测。目标检测算法需要人工标注数据，费时费力，所以能不用我就尽量不用。2.甲方只有工控机CPU还可以是i5的（还算不错，之前有的甲方想在赛扬CPU的工控机上搞深度学习）。甲方也不接受再买GPU等设备。所以，分类模型+onnx+opencv的部署方式比较适合。下午回到家我就动手开始做数据集训练模型，晚上就做好了demo。和甲方也估算了工作量，签了一个合同。之后，就在也没有下文了。。。
由于模型没有实地部署，这次只开源了训练和测试的代码，一段演示视频，训练好的模型，还有测试用的数据集。代码是用pytorch做的，改改里面的路径就可以跑起来。希望能对你的开发和学习之路有所帮助。也希望你看了之后多提意见。在知识面前我们永远都是初学者。
链接：https://pan.baidu.com/s/1JXvf67Omkfl-XapMCRnb5A?pwd=elgy 
提取码：elgy 

Secondary disappearance of Party A: Loading status recognition of heavy trucks via image classification algorithm

In the second half of 2022, the Party A calls me and says that they have an very urgent work for me to do it. After my acceptance, we meet in a McDonald's near my house in the afternoon. Party A's requirement is to recognize whether there are containers or other goods on a large truck when it passes through the gateway. Moreover, the model should be deployed on an industrial computer which they are equipped now. My observation about this scenario is as follows: 1. The trucks pass through the gate one by one. There is no overlap between these trucks. Only one truck stays in the camera's field at one time. In this case, the image classification algorithm is a very suitable candidate. Using an object detection algorithm may be possible but it would be unnecessary. The object detection algorithm requires data annotation by hand, that is time-consuming and laborious. Therefore, I would not to use it if I could. 2. There is only an industrial computer with a CPU of i5 (By the way, this is good in that some Party A demands to deploy deep learning models on an industrial computer with even Celeron CPU). Party A also does not accept the purchase of a GPU or any other devices. Therefore, the deployment of a classification model+onnx+opencv may be the best way. When I get home in the afternoon, I start working on making dataset and training the model. By the evening, the first demonstration is available. I also estimate the payment with Party A, and sign the contract. After that, Party A disappears again...
Since the model is not in the deployed from, only the training and testing code with a demo video, the trained model, and the dataset for testing are opened. I have coded it using pytorch. So, changing the path in scripts will get them running. I hope this will be helpful to your development and learning. I also hope to hear from you with more advice. We are always beginners in front of knowledge.
link：https://pan.baidu.com/s/1JXvf67Omkfl-XapMCRnb5A?pwd=elgy 
code：elgy
