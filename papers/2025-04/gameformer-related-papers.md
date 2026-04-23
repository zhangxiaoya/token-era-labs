# GameFormer 相关论文列表

> 整理时间: 2025-04-22
> 来源: arXiv + ScholarAIO 搜索

---

## 🎯 高度相关论文

### 1. Level-k 博弈论 / 分层博弈

| 论文 | 年份 | arXiv | 说明 |
|------|------|-------|------|
| **Solution Concepts in Hierarchical Games under Bounded Rationality with Applications to Autonomous Driving** | 2020 | [2009.10033](https://arxiv.org/abs/2009.10033) | **核心相关**：分层博弈论在自动驾驶中的应用，GameFormer的理论基础之一 |
| **Bridging Level-K to Nash Equilibrium** | 2022 | [2202.12292](https://arxiv.org/abs/2202.12292) | Level-K到纳什均衡的理论桥接 |

---

### 2. 条件预测 / 交互式规划（GameFormer对比的方法）

| 论文 | 年份 | arXiv | 说明 |
|------|------|-------|------|
| **PiP: Planning-informed Trajectory Prediction for Autonomous Driving** | 2020 | [2003.11476](https://arxiv.org/abs/2003.11476) | 规划感知的轨迹预测，GameFormer引用的baseline之一 |
| **Joint Interaction and Trajectory Prediction for Autonomous Driving using Graph Neural Networks** | 2019 | [1912.07882](https://arxiv.org/abs/1912.07882) | GNN交互预测 |

---

### 3. Transformer-based 运动预测（同类方法）

| 论文 | 年份 | arXiv | 说明 |
|------|------|-------|------|
| **MTR: Motion Transformer** | 2022 | [2209.10033](https://arxiv.org/abs/2209.10033) | Waymo 2022挑战赛冠军方案 |
| **MTR++: Multi-Agent Motion Prediction** | 2023 | [2306.17770](https://arxiv.org/abs/2306.17770) | MTR的改进版，多智能体预测 |
| **Trajformer: Trajectory Prediction with Local Self-Attentive Contexts** | 2020 | [2011.14910](https://arxiv.org/abs/2011.14910) | 局部自注意力轨迹预测 |
| **Multi-modal Trajectory Prediction with Semantic Map and Dynamic Graph Attention** | 2021 | [2103.16273](https://arxiv.org/abs/2103.16273) | 语义地图+动态图注意力 |

---

## 📌 阅读优先级建议

| 优先级 | 论文 | 原因 |
|--------|------|------|
| ⭐⭐⭐ | [2009.10033](https://arxiv.org/abs/2009.10033) | Level-k游戏理论在自动驾驶中的基础工作 |
| ⭐⭐⭐ | [2003.11476](https://arxiv.org/abs/2003.11476) | PiP (Planning-informed Prediction)，GameFormer的主要对比方法 |
| ⭐⭐ | [2209.10033](https://arxiv.org/abs/2209.10033) | MTR，SOTA基线方法 |
| ⭐⭐ | [2306.17770](https://arxiv.org/abs/2306.17770) | MTR++，多智能体预测的改进 |
| ⭐ | [1912.07882](https://arxiv.org/abs/1912.07882) | GNN交互预测的早期工作 |

---

## 🔍 搜索关键词

用于在 arXiv/ScholarAIO 中查找更多相关论文：

- `game-theoretic autonomous driving trajectory prediction`
- `level-k game theory autonomous driving`
- `conditional prediction autonomous driving planning`
- `Scene Transformer Waymo motion prediction`
- `interactive prediction planning autonomous driving`

---

## 📚 GameFormer 原始信息

- **论文**: GameFormer: Game-theoretic Modeling and Learning of Transformer-based Interactive Prediction and Planning for Autonomous Driving
- **作者**: Zhiyu Huang, Haochen Liu, Chen Lv
- **会议**: ICCV 2023
- **arXiv**: 2303.05760
- **DOI**: 10.1109/iccv51070.2023.00361
- **项目主页**: https://mczhi.github.io/GameFormer/
