# 面向移动设备图形界面文本输入的大型语言模型：实证分析

发布时间：2024年04月13日

`LLM应用` `移动应用` `GUI测试`

> Large Language Models for Mobile GUI Text Input Generation: An Empirical Study

# 摘要

> 移动应用已成为我们日常不可或缺的存在，确保它们的质量至关重要。GUI测试作为质量保障的一环，对移动应用尤为重要。在GUI测试中，为文本输入组件生成有效的文本至关重要，有些界面甚至需要文本输入才能顺利翻页，这对于全面探索用户界面构成了挑战。近期，大型语言模型（LLM）在文本生成方面展现出了卓越的能力，尤其是OpenAI的GPT系列备受瞩目。但由于安全和隐私的考量，这些模型并不适用于真实移动应用的GUI测试。因此，研究不同LLM在移动GUI测试中指导文本输入生成的能力显得尤为必要。本文通过一项大规模实证研究，深入探讨了九种顶尖LLM在Android界面文本输入生成方面的成效。我们从62个开源Android应用中筛选出114个界面，并从中提取信息构建提示，以便LLM生成文本输入。实验结果显示，部分LLM能够生成更有效、更优质的文本输入，页面通过率达到了50.58%至66.67%，甚至发现了一些开源应用中的真实漏洞。与GPT-3.5和GPT-4相比，其他LLM的页面通过率降低了17.97%至84.79%以及21.93%至85.53%。我们还发现，利用更完整的界面上下文信息能显著提升LLM生成文本输入的成功率。此外，本文还总结了六点关于使用LLM进行Android测试的深刻见解，这些见解将为Android测试领域带来积极影响。

> Mobile applications (apps) have become an essential part of our daily lives, making ensuring their quality an important activity. GUI testing, a quality assurance method, has frequently been used for mobile apps. When conducting GUI testing, it is important to generate effective text inputs for the text-input components. Some GUIs require these text inputs to move from one page to the next, which remains a challenge to achieving complete UI exploration. Recently, Large Language Models (LLMs) have shown excellent text-generation capabilities. Among the LLMs, OpenAI's GPT series has been widely discussed and used. However, it may not be possible to use these LLMs for GUI testing actual mobile apps, due to the security and privacy issues related to the production data. Therefore, it is necessary to explore the potential of different LLMs to guide text-input generation in mobile GUI testing. This paper reports on a large-scale empirical study that extensively investigates the effectiveness of nine state-of-the-art LLMs in Android text-input generation for UI pages. We collected 114 UI pages from 62 open-source Android apps and extracted contextual information from the UI pages to construct prompts for LLMs to generate text inputs. The experimental results show that some LLMs can generate relatively more effective and higher-quality text inputs, achieving a 50.58% to 66.67% page-pass-through rate, and even detecting some real bugs in open-source apps. Compared with the GPT-3.5 and GPT-4 LLMs, other LLMs reduce the page-pass-through rates by 17.97% to 84.79% and 21.93% to 85.53%, respectively. We also found that using more complete UI contextual information can increase the page-pass-through rates of LLMs for generating text inputs. In addition, we also describe six insights gained regarding the use of LLMs for Android testing: These insights will benefit the Android testing community.

[Arxiv](https://arxiv.org/abs/2404.08948)