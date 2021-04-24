# Bert

《BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding》

《预训练的深度双向transformer用于语义理解》 Jacob Devlin Google 2018

### 知识储备

1. 概率论
2. 语言模型
3. Transformer
4. 注意力机制

### 学习目标

1. Bert蒸馏
2. Glue
3. Bert衍生模型
4. Masked LM
5. Next Sentence Prediction
6. Fine-tuning

## 论文导读

Feature-Based vs. Fine-tuning

Feature-Based 在大数据集训练后，不会进行调整。

#### Bert历史意义

- 获取了left-to-right和right-to-left的上下文信息。
- nlp领域正式开始pre-training+fine-tuning的模型训练方式

### 论文泛读

#### 摘要

1. 我们提出了一种新的语言表征模型bert，不同于其他的语言表征模型，bert可以同时学习到向左和向右的上下文信息。
2. 预训练好的bert可以直接fine-tuning，只需加相应的输出层；无需太多模型结构的改动。
3. bert模型在各项nlp下游任务中都表现得良好。























