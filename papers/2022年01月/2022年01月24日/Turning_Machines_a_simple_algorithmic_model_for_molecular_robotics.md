# 转机：一种用于分子机器人领域的简洁算法模型

发布时间：2022年01月24日

`分类：Agent` `分子机器人技术` `计算机科学`

> Turning Machines: a simple algorithmic model for molecular robotics

# 摘要

> 分子机器人技术充满挑战，简化处理显得更为明智。我们提出了一个基于简易折叠指令的分子机器人抽象模型，这些指令能够异步运作。转向机模型以其简洁性著称，它从一维线性结构向二维形态转变，且易于扩展至三维。该模型以离散平面上的单体链起始，每个单体都配有特定的转向编号。单体相对于相邻单体进行旋转，带动其他单体同步移动，通过协同作用，原始的单体链最终折叠成预定的形态。我们开发了一系列工具，全面分析了转向机执行线旋转的能力：实现接近完整的 $5π/3$ 弧度旋转是可行的，但完整的 $2π$ 旋转则不可行。更重要的是，这些线旋转操作在连续时间马尔可夫链模型中，以 $O(\log n)$ 的期望时间高效完成。进一步地，我们证明了这些线旋转是模型中的基础操作，利用它们可以高效、异步地折叠出各种形状。例如，任意大小的之字形栅格正方形和之字形路径均可实现折叠，而 $y$-单调形状虽有误差（受限于周长）也能完成折叠。最后，我们展示了一些尽管路径遍历所有点但实际无法折叠的形状，并提供了一些无误差折叠特定类别（缩放版）形状的技术。本研究的方法论基于对极简机器人系统可能与不可能完成的任务进行精细的几何分析，将概念上的复杂性转化为数学分析，而非分子层面的实现。

> Molecular robotics is challenging, so it seems best to keep it simple. We consider an abstract molecular robotics model based on simple folding instructions that execute asynchronously. Turning Machines are a simple 1D to 2D folding model, also easily generalisable to 2D to 3D folding. A Turning Machine starts out as a line of connected monomers in the discrete plane, each with an associated turning number. A monomer turns relative to its neighbours, executing a unit-distance translation that drags other monomers along with it, and through collective motion the initial set of monomers eventually folds into a programmed shape. We provide a suite of tools for reasoning about Turning Machines by fully characterising their ability to execute line rotations: executing an almost-full line rotation of $5π/3$ radians is possible, yet a full $2π$ rotation is impossible. Furthermore, line rotations up to $5π/3$ are executed efficiently, in $O(\log n)$ expected time in our continuous time Markov chain time model. We then show that such line-rotations represent a fundamental primitive in the model, by using them to efficiently and asynchronously fold shapes. In particular, arbitrarily large zig-zag-rastered squares and zig-zag paths are foldable, as are $y$-monotone shapes albeit with error (bounded by perimeter length). Finally, we give shapes that despite having paths that traverse all their points, are in fact impossible to fold, as well as techniques for folding certain classes of (scaled) shapes without error. Our approach relies on careful geometric-based analyses of the feats possible and impossible by a very simple robotic system, and pushes conceptional hardness towards mathematical analysis and away from molecular implementation.

[Arxiv](https://arxiv.org/abs/2009.00755)