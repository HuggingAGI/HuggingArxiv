# GuardAgent：利用知识驱动推理，守护大型语言模型代理的安全卫士
发布时间：2024年06月13日

`Agent应用`
> GuardAgent: Safeguard LLM Agents by a Guard Agent via Knowledge-Enabled Reasoning
>
> 随着大型语言模型（LLMs）技术的飞速进步，LLM驱动的代理在多个领域广泛应用，同时也带来了对其安全性和可信度的新挑战。由于目标和输出模式的多样性，现有的LLMs安全增强方法难以直接应用于这些代理。为此，我们提出了GuardAgent，首个作为其他LLM代理安全屏障的LLM代理。GuardAgent通过监控目标LLM代理的输入/输出，确保它们符合用户设定的防护请求。其工作流程包括两个关键步骤：首先，通过分析防护请求制定任务计划；其次，依据任务计划生成并执行护栏代码，这一过程通过调用API或利用外部引擎实现。在整个过程中，LLM作为核心推理引擎，辅以从内存模块中提取的上下文示例，确保GuardAgent能准确理解并执行各种文本防护请求，将其转化为可靠的执行代码。GuardAgent还配备了一个包含丰富函数和API的可扩展工具箱，无需额外训练，展现了其强大的泛化能力和低操作成本。此外，我们推出了两个创新基准：EICU-AC用于评估医疗保健代理的隐私访问控制，Mind2Web-SC用于评估网络代理的安全性。实验结果显示，GuardAgent在这两个基准上分别实现了98.7%和90.0%的准确率，有效管理了无效的输入和输出。此外，GuardAgent还能根据新兴的LLM代理和防护请求灵活定义新功能，进一步证明了其卓越的泛化能力。
>
> https://arxiv.org/abs/2406.09187

![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/figure1_v3.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/benchmark_example.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/case_study.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/n_demo_eicu-ac.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/n_demo_mind2web-sc.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/access_all.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/access_physician.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/access_nursing.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/access_general_administration.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/access_query.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/prompt_baseline_naive.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/input_system_guardagent.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/input_data_guardagent.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/output_guardagent.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/functions.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/prompt_baseline.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/example_demos.png)
![](https://raw.githubusercontent.com/HuggingAGI/HuggingArxiv/main/paper_images/2406.09187/codegen.png)

<hr />

- 论文原文: [https://arxiv.org/abs/2406.09187](https://arxiv.org/abs/2406.09187)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 最新论文订阅体验（3天）：公众号号菜单回复1
- 最新论文订阅新人优惠：公众号号菜单回复2