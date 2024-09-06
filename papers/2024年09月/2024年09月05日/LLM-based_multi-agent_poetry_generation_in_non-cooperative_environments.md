# 在非合作环境中，基于 LLM 的多代理诗歌生成

发布时间：2024年09月05日

`Agent` `人工智能`

> LLM-based multi-agent poetry generation in non-cooperative environments

# 摘要

> 尽管 LLM 在自动诗歌生成方面取得了显著进展，但生成的诗歌缺乏多样性，训练过程与人类学习大相径庭。我们提出了一种基于社会学习的框架，强调非合作互动以促进多样性。实验首次在非合作环境中使用 LLM 多代理系统生成诗歌，评估显示，基于训练的代理在多样性和新颖性上分别提升了 3.0-3.7 pp 和 5.6-11.3 pp。基于提示的代理在多样性上提升了 7.0-17.5 pp，但词汇多样性随时间下降，未表现出群体差异。我们主张在诗歌生成等创造性任务中引入类似人类互动的社会学习过程。

> Despite substantial progress of large language models (LLMs) for automatic poetry generation, the generated poetry lacks diversity while the training process differs greatly from human learning. Under the rationale that the learning process of the poetry generation systems should be more human-like and their output more diverse and novel, we introduce a framework based on social learning where we emphasize non-cooperative interactions besides cooperative interactions to encourage diversity. Our experiments are the first attempt at LLM-based multi-agent systems in non-cooperative environments for poetry generation employing both TRAINING-BASED agents (GPT-2) and PROMPTING-BASED agents (GPT-3 and GPT-4). Our evaluation based on 96k generated poems shows that our framework benefits the poetry generation process for TRAINING-BASED agents resulting in 1) a 3.0-3.7 percentage point (pp) increase in diversity and a 5.6-11.3 pp increase in novelty according to distinct and novel n-grams. The generated poetry from TRAINING-BASED agents also exhibits group divergence in terms of lexicons, styles and semantics. PROMPTING-BASED agents in our framework also benefit from non-cooperative environments and a more diverse ensemble of models with non-homogeneous agents has the potential to further enhance diversity, with an increase of 7.0-17.5 pp according to our experiments. However, PROMPTING-BASED agents show a decrease in lexical diversity over time and do not exhibit the group-based divergence intended in the social network. Our paper argues for a paradigm shift in creative tasks such as automatic poetry generation to include social learning processes (via LLM-based agent modeling) similar to human interaction.

[Arxiv](https://arxiv.org/abs/2409.03659)