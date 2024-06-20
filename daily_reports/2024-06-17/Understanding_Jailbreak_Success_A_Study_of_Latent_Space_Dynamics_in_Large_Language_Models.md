# 探究大型语言模型中的潜在空间动态：越狱成功的奥秘
发布时间：2024年06月13日

`模型安全`
> Understanding Jailbreak Success: A Study of Latent Space Dynamics in Large Language Models
>
> 对话大型语言模型虽被训练以拒绝有害问题，但新兴的越狱技术仍能引发不安全输出，挑战着模型的安全对齐。本文通过分析模型在不同越狱输入下的反应，揭示了不同越狱类型如何规避安全措施。研究发现，一种越狱向量能从单一越狱类型中提取，有效削弱其他类型越狱的效果，暗示了不同越狱可能共享相似的内部机制。我们探讨了有害特征抑制这一潜在共同机制，并通过有害向量分析证实了其存在。这些发现不仅为强化越狱对策提供了洞见，也为深入探究语言模型中越狱机制奠定了基础。
>
> https://arxiv.org/abs/2406.09289

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/pca_layer_20_diff_none_jail_EOS_token_potent_middle.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/pca_layer_40_diff_none_jail_EOS_token_potent_middle.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/heatmap_similarity_layer_19_none_jail_subset_flow.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/pca_layer_20_harmful_harmless.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/cosine_comparison_19_None.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_none_19_figure_1_cropped_2.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/selected_evolution_directions_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/selected_evolution_directions_figure_2_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_none_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_AIM_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_dev_mode_v2_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_distractors_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_evil_confidant_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_refusal_suppression_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_style_injection_short_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_poems_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_few_shot_json_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_payload_split_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_prefix_injection_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_style_injection_json_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_wikipedia_with_title_19_figure_1_.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/evolution_directions_none_19_figure_1_with_helpfulness.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/selected_evolution_directions_figure_1_with_helpfulness.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09289/selected_evolution_directions_figure_2_with_helpfulness.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.09289](https://arxiv.org/abs/2406.09289)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2