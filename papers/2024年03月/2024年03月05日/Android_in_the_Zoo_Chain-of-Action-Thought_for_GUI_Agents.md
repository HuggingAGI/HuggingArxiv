# 在“Android in the Zoo”研究中，我们提出了 GUI 代理的“行动思维链”概念，旨在通过模拟人类在面对界面操作时的逻辑思考过程，提升 Android 系统中 GUI 代理的智能决策与执行能力。

发布时间：2024年03月05日

`Agent`

> Android in the Zoo: Chain-of-Action-Thought for GUI Agents

# 摘要

> 得益于LLM的发展，智能手机界涌现出大量能够依据自然语言指令预测API操作序列以完成任务的自主GUI代理。然而，过往研究较少关注这些任务中蕴含在中间截图及屏幕操作中的语义信息。为此，我们创新性地提出了“行动思维链”（CoAT），它在处理任务时兼顾前序动作描述、当前屏幕状况，以及对未来行动选择及其可能结果的深度思考。实验证明，在未经训练的LLM上采用零样本设置时，CoAT相比标准情境建模方法能大幅提高任务达成度。为了促进相关研究，我们还创建了一个名为Android-In-The-Zoo（AitZ）的基准数据集，其中包括18,643个带有行动思维链注解的屏幕-动作配对。进一步实验显示，在AitZ数据集上对一个200M模型进行微调后，其性能可与强大的CogAgent-Chat-18B相当。

> Large language model (LLM) leads to a surge of autonomous GUI agents for smartphone, which completes a task triggered by natural language through predicting a sequence of actions of API. Even though the task highly relies on past actions and visual observations, existing studies typical consider little semantic information carried out by intermediate screenshots and screen operations. To address this, this work presents Chain-of-Action-Thought (dubbed CoAT), which takes the description of the previous actions, the current screen, and more importantly the action thinking of what actions should be performed and the outcomes led by the chosen action. We demonstrate that, in a zero-shot setting upon an off-the-shell LLM, CoAT significantly improves the goal progress compared to standard context modeling. To further facilitate the research in this line, we construct a benchmark Android-In-The-Zoo (AitZ), which contains 18,643 screen-action pairs together with chain-of-action-thought annotations. Experiments show that fine-tuning a 200M model on our AitZ dataset achieves on par performance with CogAgent-Chat-18B.

[Arxiv](https://arxiv.org/abs/2403.02713)