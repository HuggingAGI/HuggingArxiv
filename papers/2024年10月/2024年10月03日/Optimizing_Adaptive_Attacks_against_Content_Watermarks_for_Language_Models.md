# 优化语言模型内容水印的自适应攻击

发布时间：2024年10月03日

`LLM应用` `网络安全` `人工智能`

> Optimizing Adaptive Attacks against Content Watermarks for Language Models

# 摘要

> 大型语言模型 (LLM) 可能被滥用，用于传播网络垃圾信息。内容水印技术通过在模型输出中隐藏信息，阻止这种滥用，并能用密钥检测这些隐藏信息。鲁棒性是核心安全特性，意味着逃避检测会导致内容质量显著下降。尽管已有多种 LLM 水印方法，但仅针对不了解水印技术的非自适应攻击者测试了鲁棒性。我们将 LLM 水印的鲁棒性定义为目标函数，并提出基于偏好的优化方法，以针对特定水印技术调整自适应攻击。评估结果显示：(i) 自适应攻击远超非自适应基线；(ii) 即使在非自适应环境下，针对少数已知水印优化的自适应攻击对其他未见水印依然有效；(iii) 基于优化的攻击实用且仅需不到七小时的 GPU 时间。这些发现强调了测试针对自适应攻击者鲁棒性的重要性。

> Large Language Models (LLMs) can be \emph{misused} to spread online spam and misinformation. Content watermarking deters misuse by hiding a message in model-generated outputs, enabling their detection using a secret watermarking key. Robustness is a core security property, stating that evading detection requires (significant) degradation of the content's quality. Many LLM watermarking methods have been proposed, but robustness is tested only against \emph{non-adaptive} attackers who lack knowledge of the watermarking method and can find only suboptimal attacks. We formulate the robustness of LLM watermarking as an objective function and propose preference-based optimization to tune \emph{adaptive} attacks against the specific watermarking method. Our evaluation shows that (i) adaptive attacks substantially outperform non-adaptive baselines. (ii) Even in a non-adaptive setting, adaptive attacks optimized against a few known watermarks remain highly effective when tested against other unseen watermarks, and (iii) optimization-based attacks are practical and require less than seven GPU hours. Our findings underscore the need to test robustness against adaptive attackers.

[Arxiv](https://arxiv.org/abs/2410.02440)