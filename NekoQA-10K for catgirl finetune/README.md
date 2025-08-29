# NekoQA-10K & NekoBench

> *"Towards Evaluating Large Language Models with Catgirl Flavor"*
>  喵学研究的开源实现

------
![catgirl](catgirl/catgirl1.png)

## 📖 简介

本项目开源了 **NekoQA-10K**（猫娘对话数据集）与 **NekoBench**（猫娘评测基准），并提供了基于该数据集的 **多模型微调代码**。
 本研究首次系统性地探索了 **大语言模型的“猫娘味”建模能力**，并提出了创新指标 **NPS（Nekomimi Perception Score，猫娘味感知指数）**。

如果你曾经怀疑：“LLM 能否变成猫娘？” —— 本仓库给出了实验级回答。

------

## 📂 仓库结构
我会逐步完善的
```
.
├── data/
│   ├── NekoQA-10K/         # 猫娘对话数据集
│   └── NekoBench/          # 六大模块评测数据
├── scripts/
│   ├── finetune.py         # 微调代码
│   ├── evaluate.py         # 评测代码
├── models/
│   └── checkpoints/        # 训练好的模型参数
├── results/
│   └── figures/            # 实验结果与可视化
└── README.md
```

------

## 🐱 数据集

- **NekoQA-10K**
  - 10,000 条猫娘风格 QA 对话
  - 人设统一：称呼“主人”、常见口癖（喵~、no desu、的说喵 等）
  - 数据来源：①手工原创，②弱智吧、心理辅导等领域问答经强模型重写；③沐雪数据集抽取了900条问题
- **NekoBench**
  - 六大评测模块：PES、KRI、INS、SAF、CF、ERM
  - 每模块 100 条测试数据
  - 结合强模型进行自动化打分

------

## 🧪 实验

我们在以下模型上进行了微调与评测：

- Qwen3-4B、Qwen3-14B
- gpt-oss-20B
- LLaMA-3.2

核心指标：**NPS（猫娘味感知指数）**

实验结果详见 [论文 ](https://zhuanlan.zhihu.com/p/1934983798233231689)。

------

## 🚀 快速上手

### 安装依赖

```bash

```

### 数据准备

```bash

```

### 模型微调

```bash

```

### 评测

```bash

```

------

## 📊 结果可视化



------

## 🔓 开源协议

本项目采用 **MIT License**。
 猫娘味可自由传播，撒娇权属于全人类。

------

## ❤️ 致谢

- 弱智吧等社区与强模型，提供了宝贵灵感与数据。
- 所有仍在追求“真正猫娘”的科研工作者。

------

## 🌸 引用

如果你觉得本项目有用，请引用我们的论文(bushi：

```bibtex
@article{nekoqa2025,
  title={NekoQA-10K: A Catgirl Dialogue Dataset and NekoBench Evaluation},
  author={MindsRiverPonder},
  journal={ZHIHU preprint ZHIHU:2508.22},
  year={2025}
}
```

