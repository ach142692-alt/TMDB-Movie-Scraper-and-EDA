# TMDB 高分电影数据采集与多维度探索性数据分析（EDA）系统

本项目是一个闭环的 Python 数据工程小项目。实现了从 TMDB (The Movie Database) 官网**自动化分页爬取高分榜单、精准解析详情页、数据清洗规整**，到最终利用 **Matplotlib 矩阵多子图进行可视化看板洞察** 的全流程。

## 🚀 项目技术栈
* **数据采集/解析**：Python / Requests / lxml (XPath)
* **数据清洗/处理**：Pandas
* **数据可视化**：Matplotlib

## 📂 项目结构
```text
├── data/
│   ├── movies.csv          # 经过清洗后的结构化电影数据（300条）
│   └── TMDB-TOP300.png     # 运行可视化脚本生成的 2x2 看板矩阵图
├── scraper.py              # TMDB 高分电影自动化数据抓取脚本
├── analysis.py             # 探索性数据分析与可视化脚本
└── README.md               # 项目说明文档