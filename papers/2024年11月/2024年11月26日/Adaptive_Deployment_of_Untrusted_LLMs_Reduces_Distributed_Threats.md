# 通过自适应部署不可信的大型语言模型（LLMs），能够降低分布式威胁。

发布时间：2024年11月26日

`LLM应用` `代码生成` `安全评估`

> Adaptive Deployment of Untrusted LLMs Reduces Distributed Threats

# 摘要

> 随着大型语言模型（LLMs）的能力不断提升，有必要审慎评估即便 LLMs 有意试图避开安全措施，这些措施是否依然有效。此前的工作引入了控制评估，这是用于测试不可信模型（即可能试图绕开安全措施的模型）部署策略的对抗性框架。先前的工作将单次失败视为不可接受，而我们则在“分布式威胁场景”中开展控制评估——在此场景中，单个行为并非灾难性的，也没有单个行为能提供压倒性的失调证据。我们通过一个两级部署框架来处理此问题，该框架运用自适应宏观协议在微观协议间进行抉择。微观协议针对单个任务运作，利用能力稍弱但经过大量测试（可信）的模型来驾驭和监控不可信模型。与此同时，宏观协议依据不可信模型过往的行为对其一致性保持自适应的信任度，并据此在更安全和更具风险的微观协议间选取。我们在一个代码生成测试平台上对我们的方法进行评估，在该平台上，红队试图用一个 LLM 生成暗藏后门的代码，而其部署由蓝队守护。我们描绘了安全（非后门解决方案的数量）和有用性（正确解决方案的数量）的帕累托前沿。在给定的有用性水平下，与非自适应基线相比，我们的自适应部署策略使后门数量减少了 80%。

> As large language models (LLMs) become increasingly capable, it is prudent to assess whether safety measures remain effective even if LLMs intentionally try to bypass them. Previous work introduced control evaluations, an adversarial framework for testing deployment strategies of untrusted models (i.e., models which might be trying to bypass safety measures). While prior work treats a single failure as unacceptable, we perform control evaluations in a "distributed threat setting" -- a setting where no single action is catastrophic and no single action provides overwhelming evidence of misalignment. We approach this problem with a two-level deployment framework that uses an adaptive macro-protocol to choose between micro-protocols. Micro-protocols operate on a single task, using a less capable, but extensively tested (trusted) model to harness and monitor the untrusted model. Meanwhile, the macro-protocol maintains an adaptive credence on the untrusted model's alignment based on its past actions, using it to pick between safer and riskier micro-protocols. We evaluate our method in a code generation testbed where a red team attempts to generate subtly backdoored code with an LLM whose deployment is safeguarded by a blue team. We plot Pareto frontiers of safety (# of non-backdoored solutions) and usefulness (# of correct solutions). At a given level of usefulness, our adaptive deployment strategy reduces the number of backdoors by 80% compared to non-adaptive baselines.

[Arxiv](https://arxiv.org/abs/2411.17693)