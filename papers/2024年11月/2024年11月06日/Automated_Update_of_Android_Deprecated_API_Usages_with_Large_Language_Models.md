# 使用大型语言模型对 Android 已弃用 API 用法进行自动更新

发布时间：2024年11月06日

`LLM应用` `Android` `软件开发`

> Automated Update of Android Deprecated API Usages with Large Language Models

# 摘要

> Android 应用程序依赖应用程序编程接口（APIs）来访问 Android 设备的各种功能。然而，这些 APIs 会定期更新以纳入新功能，而旧的 APIs 则会被弃用。尽管用推荐的替代 APIs 更新已弃用 API 的使用的重要性已得到广泛认可，但更新已弃用的 API 用法并非易事。因此，已弃用 APIs 的使用在 Android 应用程序中仍然存在，并在实践中导致兼容性问题。本文介绍了 GUPPY，这是一种利用大型语言模型（LLMs）来更新 Android 已弃用 API 用法的自动化方法。通过使用精心设计的提示，GUPPY 利用 GPT-4（最强大的 LLMs 之一）来更新已弃用的 API 用法，确保在旧和新的 API 级别上的兼容性。此外，GUPPY 使用 GPT-4 生成测试、识别不正确的更新，并通过迭代过程改进 API 用法，直到测试通过或达到指定的限制。我们对来自 20 个已弃用 APIs 的 360 个基准 API 用法以及来自最新 API 级别 33 和 34 的另外 156 个已弃用 API 用法进行的评估表明，GUPPY 优于最先进的技术。

> Android apps rely on application programming interfaces (APIs) to access various functionalities of Android devices. These APIs however are regularly updated to incorporate new features while the old APIs get deprecated. Even though the importance of updating deprecated API usages with the recommended replacement APIs has been widely recognized, it is non-trivial to update the deprecated API usages. Therefore, the usages of deprecated APIs linger in Android apps and cause compatibility issues in practice. This paper introduces GUPPY, an automated approach that utilizes large language models (LLMs) to update Android deprecated API usages. By employing carefully crafted prompts, GUPPY leverages GPT-4, one of the most powerful LLMs, to update deprecated-API usages, ensuring compatibility in both the old and new API levels. Additionally, GUPPY uses GPT-4 to generate tests, identify incorrect updates, and refine the API usage through an iterative process until the tests pass or a specified limit is reached. Our evaluation, conducted on 360 benchmark API usages from 20 deprecated APIs and an additional 156 deprecated API usages from the latest API levels 33 and 34, demonstrates GUPPY's advantages over the state-of-the-art techniques.

[Arxiv](https://arxiv.org/abs/2411.04387)