# 噪声扩散以增强文本到图像合成中的语义忠实程度

发布时间：2024年11月25日

`LLM应用` `图像生成` `计算机视觉`

> Noise Diffusion for Enhancing Semantic Faithfulness in Text-to-Image Synthesis

# 摘要

> 扩散模型在生成逼真图像方面成就斐然，但在实现与输入提示的精准语义对齐上仍面临挑战。优化初始的噪声潜在表示，是改进语义对齐的一种比修改模型架构或提示工程更高效的选择。最新的 InitNo 方法借助注意力图来优化初始噪声潜在表示；然而，这些图所捕捉的信息有限，而且 InitNo 的效果高度依赖初始起点，因其往往会在该点附近收敛至局部最优。为此，本文提议借助大型视觉语言模型（LVLMs）的语言理解能力来引导初始噪声潜在表示的优化，并引入噪声扩散过程，该过程在保持分布一致性的同时更新噪声潜在表示，以生成语义忠实的图像。此外，我们还对更新能提高语义忠实度的条件进行了理论分析。实验结果表明，我们的框架有效且适应性强，能在各类扩散模型中持续增强语义对齐。代码可在 https://github.com/Bomingmiao/NoiseDiffusion 获取。

> Diffusion models have achieved impressive success in generating photorealistic images, but challenges remain in ensuring precise semantic alignment with input prompts. Optimizing the initial noisy latent offers a more efficient alternative to modifying model architectures or prompt engineering for improving semantic alignment. A latest approach, InitNo, refines the initial noisy latent by leveraging attention maps; however, these maps capture only limited information, and the effectiveness of InitNo is highly dependent on the initial starting point, as it tends to converge on a local optimum near this point. To this end, this paper proposes leveraging the language comprehension capabilities of large vision-language models (LVLMs) to guide the optimization of the initial noisy latent, and introduces the Noise Diffusion process, which updates the noisy latent to generate semantically faithful images while preserving distribution consistency. Furthermore, we provide a theoretical analysis of the condition under which the update improves semantic faithfulness. Experimental results demonstrate the effectiveness and adaptability of our framework, consistently enhancing semantic alignment across various diffusion models. The code is available at https://github.com/Bomingmiao/NoiseDiffusion.

[Arxiv](https://arxiv.org/abs/2411.16503)