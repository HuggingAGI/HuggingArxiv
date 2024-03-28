# 本研究致力于揭示大型语言模型中存在的性别与种族偏见问题，通过量化评估方法，深入探究其内在的不公平性特征。

发布时间：2024年03月22日

`LLM应用` `人力资源` `公平性/偏见研究`

> Measuring Gender and Racial Biases in Large Language Models

# 摘要

> 传统决策过程中的社会偏见往往导致女性、少数族裔等弱势群体在经济成果上遭受不平等对待。如今，基于大型语言模型的人工智能广泛应用，正引领决策权由人类向AI转移。这种转型会对不同社会群体的分配结果产生何种影响呢？本次研究聚焦于广泛应用的LLM——OpenAI GPT，在涉及高风险决策的场景中，特别是针对不同社会背景的初级职位求职者时的性别与种族偏见。我们让GPT随机处理约361000份附带社会身份信息的简历并进行打分，结果显示，当工作经验、教育程度和技能相当时，该LLM会给予女性候选人更高的评价分数，而对于同等条件的黑人男性候选人则给出较低分数。这种偏见可能导致在特定门槛下，原本条件相似的候选人间的录用概率差距达到1%至2%，并且这一趋势在各种岗位及子样本中均普遍存在。另外，我们还发现在民主州呈现更强的亲女性和相对较弱的反黑人男性偏好。这项研究表明，基于LLM的AI系统在一定程度上有助于缓解性别偏见，但在解决种族偏见问题上却未必奏效。因此，需要更深入的研究来揭示这些现象的根本原因，并探索有效方法以减小人工智能系统中剩余的偏见。随着AI决策工具在各行各业的应用不断加深，我们的研究凸显了理解和解决可能出现的不公平结果的重要性，以期实现各社会群体间的公正待遇。

> In traditional decision making processes, social biases of human decision makers can lead to unequal economic outcomes for underrepresented social groups, such as women, racial or ethnic minorities. Recently, the increasing popularity of Large language model based artificial intelligence suggests a potential transition from human to AI based decision making. How would this impact the distributional outcomes across social groups? Here we investigate the gender and racial biases of OpenAIs GPT, a widely used LLM, in a high stakes decision making setting, specifically assessing entry level job candidates from diverse social groups. Instructing GPT to score approximately 361000 resumes with randomized social identities, we find that the LLM awards higher assessment scores for female candidates with similar work experience, education, and skills, while lower scores for black male candidates with comparable qualifications. These biases may result in a 1 or 2 percentage point difference in hiring probabilities for otherwise similar candidates at a certain threshold and are consistent across various job positions and subsamples. Meanwhile, we also find stronger pro female and weaker anti black male patterns in democratic states. Our results demonstrate that this LLM based AI system has the potential to mitigate the gender bias, but it may not necessarily cure the racial bias. Further research is needed to comprehend the root causes of these outcomes and develop strategies to minimize the remaining biases in AI systems. As AI based decision making tools are increasingly employed across diverse domains, our findings underscore the necessity of understanding and addressing the potential unequal outcomes to ensure equitable outcomes across social groups.

[Arxiv](https://arxiv.org/abs/2403.15281)