# 多样化、验证、适应：一种高效且健壮的检索增强模糊问答方法

发布时间：2024年09月03日

`RAG` `问答系统` `信息检索`

> Diversify-verify-adapt: Efficient and Robust Retrieval-Augmented Ambiguous Question Answering

# 摘要

> RAG框架通过检索并整合多角度段落来解决QA系统中的查询歧义，但单一检索常因遗漏关键解释而效果不佳。迭代RAG虽能改善，却牺牲了效率。为此，我们设计了DIVA框架，它首先扩展检索范围以包含多样解释，然后验证并优化段落质量，从而在提升准确性与鲁棒性的同时，确保了系统的高效运行。

> The retrieval augmented generation (RAG) framework addresses an ambiguity in user queries in QA systems by retrieving passages that cover all plausible interpretations and generating comprehensive responses based on the passages. However, our preliminary studies reveal that a single retrieval process often suffers from low quality results, as the retrieved passages frequently fail to capture all plausible interpretations. Although the iterative RAG approach has been proposed to address this problem, it comes at the cost of significantly reduced efficiency. To address these issues, we propose the diversify-verify-adapt (DIVA) framework. DIVA first diversifies the retrieved passages to encompass diverse interpretations. Subsequently, DIVA verifies the quality of the passages and adapts the most suitable approach tailored to their quality. This approach improves the QA systems accuracy and robustness by handling low quality retrieval issue in ambiguous questions, while enhancing efficiency.

[Arxiv](https://arxiv.org/abs/2409.02361)