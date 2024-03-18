# AtP*：一项创新技术，高效且易于规模化应用，旨在对大型语言模型（LLM）的行为进行精细化组件定位。

发布时间：2024年03月01日

`LLM理论`

> AtP*: An efficient and scalable method for localizing LLM behaviour to components

> 激活修补技术能精准定位模型组件对特定行为的影响，但面对顶尖的大型语言模型（LLMs），因其所需资源与模型组件数量成线性增长，实施起来成本高昂。为此，我们探索了一种高效的梯度近似方法——Attribution Patching（简称AtP），并揭示了该方法出现两类导致严重假阴性结果的失效模式。为了解决这些问题同时保持算法的高效性，我们提出了改良版AtP——AtP*。首个系统性研究表明，AtP相较于其他同类方法具有显著优势，而AtP*则在此基础上带来了更进一步的提升。最终，我们还给出了一种估算方法，能够对AtP*可能存在假阴性的概率进行有效界定。

> Activation Patching is a method of directly computing causal attributions of behavior to model components. However, applying it exhaustively requires a sweep with cost scaling linearly in the number of model components, which can be prohibitively expensive for SoTA Large Language Models (LLMs). We investigate Attribution Patching (AtP), a fast gradient-based approximation to Activation Patching and find two classes of failure modes of AtP which lead to significant false negatives. We propose a variant of AtP called AtP*, with two changes to address these failure modes while retaining scalability. We present the first systematic study of AtP and alternative methods for faster activation patching and show that AtP significantly outperforms all other investigated methods, with AtP* providing further significant improvement. Finally, we provide a method to bound the probability of remaining false negatives of AtP* estimates.

[Arxiv](https://arxiv.org/abs/2403.00745)