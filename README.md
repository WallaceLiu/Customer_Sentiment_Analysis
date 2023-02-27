# CustomerReviewSummarizeSystem
用户评价情感分析系统

大纲

    1.项目背景
    2.项目描述
    3.系统整体架构
    4.主流程及关键点分析
       4.1 数据读取
       4.2 提取评价的aspects
       4.3 提取用户评价、对用户评价进行打分及归纳
       4.4 打印结果
    5.用户评价情感二分类模型
    6.结果展示
        6.1 展示评价结果
        6.2 分类模型ROC-AUC score
    7.总结和思考
    
 具体内容参考我写的知乎博客
https://zhuanlan.zhihu.com/p/86579316



运行前需要从以下百度网盘链接下载

https://pan.baidu.com/s/1hSFBjQHLhYDw9jPBDNH6pw&shfl=sharepset
这个路径包含data文件夹下的内容
business.json
glove.6B.100d.txt
review.json

https://pan.baidu.com/s/1gnANAnoGv5GHQKWwAIVE4Q&shfl=sharepset
这个路径包含data文件夹下的模型文件
svm_clf.pkl