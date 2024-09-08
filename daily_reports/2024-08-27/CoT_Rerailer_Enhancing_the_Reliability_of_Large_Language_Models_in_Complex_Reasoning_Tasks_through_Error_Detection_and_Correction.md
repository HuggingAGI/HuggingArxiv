# CoT Rerailer：通过错误检测与纠正机制，提升大型语言模型在复杂推理任务中的可靠性。
发布时间：2024年08月25日

`提示工程`
> CoT Rerailer: Enhancing the Reliability of Large Language Models in Complex Reasoning Tasks through Error Detection and Correction
>
> 通过生成中间步骤，Chain-of-Thought (CoT) prompting 提升了大型语言模型 (LLM) 的复杂推理能力，但这些步骤可能带来幻觉和错误累积。为此，我们设计了 CoT Rerailer，它利用自我一致性和多代理辩论系统来识别并修正推理错误。首先，CoT Rerailer 通过一致性检查和自动化代理的评估选择最合逻辑的推理路径。接着，它启动多代理辩论系统，提出并验证修正，确保生成无误的中间逻辑路径。修正后的步骤用于构建更精确的推理链，减少幻觉，提升答案质量。我们在跨领域的多样化问答数据集中验证了这一方法的有效性，增强了 LLM 推理的可靠性，推动了更可信赖的 AI 决策过程。
>
> https://arxiv.org/abs/2408.13940

**如遇无法添加，请+ vx: iamxxn886**
<hr />

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/model_compare.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/rerailer_overview.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/multi_agent_debate_schematic.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/postive_sample_2math_big.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/cms.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/acc_sub.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/postive_sample_physics.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/judge.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/judge2.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/step_verifier.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/step_verifier_1.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/multiagent_debate_1.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/multiagent_debate.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/Multi-Step_Correction.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/wrong_gt.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/lack_of_background_info.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/Ambigious_Question.jpg)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2408.13940/samples.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2408.13940](https://arxiv.org/abs/2408.13940)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)