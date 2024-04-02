# 聊天建模：利用自然语言进行生物结构的程序化设计，无需经过训练过程。

发布时间：2024年04月01日

`LLM应用` `生物结构` `三维建模`

> Chat Modeling: Natural Language-based Procedural Modeling of Biological Structures without Training

# 摘要

> 三维建模技术在生物结构领域虽然复杂，但通过结合生物学与几何学知识，我们能够应对这一挑战。然而，三维建模软件的复杂操作界面和学习难度常常令人望而却步。为此，我们提出了一种创新框架，它能够将用户的文本指令转化为交互式建模系统中的实际建模操作。该框架融合了一种新式代码生成器及其解释器，技术上的突破在于引入了用户反馈机制，它能够根据用户对建模成果的满意度进行互动式优化，并以此反馈促进未来建模质量的提升。这一框架依托于先进的大型语言模型，摒弃了传统的训练流程。我们据此开发了名为 Chat Modeling 的原型工具，支持自动化及分步进行三维建模。通过与结构生物学家的合作评估，我们的方法展现出在科学研究中的应用潜力。相关资料可在 https://osf.io/x4qb7/ 访问。

> 3D modeling of biological structures is an inherently complex process, necessitating both biological and geometric understanding. Additionally, the complexity of user interfaces of 3D modeling tools and the associated steep learning curve further exacerbate the difficulty of authoring a 3D model. In this paper, we introduce a novel framework to address the challenge of using 3D modeling software by converting users' textual inputs into modeling actions within an interactive procedural modeling system. The framework incorporates a code generator of a novel code format and a corresponding code interpreter. The major technical innovation includes the user-refinement mechanism that captures the degree of user dissatisfaction with the modeling outcome, offers an interactive revision, and leverages this feedback for future improved 3D modeling. This entire framework is powered by large language models and eliminates the need for a traditional training process. We develop a prototype tool named Chat Modeling, offering both automatic and step-by-step 3D modeling approaches. Our evaluation of the framework with structural biologists highlights the potential of our approach being utilized in their scientific workflows. All supplemental materials are available at https://osf.io/x4qb7/.

[Arxiv](https://arxiv.org/abs/2404.01063)