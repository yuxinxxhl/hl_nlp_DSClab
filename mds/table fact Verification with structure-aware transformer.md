## table fact Verification with structure-aware transformer

### 摘要

在半结构依据（表格）上的事实检测需要编码结构信息和符号推理的能力，在自然语言上预训练的NL模型不能直接应用在表格上，因为简单的线性化会丢失表格对其信息。

提出了一种结构感知的transformer，将表格信息融入自注意力层，是一种结合了符号推理和语言推理的探索

### 模型

输入还是把陈述和表格flatten，然后接一个mask了的自注意力层，把不重要的信息屏蔽

### 结果