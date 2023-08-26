# 美国交通事故数据分析和可视化

这是一个使用Python对2016年到2023年美国交通事故数据进行分析和可视化的项目。数据来源于kaggle美国交通事故数据集(2016-2023)，这个数据集覆盖了美国49个州的全国性交通。

----
### 热力图，展示相关系数
<img src="../us-accident/assets/1relitu.png" alt="image" style="zoom:72%;" />

----
### 不同特征对事故严重程度的影响
<img src="../us-accident/assets/2tezhengyanzhong.png" alt="image" style="zoom:72%;" />

----
### 特征重要性柱状图
<img src="../us-accident/assets/2tezhengzhongyao.png" alt="image" style="zoom:72%;" />


------------
### 发生事故最多的前10个州
![image](../us-accident/assets/4tenstate.png)

------------
### 在地图上标出发生事故最多的前10个州
<img src="../us-accident/assets/5maptenstate.png" alt="image" style="zoom:72%;" />

------------
### 地图可视化不同事故等级分布情况（等级1为严重程度最小，等级4为严重程度最大）
<img src="../us-accident/assets/6dengjimap.png" alt="image" style="zoom:72%;" />

------------
### 大多数(4.7%)的交通事故对交通流量的影响持续了6小时。
<img src="../us-accident/assets/7sixhour.png" alt="image" style="zoom:90%;" />

------------
### 2021年是发生事故最多的一年（到2023年3月为止）
<img src="../us-accident/assets/8year.png" alt="image" style="zoom:90%;" />

------------
### 平均每天和每小时发生的事故数量
<img src="../us-accident/assets/9dayandhour.png" alt="image" style="zoom:36%;" />

------------
### 可以看出在上下班时间交通事故发生率最高
<img src="../us-accident/assets/10hour.png" alt="image" style="zoom:90%;" />

------------
### 不同道路状况下事故的发生率
<img src="../us-accident/assets/11road.png" alt="image" style="zoom:72%;" />

------------


## 主要包含以下内容：

- 数据清洗：这部分使用Python对原始数据进行清洗和预处理，如处理缺失值、异常值、重复值和不一致的格式。
- 数据分析：这部分使用Python对数据进行描述性统计，如汇总统计、相关分析等。
- 数据可视化：这部分使用Python创建各种图表和地图来可视化数据，并提出一些见解和结论。
- 数据挖掘：探索不同特征对事故严重程度的影响，以及特征的重要性。

## 主要使用了以下Python库：

- pandas: 用于数据处理和分析
- numpy: 用于数值计算
- matplotlib: 用于绘制基本图表
- seaborn: 用于绘制高级图表
- plotly: 用于绘制交互式图表
- folium: 用于绘制地理信息地图
- sklearn: 用于数据挖掘

