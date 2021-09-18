# topic_modeling_and_sentiment_analysis
基于Twitter数据，以新冠肺炎为主题，进行主题挖掘与情感分析

数据来源：Twitter（数据获取工具：snscrape）
检索词：#COVID19

1.原始数据表

![image](https://user-images.githubusercontent.com/71856637/133883468-782a71c2-b39d-4cb2-bb2f-1a0e310c95a7.png)


2.预处理后的数据表

![image](https://user-images.githubusercontent.com/71856637/133883506-651ae6d9-b4e4-412b-b5b7-7e6e331528e2.png)

3.主题挖掘（使用工具：gensim）

4.选择最佳主题数量（依据指标：Coherence）

![image](https://user-images.githubusercontent.com/71856637/133883561-2bbab565-dac1-4782-b912-aeb83e4bd808.png)

5.可视化主题挖掘结果（使用工具：pyLDAvis）

![image](https://user-images.githubusercontent.com/71856637/133883640-c659997b-7a30-4e8f-8fcc-4c540eb55aae.png)

6.2021年4月30日的相关推文分布地图

![image](https://user-images.githubusercontent.com/71856637/133883702-da0740c0-b4d2-42a7-947e-310360c6b29b.png)

7.实时推文获取与分析

A.实时推文数据表

![image](https://user-images.githubusercontent.com/71856637/133883783-3140e652-54cd-4000-b00f-1ed718f86329.png)

B.部分实时收集的推文数据

![image](https://user-images.githubusercontent.com/71856637/133883842-62fa6afb-8e1f-4aed-a378-c96e96f3ab26.png)

C.部分实时推文的地理分布

![image](https://user-images.githubusercontent.com/71856637/133883905-2403d55d-be04-4a38-8560-5e6bf0fda4f4.png)
