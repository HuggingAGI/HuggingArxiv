# NatureLM-audio：用于生物声学的音频语言基础模型

发布时间：2024年11月11日

`LLM应用` `生物声学` `音频处理`

> NatureLM-audio: an Audio-Language Foundation Model for Bioacoustics

# 摘要

> 大型语言模型（LLMs）在文本和音频的提示下，代表了包括语音、音乐和一般音频在内的各种听觉任务的最新技术水平，在未见过的任务中显示出新兴能力。然而，这些能力在生物声学任务中尚未得到充分展示，例如在大型录音中检测动物发声、对稀有和濒危物种进行分类以及标注背景和行为——这些任务对于保护、生物多样性监测和动物行为研究至关重要。在这项工作中，我们提出了 NatureLM-audio，这是第一个专门为生物声学设计的音频语言基础模型。我们精心策划的训练数据集包括涵盖各种生物声学、语音和音乐数据的文本-音频对，旨在解决该领域有限的标注数据集带来的挑战。我们展示了从音乐和语音到生物声学的学习表示的成功转移，并且我们的模型对未见过的分类群和任务显示出有希望的泛化能力。重要的是，我们在一个新的基准（BEANS-Zero）上测试了 NatureLM-audio，它在包括未见过物种的零样本分类在内的几个生物声学任务上设定了新的技术水平（SotA）。为了推进生物声学研究，我们还开源了用于生成训练和基准数据以及训练模型的代码。

> Large language models (LLMs) prompted with text and audio represent the state of the art in various auditory tasks, including speech, music, and general audio, showing emergent abilities on unseen tasks. However, these capabilities have yet to be fully demonstrated in bioacoustics tasks, such as detecting animal vocalizations in large recordings, classifying rare and endangered species, and labeling context and behavior - tasks that are crucial for conservation, biodiversity monitoring, and the study of animal behavior. In this work, we present NatureLM-audio, the first audio-language foundation model specifically designed for bioacoustics. Our carefully curated training dataset comprises text-audio pairs spanning a diverse range of bioacoustics, speech, and music data, designed to address the challenges posed by limited annotated datasets in the field. We demonstrate successful transfer of learned representations from music and speech to bioacoustics, and our model shows promising generalization to unseen taxa and tasks. Importantly, we test NatureLM-audio on a novel benchmark (BEANS-Zero) and it sets the new state of the art (SotA) on several bioacoustics tasks, including zero-shot classification of unseen species. To advance bioacoustics research, we also open-source the code for generating training and benchmark data, as well as for training the model.

[Arxiv](https://arxiv.org/abs/2411.07186)