# 国税局验证码识别 | 发票查验 | 97.5%识别率 | 

```python
凡尔赛模式 = True
以下内容是否全部属实 = True
```

**国税发票查验的验证码识别率垄断了2年，目前识别率97.5%，从未被超越，不过近日来差距缩小了，原本市面上除了我这里，平均在70-80左右的识别率。**

## 测试接口
---
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205010453849.png)
识别速度如上图所示5毫秒左右，机器配置如下图：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205010615398.png)
可见，**低配1核CPU**足以支撑业务**日调用1.7千万级别**的负载调用，加之识别率一直是全网最高，业内不少头部的财税服务提供商都是使用笔者的版本，因保密协议不得透露合作关系，在此不举例，毕竟大多数公司都会说自己并非使用爬虫技术实现查验功能，行内人应该都知道的，可自行查证。敢在合同上写下识别率指标的不存在一丝丝水分。

**测试地址：[http://152.136.207.29:19812/preview?model_name=TAX](http://152.136.207.29:19812/preview?model_name=TAX)**



使用方法本篇博客就不赘述了，从官网保存验证码原图，选择需要识别的颜色，上传图片识别即可。



本接口防止白嫖设立了一定的风控，如有商业合作意愿可联系本人QQ（27009583）或合伙人QQ（1095085167），获取文本接口测试。

---
## 12.28 更新 （我又回来了）
最近真是不安分，从11月开始有个人就开始各种搞事，我今天一看，又来了，不用想我都知道是谁。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228113609588.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)

又去搜了一波辣个人的博客，发现对方把文章都删了，眉头一皱，原来事情果然并没有那么简单，开始自导自演上演苦肉计了。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228111735960.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)
针对以上，我做出以下回应：
1. 对方说我举报他，举报的直接证据是后台的系统通知，**为啥光说不上图？** 12月27日，我还在参加考研生考试，考完睡了半天，他的意思我考试完第一件事就是去举报这玩意儿，也把自己看的太高了吧，就算写十篇，技术摆在那里，只要不吹嘘指标行骗，有点头脑的人都知道该怎么选，有一个对比对我来说不是更有利吗？我有举报的动机？（那么文章被下架会是系统自发的行为？让我们误会是对方举报的？**我是持怀疑的态度**，我没记错的话对方之前有好几篇文章吧，突然全都空了，我觉得是对方自导自演自己删除的。**我列表里可这不止一篇广告，怎么就只有这一篇发了超过一年的文章今天突然被判定广告，**不用想也知道吧。）

2. 还有对方为什么全是小号，全是新注册的，为了国税而国税。有很大概率是大号有污点或存在争议，所谓的“潘多拉效应”，越隐藏自己越让人好奇，不得不联想，难道是为了摆脱以前用易语言的痕迹？或者说以前的QQ能搜到负面信息？到底为什么不敢用，这里我就不做推测了，各位自己调查。换位思考，我要是买家，要给这个小号打几万是不可能的。小号属于风险交易，无法建立信任。所以我一般会建议买家这么做：**1.当面交易。2. 确认对方真实个人信息并且签合同 3.把识别率指标作为合同的交付指标，达不到须全额退还。** 对方如果能做到这些，我非常赞成各位选择自己喜欢的买。

3. 说他对我造成威胁，我加过他好友，一直没给我通过，毕竟也有90识别率了，统一下市场定价，不要差距太大，**比如我97.5的版本定位在8w，对方90的版本定位在1k**。确实会对我造成威胁。本来井水不犯河水的，我现在是看他不爽了，有本事就提升自己技术，从知乎事件开始，我还真的有被烦到，整天阴魂不散的玩这些把戏。不过我现在是放心了，既然认定我有暴利收入起码不会傻到定位1k了。

4. 说我心虚？有点意思，知乎我被举报之后我果断复仇了，我也反手一个举报，起码我做的我就敢作敢当。是诋毁你还是说的实话，想必心理应该有X数。自己整小号见不得光，反倒说别人不够光明磊落了。

