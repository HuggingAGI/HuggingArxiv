# DrugGen：借助大型语言模型和强化学习反馈促进药物发现

发布时间：2024年11月19日

`其他` `药物研发`

> DrugGen: Advancing Drug Discovery with Large Language Models and Reinforcement Learning Feedback

# 摘要

> 传统药物设计因内在的化学和生物复杂性面临严峻挑战，致使临床试验失败率颇高。深度学习的发展，尤其是生成模型，为这些难题带来了潜在的解决办法。其中颇具前景的算法DrugGPT，这是一个基于转换器的模型，能为输入的蛋白质序列生成小分子。不过，它虽有潜力，却既会生成化学有效的结构，也会生成无效结构，且未融入已获批药物的特征，致使药物研发既耗时又低效。为应对这些问题，我们推出了DrugGen，这是基于DrugGPT结构的强化模型。DrugGen在已获批的药物-靶点相互作用方面进行了微调，并运用近端策略优化加以优化。借由使用预训练的转换器（PLAPT）和定制的无效结构评估器从蛋白质-配体结合亲和力预测中获取奖励反馈，DrugGen的性能大幅提升。针对多个靶点的评估显示，相较于DrugGPT的95.5%，DrugGen实现了100%的有效结构生成，所生成分子的预测结合亲和力更高（7.22 [6.30 - 8.07]），而DrugGPT为（5.81 [4.97 - 6.63]），同时还保持了多样性和新颖性。对接模拟进一步证实了其有效生成针对结合位点分子的能力。比如在脂肪酸结合蛋白5（FABP5）的案例中，DrugGen生成的分子对接得分更优（FABP5/11，-9.537和FABP5/5，-8.399），相比参照分子（棕榈酸，-6.177）。除了生成先导化合物，DrugGen在药物重新定位以及为现有靶点创建新药效团方面也展现出潜力。通过产出高质量的小分子，DrugGen为推进药物研究和药物发现提供了高性能的手段。

> Traditional drug design faces significant challenges due to inherent chemical and biological complexities, often resulting in high failure rates in clinical trials. Deep learning advancements, particularly generative models, offer potential solutions to these challenges. One promising algorithm is DrugGPT, a transformer-based model, that generates small molecules for input protein sequences. Although promising, it generates both chemically valid and invalid structures and does not incorporate the features of approved drugs, resulting in time-consuming and inefficient drug discovery. To address these issues, we introduce DrugGen, an enhanced model based on the DrugGPT structure. DrugGen is fine-tuned on approved drug-target interactions and optimized with proximal policy optimization. By giving reward feedback from protein-ligand binding affinity prediction using pre-trained transformers (PLAPT) and a customized invalid structure assessor, DrugGen significantly improves performance. Evaluation across multiple targets demonstrated that DrugGen achieves 100% valid structure generation compared to 95.5% with DrugGPT and produced molecules with higher predicted binding affinities (7.22 [6.30-8.07]) compared to DrugGPT (5.81 [4.97-6.63]) while maintaining diversity and novelty. Docking simulations further validate its ability to generate molecules targeting binding sites effectively. For example, in the case of fatty acid-binding protein 5 (FABP5), DrugGen generated molecules with superior docking scores (FABP5/11, -9.537 and FABP5/5, -8.399) compared to the reference molecule (Palmitic acid, -6.177). Beyond lead compound generation, DrugGen also shows potential for drug repositioning and creating novel pharmacophores for existing targets. By producing high-quality small molecules, DrugGen provides a high-performance medium for advancing pharmaceutical research and drug discovery.

[Arxiv](https://arxiv.org/abs/2411.14157)