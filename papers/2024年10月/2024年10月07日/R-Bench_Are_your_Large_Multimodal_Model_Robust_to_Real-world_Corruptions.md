# R-Bench：你的大型多模态模型能否抵御现实世界的损坏？

发布时间：2024年10月07日

`LLM应用` `计算机视觉` `人工智能`

> R-Bench: Are your Large Multimodal Model Robust to Real-world Corruptions?

# 摘要

> 大型多模态模型（LMM）在视觉任务中的出色表现使其应用广泛。然而，现实世界中的图像损坏问题给 LMM 的实际应用带来了挑战。为此，我们推出了 R-Bench，一个专注于 LMM 现实世界鲁棒性的基准测试。我们模拟了从用户捕捉到 LMM 接收的完整链路，涵盖 33 个损坏维度，并收集了 2,970 个带有人工标注的问题-答案对。我们还对 20 个主流 LMM 进行了综合评估。结果表明，LMM 在处理失真图像时性能不稳定，与人类视觉系统相比，鲁棒性差距显著。我们希望通过 R-Bench 推动 LMM 从实验模拟走向现实应用。详情请访问 https://q-future.github.io/R-Bench。

> The outstanding performance of Large Multimodal Models (LMMs) has made them widely applied in vision-related tasks. However, various corruptions in the real world mean that images will not be as ideal as in simulations, presenting significant challenges for the practical application of LMMs. To address this issue, we introduce R-Bench, a benchmark focused on the **Real-world Robustness of LMMs**. Specifically, we: (a) model the complete link from user capture to LMMs reception, comprising 33 corruption dimensions, including 7 steps according to the corruption sequence, and 7 groups based on low-level attributes; (b) collect reference/distorted image dataset before/after corruption, including 2,970 question-answer pairs with human labeling; (c) propose comprehensive evaluation for absolute/relative robustness and benchmark 20 mainstream LMMs. Results show that while LMMs can correctly handle the original reference images, their performance is not stable when faced with distorted images, and there is a significant gap in robustness compared to the human visual system. We hope that R-Bench will inspire improving the robustness of LMMs, **extending them from experimental simulations to the real-world application**. Check https://q-future.github.io/R-Bench for details.

[Arxiv](https://arxiv.org/abs/2410.05474)