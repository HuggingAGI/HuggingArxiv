# 探究上下文学习之谜：通过干扰手段剖析提示的本质

发布时间：2024年04月02日

`LLM应用` `人工智能`

> Deconstructing In-Context Learning: Understanding Prompts via Corruption

# 摘要

> 大型语言模型（LLMs）凭借所给提示进行“上下文学习”的能力，引发了它们应用的迅猛扩张，催生了ChatGPT、Claude和Bard等AI助手的流行。这些AI助手对轻微的提示调整表现出强大的适应性，主要归功于利用人类反馈的对齐技术。然而，它们所依赖的预训练LLMs本身却易受此类变动的影响。打造高质量的基础模型仍是一大挑战，而通过少量样本评估来衡量其质量是一种常见做法。这种评估对提示的微小变化和具体示例的选择极为敏感。以往的研究探讨了调整提示的不同部分如何影响模型表现，但往往只关注少数特定属性，且结果常常相互矛盾。此外，先前的研究要么聚焦于参数不足150亿的模型，要么只研究GPT-3或PaLM这样的黑盒模型，难以复制。在本研究中，我们把整个提示拆分为四个部分：任务描述、示范输入、标签和每个示范提供的内联指令，探究这些元素的结构和语义损坏对模型性能的影响。我们研究了规模从15亿到700亿不等的模型，并使用了十个包含分类和生成任务的数据集。我们发现，提示内的文本重复能够提升模型性能，而更大规模的模型（$\geq$30B）对提示的语义更加敏感。最终，我们观察到，即便指令语义受损，向示范中添加任务和内联指令也能提高模型的性能。

> The ability of large language models (LLMs) to "learn in context" based on the provided prompt has led to an explosive growth in their use, culminating in the proliferation of AI assistants such as ChatGPT, Claude, and Bard. These AI assistants are known to be robust to minor prompt modifications, mostly due to alignment techniques that use human feedback. In contrast, the underlying pre-trained LLMs they use as a backbone are known to be brittle in this respect. Building high-quality backbone models remains a core challenge, and a common approach to assessing their quality is to conduct few-shot evaluation. Such evaluation is notorious for being highly sensitive to minor prompt modifications, as well as the choice of specific in-context examples. Prior work has examined how modifying different elements of the prompt can affect model performance. However, these earlier studies tended to concentrate on a limited number of specific prompt attributes and often produced contradictory results. Additionally, previous research either focused on models with fewer than 15 billion parameters or exclusively examined black-box models like GPT-3 or PaLM, making replication challenging. In the present study, we decompose the entire prompt into four components: task description, demonstration inputs, labels, and inline instructions provided for each demonstration. We investigate the effects of structural and semantic corruptions of these elements on model performance. We study models ranging from 1.5B to 70B in size, using ten datasets covering classification and generation tasks. We find that repeating text within the prompt boosts model performance, and bigger models ($\geq$30B) are more sensitive to the semantics of the prompt. Finally, we observe that adding task and inline instructions to the demonstrations enhances model performance even when the instructions are semantically corrupted.

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x1.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x2.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x3.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x4.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x5.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x6.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x7.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x8.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x9.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x10.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x11.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x12.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x13.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x14.png)

![探究上下文学习之谜：通过干扰手段剖析提示的本质](../../../paper_images/2404.02054/x15.png)

[Arxiv](https://arxiv.org/abs/2404.02054)