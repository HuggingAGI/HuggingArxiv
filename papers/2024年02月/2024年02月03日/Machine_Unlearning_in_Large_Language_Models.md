# 机器忘却在大型语言模型领域备受关注，这一话题在学术界和工业界都引起了广泛的讨论。

发布时间：2024年02月03日

`LLM应用` `人工智能安全` `隐私保护`

> Machine Unlearning in Large Language Models

# 摘要

> 近期，大型语言模型（LLMs）作为新兴领域崭露头角，因其自动生成多样化应用领域智能内容的能力而备受瞩目。尽管如此，LLMs在安全与隐私方面仍存在不少挑战，如可能因黑客攻击或特定提示而泄露用户隐私。为应对这一问题，本研究提出了一种创新的机器退训练框架，旨在提升LLMs的安全性。我们的目标是确保LLMs不会生成有害、产生幻觉或侵犯隐私的响应，同时维持其标准的输出功能。通过采用评估模型精准识别需要退训练的对话，并引入距离损失作为负面损失，引导模型避免不良输出。同时，我们计算预期输出的簇均值，构建正面损失，以促进模型输出朝着更优结果发展，同时保证其推理和性能不受影响。实验结果显示，该方法在不牺牲模型性能的前提下，有效实现了退训练的目标。

> Recently, large language models (LLMs) have emerged as a notable field, attracting significant attention for its ability to automatically generate intelligent contents for various application domains. However, LLMs still suffer from significant security and privacy issues. For example, LLMs might expose user privacy from hacking attacks or targeted prompts. To address this problem, this paper introduces a novel machine unlearning framework into LLMs. Our objectives are to make LLMs not produce harmful, hallucinatory, or privacy-compromising responses, while retaining their standard output capabilities. To accomplish this, we use an evaluative model to pinpoint dialogues needing unlearning. We also establish a distance loss to function as the model's negative loss, diverting it from previous undesirable outputs. Furthermore, we determine the expected output's cluster mean to formulate a positive loss, directing the model's outputs toward preferable outcomes without compromising its reasoning abilities and performance. Experimental results show that our approach effectively meets unlearning objectives without substantially compromising model performance.

[Arxiv](https://arxiv.org/abs/2404.16841)