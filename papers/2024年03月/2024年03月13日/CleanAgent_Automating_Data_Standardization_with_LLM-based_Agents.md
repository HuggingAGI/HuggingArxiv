# [CleanAgent是一款利用大型语言模型（LLM）构建的数据标准化自动化工具，它借助LLM智能代理技术，实现高效、自动化的数据清洗与标准化。](https://arxiv.org/abs/2403.08291)

发布时间：2024年03月13日

`Agent` `数据科学` ``

> CleanAgent: Automating Data Standardization with LLM-based Agents

> 在数据科学工作中，数据标准化举足轻重，但现有工具虽功能强大，却因操作复杂及针对各类列类型自定义代码的工作量大而面临困扰。尽管大型语言模型（如ChatGPT）已初露端倪，尝试通过自然语言理解与代码生成来简化此过程，但依然要求专家级编程知识，并需不断调整提示信息以优化效果。因此，我们计划推出一款Python库，它具备声明式、一体化的API接口，能便捷地对列类型进行标准化设定，仅需寥寥几行简洁的API调用，即可让LLM轻松生成相关代码。首先，我们构建了Dataprep.Clean组件，作为Dataprep库的一部分，凭借一行代码即可完成特定列类型的标准化，极大地简化了操作难度。接着，我们推出了CleanAgent框架，整合了Dataprep.Clean与基于LLM的智能代理，全自动实现数据标准化流程。这样一来，数据科学家只需一次性表达需求，CleanAgent就能全程“无人驾驶”，自动执行数据标准化任务。

> Data standardization is a crucial part in data science life cycle. While tools like Pandas offer robust functionalities, their complexity and the manual effort required for customizing code to diverse column types pose significant challenges. Although large language models (LLMs) like ChatGPT have shown promise in automating this process through natural language understanding and code generation, it still demands expert-level programming knowledge and continuous interaction for prompt refinement. To solve these challenges, our key idea is to propose a Python library with declarative, unified APIs for standardizing column types, simplifying the code generation of LLM with concise API calls. We first propose Dataprep.Clean which is written as a component of the Dataprep Library, offers a significant reduction in complexity by enabling the standardization of specific column types with a single line of code. Then we introduce the CleanAgent framework integrating Dataprep.Clean and LLM-based agents to automate the data standardization process. With CleanAgent, data scientists need only provide their requirements once, allowing for a hands-free, automatic standardization process.

![CleanAgent是一款利用大型语言模型（LLM）构建的数据标准化自动化工具，它借助LLM智能代理技术，实现高效、自动化的数据清洗与标准化。](../../../paper_images/2403.08291/x1.png)

![CleanAgent是一款利用大型语言模型（LLM）构建的数据标准化自动化工具，它借助LLM智能代理技术，实现高效、自动化的数据清洗与标准化。](../../../paper_images/2403.08291/x2.png)

![CleanAgent是一款利用大型语言模型（LLM）构建的数据标准化自动化工具，它借助LLM智能代理技术，实现高效、自动化的数据清洗与标准化。](../../../paper_images/2403.08291/x3.png)

![CleanAgent是一款利用大型语言模型（LLM）构建的数据标准化自动化工具，它借助LLM智能代理技术，实现高效、自动化的数据清洗与标准化。](../../../paper_images/2403.08291/x4.png)

[Arxiv](https://arxiv.org/abs/2403.08291)