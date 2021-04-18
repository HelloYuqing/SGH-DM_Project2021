## Data Mining Final Project 2021 Summer

## 📊STEPS

### 无用数据
* 删除Unnamed列
* 删除部分难以观测的变量
### Missing
* 填补unknown
* 填补blank
* 比较特殊的Salary_range
max_salary
min_salary
* 数值变量格式str转numeric
df.val = pd.to_numeric(df.val)
*  Text info的处理，采用编码
#### 离散特征的取值之间没有大小的意义，比如color：[red,blue],那么就使用one-hot编码 离散特征的取值有大小的意义，比如size:[X,XL,XXL],那么就使用数值的映射{X:1,XL:2,XXL:3}
归一化处理
### 标准差标准化（standardScale）使得经过处理的数据符合标准正态分布
* 提高精度
### 特征选择
* PCA降维处理
### 拆分数据集
* 70%训练集
* 30%验证集
### 建立模型
* 克隆处理
* LR
* Decession Tree
* Bagging
### 总结模型分数
* LR | 0.447
* DT | 0.879
* BA | 0.961
