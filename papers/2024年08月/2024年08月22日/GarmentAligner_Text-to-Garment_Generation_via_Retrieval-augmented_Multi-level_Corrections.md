# GarmentAligner：借助检索增强的多级校正技术，实现从文本到服装的精准生成。

发布时间：2024年08月22日

`LLM应用`

> GarmentAligner: Text-to-Garment Generation via Retrieval-augmented Multi-level Corrections

# 摘要

> 通用文本到图像模型在艺术、设计和媒体领域掀起了创新浪潮。但在服装生成领域，即便是顶尖的模型也难以避免细粒度语义错位，尤其是服装部件的数量、位置及相互关系。为此，我们研发了GarmentAligner，一款结合检索增强与多级修正的文本到服装扩散模型。通过自动部件提取流程，我们精准捕捉服装部件的空间与数量信息，进而通过检索增强与对比学习深化模型对部件关系的理解。多级修正损失的引入，更确保了部件在语义、空间和数量上的精准对齐。实验证明，GarmentAligner在细粒度语义对齐上超越了同类产品，展现了卓越的保真度。

> General text-to-image models bring revolutionary innovation to the fields of arts, design, and media. However, when applied to garment generation, even the state-of-the-art text-to-image models suffer from fine-grained semantic misalignment, particularly concerning the quantity, position, and interrelations of garment components. Addressing this, we propose GarmentAligner, a text-to-garment diffusion model trained with retrieval-augmented multi-level corrections. To achieve semantic alignment at the component level, we introduce an automatic component extraction pipeline to obtain spatial and quantitative information of garment components from corresponding images and captions. Subsequently, to exploit component relationships within the garment images, we construct retrieval subsets for each garment by retrieval augmentation based on component-level similarity ranking and conduct contrastive learning to enhance the model perception of components from positive and negative samples. To further enhance the alignment of components across semantic, spatial, and quantitative granularities, we propose the utilization of multi-level correction losses that leverage detailed component information. The experimental findings demonstrate that GarmentAligner achieves superior fidelity and fine-grained semantic alignment when compared to existing competitors.

[Arxiv](https://arxiv.org/abs/2408.12352)