# 关于我的介绍

> 您好，如果您能看到这个页面，想必您已经收到了我的简历
> 由于做的项目可能较多，请恕我无法实时更新我的简历内容
> 我会在这个文档下定期维护更新我做的事，您可以对我的技术内容有更多的了解

## 我的技术栈

### Java:

- 主流框架：
    - SSM
    - SpringBoot
    - SpringCloud
    - SpringAlibabaCloud
    - 若依
- MQ：
    - Rabbit(主要用的)
    - Rocket(自己写过demo)
    - Active(早期使用)
    - KafkA(项目中使用，主要用于日志收集)
- 通信框架：Netty，有自己实现过相关的开源项目
    - https://github.com/loks666/niubaide_im （早期uniapp版本）
    - https://github.com/loks666/niubaide_im_ByWeb (web版本，UI不太行)
    - https://github.com/loks666/webchat （https实现的版本，考虑过使用这版的UI，改为ws形式，但时间不够，遂搁置）
- 数据库：
    - redis(主要使用)
    - mysql(深度使用)
    - oracle(往期公司中主要使用)
    - mongo(爬虫作业中主要使用)
    - postgre,H2,neo4j,hbase,sqlite(
      这些数据库主要是做的项目中使用，处于会用阶段，目前八股了解的不多，如果公司有需要我也可以学习)
- ORM：
    - Mybatis/iBatis (主要使用)
    - MybatisPlus (公司与开源项目都使用过)
    - SpringData/Jpa/Hibernate(公司项目使用)

### Python：
- 大模型：
  - 使用bertopic训练模型，用于提取文本的主题词，并评估模型的精度，召回率，精确率，F1 分数
  - FlyAI集成各类大模型：https://ai.ruyun.fun
  - 本地部署大模型(代码运行/ollama/anything)：qwen，llama，gemma
  - 文生图本地部署大模型:comfyui && stable_diffusion
- web：Flask/Django/Fast api
  - Django
    - Python网络爬虫与推荐算法的新闻推荐平台(scrapy+Django)：https://github.com/loks666/NewsRecommends
    - 如云图书馆：https://github.com/loks666/ruyun_library
  - flask：
    - 政务主题词可视化分析：https://github.com/loks666/policy_image
- 深度学习：
    - yolo5，识别交通标志并添加识别率：https://github.com/loks666/yolov5-5.0
    - 京津冀政策分析(类似kg知识图谱抽取)：https://github.com/loks666/policy_analysis
- 爬虫
    - selenium(Java/Go/Python都能写)，基于selenium实现的自动投简历：https://github.com/loks666/get_jobs 【自主开源】
    - scrapy 
    - bs4 && lxml
  
### Golang：
- web：gin
  - 基于One Api二次开发的openai key分发网站：https://github.com/loks666/fly-api
- 爬虫
  - 基于selenium的投简历助手go版本(还未重构)：https://github.com/loks666/go_jobs
- 微信机器人
  - 把chatgpt与coze接入微信：https://github.com/loks666/gpt-wechat-bot