# 🦠新冠肺炎疫情数据动态交互可视化(时空交互）

---

## 1. 数据分析描述

### 1.1 数据源

- china_provincedata.csv 中国各省、直辖市、自治区、特别行政区的疫情数据

- countrydata.csv 全球214个国家地区以及钻石公主号邮轮的疫情数据

### 1.2 数据分析目标

- 📁china_provincedata.csv 有效数据参数
  - confirmedCount：确诊数
  - curedCount：治愈数
  - currentConfirmedCount：现存确诊数
  - dateId：日期
  - deadCount：死亡数
  - suspectedCount：疑似数
  - provinceName：省份名
  - provinceShortName：省份缩写

- 📁countrydata.csv 有效数据参数
  - confirmedCount：确诊数
  - curedCount：治愈数
  - currentConfirmedCount：现存确诊数
  - dateId：日期
  - deadCount：死亡数
  - suspectedCount：疑似数
  - countryName：国家名名
  - countryShortName：国家缩写

用的两个数据集已经是非常工整的数据，只需要取想要的列即可，无需再去进行进一步清洗。

### 1.3 数据分析结果

新型冠状病毒肺炎（Corona Virus Disease 2019，COVID-19），简称“新冠肺炎”，世界卫生组织命名为“2019冠状病毒病”，是指2019新型冠状病毒感染导致的肺炎。
在全球抗击新型冠状病毒疫情的过程中，出现了大量的数据，在此项目中，**我们用数据展示了疫情在全球的传播影响的动态变化。**让我们能够直观看出疫情的传播。

### 1.4 数据分析结果可视化

- 使用的图表模块：
  - pandas
  - pyecharts

使用pandas处理相关数据，pyecharts进行可交互的图像输出，再使用🌶Flask🌶进行部署至网页。

## 2.数据分析电子档

- 项目人：丘天惠
- 时间：2020.7.16
- 数据源：
  - china_provincedata.csv
  - countrydata.csv
- 目标：用数据展示疫情在全球的传播影响的动态变化。