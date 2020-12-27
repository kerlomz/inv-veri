# 国税局验证码识别 | 97.5%识别率

```python
凡尔赛模式 = True
以下内容是否全部属实 = True
```

**国税发票查验的验证码识别率垄断了2年，目前识别率97.5%，从未被超越，不过近日来差距缩小了，原本市面上除了我这里，平均在70-80左右的识别率。**


无意中看到Github有人回复了一个很早的issues，

https://github.com/Hanmengnan/Identify-the-Captcha/issues/3

在里面看到了一个老哥的评论：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205013215674.png)
新晋老铁的文章地址：https://blog.csdn.net/Open_CV_NLP/article/details/109828259

他刚刚破了90识别率大关，我还惊奇的发现这篇文章居然保留了我早期写的生成器的代码，![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205013506757.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)
很明显的印记了，当时一两年前发布在简书上的，挖了不少坑，精准控制了低识别率，还是有不错的小伙子填坑生成出不错的效果，想必这位老哥的生成代码应该是在这份代码的基础上修改的。
这个Github的作者还提供了模型下载：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205013934550.png)
仔细一看是不是很眼熟？可不就是我写的**开源框架**训练出来的模型命名格式嘛，对一键训练部署的深度学习图像分类框架感兴趣的可以移步：[https://github.com/kerlomz/captcha_trainer](https://github.com/kerlomz/captcha_trainer)

各位感兴趣的可以去比对比对。秉着公平竞争的原则，老板们可各取所需。

我这边的定位是**企业级-商用**水准，**识别率目前97.5%**，12月忙，对手若是突破了95大关，**我将会在年后推出98/99以上识别率的版本**。

如果对竞品感兴趣可以移步：[https://blog.csdn.net/kerlomz/article/details/111396350](https://blog.csdn.net/kerlomz/article/details/111396350) 了解一下，或许对你们的选择会有帮助。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205010453849.png)
识别速度如上图所示5毫秒左右，机器配置如下图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205010615398.png)
可见，**低配1核CPU**足以支撑业务**日调用1.7千万级别**的负载调用，加之识别率一直是全网最高，业内不少头部的财税服务提供商都是使用笔者的版本，因保密协议不得透露合作关系，在此不举例，毕竟大多数公司都会说自己并非使用爬虫技术实现查验功能，行内人应该都知道的，可自行查证。敢在合同上写下识别率指标的不存在一丝丝水分。

测试地址：[http://152.136.207.29:19812/preview?model_name=TAX](http://152.136.207.29:19812/preview?model_name=TAX)

这里提一嘴，如果是截图玩家的话，可以选择测试版模型：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205015103679.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)

使用方法本篇博客就不赘述了，从官网保存验证码原图，选择需要识别的颜色，上传图片识别即可。

本接口防止白嫖设立了一定的风控，如有商业合作意愿可联系本人QQ（27009583）或合伙人QQ（1095085167），获取文本接口测试。



# 发票查验服务

[https://inv.gouzai.pw/](https://inv.gouzai.pw/)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205015406174.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)
提供全票种秒查询的服务，查验服务若有商业合作可以联系我的合伙人。可为高端用户提供毫秒级的查验效率，快至200毫秒以内（光这个200基本上没有对手，需要联系合伙人QQ：1095085167，才提供测试）可高速并发（依赖高质代理IP），搭配97.5%识别率验证码识别服务，
连续查验失败的概率低至10亿分之9，可以说失败率为0，大型银行年查验数大约千万量级，换算一下大约100年中将发生9次查验失败。稳定性不用多说，实力在这里，放马过来测试比对。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205020021938.png)

目标客户：大型财税公司首选，或者想一跃成为行业头部的公司首选，可直接对标市面上的任何一家公司的查验服务，言尽于此。不喜犹豫不决拖拖拉拉的客户，加了好友不回消息的直接拉黑，屌丝勿扰。
