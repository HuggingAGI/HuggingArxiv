# LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试

发布时间：2024年07月22日

`LLM应用` `视频处理`

> LongVideoBench: A Benchmark for Long-context Interleaved Video-Language Understanding

# 摘要

> 大型多模态模型 (LMMs) 正处理着越来越长且内容丰富的输入，但衡量这一进步的公开基准却寥寥无几。为此，我们推出了 LongVideoBench，一个长达一小时的视频-语言交错输入问答基准。该基准包含 3,763 个不同长度的网络视频及其字幕，覆盖多种主题，全面评估 LMMs 的长期多模态理解能力。我们定义了一个新任务——引用推理，模型需从引用视频上下文中提取细节进行推理。基于此，我们整理了 6,678 道人工标注的多项选择题，涵盖 17 个细分类别，构建了全面的长视频理解基准。评估显示，即便是最先进的专有模型也面临挑战，而开源模型差距更大。此外，模型性能提升的关键在于处理更多帧，LongVideoBench 因此成为评估未来长上下文 LMMs 的重要基准。

> Large multimodal models (LMMs) are processing increasingly longer and richer inputs. Albeit the progress, few public benchmark is available to measure such development. To mitigate this gap, we introduce LongVideoBench, a question-answering benchmark that features video-language interleaved inputs up to an hour long. Our benchmark includes 3,763 varying-length web-collected videos with their subtitles across diverse themes, designed to comprehensively evaluate LMMs on long-term multimodal understanding. To achieve this, we interpret the primary challenge as to accurately retrieve and reason over detailed multimodal information from long inputs. As such, we formulate a novel video question-answering task termed referring reasoning. Specifically, as part of the question, it contains a referring query that references related video contexts, called referred context. The model is then required to reason over relevant video details from the referred context. Following the paradigm of referring reasoning, we curate 6,678 human-annotated multiple-choice questions in 17 fine-grained categories, establishing one of the most comprehensive benchmarks for long-form video understanding. Evaluations suggest that the LongVideoBench presents significant challenges even for the most advanced proprietary models (e.g. GPT-4o, Gemini-1.5-Pro, GPT-4-Turbo), while their open-source counterparts show an even larger performance gap. In addition, our results indicate that model performance on the benchmark improves only when they are capable of processing more frames, positioning LongVideoBench as a valuable benchmark for evaluating future-generation long-context LMMs.

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/x1.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/x2.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/x3.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/x4.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/llava-next-m7.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/iblip.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/blip2.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/llava-1.5-13b.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/llava-1.5-7b.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/mplugowl2.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/llavavid34b.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/pllava34b.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/pllava13b.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/llava-next-video-m7.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/sharegpt4video.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/pllava7b.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/videochat2mistral.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/videollava.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/videochat2vicuna.png)

![LongVideoBench：一款专为长篇交错视频与语言理解设计的基准测试](../../../paper_images/2407.15754/lvb_interface_screenshot.png)

[Arxiv](https://arxiv.org/abs/2407.15754)