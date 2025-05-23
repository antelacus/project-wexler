# Project Wexler - 一个机器学习分析项目

本项目展示了机器学习在回归预测任务中的完整应用流程，包括数据探索、特征处理、模型训练、评估与解释。该项目适合用于数据分析和机器学习项目展示，也可作为入门项目参考。

📊 **技术栈：**
- 分析工具：Python, Jupyter Notebook
- 可视化：Matplotlib, Seaborn
- 模型方法：LightFM

---

## 📂 项目结构

```
project-white/
├── docs/                      # GitHub Pages 页面内容
├── Project_Wexler_Code.ipynb  # Jupyter Notebook，包含从数据预处理到建模的完整代码
├── .gitignore                 # Git 忽略文件配置
├── requirements.txt           # Python 依赖说明
└── README.md                  # 项目说明（当前文件）
```
---

## 🎯 项目目标

- 利用机器学习模型对某变量进行精确预测
- 探索数据特征与目标变量之间的关系
- 比较多种模型性能，挑选最优方案
- 解释模型结果并提出改进建议

---

## 🔍 分析流程

1. **项目背景说明**：明确业务目标与预测任务
2. **数据探索与清洗**：
   - 缺失值处理、异常检测
   - 可视化数据分布与变量相关性
3. **特征工程**：
   - 独热编码、数值转换、特征缩放
4. **模型训练与选择**：
   - 采用 Linear Regression、XGBoost 等模型进行对比
5. **模型评估与调优**：
   - 使用 RMSE、R² 评分、交叉验证
6. **模型解释**：
   - 分析特征重要性，辅助理解预测依据
7. **总结与展望**：
   - 反思模型局限与未来改进方向

---

## 🌐 在线浏览报告

项目报告已通过 GitHub Pages 发布，可直接在线阅读：

👉 [点击访问 Project Wexler 网页版报告](https://antelacus.github.io/project-wexler/)

---

## 💻 快速开始

### ✅ 安装依赖

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost shap
```

### 🚀 启动分析

```bash
git clone https://github.com/antelacus/project-wexler.git
cd project-wexler
jupyter notebook Project_Wexler_Code.ipynb
```

---

## 📜 数据来源与授权

- 数据集来自 [Kaggle - Retailrocket recommender system dataset](https://www.kaggle.com/datasets/retailrocket/ecommerce-dataset)
- 本项目遵循 MIT License 许可协议

---

## 🙋‍♂️ 作者

项目由 [@antelacus](https://github.com/antelacus) 制作，用于数据分析能力展示与公开分享。如有建议欢迎反馈或交流！
