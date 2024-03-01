# 研究报告复现（研报复现 or 分析师报告复现 or analyst-report-reimplementation）
现在各种研报复现的文章和项目，但是存在格式不统一、数据源不统一、python 版本、包管理、数据更新困难、研报重复做等等问题，比较乱。所以，计划弄一个收集、整理各路英雄的研报复现的文章和项目，统一格式，统一数据源，成为一个统一的完善的研报复现大集合！

## 环境安装
### 基础环境
需要 python 和 poetry
```python
conda create -p .venv python=3.11
conda insdtall pipx
pipx install poetry
pipx ensurepath
```

### 安装依赖包
```python
poetry install
```
