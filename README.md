<h1 align='center'>医疗大模型中文考试评估</h1>


<div align="center"><img width="300" height="300" src="./image/logo.png"></div>


### 🔎 数据集介绍

**MLCE(Medical-LLMs-Chinese-Exam):医疗大模型中文考试评估**，针对于**中国各类医疗考试**、**相关比赛**数据集进行收集整理，用于助力大模型评测自身**专项能力**并进行针对性训练，目的是促进医疗领域具有全方位能力的大模型开发。

### 🌈 数据集进展

[2024/7/7] :new: **2017-2021年中国国家执业医师资格考试、中国国家执业药师资格考试、中国国家执业护士资格考试题目**

[2024/7/7] :new:   MLCE数据集**首次开源**

### 📃 数据样例

针对考题类型数据，采用下列格式:
```
    {
        "id": "",   # 测试题相关信息组成的题目id
        "question": "",  # 测试题问题
        "options": {},  # 选项键值对
        "answer": "",  # 标准答案
        "question_type": ""  # 选择题类型，单选/多选
    }
```
例如：
```
    {
        "id": "2017-Unit1-1",
        "question": "男，40岁，因劳累近2周自感头晕、头疼，连续三次测血压值为21",
        "options": {
            "A": "急进性高血压",
            "B": "慢性肾炎",
            "C": "甲亢",
            "D": "原发性高血压",
            "E": "SLE"
        },
        "answer": "D",
        "question_type": "单项选择题"
    }
```
### 🔬 数据细节

| 数据集名称  |  样本数量  | 数据归属 | 数据源 |
|:---:|:---:|:---:|:---:|
|2017-2021physician.json|3000|中国国家执业医师资格考试|[LLM-Chinese-NMLE](https://github.com/zonghui0228/LLM-Chinese-NMLE)|
|2017-2021pharmacist.json|2400|中国国家执业药师资格考试|[LLM-Chinese-NMLE](https://github.com/zonghui0228/LLM-Chinese-NMLE)|
|2017-2021nurse.json|1200|中国国家执业护士资格考试|[LLM-Chinese-NMLE](https://github.com/zonghui0228/LLM-Chinese-NMLE)|
||总计|6600||

**感谢所有数据源的开源作者！**，已处理完毕的数据可在`data/`中获取

**更多数据正在处理中~**

### 💌 联系
  若您对该工作**感兴趣**或有**数据支持**，以及**相关问题**可联系**邮箱：jingnant@163.com**

