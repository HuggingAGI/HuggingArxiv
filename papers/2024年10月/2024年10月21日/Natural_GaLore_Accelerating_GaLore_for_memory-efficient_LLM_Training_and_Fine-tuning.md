# 自然 GaLore：加速 GaLore，实现内存高效的大型语言模型训练与微调

发布时间：2024年10月21日

`LLM理论` `人工智能` `云计算`

> Natural GaLore: Accelerating GaLore for memory-efficient LLM Training and Fine-tuning

# 摘要

> 训练 LLM 面临巨大内存挑战，因数据、权重和优化器状态不断膨胀。尽管有数据和模型并行、梯度检查点等技术，但硬件限制使其难以实施。为此，PEFT 和 GaLore 等方法应运而生，前者如 LoRA 需全秩预热，后者则更高效。我们提出 Natural GaLore，作为 AdamW 的简易替代，利用 Woodbury 恒等式高效处理低秩梯度。实验表明，结合二阶信息显著加速优化，尤其在迭代预算有限时。预训练 Llama 模型显示，Natural GaLore 在困惑度上显著优于 GaLore，且无额外内存开销。微调 RoBERTa 和 TinyLlama 1.1B 模型进一步验证了其优势，不仅性能提升，内存使用也减少 30%。所有代码已公开，详见：https://github.com/selfsupervised-ai/Natural-GaLore.git

> Training LLMs presents significant memory challenges due to growing size of data, weights, and optimizer states. Techniques such as data and model parallelism, gradient checkpointing, and offloading strategies address this issue but are often infeasible due to hardware constraints. To mitigate memory usage, alternative methods like Parameter-Efficient-Fine-Tuning (PEFT) and GaLore approximate weights or optimizer states. PEFT methods, such as LoRA, have gained popularity for fine-tuning LLMs, though they require a full-rank warm start. In contrast, GaLore allows full-parameter learning while being more memory-efficient. This work introduces Natural GaLore, a simple drop in replacement for AdamW, which efficiently applies the inverse Empirical Fisher Information Matrix to low-rank gradients using Woodbury's Identity. We demonstrate that incorporating second-order information speeds up optimization significantly, especially when the iteration budget is limited. Empirical pretraining on 60M, 130M, 350M, and 1.1B parameter Llama models on C4 data demonstrate significantly lower perplexity over GaLore without additional memory overhead. By fine-tuning RoBERTa on the GLUE benchmark using Natural GaLore, we demonstrate significant reduction in gap 86.05% vs 86.28% for full-finetuning. Furthermore, fine-tuning the TinyLlama 1.1B model for function calling using the TinyAgent framework shows that Natural GaLore achieving 83.09% accuracy on the TinyAgent dataset, significantly outperforms 16-bit LoRA at 80.06% and even surpasses GPT4-Turbo by 4%, all while using 30% less memory.
  All code to reproduce the results are available at: https://github.com/selfsupervised-ai/Natural-GaLore.git

[Arxiv](https://arxiv.org/abs/2410.16029)