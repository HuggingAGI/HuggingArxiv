# FlexEdit 结合自由形状遮罩与 VLLM，开创灵活图像编辑新境界。

发布时间：2024年08月22日

`LLM应用` `图像编辑` `人工智能`

> FlexEdit: Marrying Free-Shape Masks to VLLM for Flexible Image Editing

# 摘要

> 结合VLLMs与扩散模型，我们开发了一种强大的图像编辑方法，能够根据人类语言指令进行操作。尽管语言指令在传达用户需求时存在局限，尤其是在图像特定区域进行元素添加或替换时，遮罩技术却能有效指示编辑位置。然而，精确绘制遮罩形状对用户并不友好。为此，我们推出了FlexEdit，一种端到端图像编辑方法，结合自由形状遮罩与语言指令，实现灵活编辑。通过VLLM理解图像内容与用户指令，并引入遮罩增强适配器（MEA）融合VLLM嵌入与图像数据，确保遮罩信息与模型输出的无缝集成。我们还创建了FSMI-Edit基准，涵盖8种自由形状遮罩类型。实验证明，我们的方法在LLM图像编辑领域达到顶尖水平，简单提示技术尤为高效。相关代码与数据已公开于https://github.com/A-new-b/flex_edit。

> Combining Vision Large Language Models (VLLMs) with diffusion models offers a powerful method for executing image editing tasks based on human language instructions. However, language instructions alone often fall short in accurately conveying user requirements, particularly when users want to add, replace elements in specific areas of an image. Luckily, masks can effectively indicate the exact locations or elements to be edited, while they require users to precisely draw the shapes at the desired locations, which is highly user-unfriendly. To address this, we propose FlexEdit, an end-to-end image editing method that leverages both free-shape masks and language instructions for Flexible Editing. Our approach employs a VLLM in comprehending the image content, mask, and user instructions. Additionally, we introduce the Mask Enhance Adapter (MEA) that fuses the embeddings of the VLLM with the image data, ensuring a seamless integration of mask information and model output embeddings. Furthermore, we construct FSMI-Edit, a benchmark specifically tailored for free-shape mask, including 8 types of free-shape mask. Extensive experiments show that our method achieves state-of-the-art (SOTA) performance in LLM-based image editing, and our simple prompting technique stands out in its effectiveness. The code and data can be found at https://github.com/A-new-b/flex_edit.

[Arxiv](https://arxiv.org/abs/2408.12429)