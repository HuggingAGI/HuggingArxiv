# 驾驭大型语言模型，游走于代码执行与文本推理之间

发布时间：2024年10月04日

`LLM应用` `人工智能` `软件开发`

> Steering Large Language Models between Code Execution and Textual Reasoning

# 摘要

> 尽管许多研究致力于通过优化多代理框架或推理链来提升大型语言模型（LLMs）的文本推理能力，但直接编码却能以100%的成功率解决某些基准任务，这种方法不仅更具扩展性，还避免了文本迭代和搜索带来的计算负担。文本推理在应对数学、逻辑、优化和搜索等复杂任务时存在固有局限，仅靠扩大模型和数据规模难以克服。最近，OpenAI的GPT代码解释器和AutoGen等多代理框架展示了集成代码生成与执行以解决复杂任务的强大能力。然而，我们的实验表明，在7种现有方法中，尚无一种能在需要时完美引导LLMs编写代码。我们观察到，随着任务复杂性和模型规模的增加，模型在代码与文本推理间的选择呈现出有趣的模式，甚至出现了逆缩放定律。此外，即使任务可通过代码解决，LLM生成的代码结果未必优于文本推理。为此，我们提出了三种改进方法，显著提升了代码/文本生成的引导效果，并详细分析了各方法的令牌长度和运行时成本。我们认为，这一领域对未来研究至关重要，仍有广阔的改进空间。项目详情、数据集和代码可访问https://yongchao98.github.io/CodeSteer/。

> While a lot of recent research focuses on enhancing the textual reasoning capabilities of Large Language Models (LLMs) by optimizing the multi-agent framework or reasoning chains, several benchmark tasks can be solved with 100% success through direct coding, which is more scalable and avoids the computational overhead associated with textual iterating and searching. Textual reasoning has inherent limitations in solving tasks with challenges in math, logics, optimization, and searching, which is unlikely to be solved by simply scaling up the model and data size. The recently released OpenAI GPT Code Interpreter and multi-agent frameworks such as AutoGen have demonstrated remarkable proficiency of integrating code generation and execution to solve complex tasks using LLMs. However, based on our experiments on 7 existing popular methods for steering code/text generation in both single- and multi-turn settings with 14 tasks and 6 types of LLMs (including the new O1-preview), currently there is no optimal method to correctly steer LLMs to write code when needed. We discover some interesting patterns on when models use code vs. textual reasoning with the evolution to task complexity and model sizes, which even result in an astonishingly inverse scaling law. We also discover that results from LLM written code are not always better than using textual reasoning, even if the task could be solved through code. To mitigate the above issues, we propose three methods to better steer LLM code/text generation and achieve a notable improvement. The costs of token lengths and runtime are thoroughly discussed for all the methods. We believe the problem of steering LLM code/text generation is critical for future research and has much space for further improvement. Project Page, Datasets, and Codes are available at https://yongchao98.github.io/CodeSteer/.

[Arxiv](https://arxiv.org/abs/2410.03524)