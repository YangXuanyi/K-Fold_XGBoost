# 项目介绍：
    在机器学习中，K-Fold交叉验证是一种充分利用数据集的训练验证方式，有助于避免过拟合并且是一种超参数优化技术。
    本项目从代码实践的角度剖析在Xgboost模型中如何在普通方式和使用K-Fold技术进行训练和预测。
# 创作信息：
    Author：Elbert
    Date：2022/12/30

# 环境依赖：
    sklearn
    numpy
    pandas
# 项目文件目录介绍：
    1、DataHousePricePrediction文件夹中存储本项目需要用到的数据文件
    2、XgbModels文件夹用于存储K-Fold训练后的模型文件
    3、main.ipynb为主程序文件,主要实现XGBoost模型基于普通方法和K-Fold方法的训练和预测过程
    4、opt_search.ipynb文件为XGBoost参数调优文件，主要实现了使用GridSearchCV方法网格搜索优化参数

# 版本内容更新
###### v1.0.0: 

 
 