# 美国交通事故数据分析和可视化

这是一个使用Python对2016年到2023年美国交通事故数据进行分析和可视化的项目。数据来源于kaggle美国交通事故数据集(2016-2023)，这是一个覆盖美国49个州的全国性交通事故数据集。

## 主要目标：

- 探索事故的特征和模式，如事故的分布、频率、严重程度、原因和影响。
- 使用各种图表和地图来可视化数据，如直方图、条形图、饼图、散点图、热力图和分级统计地图。
- 提出一些有趣的见解和结论，如哪些州、哪些天、哪些时间段发生最多的事故，以及哪些因素影响事故的严重程度和对交通流量的影响。
------------
### 发生事故最多的前10个州
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/72a9f169-81e3-4544-a081-553d97c7554d)

------------
### 在地图上标出发生事故最多的前10个州
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/1252ae2d-df3b-437e-89a2-0fc4dbde8be9)

------------
### 地图可视化不同事故等级分布情况（等级1为严重程度最小，等级4为严重程度最大）
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/bf00207b-d233-4d2e-9a75-78ed877f0fb9)

------------
### 大多数(4.7%)的交通事故对交通流量的影响持续了6小时。
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/6e1732ce-c0ec-495c-a7e4-55cd8ce8e429)

------------
### 2021年是发生事故最多的一年（到2023年3月为止）
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/e82169dd-01d2-4801-916b-6cdd537407d0)

------------
### 平均每天和每小时发生的事故数量
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/7148df0d-0f1b-4e5f-ad4b-b7566e4bb9a8)

------------
### 可以看出在上下班时间交通事故发生率最高
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/eeeb85ae-5dfe-402b-a7c1-39d25a991f4e)

------------
### 在大多数发生事故的情况下，天气都较为晴朗
![image](https://github.com/Hebo-2015/us-accident-analysis/assets/142399606/3d306fb0-ef96-42c0-99c8-e6a5a986eb35)

------------


## 主要包含以下内容：

- 数据清洗：这部分使用Python对原始数据进行清洗和预处理，如处理缺失值、异常值、重复值和不一致的格式。
- 数据分析：这部分使用Python对数据进行描述性统计，如汇总统计、相关分析等。
- 数据可视化：这部分使用Python创建各种图表和地图来可视化数据，并提出一些见解和结论。

## 主要使用了以下Python库：

- pandas: 用于数据处理和分析
- numpy: 用于数值计算
- matplotlib: 用于绘制基本图表
- seaborn: 用于绘制高级图表
- plotly: 用于绘制交互式图表
- folium: 用于绘制地理信息地图


