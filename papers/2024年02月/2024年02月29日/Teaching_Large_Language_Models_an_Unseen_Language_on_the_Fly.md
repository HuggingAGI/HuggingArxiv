# [实时教授大型语言模型掌握新语言](https://arxiv.org/abs/2402.19167)

发布时间：2024年02月29日

`LLM应用`

> Teaching Large Language Models an Unseen Language on the Fly

> 面对大量低资源乃至极低资源语言（尤其是训练数据极其有限）的支持难题，现有大型语言模型显得力不从心。为此，我们研究LLMs能否通过提示即刻习得新语言。为深入探讨此问题，我们精心构建了一套专门针对当前尚未被任何LLM支持的壮语的研究集，并创新提出了\textsc{DiPMT++}框架，利用上下文学习技术令LLMs适应未曾遇见的语言。仅使用一本词典和5千句平行语料，\textsc{DiPMT++}就显著提高了GPT-4对中壮互译任务的表现，使得中译壮的BLEU得分从零跃升至16分，而壮译中的成绩更是高达32分。不仅如此，我们进一步证实了这一框架在实际应用中能够帮助人们翻译完全陌生的语言，从而有力地推动了语言多样性的保护工作。

> Existing large language models struggle to support numerous low-resource languages, particularly the extremely low-resource ones where there is minimal training data available for effective parameter updating. We thus investigate whether LLMs can learn a new language on the fly solely through prompting. To study this question, we collect a research suite for Zhuang, a language supported by no LLMs currently. We introduce \textsc{DiPMT++}, a framework for adapting LLMs to unseen languages by in-context learning. Using a dictionary and only 5K parallel sentences, \textsc{DiPMT++} significantly enhances the performance of GPT-4 from 0 to 16 BLEU for Chinese-to-Zhuang translation and achieves 32 BLEU for Zhuang-to-Chinese translation. Furthermore, we demonstrate the practical utility of this framework in aiding humans to translate completely unseen languages, which could contribute to the preservation of linguistic diversity.

[Arxiv](https://arxiv.org/abs/2402.19167)