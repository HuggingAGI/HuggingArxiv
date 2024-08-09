# 3D场景中的任务导向顺序基础

发布时间：2024年08月07日

`Agent` `人工智能` `计算机视觉`

> Task-oriented Sequential Grounding in 3D Scenes

# 摘要

> 将自然语言融入物理3D环境是推动实体人工智能发展的关键。现有的3D视觉定位方法主要针对静态物体描述进行物体识别和定位，未能充分应对实际应用中所需的动态和顺序任务导向定位。为此，我们提出了一项新任务：3D场景中的任务导向顺序定位，要求代理根据详细步骤指令，在室内场景中依次定位目标物体以完成日常活动。为支持这一任务，我们创建了SG3D数据集，包含22,346个任务和112,236个步骤，覆盖4,895个真实3D场景。该数据集结合了多种3D场景的RGB-D扫描和自动化任务生成，并经过人工验证确保质量。我们调整了三种顶尖的3D视觉定位模型以适应顺序定位，并在SG3D上进行了性能评估。结果表明，尽管这些模型在传统测试中表现优异，但在任务导向的顺序定位上仍面临显著挑战，凸显了该领域进一步研究的重要性。

> Grounding natural language in physical 3D environments is essential for the advancement of embodied artificial intelligence. Current datasets and models for 3D visual grounding predominantly focus on identifying and localizing objects from static, object-centric descriptions. These approaches do not adequately address the dynamic and sequential nature of task-oriented grounding necessary for practical applications. In this work, we propose a new task: Task-oriented Sequential Grounding in 3D scenes, wherein an agent must follow detailed step-by-step instructions to complete daily activities by locating a sequence of target objects in indoor scenes. To facilitate this task, we introduce SG3D, a large-scale dataset containing 22,346 tasks with 112,236 steps across 4,895 real-world 3D scenes. The dataset is constructed using a combination of RGB-D scans from various 3D scene datasets and an automated task generation pipeline, followed by human verification for quality assurance. We adapted three state-of-the-art 3D visual grounding models to the sequential grounding task and evaluated their performance on SG3D. Our results reveal that while these models perform well on traditional benchmarks, they face significant challenges with task-oriented sequential grounding, underscoring the need for further research in this area.

[Arxiv](https://arxiv.org/abs/2408.04034)