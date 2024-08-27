# GR-MG 策略：巧妙利用部分标注数据，实现多模态目标条件下的高效学习

发布时间：2024年08月26日

`Agent` `机器人` `人工智能`

> GR-MG: Leveraging Partially Annotated Data via Multi-Modal Goal Conditioned Policy

# 摘要

> 机器人社区一直追求通过灵活的自然语言指令实现机器人的泛化操作。然而，获取全面标注的机器人数据既耗时又费力。相比之下，部分标注的数据（如无动作标签的视频和无语言标签的玩耍数据）更易收集。我们能否利用这些数据提升机器人的泛化能力？本文提出GR-MG方法，该方法支持以语言指令和目标图像为条件，有效利用部分标注数据，同时保持语言的灵活性。通过引入进度引导的目标图像生成模型，我们显著提升了图像的准确性和性能。实验结果显示，GR-MG在模拟和真实环境中均大幅提升了任务完成率和成功率。详细信息和资源将在项目页面提供。

> The robotics community has consistently aimed to achieve generalizable robot manipulation with flexible natural language instructions. One of the primary challenges is that obtaining robot data fully annotated with both actions and texts is time-consuming and labor-intensive. However, partially annotated data, such as human activity videos without action labels and robot play data without language labels, is much easier to collect. Can we leverage these data to enhance the generalization capability of robots? In this paper, we propose GR-MG, a novel method which supports conditioning on both a language instruction and a goal image. During training, GR-MG samples goal images from trajectories and conditions on both the text and the goal image or solely on the image when text is unavailable. During inference, where only the text is provided, GR-MG generates the goal image via a diffusion-based image-editing model and condition on both the text and the generated image. This approach enables GR-MG to leverage large amounts of partially annotated data while still using language to flexibly specify tasks. To generate accurate goal images, we propose a novel progress-guided goal image generation model which injects task progress information into the generation process, significantly improving the fidelity and the performance. In simulation experiments, GR-MG improves the average number of tasks completed in a row of 5 from 3.35 to 4.04. In real-robot experiments, GR-MG is able to perform 47 different tasks and improves the success rate from 62.5% to 75.0% and 42.4% to 57.6% in simple and generalization settings, respectively. Code and checkpoints will be available at the project page: https://gr-mg.github.io/.

[Arxiv](https://arxiv.org/abs/2408.14368)