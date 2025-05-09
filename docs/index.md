# Project Wexler - 推荐系统实践项目

欢迎来到 Project Wexler 的项目展示页面。本项目旨在构建一个基于 LightFM 算法的推荐系统，使用真实用户行为数据进行建模、评估和总结。

- **目标**：构建具有商业意义的推荐系统原型
- **算法**：LightFM（融合 Collaborative & Content-based 方法）
- **数据集**：Retailrocket Recommender Dataset
- **工具**：Python, LightFM, Pandas, Numpy, Matplotlib

---

## 📂 报告导航

### 📑 报告目录
- [方法与建模流程](methodology.md)
- [模型评估与结果](evaluation.md)

### 📁 附件下载
- [Jupyter Notebook](../Project_Wexler_Code.ipynb)
- [PDF报告](../Project_Wexler.pdf)

---

## 📁 项目结构

```
project-wexler/
├── docs/                      # GitHub Pages 页面内容
├── Project_Wexler_Code.ipynb  # 分析用 Jupyter Notebook
├── Project_Wexler.pdf         # 分析报告 PDF 版本
├── .gitignore                 # Git 忽略文件配置
├── requirements.txt           # Python 依赖说明
└── README.md                  # 项目说明（当前文件）
```

---

## 🛠 快速启动

如需在本地运行分析：

```bash
# 克隆仓库
git clone https://github.com/antelacus/project-wexler.git
cd project-white

# 安装依赖
pip install pandas numpy scikit-learn matplotlib seaborn xgboost shap

# 启动 Jupyter
jupyter notebook Project_Wexler_Code.ipynb
```

---

## 📜 数据来源与授权

- 数据集来自 [Kaggle - Retailrocket recommender system dataset](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset)
- 本项目遵循 MIT License 许可协议

---

## 🙋‍♂️ 作者

项目由 [@antelacus](https://github.com/antelacus) 制作，用于数据分析能力展示与公开分享。如有建议欢迎反馈或交流！

---
