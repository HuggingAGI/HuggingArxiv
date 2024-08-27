# LLM-3D Print：利用大型语言模型监控与控制3D打印过程

发布时间：2024年08月26日

`LLM应用` `制造业` `增材制造`

> LLM-3D Print: Large Language Models To Monitor and Control 3D Printing

# 摘要

> 工业4.0引领制造业数字化革命，转向增材制造（AM），其中熔融沉积建模（FDM）技术通过逐层挤出，实现高度定制、成本效益高且材料浪费极少的产品生产，挑战传统减材工艺。然而，材料挤出技术的易错性常需专家介入以检测和缓解可能严重影响产品质量的缺陷。尽管有自动错误检测和机器学习模型，但它们在多样化的3D打印环境中的通用性受限，且深度学习方法依赖大量标记数据，限制了其可扩展性和适应性。为此，我们提出一种结合预训练大型语言模型（LLM）与3D打印机的过程监控和控制框架，用于检测和纠正打印缺陷。LLM通过分析每层或打印段后捕获的图像评估打印质量，识别故障模式并查询打印机参数，进而生成并执行纠正措施。通过与多样化AM专业工程师对照组比较，验证了该框架在缺陷识别上的有效性。评估显示，基于LLM的代理不仅能准确识别常见3D打印错误，如挤出不一致、拉丝、翘曲和层粘附问题，还能有效确定故障参数并自主纠正，无需人工干预。

> Industry 4.0 has revolutionized manufacturing by driving digitalization and shifting the paradigm toward additive manufacturing (AM). Fused Deposition Modeling (FDM), a key AM technology, enables the creation of highly customized, cost-effective products with minimal material waste through layer-by-layer extrusion, posing a significant challenge to traditional subtractive methods. However, the susceptibility of material extrusion techniques to errors often requires expert intervention to detect and mitigate defects that can severely compromise product quality. While automated error detection and machine learning models exist, their generalizability across diverse 3D printer setups, firmware, and sensors is limited, and deep learning methods require extensive labeled datasets, hindering scalability and adaptability. To address these challenges, we present a process monitoring and control framework that leverages pre-trained Large Language Models (LLMs) alongside 3D printers to detect and address printing defects. The LLM evaluates print quality by analyzing images captured after each layer or print segment, identifying failure modes and querying the printer for relevant parameters. It then generates and executes a corrective action plan. We validated the effectiveness of the proposed framework in identifying defects by comparing it against a control group of engineers with diverse AM expertise. Our evaluation demonstrated that LLM-based agents not only accurately identify common 3D printing errors, such as inconsistent extrusion, stringing, warping, and layer adhesion, but also effectively determine the parameters causing these failures and autonomously correct them without any need for human intervention.

[Arxiv](https://arxiv.org/abs/2408.14307)