# KITTEN：视觉实体图像生成的知识密集型评估

发布时间：2024年10月15日

`LLM应用` `计算机视觉` `图像生成`

> KITTEN: A Knowledge-Intensive Evaluation of Image Generation on Visual Entities

# 摘要

> 近期文本到图像生成技术的进步虽提升了合成图像质量，但评估多集中于美学或文本对齐，对模型能否准确呈现多样现实视觉实体的理解仍有限。为此，我们提出 KITTEN 基准，系统评估模型生成地标、飞机、植物等现实实体的能力。研究发现，最先进模型也常在视觉细节上失准。检索增强模型虽能通过参考图像提升保真度，但过度依赖导致创意生成受限。

> Recent advancements in text-to-image generation have significantly enhanced the quality of synthesized images. Despite this progress, evaluations predominantly focus on aesthetic appeal or alignment with text prompts. Consequently, there is limited understanding of whether these models can accurately represent a wide variety of realistic visual entities - a task requiring real-world knowledge. To address this gap, we propose a benchmark focused on evaluating Knowledge-InTensive image generaTion on real-world ENtities (i.e., KITTEN). Using KITTEN, we conduct a systematic study on the fidelity of entities in text-to-image generation models, focusing on their ability to generate a wide range of real-world visual entities, such as landmark buildings, aircraft, plants, and animals. We evaluate the latest text-to-image models and retrieval-augmented customization models using both automatic metrics and carefully-designed human evaluations, with an emphasis on the fidelity of entities in the generated images. Our findings reveal that even the most advanced text-to-image models often fail to generate entities with accurate visual details. Although retrieval-augmented models can enhance the fidelity of entity by incorporating reference images during testing, they often over-rely on these references and struggle to produce novel configurations of the entity as requested in creative text prompts.

[Arxiv](https://arxiv.org/abs/2410.11824)