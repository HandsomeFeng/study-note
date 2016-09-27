###数据采集
1. 总结（复用）各个公司数据采集手段
2. 隐私
3. 众包

###存储与计算框架
#####存储
1. 总结去年的存储部分

#####计算框架
1. 可复用去年分布式计算框架, 计算部分加上storm
2. 符号计算框架多个(theano[keras, lasagne, blocks], tensorflow, mxnet, cntk)
3. 非符号计算框架(caffe, torch, paddlepaddle)

###数据处理

1. 采样(simple random sampling， systematic random sampling，stratified random sampling，Cluster Sampling, sampling in network...)
2. 非深度
	- 聚类（复用总结去年）
	- 降维
	- 稀疏学习（复用总结去年）
	- FM, FFM
	- GBDT
	- [排序算法](https://www.siam.org/meetings/sdm10/tutorial1.pdf)
	- hits, page rank
	- [图模型算法1](http://snap.stanford.edu/proj/socmedia-www/socMedia-www11-part1.pdf),[算法2](http://snap.stanford.edu/proj/socmedia-www/socMedia-www11-part2.pdf)

3. 深度
	- CNN
	- RNN
	- DRL

###应用

1. 舆情分析（微博，social network）
2. 视频监控
3. 征信
4. 作弊检测fraud detection
5. 排序：搜索、bioinfomatics、drug discovery
6. 推荐（朋友推荐、广告推荐、点击率（转化率）预测、数据营销）
7. 翻译
8. 语音识别
9. 可视化
10. 智慧交通
11. 电网功耗预测


* * *
###分工

| id | 应用部分 | 算法部分 | 附加部分 |
|--------|--------|------|------|
|1|舆情分析|非深度-图模型算法||
|2|视频监控|深度-CNN|存储1|
|3|数据征信|采样|数据采集1|
|4|推荐|非深度-FM、GBDT||
|5|作弊检测|非深度-聚类|计算框架1|
|6|排序|非深度-排序算法、hits&page rank||
|7|翻译、语音识别|深度-RNN|计算框架3|
|8|可视化|非深度-降维|计算框架2|
|9|智慧交通|深度-DRL|数据采集2|
|10|电网功率预测|非深度-稀疏|数据采集3|

###备注

1. 算法介绍可以参考去年的框架
2. 应用部分应阐述问题，并给出公司实际中使用的解决方案(case 分析)
2. 部分应用可以参考[学堂在线](http://www.xuetangx.com/courses/course-v1:TsinghuaX+60250131X+sp/about)的《大数据科学与应用系列讲座》
 - 征信：艾小缤：大数据评价体系在金融、征信领域的创新
 - 推荐：屈燕：大数据在社交媒体的应用，龚笔宏：大数据在工业界中的经典案例分享
 - 可视化：时磊：大数据网络可视化