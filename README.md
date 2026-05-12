# 📊 中国电商销售数据分析
> China E-Commerce Sales Data Analysis | Python · Pandas · Seaborn · Matplotlib

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Lab-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 项目简介

本项目基于模拟的中国电商平台销售数据（5000 条订单记录），通过数据清洗、探索性分析与可视化，
系统呈现 2024 年全年电商销售趋势、平台竞争格局、用户地域分布及促销活动效果。

研究背景来自数字经济视角下中国电商市场的结构性分析需求。

---

## 🗂️ 项目结构

```
ecommerce-sales-analysis/
├── ecommerce_analysis.ipynb   # 主分析 Notebook
├── monthly_trend.png          # 月度销售趋势图
├── platform_category.png      # 平台与类目分析图
├── region_promo.png           # 地区热力图 & 促销效果图
└── README.md
```

---

## 🔍 分析维度

| 维度 | 内容 |
|------|------|
| 时间趋势 | 2024 全年月度销售额波动，识别双十一等促销节点 |
| 平台对比 | 淘宝 / 京东 / 拼多多 / 抖音 / 天猫 销售额排名 |
| 类目分析 | 7 大商品类目销售占比（服装、数码、食品等） |
| 地域分布 | 华东 / 华南 / 华北 等 7 大区销售热力图 |
| 促销效果 | 促销 vs 非促销订单客单价对比（箱线图） |

---

## 📈 核心发现

- 📅 **销售峰值**：11 月（双十一）为全年最高，12 月次之
- 🏆 **最强平台**：淘宝累计销售额最高，抖音增速显著
- 🛍️ **最畅销类目**：服装鞋帽占比最大，手机数码客单价最高
- 📍 **消费重镇**：华东、华南地区贡献超 50% 销售额
- 🎯 **促销效果**：促销活动平均提升客单价约 15-25%

---

## 🛠️ 技术栈

- **数据处理**：`pandas` `numpy`
- **数据可视化**：`matplotlib` `seaborn`
- **运行环境**：JupyterLab · Python 3.8+

---

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/Patro-gpu/ecommerce-sales-analysis.git
cd ecommerce-sales-analysis

# 安装依赖
pip install pandas numpy matplotlib seaborn

# 启动 Jupyter Lab
jupyter lab
```

打开 `ecommerce_analysis.ipynb`，依次运行各 Cell 即可。

---

## 📚 学习要点

- `pandas` 数据清洗与 GroupBy 聚合
- `seaborn` 热力图、箱线图绘制
- `matplotlib` 时间序列可视化与图表注释
- RFM 数据结构理解与业务解读

---

## 👤 作者

**Zhong Guoming (钟国铭)**  
Graduate student in Digital Economy  
GitHub: [@Patro-gpu](https://github.com/Patro-gpu)
