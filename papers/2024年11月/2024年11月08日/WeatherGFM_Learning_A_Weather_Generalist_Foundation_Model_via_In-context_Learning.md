# WeatherGFM：通过上下文学习来学习一个天气通才基础模型

发布时间：2024年11月08日

`LLM应用`

> WeatherGFM: Learning A Weather Generalist Foundation Model via In-context Learning

# 摘要

> 地球的天气系统包含复杂的天气数据模式和多样的天气理解任务，这对人类生活具有重要价值。现有的数据驱动模型专注于单一的天气理解任务（例如，天气预报）。尽管这些模型取得了有希望的结果，但它们无法在单个统一的模型中处理各种复杂任务。此外，依赖于单一场景有限的真实观测的范式阻碍了模型的性能上限。针对这些限制，我们从最先进的视觉基础模型和大型语言模型中采用的上下文学习范式中获得灵感。在本文中，我们引入了第一个通用天气基础模型（WeatherGFM），旨在以统一的方式处理各种各样的天气理解任务。更具体地说，我们首先统一了不同天气理解任务的表示和定义。随后，我们设计了天气提示格式来管理不同的天气数据模式，即单一、多个和时间模式。最后，我们采用了视觉提示问答范式来训练统一的天气理解任务。大量实验表明，我们的 WeatherGFM 能够有效地处理多达十个天气理解任务，包括天气预报、超分辨率、天气图像翻译和后处理。我们的方法还在未见过的任务上展示了泛化能力。

> The Earth's weather system encompasses intricate weather data modalities and diverse weather understanding tasks, which hold significant value to human life. Existing data-driven models focus on single weather understanding tasks (e.g., weather forecasting). Although these models have achieved promising results, they fail to tackle various complex tasks within a single and unified model. Moreover, the paradigm that relies on limited real observations for a single scenario hinders the model's performance upper bound. In response to these limitations, we draw inspiration from the in-context learning paradigm employed in state-of-the-art visual foundation models and large language models. In this paper, we introduce the first generalist weather foundation model (WeatherGFM), designed to address a wide spectrum of weather understanding tasks in a unified manner. More specifically, we initially unify the representation and definition of the diverse weather understanding tasks. Subsequently, we devised weather prompt formats to manage different weather data modalities, namely single, multiple, and temporal modalities. Finally, we adopt a visual prompting question-answering paradigm for the training of unified weather understanding tasks. Extensive experiments indicate that our WeatherGFM can effectively handle up to ten weather understanding tasks, including weather forecasting, super-resolution, weather image translation, and post-processing. Our method also showcases generalization ability on unseen tasks.

[Arxiv](https://arxiv.org/abs/2411.05420)