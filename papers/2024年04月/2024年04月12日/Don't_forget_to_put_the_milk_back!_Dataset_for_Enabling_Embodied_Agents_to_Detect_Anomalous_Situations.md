# 别忘了将牛奶归位！这个数据集旨在让具身代理能够识别异常状况。

发布时间：2024年04月12日

`Agent` `家庭自动化` `机器人技术`

> "Don't forget to put the milk back!" Dataset for Enabling Embodied Agents to Detect Anomalous Situations

# 摘要

> 家庭机器人的使命是简化用户的日常家务。我们的研究通过赋予机器人监测家中潜在危险或卫生问题的能力，进而助力这一使命。例如，提醒用户注意未冷藏的牛奶、未关闭的炉火或儿童可能触及的有毒物品。为此，我们开发了一个新的数据集——SafetyDetect。该数据集包含1000个家庭异常场景，每个场景都模拟了需要智能代理识别的安全或卫生隐患。我们的解决方案结合了大型语言模型（LLMs）以及场景的图形表示和对象间的关系。核心洞见在于，通过场景图和对象间的关系，LLMs能更精准地理解和推理场景，尤其是在识别危险或不卫生情况时。我们采用的最有前景的方法是利用GPT-4，通过将场景图中的对象关系分类为正常、危险、不卫生或儿童危险，来识别异常情况。这种方法在SafetyDetect数据集上的识别准确率超过90%。此外，我们在ClearPath TurtleBot上进行了实地测试，通过实景视觉生成场景图，并直接应用我们的算法，结果表明性能仅略有下降。随着本文的发表，SafetyDetect数据集和相关代码将向公众开放。

> Home robots intend to make their users lives easier. Our work assists in this goal by enabling robots to inform their users of dangerous or unsanitary anomalies in their home. Some examples of these anomalies include the user leaving their milk out, forgetting to turn off the stove, or leaving poison accessible to children. To move towards enabling home robots with these abilities, we have created a new dataset, which we call SafetyDetect. The SafetyDetect dataset consists of 1000 anomalous home scenes, each of which contains unsafe or unsanitary situations for an agent to detect. Our approach utilizes large language models (LLMs) alongside both a graph representation of the scene and the relationships between the objects in the scene. Our key insight is that this connected scene graph and the object relationships it encodes enables the LLM to better reason about the scene -- especially as it relates to detecting dangerous or unsanitary situations. Our most promising approach utilizes GPT-4 and pursues a categorization technique where object relations from the scene graph are classified as normal, dangerous, unsanitary, or dangerous for children. This method is able to correctly identify over 90% of anomalous scenarios in the SafetyDetect Dataset. Additionally, we conduct real world experiments on a ClearPath TurtleBot where we generate a scene graph from visuals of the real world scene, and run our approach with no modification. This setup resulted in little performance loss. The SafetyDetect Dataset and code will be released to the public upon this papers publication.

![别忘了将牛奶归位！这个数据集旨在让具身代理能够识别异常状况。](../../../paper_images/2404.08827/x1.png)

![别忘了将牛奶归位！这个数据集旨在让具身代理能够识别异常状况。](../../../paper_images/2404.08827/Qualitative.png)

![别忘了将牛奶归位！这个数据集旨在让具身代理能够识别异常状况。](../../../paper_images/2404.08827/x2.png)

![别忘了将牛奶归位！这个数据集旨在让具身代理能够识别异常状况。](../../../paper_images/2404.08827/x3.png)

[Arxiv](https://arxiv.org/abs/2404.08827)