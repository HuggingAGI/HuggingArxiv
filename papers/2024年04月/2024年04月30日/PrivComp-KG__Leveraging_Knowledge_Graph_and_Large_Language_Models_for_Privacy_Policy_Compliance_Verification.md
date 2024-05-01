# PrivComp-KG：结合知识图谱与大型语言模型，致力于隐私政策的合规性检查

发布时间：2024年04月30日

`LLM应用` `数据安全与隐私保护` `知识图谱`

> PrivComp-KG : Leveraging Knowledge Graph and Large Language Models for Privacy Policy Compliance Verification

# 摘要

> 在数字化浪潮中，数据安全与隐私保护的重要性日益凸显。众多企业将数据处理、存储等关键业务流程外包给第三方，这无疑带来了安全隐患，因为这些外部服务提供商的安全标准可能与法规要求不同步。法律往往要求企业必须遵守不断更新的监管规则，违反者可能面临法律制裁。这些复杂的法规文件需要大量精力去解读，而供应商提供的隐私政策往往细节不足，难以满足完全合规的要求，造成了许多不确定性。为了简化监管要求的解读并确保企业隐私政策与法规相符，本文提出了一种结合大型语言模型（LLM）和语义网的隐私合规解决方案。我们构建了一个创新的隐私政策合规性验证知识图谱PrivComp-KG，用以高效地存储和检索隐私政策、监管框架和法律领域相关知识。利用检索增强生成技术，我们能够在隐私政策文件中定位与监管规则相匹配的关键部分，并将这些信息整合到PrivComp-KG中。结合领域背景和规则，PrivComp-KG能够被用来查询并验证供应商的隐私政策是否遵守了相关规定。我们通过验证多家组织的隐私政策文件，证明了PrivComp-KG的有效性和实用性。

> Data protection and privacy is becoming increasingly crucial in the digital era. Numerous companies depend on third-party vendors and service providers to carry out critical functions within their operations, encompassing tasks such as data handling and storage. However, this reliance introduces potential vulnerabilities, as these vendors' security measures and practices may not always align with the standards expected by regulatory bodies. Businesses are required, often under the penalty of law, to ensure compliance with the evolving regulatory rules. Interpreting and implementing these regulations pose challenges due to their complexity. Regulatory documents are extensive, demanding significant effort for interpretation, while vendor-drafted privacy policies often lack the detail required for full legal compliance, leading to ambiguity. To ensure a concise interpretation of the regulatory requirements and compliance of organizational privacy policy with said regulations, we propose a Large Language Model (LLM) and Semantic Web based approach for privacy compliance. In this paper, we develop the novel Privacy Policy Compliance Verification Knowledge Graph, PrivComp-KG. It is designed to efficiently store and retrieve comprehensive information concerning privacy policies, regulatory frameworks, and domain-specific knowledge pertaining to the legal landscape of privacy. Using Retrieval Augmented Generation, we identify the relevant sections in a privacy policy with corresponding regulatory rules. This information about individual privacy policies is populated into the PrivComp-KG. Combining this with the domain context and rules, the PrivComp-KG can be queried to check for compliance with privacy policies by each vendor against relevant policy regulations. We demonstrate the relevance of the PrivComp-KG, by verifying compliance of privacy policy documents for various organizations.

[Arxiv](https://arxiv.org/abs/2404.19744)