# SGNet 是一个运用深度学习技术来高效折叠对称蛋白质复合体的方法。

发布时间：2024年03月07日

`Agent`

> SGNet: Folding Symmetrical Protein Complex with Deep Learning

# 摘要

> 深度学习技术极大地推进了蛋白质结构预测领域，助力了计算生物学的发展。然而，在单链结构预测取得高准确率的同时，面对那些拥有内部对称性的大型同源寡聚体组装体，其结构解析仍是一大难题。当前深度学习方法受限于对称性蛋白质组装体通常过长的序列，使得结构计算难以进行；同时，对称蛋白质复合物中多个相同的亚基导致标签分配时监督信息模糊不清，要求模型在训练过程中保持一致性结构模拟。为此，我们创新提出了一个名为SGNet的蛋白质折叠框架，专门针对对称组装体中的蛋白质间相互作用进行建模。SGNet通过在单一亚基上提取特征，并结合我们独创的对称模块来生成整个组装体结构，从而有效地减轻了因序列过长带来的计算难题。得益于对对称性巧妙而一致的设计，SGNet能成功应用于各种全局对称类型的四级蛋白质结构预测任务。大量的实验证据表明，我们的方法在对称蛋白质复合物基准测试集上表现优异，充分验证了其实效性。

> Deep learning has made significant progress in protein structure prediction, advancing the development of computational biology. However, despite the high accuracy achieved in predicting single-chain structures, a significant number of large homo-oligomeric assemblies exhibit internal symmetry, posing a major challenge in structure determination. The performances of existing deep learning methods are limited since the symmetrical protein assembly usually has a long sequence, making structural computation infeasible. In addition, multiple identical subunits in symmetrical protein complex cause the issue of supervision ambiguity in label assignment, requiring a consistent structure modeling for the training. To tackle these problems, we propose a protein folding framework called SGNet to model protein-protein interactions in symmetrical assemblies. SGNet conducts feature extraction on a single subunit and generates the whole assembly using our proposed symmetry module, which largely mitigates computational problems caused by sequence length. Thanks to the elaborate design of modeling symmetry consistently, we can model all global symmetry types in quaternary protein structure prediction. Extensive experimental results on a benchmark of symmetrical protein complexes further demonstrate the effectiveness of our method.

[Arxiv](https://arxiv.org/abs/2403.04395)