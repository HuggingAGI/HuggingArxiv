# 降低推理成本——借助稀疏注意力机制优化思维链的途径

发布时间：2024年11月13日

`LLM应用` `语言模型`

> Reducing Reasoning Costs -- The Path of Optimization for Chain of Thought via Sparse Attention Mechanism

# 摘要

> 为解决大型语言模型推理成本飙升中的思维链问题，本研究提出采用仅关注少量相关标记的稀疏注意力机制。研究人员构建了新的注意力机制，并以用自定义 GPT 训练的 GiantRabbit 作为实验工具。实验对该模型和 o1 Preview 在解决麻省理工学院开放式课程线性代数测试题时的推理时间、正确性得分及思维链长度进行了测试和对比。结果显示，GiantRabbit 的推理时间和思维链长度明显低于 o1 Preview，证明了稀疏注意力机制在降低思维链推理方面的可行性。详细的架构细节和实验过程已上传至 Github，链接为：https://github.com/brucewang123456789/GeniusTrail.git。

> In order to address the chain of thought in the large language model inference cost surge, this research proposes to use a sparse attention mechanism that only focuses on a few relevant tokens. The researcher constructed a new attention mechanism and used GiantRabbit trained with custom GPTs as an experimental tool. The experiment tested and compared the reasoning time, correctness score and chain of thought length of this model and o1 Preview in solving the linear algebra test questions of MIT OpenCourseWare. The results show that GiantRabbit's reasoning time and chain of thought length are significantly lower than o1 Preview, confirming the feasibility of the sparse attention mechanism in reducing chain of thought reasoning. Detailed architectural details and experimental process have been uploaded to Github, the link is:https://github.com/brucewang123456789/GeniusTrail.git.

[Arxiv](https://arxiv.org/abs/2411.09111)