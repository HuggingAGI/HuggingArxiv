# Anywhere：一种多智能体框架，旨在实现可靠且多样化的前景条件图像修复

发布时间：2024年04月29日

`Agent` `图像处理` `人工智能`

> Anywhere: A Multi-Agent Framework for Reliable and Diverse Foreground-Conditioned Image Inpainting

# 摘要

> 图像修复技术的最新进展，尤其是扩散模型的应用，已经带来了令人鼓舞的成果。但在基于前景对象完成图像的场景下，现有端到端图像修复方法面临诸多挑战，如过度想象、前景背景不一致和多样性不足。为此，我们推出了Anywhere，这是一个创新的多代理框架，专门设计来应对这些挑战。Anywhere采用了一个包含视觉语言模型（VLM）、大型语言模型（LLM）和图像生成模型的复杂流水线框架。该框架包括三个核心组件：提示生成模块、图像生成模块和结果分析器。提示生成模块通过VLM进行语义分析，预测相关语言描述，并利用LLM推荐最佳语言提示。图像生成模块使用文本引导的canny到图像生成模型，基于前景图像的边缘图和语言提示创建模板图像，并通过图像细化器融合输入前景和模板图像生成最终结果。结果分析器利用VLM评估图像内容的合理性、审美评分和前景背景的相关性，并在必要时触发提示和图像的重新生成。大量实验证明，Anywhere框架在前景条件图像修复任务上表现卓越，有效减少了过度想象，解决了前景背景不一致的问题，并提升了结果的多样性。它成功地推动了前景条件图像修复技术的发展，产生了更可靠和多样化的图像修复结果。

> Recent advancements in image inpainting, particularly through diffusion modeling, have yielded promising outcomes. However, when tested in scenarios involving the completion of images based on the foreground objects, current methods that aim to inpaint an image in an end-to-end manner encounter challenges such as "over-imagination", inconsistency between foreground and background, and limited diversity. In response, we introduce Anywhere, a pioneering multi-agent framework designed to address these issues. Anywhere utilizes a sophisticated pipeline framework comprising various agents such as Visual Language Model (VLM), Large Language Model (LLM), and image generation models. This framework consists of three principal components: the prompt generation module, the image generation module, and the outcome analyzer. The prompt generation module conducts a semantic analysis of the input foreground image, leveraging VLM to predict relevant language descriptions and LLM to recommend optimal language prompts. In the image generation module, we employ a text-guided canny-to-image generation model to create a template image based on the edge map of the foreground image and language prompts, and an image refiner to produce the outcome by blending the input foreground and the template image. The outcome analyzer employs VLM to evaluate image content rationality, aesthetic score, and foreground-background relevance, triggering prompt and image regeneration as needed. Extensive experiments demonstrate that our Anywhere framework excels in foreground-conditioned image inpainting, mitigating "over-imagination", resolving foreground-background discrepancies, and enhancing diversity. It successfully elevates foreground-conditioned image inpainting to produce more reliable and diverse results.

[Arxiv](https://arxiv.org/abs/2404.18598)