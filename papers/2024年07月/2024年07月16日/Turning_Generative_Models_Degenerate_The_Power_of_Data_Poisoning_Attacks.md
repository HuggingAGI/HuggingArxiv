# 数据中毒攻击：揭秘其如何削弱生成模型的威力

发布时间：2024年07月16日

`LLM应用` `人工智能安全`

> Turning Generative Models Degenerate: The Power of Data Poisoning Attacks

# 摘要

> 随着第三方训练的大型语言模型的广泛应用，安全问题日益凸显。恶意分子可能通过中毒攻击植入后门，导致生成不良内容。尽管图像和分类任务中的此类攻击已被深入研究，但针对自然语言生成任务的研究仍显不足。为此，我们通过前缀调优这一高效微调方法，深入探讨了针对LLM微调阶段的中毒技术。我们不仅评估了这些技术在文本摘要和文本补全任务中的效果，还创新性地引入了衡量攻击成功与隐蔽性的新指标。实验表明，前缀调优的超参数和触发设计是决定攻击成败的关键。同时，我们发现现有防御措施对这些攻击束手无策。本研究首次全面分析了通过PEFT进行微调时，针对NLG任务的中毒攻击，期待能为AI安全领域提供有力支持，助力开发有效防御策略。

> The increasing use of large language models (LLMs) trained by third parties raises significant security concerns. In particular, malicious actors can introduce backdoors through poisoning attacks to generate undesirable outputs. While such attacks have been extensively studied in image domains and classification tasks, they remain underexplored for natural language generation (NLG) tasks. To address this gap, we conduct an investigation of various poisoning techniques targeting the LLM's fine-tuning phase via prefix-tuning, a Parameter Efficient Fine-Tuning (PEFT) method. We assess their effectiveness across two generative tasks: text summarization and text completion; and we also introduce new metrics to quantify the success and stealthiness of such NLG poisoning attacks. Through our experiments, we find that the prefix-tuning hyperparameters and trigger designs are the most crucial factors to influence attack success and stealthiness. Moreover, we demonstrate that existing popular defenses are ineffective against our poisoning attacks. Our study presents the first systematic approach to understanding poisoning attacks targeting NLG tasks during fine-tuning via PEFT across a wide range of triggers and attack settings. We hope our findings will aid the AI security community in developing effective defenses against such threats.

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/attack_system.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/trigger_insertion_v2.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_billsum_clean_rouge_1_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_billsum_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_billsum_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_virtual_tokens_billsum.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_xsum_clean_rouge_1_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_xsum_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_xsum_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_virtual_tokens_xsum.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_wikitext_clean_perplexity_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_wikitext_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_wikitext_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_virtual_tokens_wikitext.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_aeslc_clean_perplexity_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_aeslc_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_n_virtual_tokens_aeslc_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_virtual_tokens_aeslc.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_billsum_clean_rouge_1_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_billsum_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_billsum_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_wlr_billsum.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_xsum_clean_rouge_1_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_xsum_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_xsum_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_wlr_xsum.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_wikitext_clean_perplexity_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_wikitext_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_wikitext_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_wlr_wikitext.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_aeslc_clean_perplexity_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_aeslc_clean_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_wlr_comp_aeslc_poisoned_target_hit_model_last_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_wlr_aeslc.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_billsum_clean_rouge_1_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_billsum_clean_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_billsum_poisoned_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_trigger_comp_billsum.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_xsum_clean_rouge_1_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_xsum_clean_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_xsum_poisoned_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_trigger_comp_xsum.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_wikitext_clean_perplexity_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_wikitext_clean_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_wikitext_poisoned_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_trigger_comp_wikitext.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_aeslc_clean_perplexity_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_aeslc_clean_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_trigger_comp_aeslc_poisoned_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_trigger_comp_aeslc.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_billsum_clean_rouge_1_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_billsum_clean_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_billsum_poisoned_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_xsum_clean_rouge_1_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_xsum_clean_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_xsum_poisoned_target_hit_model_last_epochs_10_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_trigger_insertion.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_wikitext_clean_perplexity_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_wikitext_clean_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_wikitext_poisoned_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_aeslc_clean_perplexity_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_aeslc_clean_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/prefix_tuning_insertion_aeslc_poisoned_target_hit_model_last_epochs_20_3_runs.png)

![数据中毒攻击：揭秘其如何削弱生成模型的威力](../../../paper_images/2407.12281/legend_trigger_insertion.png)

[Arxiv](https://arxiv.org/abs/2407.12281)