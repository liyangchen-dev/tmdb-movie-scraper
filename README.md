# 🎬 TMDB 高分电影爬虫 (TMDB Movie Scraper)

这是一个基于 Python 开发的轻量级网页爬虫，专门用于抓取 **The Movie Database (TMDB)** 榜单上的高分电影详细信息。

## ✨ 功能特点
- 🚀 **自动化抓取**：自动遍历多页榜单，获取电影列表。
- 📊 **多维度数据**：抓取包括电影名、年份、评分、导演、时长、简介等 10+ 项关键数据。
- 💾 **本地存储**：自动将抓取结果保存为标准 CSV 格式，方便后续进行数据分析。

## 🛠️ 技术栈
- **语言**: Python 3.x
- **库**: `requests` (网络请求), `lxml` (XPath 解析), `csv` (数据存储)

## 快速上手
1. 安装依赖：`pip install -r requirements.txt`
2. 运行爬虫：`python tmdb-spider.py`
3. 查看数据：结果将保存在 `csv_data/` 文件夹中