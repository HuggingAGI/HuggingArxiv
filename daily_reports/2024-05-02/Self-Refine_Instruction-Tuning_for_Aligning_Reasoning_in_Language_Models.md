![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/follow2.gif)
# 自我精炼的指令调优：优化语言模型中的推理对齐。
发布时间：2024年05月01日

`动手训练`
> 本文提出了一种自我精炼指令调整方法，旨在激发小型语言模型（SLMs）自主提升其推理能力。该方法采用两阶段流程：首先，通过LLMs提供的示例进行指令调整，将推理能力从大型语言模型（LLMs）迁移至SLMs；其次，经过指令调整的模型通过偏好优化策略进行自我能力提升。特别是在第二阶段，SLMs利用直接偏好优化算法，自动采样生成的响应，并通过LLMs的基准真值来提供奖励，从而生成一系列推理路径。在常识推理和数学推理任务上的实验结果表明，这种方法在领域内和跨领域场景中均显著超越了传统的指令调整方法，有效拉近了小型与大型语言模型在推理能力上的差距。

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/DPO_new.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/OBQA_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/PIQA_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/GSM8K_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/CSQA_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/SIQA_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/MultiArith_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/legend_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/OBQA_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/PIQA_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/GSM8K_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/CSQA_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/SIQA_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/MultiArith_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/legend_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/OBQA_Llama2_7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/CSQA_Llama2_7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/PIQA_Llama2_7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/SIQA_Llama2_7.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/OBQA_Llama2_13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/CSQA_Llama2_13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/PIQA_Llama2_13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/SIQA_Llama2_13.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/Legend.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/MATH_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/MMLU_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/legend_in_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/MATH_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/MMLU_out_family.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2405.00402/legend_out_family.png)


- 论文原文: [https://arxiv.org/abs/2405.00402](https://arxiv.org/abs/2405.00402)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/imgs/qrcode.png)