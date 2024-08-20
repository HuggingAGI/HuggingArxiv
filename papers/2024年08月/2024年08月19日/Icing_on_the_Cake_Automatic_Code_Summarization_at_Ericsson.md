# 锦上添花：Ericsson 的自动代码摘要技术

发布时间：2024年08月19日

`LLM应用` `软件开发` `信息技术`

> Icing on the Cake: Automatic Code Summarization at Ericsson

# 摘要

> 本文展示了我们在爱立信公司对Java方法自动摘要的研究成果。我们评估了自动语义增强提示（ASAP）方法的性能，该方法利用大型语言模型（LLM）为Java方法生成引导性摘要。ASAP通过结合静态程序分析和信息检索技术，识别并利用相似示例方法及其开发者编写的Javadocs，增强LLM的提示上下文，并在研究中作为基准。与之相对，我们探索并比较了四种更简便的方法，这些方法无需静态程序分析、信息检索或示例方法。我们的方法仅依赖Java方法体作为输入，轻量且适合快速部署于商业软件开发环境。我们在爱立信的软件项目上进行了实验，并使用Guava和Elasticsearch两个广泛使用的开源Java项目复制研究，以确保结果的可靠性。性能通过八个涵盖相似性多方面的指标进行评估。特别地，我们的一个简便方法在爱立信和开源项目上的表现与ASAP方法相当或更优。此外，我们通过消融研究分析了方法名称对Javadoc摘要生成的影响，发现我们的方法在统计上受方法名称缺失的影响较小，表明我们的方法对方法名称变化更为鲁棒，且可能更全面地从方法体中提取摘要。

> This paper presents our findings on the automatic summarization of Java methods within Ericsson, a global telecommunications company. We evaluate the performance of an approach called Automatic Semantic Augmentation of Prompts (ASAP), which uses a Large Language Model (LLM) to generate leading summary comments for Java methods. ASAP enhances the $LLM's$ prompt context by integrating static program analysis and information retrieval techniques to identify similar exemplar methods along with their developer-written Javadocs, and serves as the baseline in our study. In contrast, we explore and compare the performance of four simpler approaches that do not require static program analysis, information retrieval, or the presence of exemplars as in the ASAP method. Our methods rely solely on the Java method body as input, making them lightweight and more suitable for rapid deployment in commercial software development environments. We conducted experiments on an Ericsson software project and replicated the study using two widely-used open-source Java projects, Guava and Elasticsearch, to ensure the reliability of our results. Performance was measured across eight metrics that capture various aspects of similarity. Notably, one of our simpler approaches performed as well as or better than the ASAP method on both the Ericsson project and the open-source projects. Additionally, we performed an ablation study to examine the impact of method names on Javadoc summary generation across our four proposed approaches and the ASAP method. By masking the method names and observing the generated summaries, we found that our approaches were statistically significantly less influenced by the absence of method names compared to the baseline. This suggests that our methods are more robust to variations in method names and may derive summaries more comprehensively from the method body than the ASAP approach.

[Arxiv](https://arxiv.org/abs/2408.09735)