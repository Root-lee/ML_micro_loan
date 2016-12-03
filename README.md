# ML_micro_loan
机器学习项目：微额借款用户人品预测
# 项目说明
互联网金融近年来异常火热，大量的资本和人才涌入这个领域发掘富藏价值。金融领域无论是投资理财还是借贷放款，风险控制永远是业务的核心基础。而在所有的互联网金融产品中，微额借款（借款金额500元~1000元）因其主要服务对象的特殊性，被公认为是风险最高的细分领域。本项目是预测”小额微贷“申请借款用户的信用状况，以分析其是否逾期。
# 数据说明
1. 训练集（带标签）：15,000个样本
2. 测试集：5000个样本
3. 训练集（无标签）：50,000个样本
4. 特征描述（描述特征是数值型还是类别型）

# 更新记录
2016.12.2 ===============
- 第一次提交训练结果文件，本次项目使用了scilearn机器学习库中的逻辑回归模型预测用户的人品，根据网站反馈结果，本次预测AUC评分是0.55

2016.12.3 ===============
- 新增了随机森林、朴素贝叶斯、支持向量机、K最紧邻算法。
- 比较这些机器学习算法，发现逻辑回归、随机森林及K最近邻算法可以取得较好的效果。
