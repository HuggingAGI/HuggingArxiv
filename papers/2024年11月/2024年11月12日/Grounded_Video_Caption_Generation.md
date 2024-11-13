# 基于基础的视频字幕生成

发布时间：2024年11月12日

`LLM应用` `字幕生成`

> Grounded Video Caption Generation

# 摘要

> 我们为基于基础的视频字幕生成提出了一个新的任务、数据集和模型。这个任务将视频中的字幕和对象基础统一起来，其中字幕中的对象通过时间上一致的边界框在视频中得到基础。我们介绍了以下贡献。首先，我们为这个任务提出了一个任务定义和一个手动注释的测试数据集，称为基于基础的视频字幕生成（GROC）。其次，我们引入了一种大规模的自动注释方法，利用现有的基于基础的静态图像字幕模型和一个 LLM，将帧级字幕总结为视频中时间上一致的字幕。此外，我们提示 LLM 通过语言进行跟踪——将帧级字幕中的名词短语分类为视频级生成字幕中的名词短语。我们将这种方法应用于 HowTo100M 数据集中的视频，从而产生了一个新的大规模训练数据集，称为 HowToGround，具有自动注释的字幕和具有连贯自然语言标签的时空一致的边界框。第三，我们引入了一个新的基于基础的视频字幕生成模型，称为 VideoGround，并在新的自动注释的 HowToGround 数据集上训练该模型。最后，我们的 VideoGround 模型的结果为基于基础的视频字幕生成的新任务设定了最新技术水平。我们进行了广泛的消融实验，并展示了我们模型的关键技术贡献的重要性。

> We propose a new task, dataset and model for grounded video caption generation. This task unifies captioning and object grounding in video, where the objects in the caption are grounded in the video via temporally consistent bounding boxes. We introduce the following contributions. First, we present a task definition and a manually annotated test dataset for this task, referred to as GROunded Video Caption Generation (GROC). Second, we introduce a large-scale automatic annotation method leveraging an existing model for grounded still image captioning together with an LLM for summarising frame-level captions into temporally consistent captions in video. Furthermore, we prompt the LLM to track by language -- classifying noun phrases from the frame-level captions into noun phrases of the video-level generated caption. We apply this approach to videos from the HowTo100M dataset, which results in a new large-scale training dataset, called HowToGround, with automatically annotated captions and spatio-temporally consistent bounding boxes with coherent natural language labels. Third, we introduce a new grounded video caption generation model, called VideoGround, and train the model on the new automatically annotated HowToGround dataset. Finally, results of our VideoGround model set the state of the art for the new task of grounded video caption generation. We perform extensive ablations and demonstrate the importance of key technical contributions of our model.

[Arxiv](https://arxiv.org/abs/2411.07584)