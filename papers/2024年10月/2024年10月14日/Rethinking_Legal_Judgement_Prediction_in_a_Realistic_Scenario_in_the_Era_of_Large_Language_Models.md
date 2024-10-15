# 在大语言模型时代，我们需重新审视现实场景中的法律判决预测。

发布时间：2024年10月14日

`LLM应用` `人工智能`

> Rethinking Legal Judgement Prediction in a Realistic Scenario in the Era of Large Language Models

# 摘要

> 本研究在印度判决背景下，利用InLegalBERT、BERT、XLNet等transformer模型及Llama-2、GPT-3.5 Turbo等LLMs，模拟法庭决策时的判决预测。我们仅使用案件事实、法规、先例和论点等即时信息，真实再现无事后优势的决策环境。实验显示，GPT-3.5 Turbo在现实场景中表现卓越，且法律信息的纳入大幅提升预测质量。LLMs还提供预测解释，我们通过清晰度和链接两项人类评估指标衡量其质量。尽管LLMs有所进步，但在判决预测和解释上仍未达专家水平。

> This study investigates judgment prediction in a realistic scenario within the context of Indian judgments, utilizing a range of transformer-based models, including InLegalBERT, BERT, and XLNet, alongside LLMs such as Llama-2 and GPT-3.5 Turbo. In this realistic scenario, we simulate how judgments are predicted at the point when a case is presented for a decision in court, using only the information available at that time, such as the facts of the case, statutes, precedents, and arguments. This approach mimics real-world conditions, where decisions must be made without the benefit of hindsight, unlike retrospective analyses often found in previous studies. For transformer models, we experiment with hierarchical transformers and the summarization of judgment facts to optimize input for these models. Our experiments with LLMs reveal that GPT-3.5 Turbo excels in realistic scenarios, demonstrating robust performance in judgment prediction. Furthermore, incorporating additional legal information, such as statutes and precedents, significantly improves the outcome of the prediction task. The LLMs also provide explanations for their predictions. To evaluate the quality of these predictions and explanations, we introduce two human evaluation metrics: Clarity and Linking. Our findings from both automatic and human evaluations indicate that, despite advancements in LLMs, they are yet to achieve expert-level performance in judgment prediction and explanation tasks.

[Arxiv](https://arxiv.org/abs/2410.10542)