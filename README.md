# SimData: 用于产生模拟数据的SPSS宏    
# SimData: An SPSS macro for generating simulated data    
*Version: 1.0.5    
*Copyright 2025 Qiu Zongman    
*License: Apache 2.0    
*E-mail: qiuzongman@foxmail.com    
*Research Gate: Zongman Qiu    
*Bilibili: 邱宗满 (ID: 423767625)    
*微信公众号: 邱宗满 (ID: qiuzongman2020)    
*项目托管在Github和Gitee:    
*https://github.com/zongmanqiu/SimData    
*https://gitee.com/qiuzongman/SimData    
*引用    
*Qiu, Zongman. (2025). SimData: An SPSS macro for generating simulated data. SPSS Extension Version 1. https://github.com/zongmanqiu/SimData    

# 功能    
## 方差分析 ANOVA    
*产生单/多组的单变量数据，指定均值与标准差    
## 线性回归 Linear regression    
*根据回归系数为当前数据增加因变量，包括线性回归与二元逻辑回归    
## 结构方程模型 SEM    
*根据相关矩阵模拟多元数据    
*根据SEM系数模拟多元数据，可以输入标准化系数    
*可指定连续尺度或李克特尺度进行模拟    
## 多水平模型/混合模型 MLM    
*模拟多个自变量，可指定Level 1与Level 2的相关系数    
*在当前数据上根据固定效应系数增加因变量，可设置随机效应    
## 多水平验证性因子分析 MCFA    
*模拟两个水平的MCFA数据    
## 类别变量    
*根据联合概率与边缘概率计算二元变量相关    
*产生指定相关矩阵的二元变量    
*产生指定相关矩阵的二元变量（固定1的个数）    
*自定义不同类别组合及其数量    
*模拟连续变量、二分变量与多分类变量的混合相关    
## 其它    
*核密度图：使用nrd0方法计算核密度曲线    
*数据转换：数据缩放与四舍五入    
*抽样：对当前数据的有放回/无放回抽样    
*缺失：对当前数据随机挖空    
