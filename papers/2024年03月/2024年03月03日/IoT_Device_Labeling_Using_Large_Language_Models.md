# [借助大型语言模型实现物联网设备智能标注](https://arxiv.org/abs/2403.01586)

发布时间：2024年03月03日

`LLM应用`

> IoT Device Labeling Using Large Language Models

> 面对物联网市场的多元化与多供应商设备（例如扬声器、摄像头、吸尘器等）的特性，物联网安全与监测系统运用实时识别技术有效管控各类设备。目前主流的物联网识别方案在训练时默认已观察过供应商与功能双重标签的设备，而我们正着手解决一个核心难题：如何使AI方案能为从未见过且标签不明的物联网设备自动标注？我们提出的方法首先从网络流量中抽取出域名、主机名等文本信息，并借助谷歌搜索数据和设备供应商及功能目录对其加以丰富强化。此外，方案还搭载了基于LLMs的自动更新机制，以及时收录新型设备类型至目录中。根据收集的数据，通过与强化特征进行字符串匹配来识别设备供应商，再运用LLMs配合预设的物联网功能目录进行零样本分类，从而推断出设备的功能。在对97款独特物联网设备的实际测评中，我们的功能标注策略获得了HIT1指标0.7分和HIT2指标0.77分的好成绩。目前为止，这可能是首项研究探讨AI自动标注物联网设备的课题。

> The IoT market is diverse and characterized by a multitude of vendors that support different device functions (e.g., speaker, camera, vacuum cleaner, etc.). Within this market, IoT security and observability systems use real-time identification techniques to manage these devices effectively. Most existing IoT identification solutions employ machine learning techniques that assume the IoT device, labeled by both its vendor and function, was observed during their training phase. We tackle a key challenge in IoT labeling: how can an AI solution label an IoT device that has never been seen before and whose label is unknown?
  Our solution extracts textual features such as domain names and hostnames from network traffic, and then enriches these features using Google search data alongside catalog of vendors and device functions. The solution also integrates an auto-update mechanism that uses Large Language Models (LLMs) to update these catalogs with emerging device types. Based on the information gathered, the device's vendor is identified through string matching with the enriched features. The function is then deduced by LLMs and zero-shot classification from a predefined catalog of IoT functions.
  In an evaluation of our solution on 97 unique IoT devices, our function labeling approach achieved HIT1 and HIT2 scores of 0.7 and 0.77, respectively. As far as we know, this is the first research to tackle AI-automated IoT labeling.

[Arxiv](https://arxiv.org/abs/2403.01586)