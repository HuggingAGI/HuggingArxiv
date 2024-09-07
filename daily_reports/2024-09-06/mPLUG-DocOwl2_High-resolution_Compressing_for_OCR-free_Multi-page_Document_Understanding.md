# mPLUG-DocOwl2：无 OCR 多页文档理解的高分辨率压缩技术
发布时间：2024年09月05日

`多模态大模型`
> mPLUG-DocOwl2: High-resolution Compressing for OCR-free Multi-page Document Understanding
>
> 多模态大型语言模型 (MLLMs) 通过提升文档图像分辨率，实现了无 OCR 文档理解的新突破。然而，这导致单个文档图像生成数千个视觉标记，增加了 GPU 内存负担和推理时间，尤其在处理多页文档时。为此，我们设计了高分辨率 DocCompressor 模块，将高分辨率文档图像压缩至 324 个标记，并结合低分辨率全局视觉特征。通过这一模块，我们开发了 DocOwl2，采用三阶段训练框架：单图像预训练、多图像继续预训练和多任务微调，以增强多页文档理解能力，同时平衡标记效率和问答性能。DocOwl2 在多页文档理解基准测试中表现卓越，首次标记延迟减少 50% 以上，展现出多页问答、证据页解释和跨页结构理解的强大能力。与同类单图像 MLLMs 相比，DocOwl2 以不到 20% 的视觉标记实现了同等水平的单页理解性能。相关代码、模型和数据已公开，详见 https://github.com/X-PLUG/mPLUG-DocOwl/tree/main/DocOwl2。
>
> https://arxiv.org/abs/2409.03420

**点击公众号菜单加入大语言模型论文讨论**
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2409.03420](https://arxiv.org/abs/2409.03420)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)