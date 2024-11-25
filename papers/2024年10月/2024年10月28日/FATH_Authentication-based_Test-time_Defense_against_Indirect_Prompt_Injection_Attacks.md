# FATH：基于身份验证的抵御间接提示注入攻击的测试时防护手段

发布时间：2024年10月28日

`LLM应用` `语言模型` `网络安全`

> FATH: Authentication-based Test-time Defense against Indirect Prompt Injection Attacks

# 摘要

> 大型语言模型（LLMs）已被广泛用作核心，并搭配其他工具和文本信息应用于现实场景。但将外部信息融入 LLM 集成应用时，引发了严重的安全隐患。其中，提示注入攻击尤为危险，外部文本中注入的恶意指令能操控 LLMs 生成攻击者想要的答案。虽然已开发出训练时和测试时的防御手段来应对这类攻击，可训练时方法的高昂训练成本，以及现有测试时方法效果有限，导致它们难以落地。本文推出一种全新的测试时防御策略，名为基于哈希标签的格式化认证（FATH）。和现有的阻止 LLMs 回应外部文本中附加指令的方法不同，我们的方法构建了一个认证系统，要求 LLMs 依据安全策略回应所有收到的指令，并选择性地筛选出对用户指令的响应作为最终输出。为此，我们运用基于哈希的认证标签标记每个响应，利于按照用户指令精准识别响应，增强对自适应攻击的抵御能力。综合实验表明，我们的防御方法能有效抵御间接提示注入攻击，在 Llama3 和 GPT3.5 模型的各类攻击方式下达到了领先水平。我们的代码发布于：https://github.com/Jayfeather1024/FATH

> Large language models (LLMs) have been widely deployed as the backbone with additional tools and text information for real-world applications. However, integrating external information into LLM-integrated applications raises significant security concerns. Among these, prompt injection attacks are particularly threatening, where malicious instructions injected in the external text information can exploit LLMs to generate answers as the attackers desire. While both training-time and test-time defense methods have been developed to mitigate such attacks, the unaffordable training costs associated with training-time methods and the limited effectiveness of existing test-time methods make them impractical. This paper introduces a novel test-time defense strategy, named Formatting AuThentication with Hash-based tags (FATH). Unlike existing approaches that prevent LLMs from answering additional instructions in external text, our method implements an authentication system, requiring LLMs to answer all received instructions with a security policy and selectively filter out responses to user instructions as the final output. To achieve this, we utilize hash-based authentication tags to label each response, facilitating accurate identification of responses according to the user's instructions and improving the robustness against adaptive attacks. Comprehensive experiments demonstrate that our defense method can effectively defend against indirect prompt injection attacks, achieving state-of-the-art performance under Llama3 and GPT3.5 models across various attack methods. Our code is released at: https://github.com/Jayfeather1024/FATH

[Arxiv](https://arxiv.org/abs/2410.21492)