5. 你说自己没有用我的java生长器（生成器），说明你是知道他的存在，起码对我是很了解了的，别的不说，颜色处理方案事实用的我的方案，在我没有公布之前，市面上可没有一个人用，方案都采纳了，你说生成器没抄全自己写，又在旧版的有我生成器的开源项目里评论，会有人信吗？你不仅了解我的项目，甚至于还知道我有暴利收入，看来你现实中可能还认识我，但因为你全是小号，我对你却一无所知。我真是不屑于诋毁一个无名之辈，敢不敢用大号。

6. 补充一下，看看对方对于识别率的态度：
**知乎事件的时候，识别率是这样的，说自己有98%**![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228141412844.png)
**几个小时前，还一直说自己有97的识别率**
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228141144776.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)
**然后现在单独删了，按事件先后，为什么识别率变化这么大，这可不是自然增长，是逆生长，可信度到底多少？删除的动机首先是对自己的识别率不自信，我文章恢复之后甚至于直接删了不敢虚假承诺。什么叫心虚？这才叫。** 

7. 再补充一条动机吧，强者如果要抹杀弱者，会选择扼杀在摇篮里，正如对方说的，要举报早就举报了，唯一一次举报就是对于知乎事件的回应，我的csdn博客文章发了不止一年了，模型的发展历史也远远不止，作为强者，需要打压弱者来证明自己？**很简单，我敢说我的东西比你强，你敢说你的比我强吗？** 而往往弱者需要通过示弱，来博得同情分，举报我的动机很简单，长期没有人找他，客户都来找我，你们看他对我的描述，认为我暴利，暴利本来是中性的词，但是价值判断是主观的，潜意识暴露的是眼红并且也想暴利。那么得想办法博取关注，举报我可以制造虚假的竞争关系，其实要不是一直阴魂不散的搞事，我根本没把他当回事，和高位制造虚假竞争关系可以暗示自己的段位和高位者相当，借此提升自己的定位。


### 根据和客户交易的经验，总结上面几点建议：
1. 当面交易：
  1）在对方电脑里看到源码；
  2）现场对接官网核实识别率；
  3）看着源码从他的设备转移到你的设备上，并且成功运行起来。


2. 合同约束，在合同上注明验收指标，以我为例：![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228123612274.png)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228123727463.png)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228123804139.png)
我一般都会写的很清楚，总结为：如果识别率达不到验收指标必须全额退款。

3. **对于小号而言，最好选择第一条建议，防止跑路。** 远程交易的原则必须添加微信或者有年限等级和正常有使用痕迹的QQ，微信的朋友圈起码是超过其打算卖模型的年限的，能客观观察到对方是个真实的存在，信息越少越不真实，毕竟万一不幸被骗，掌握了真实信息，是能报警抓到的，诉讼文书能知道该寄给谁。


综合以上，如果对方能接受以上全部要求，恭喜你们，没花冤枉钱，我十分赞成你们交易，如果拒绝，建议你们自己小心了。归根结底，我不怕竞争，就怕恶性竞争，比技术可以，比心机和演技，我只能给各位提建议了。各位可以看下我的其他项目，岁月的痕迹，一步一步搞技术的，光明磊落。

什么才是真实存在的痕迹，项目一点一点写出来：
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201228132610829.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)
去年云栖社区邀请我做技术分享直播，都有痕迹可以查的，钉钉群聊天记录，从主办方那里都可以问到，社区里也有记录。



# 发票查验服务

[https://inv.gouzai.pw/](https://inv.gouzai.pw/)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205015406174.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L2tlcmxvbXo=,size_16,color_FFFFFF,t_70)
提供全票种秒查询的服务，查验服务若有商业合作可以联系我的合伙人。可为高端用户提供毫秒级的查验效率，快至200毫秒以内（光这个200基本上没有对手，需要联系合伙人QQ：1095085167，才提供测试）可高速并发（依赖高质代理IP），搭配97.5%识别率验证码识别服务，
连续查验失败的概率低至10亿分之9，可以说失败率为0，大型银行年查验数大约千万量级，换算一下大约100年中将发生9次查验失败。稳定性不用多说，实力在这里，放马过来测试比对。
![在这里插入图片描述](https://img-blog.csdnimg.cn/20201205020021938.png)

目标客户：大型财税公司首选，或者想一跃成为行业头部的公司首选，可直接对标市面上的任何一家公司的查验服务，言尽于此。不喜犹豫不决拖拖拉拉的客户，加了好友不回消息的直接拉黑，屌丝勿扰。
