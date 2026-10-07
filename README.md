# 用户留存分析项目

## 📌 项目简介

基于真实业务数据的**用户留存分析**项目，通过数据清洗、探索性分析和可视化，深入研究用户留存率、用户行为模式和产品优化方向。

> **项目类型**：个人项目 / 数据分析
> **开发时间**：2026年5月

## 🛠️ 技术栈

- **编程语言**：Python
- **数据分析**：Pandas, NumPy
- **可视化**：Matplotlib, Seaborn, Plotly
- **开发环境**：Jupyter Notebook

## ✨ 分析内容

### 📊 数据处理
- 原始数据清洗和预处理
- 缺失值处理
- 数据格式转换
- 特征工程

### 📈 分析维度
- 用户次日/7日/30日留存率
- 不同用户分群的留存对比
- 用户行为路径分析
- 留存影响因素分析

### 📉 可视化
- 留存曲线（Cohort Analysis）
- 热力图展示
- 趋势分析图表
- 对比分析图表

## 📁 项目结构

`
.
├── data/               # 数据文件（不提交，本地存储）
├── notebooks/          # Jupyter Notebook 分析过程
├── src/                # Python 源码
├── reports/            # 分析报告
├── docs/               # 文档
└── README.md
`

## 🚀 运行方式

`ash
# 创建虚拟环境
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 安装依赖
pip install pandas numpy matplotlib seaborn plotly jupyter

# 启动 Jupyter
jupyter notebook
`

## 📝 说明

本项目数据文件存储在本地 data/ 目录，未提交至 Git（数据量较大）。代码和分析 Notebook 已完整保留，可用于学习和参考。
