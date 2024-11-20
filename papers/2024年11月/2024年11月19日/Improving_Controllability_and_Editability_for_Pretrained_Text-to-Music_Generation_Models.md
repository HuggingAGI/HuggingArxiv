# 提升预训练文本到音乐生成模型的可控程度与可编辑能力

发布时间：2024年11月19日

`LLM应用` `AI 创作`

> Improving Controllability and Editability for Pretrained Text-to-Music Generation Models

# 摘要

> 在 AI 辅助音乐创作领域，已取得显著进步，然而现存系统常常难以满足迭代及精细化音乐制作的需求。其中的挑战包括对生成内容提供充分的掌控，以及实现灵活、精准的编辑。本论文通过引入一系列层层递进的改进措施来应对这些问题，提升了文本到音乐生成模型的可控性与可编辑性。
  首先，我们推出了 Loop Copilot 系统，旨在满足音乐创作中的迭代优化需求。Loop Copilot 借助大型语言模型（LLM）来协同多个专门的 AI 模型，使用户能够通过对话界面交互式地生成和优化音乐。该系统的核心在于全局属性表，它在整个迭代流程中记录并维护关键音乐属性，保证在任何阶段的修改都能维持音乐的整体连贯性。尽管 Loop Copilot 在协调音乐创作过程时表现出色，却未直接解决对生成内容进行细致编辑的需求。
  为突破这一局限，MusicMagus 作为进一步编辑 AI 生成音乐的解决方案被提出。MusicMagus 引入了一种零样本的文本到音乐编辑方式，能够修改特定的音乐属性，例如流派、情绪和乐器配置，且无需重新训练。通过操控预训练扩散模型中的潜在空间，MusicMagus 确保这些编辑在风格上保持连贯，且非目标属性不变。此系统在编辑过程中维持音乐的结构完整性方面效果显著，但在应对更复杂和真实的音频场景时会遭遇挑战。
 ...

> The field of AI-assisted music creation has made significant strides, yet existing systems often struggle to meet the demands of iterative and nuanced music production. These challenges include providing sufficient control over the generated content and allowing for flexible, precise edits. This thesis tackles these issues by introducing a series of advancements that progressively build upon each other, enhancing the controllability and editability of text-to-music generation models.
  First, we introduce Loop Copilot, a system that tries to address the need for iterative refinement in music creation. Loop Copilot leverages a large language model (LLM) to coordinate multiple specialised AI models, enabling users to generate and refine music interactively through a conversational interface. Central to this system is the Global Attribute Table, which records and maintains key musical attributes throughout the iterative process, ensuring that modifications at any stage preserve the overall coherence of the music. While Loop Copilot excels in orchestrating the music creation process, it does not directly address the need for detailed edits to the generated content.
  To overcome this limitation, MusicMagus is presented as a further solution for editing AI-generated music. MusicMagus introduces a zero-shot text-to-music editing approach that allows for the modification of specific musical attributes, such as genre, mood, and instrumentation, without the need for retraining. By manipulating the latent space within pre-trained diffusion models, MusicMagus ensures that these edits are stylistically coherent and that non-targeted attributes remain unchanged. This system is particularly effective in maintaining the structural integrity of the music during edits, but it encounters challenges with more complex and real-world audio scenarios.
  ...

[Arxiv](https://arxiv.org/abs/2411.12641)