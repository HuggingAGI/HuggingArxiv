# 深度生成模型借助视觉与语言的结合，揭开了医学图像中的奥秘。

发布时间：2024年10月17日

`LLM应用` `医学影像`

> Deep Generative Models Unveil Patterns in Medical Images Through Vision-Language Conditioning

# 摘要

> 深度生成模型不仅提升了医学影像数据集的质量和规模，还揭示了图像中的潜在模式。我们通过结合临床数据和分割掩码，创新地指导图像合成，并将临床数据转化为文本描述，简化了数据处理并利用了大型预训练模型。由于临床信息与图像的视觉关联较弱，我们引入了文本-视觉嵌入机制，确保信息有效利用。实验结果显示，肺部强度变化与临床观察一致，证明了我们方法的有效性。这为深度生成模型在早期检测和复杂临床条件可视化方面开辟了新路径。代码详见https://github.com/junzhin/DGM-VLC。

> Deep generative models have significantly advanced medical imaging analysis by enhancing dataset size and quality. Beyond mere data augmentation, our research in this paper highlights an additional, significant capacity of deep generative models: their ability to reveal and demonstrate patterns in medical images. We employ a generative structure with hybrid conditions, combining clinical data and segmentation masks to guide the image synthesis process. Furthermore, we innovatively transformed the tabular clinical data into textual descriptions. This approach simplifies the handling of missing values and also enables us to leverage large pre-trained vision-language models that investigate the relations between independent clinical entries and comprehend general terms, such as gender and smoking status. Our approach differs from and presents a more challenging task than traditional medical report-guided synthesis due to the less visual correlation of our clinical information with the images. To overcome this, we introduce a text-visual embedding mechanism that strengthens the conditions, ensuring the network effectively utilizes the provided information. Our pipeline is generalizable to both GAN-based and diffusion models. Experiments on chest CT, particularly focusing on the smoking status, demonstrated a consistent intensity shift in the lungs which is in agreement with clinical observations, indicating the effectiveness of our method in capturing and visualizing the impact of specific attributes on medical image patterns. Our methods offer a new avenue for the early detection and precise visualization of complex clinical conditions with deep generative models. All codes are https://github.com/junzhin/DGM-VLC.

[Arxiv](https://arxiv.org/abs/2410.13823)