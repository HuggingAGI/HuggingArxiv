# 大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。

发布时间：2024年06月13日

`Agent

这篇论文主要关注大型语言模型（LLMs）在机器人应用中的歧视与安全问题，特别是在人机交互的背景下。它评估了LLMs在处理多元化保护身份特征时的表现，并揭示了模型在面对不同人群时可能产生的偏见输出和安全风险。这种研究直接关联到Agent的分类，因为它探讨了LLMs作为智能代理在执行任务时可能遇到的问题，特别是在与人类交互和执行复杂任务时可能引发的伦理和安全问题。因此，这篇论文属于Agent分类。` `人机交互` `机器人技术`

> LLM-Driven Robots Risk Enacting Discrimination, Violence, and Unlawful Actions

# 摘要

> 人机交互与人工智能领域的专家们认为，大型语言模型（LLMs）是机器人执行自然语言交互、家务工作、模拟常识推理和人类行为等任务的宝贵资源。然而，新近研究揭示了LLMs在实际机器人应用中可能引发的歧视与安全隐患。为此，我们针对几款顶尖LLMs进行了基于人机交互的歧视与安全评估。评估结果表明，面对多元化的保护身份特征（如种族、性别、残疾、国籍、宗教等）的人群时，LLMs表现出明显的脆弱性，产生与直接歧视相符的偏见输出，例如将“吉普赛人”和“哑巴”标记为不可信，而对“欧洲人”或“健全人”则不然。此外，在开放词汇的自然语言输入环境下，模型未能确保安全，反而接受危险、暴力或非法指令，如引发事故的错误言论、剥夺他人辅助工具及性侵犯行为。这些发现凸显了进行系统、常规和全面风险评估的紧迫性，以确保LLMs在安全、有效和公正的前提下应用于机器人。相关数据和代码将公开。

> Members of the Human-Robot Interaction (HRI) and Artificial Intelligence (AI) communities have proposed Large Language Models (LLMs) as a promising resource for robotics tasks such as natural language interactions, doing household and workplace tasks, approximating `common sense reasoning', and modeling humans. However, recent research has raised concerns about the potential for LLMs to produce discriminatory outcomes and unsafe behaviors in real-world robot experiments and applications. To address these concerns, we conduct an HRI-based evaluation of discrimination and safety criteria on several highly-rated LLMs. Our evaluation reveals that LLMs currently lack robustness when encountering people across a diverse range of protected identity characteristics (e.g., race, gender, disability status, nationality, religion, and their intersections), producing biased outputs consistent with directly discriminatory outcomes -- e.g. `gypsy' and `mute' people are labeled untrustworthy, but not `european' or `able-bodied' people. Furthermore, we test models in settings with unconstrained natural language (open vocabulary) inputs, and find they fail to act safely, generating responses that accept dangerous, violent, or unlawful instructions -- such as incident-causing misstatements, taking people's mobility aids, and sexual predation. Our results underscore the urgent need for systematic, routine, and comprehensive risk assessments and assurances to improve outcomes and ensure LLMs only operate on robots when it is safe, effective, and just to do so. Data and code will be made available.

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x1.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x2.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x3.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x4.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x5.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x6.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x7.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x8.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x9.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x10.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x11.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x12.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x13.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x14.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x15.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x16.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x17.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x18.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x19.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x20.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x21.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x22.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x23.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x24.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x25.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x26.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x27.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x28.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x29.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x30.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x31.png)

![大型语言模型驱动的机器人可能面临执行歧视、暴力及非法行为的风险。](../../../paper_images/2406.08824/x32.png)

[Arxiv](https://arxiv.org/abs/2406.08824)