# RAGent：基于检索的访问控制策略生成

发布时间：2024年09月07日

`RAG` `信息安全` `访问控制`

> RAGent: Retrieval-based Access Control Policy Generation

# 摘要

> 手动从高级需求规范生成访问控制策略充满挑战，需耗时筛选多份文档并将其访问需求转化为策略，且规范的复杂与模糊常导致管理员出错，引发数据泄露。现有自动生成框架因缺乏领域适应性而不可靠。为此，我们推出RAGent，一种基于语言模型的检索式策略生成框架，能以87.9%的F1分数识别需求，并通过检索增强生成，以77.9%的F1分数转化策略。RAGent不仅生成主体、动作和资源，还包含目的和条件的复杂策略。其自动验证与迭代优化机制更将可靠性提升至80.6%的F1分数。此外，我们贡献了三个注释数据集，助力未来策略生成框架的研发，填补领域数据空白。

> Manually generating access control policies from an organization's high-level requirement specifications poses significant challenges. It requires laborious efforts to sift through multiple documents containing such specifications and translate their access requirements into access control policies. Also, the complexities and ambiguities of these specifications often result in errors by system administrators during the translation process, leading to data breaches. However, the automated policy generation frameworks designed to help administrators in this process are unreliable due to limitations, such as the lack of domain adaptation. Therefore, to improve the reliability of access control policy generation, we propose RAGent, a novel retrieval-based access control policy generation framework based on language models. RAGent identifies access requirements from high-level requirement specifications with an average state-of-the-art F1 score of 87.9%. Through retrieval augmented generation, RAGent then translates the identified access requirements into access control policies with an F1 score of 77.9%. Unlike existing frameworks, RAGent generates policies with complex components like purposes and conditions, in addition to subjects, actions, and resources. Moreover, RAGent automatically verifies the generated policies and iteratively refines them through a novel verification-refinement mechanism, further improving the reliability of the process by 3%, reaching the F1 score of 80.6%. We also introduce three annotated datasets for developing access control policy generation frameworks in the future, addressing the data scarcity of the domain.

[Arxiv](https://arxiv.org/abs/2409.07489)