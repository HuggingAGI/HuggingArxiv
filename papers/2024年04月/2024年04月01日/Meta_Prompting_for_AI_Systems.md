# 探索元提示技术在人工智能系统中的运用

发布时间：2024年04月01日

`LLM应用` `人工智能` `问题解决`

> Meta Prompting for AI Systems

# 摘要

> 本研究深入探讨了元提示（Meta Prompting，MP），这是一种革新性技术，正在改变语言模型和AI系统在问题解决与数据交互方面的应用。MP立足于类型理论和范畴理论，更注重信息的结构与语法，而非仅仅关注内容。文章详细阐述了MP的形式定义，阐明了其与少量示例提示的区别，并突出了其在多样AI应用中的显著效能。特别地，研究着重于将MP应用于复杂的推理任务，揭示了它如何高效地将难题拆解为简易子问题，提升令牌效率，并促进了更为公正的问题解决对比，尤其是与少量示例提示相比较。文章还介绍了MP在提示任务上的创新应用，使大型语言模型能够自我生成新提示，呈现出一种递归且类似元编程的新方式。通过一系列实证实验，如使用未经指令调整的Qwen-72B基础语言模型解决数学问题，准确度达到46.3%，超越了经过大量数学问答指令对训练的监督微调模型，甚至超过了GPT-4的初始版本；以及使用零样本元提示的Qwen-72B基础语言模型解决GSM8K问题，准确率达到83.5%；还有使用GPT-4以100%的成功率解决24点游戏任务，充分证明了MP在提升AI问题解决精度与效率方面的卓越能力，彰显了其在AI问题解决领域的革命性影响。相关代码已在 https://github.com/meta-prompting/meta-prompting 上公开。

> In this work, we present a comprehensive study of Meta Prompting (MP), an innovative technique reshaping the utilization of language models (LMs) and AI systems in problem-solving and data interaction. Grounded in type theory and category theory, Meta Prompting emphasizes the structure and syntax of information over traditional content-centric methods. The paper explores the formal definitions of Meta Prompting, sets it apart from few-shot prompting, and underlines its effectiveness in various AI applications. A key focus is applying Meta Prompting for complex reasoning tasks, showing how it effectively deconstructs intricate problems into simpler sub-problems, enhancing token efficiency, and enabling more equitable problem-solving comparisons, especially against few-shot prompting methods. Additionally, the paper introduces Meta Prompting for prompting tasks, allowing LLMs to self-generate new prompts in a recursive, metaprogramming-like manner. Empirical experiments, including using a Qwen-72B base language model equipped with meta prompt without instruction-tuning to solve MATH problems with accuracy at 46.3%, which surpass the supervised fine-tuned counterpart trained with extensive mathematical QA instruction pairs and even the initial version of GPT-4, solving GSM8K problems with 83.5% accuracy with zero-shot meta-prompted Qwen-72B base language model, and solving the Game of 24 tasks with a 100% success rate using GPT-4, demonstrate the meta prompting's efficacy in achieving high accuracy and efficiency, showcasing Meta Prompting's transformative impact on AI problem-solving. The code is available at https://github.com/meta-prompting/meta-prompting.

[Arxiv](https://arxiv.org/abs/2311.11482)