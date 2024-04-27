# Chat2Scenario：利用大型语言模型从数据集中提炼场景

发布时间：2024年04月24日

`分类：LLM应用

这篇论文摘要描述了一种利用大型语言模型（LLM）的自然语言处理（NLP）技术，从自然驾驶数据集中提炼出各种驾驶场景的方法。这种方法被称为Chat2Scenario框架，它允许用户输入关于驾驶环境的描述，并根据关键性指标的阈值来筛选和锁定目标场景。然后将这些场景转换成特定格式的文本文件，以便于自动驾驶系统（ADS）的验证。这篇论文的焦点在于应用LLM技术来解决实际问题，因此它应该被归类为LLM应用。` `自动驾驶`

> Chat2Scenario: Scenario Extraction From Dataset Through Utilization of Large Language Model

# 摘要

> 随着大型语言模型（LLM）的兴起，我们获得了验证自动驾驶系统（ADS）的新视角。本研究提出了一种创新的方法，用于从自然驾驶数据集中提炼出各种驾驶场景。我们引入了一个名为Chat2Scenario的框架，该框架借助LLM的先进自然语言处理（NLP）技术，来理解并识别多样化的驾驶情境。用户只需输入关于驾驶环境的描述，并设定关键性指标的阈值，框架便能高效地筛选并锁定目标场景，进而将这些场景转换成ASAM OpenSCENARIO和IPG CarMaker格式的文本文件。这一流程不仅简化了场景提取工作，还显著提升了工作效率。为了验证此方法的有效性，我们进行了一系列的仿真测试。Chat2Scenario框架以一个易于操作的Web应用形式呈现，并通过以下链接向公众开放：https://github.com/ftgTUGraz/Chat2Scenario。

> The advent of Large Language Models (LLM) provides new insights to validate Automated Driving Systems (ADS). In the herein-introduced work, a novel approach to extracting scenarios from naturalistic driving datasets is presented. A framework called Chat2Scenario is proposed leveraging the advanced Natural Language Processing (NLP) capabilities of LLM to understand and identify different driving scenarios. By inputting descriptive texts of driving conditions and specifying the criticality metric thresholds, the framework efficiently searches for desired scenarios and converts them into ASAM OpenSCENARIO and IPG CarMaker text files. This methodology streamlines the scenario extraction process and enhances efficiency. Simulations are executed to validate the efficiency of the approach. The framework is presented based on a user-friendly web app and is accessible via the following link: https://github.com/ftgTUGraz/Chat2Scenario.

[Arxiv](https://arxiv.org/abs/2404.16147)