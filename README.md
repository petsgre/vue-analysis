# :eyes: Vue 源码分析

项目拷贝自 [Vue.js](https://github.com/vuejs/vue)

### 灵感来源：[underscore-analysis](https://github.com/lessfish/underscore-analysis)

## **前言**：

工作了3年了，希望能够有机会进入大厂，也积极的准备着简历，后来发了几个大厂发现回复几乎为0，只有金山软件邀请了一轮电话面试，邀面时HR的一句话也够扎心的。我面试的岗位是珠海的，同时广州也在招人，就问HR广州的为什么不面试我，HR很直爽的来了句广州的岗位需要技术比较牛X的人。扎心了，还是笑眯眯的说好吧。下午电话来了，两个技术一顿提问，我一顿对答，几乎没有答不上来的，是的，三年的发开经验让我可以从容应对各种开发中的基本问题，从前台到后台，从数据库到服务器，都能答点皮毛。但是，平心而论，任何一个3年的前端，基本都可以做到。结果也在情理之中，意料之外。我并没有通过1面。我总结的原因是---学历。我一个普通二本，很可能是被同样具备能力的211或者985，亦或者研究生同学淘汰了，就是这么残酷。学历的不足让我有些失望。

但是我没放弃，我还是努力投着简历。也努力在各个渠道寻找着内推机会。有一天，在蚂蚁金服的一个开源项目上提交PR，看到贡献者也再内推，便留了微信，对方是个大牛，目测P7-P8。虽然知道自己希望渺茫，但是还是抱着试一试的态度发了简历。结果呢？是的！又扎心了，这一次把我扎醒了。大牛对我说的一句重点就是“普通，太普通了。”那淡淡的一句话让我明白了，没有优秀的学历背景，普普通通的一个开发，想进入大厂，只能靠自己的实力，让人眼前一亮的亮点。

从那以后我便计划着打造自己的亮点，vue源码剖析便是其中一点，使用了2年vue，但却对vue的原理也只是一知半解，这让我一个作为前端工程师的我感觉羞愧。


-------




- 在阅读源码的同时我会给代码中添加注释，帮助记录和理解
- 此次学习vue 2.0+(3.0作为以后的补充再做计划)
- 项目笔记同步在另一个仓库 [Vue源码解析](https://github.com/petsgre/tutorial/tree/master/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90/vue)


### 相关链接

- [bilibili vue源码分析视频讲解](https://www.bilibili.com/video/av50438659/?p=45)
- [Vue.js 技术揭秘](https://ustbhuangyi.github.io/vue-analysis/)