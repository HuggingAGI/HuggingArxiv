# FuzzCoder：利用大型语言模型实现字节级模糊测试

发布时间：2024年09月03日

`LLM应用` `软件安全`

> FuzzCoder: Byte-level Fuzzing Test via Large Language Model

# 摘要

> Fuzzing 技术通过向软件注入恶意输入，有效发现漏洞。我们创新性地引入微调大型语言模型 FuzzCoder，从成功攻击中学习输入模式，优化模糊测试。该模型在 Fuzz-Instruct 数据集上训练，能精准预测突变点，引发程序异常。实验表明，FuzzCoder 结合 AFL 工具，大幅提升了突变效率和崩溃检测率，适用于多种文件格式。

> Fuzzing is an important dynamic program analysis technique designed for finding vulnerabilities in complex software. Fuzzing involves presenting a target program with crafted malicious input to cause crashes, buffer overflows, memory errors, and exceptions. Crafting malicious inputs in an efficient manner is a difficult open problem and the best approaches often apply uniform random mutations to pre-existing valid inputs. In this work, we propose to adopt fine-tuned large language models (FuzzCoder) to learn patterns in the input files from successful attacks to guide future fuzzing explorations. Specifically, we develop a framework to leverage the code LLMs to guide the mutation process of inputs in fuzzing. The mutation process is formulated as the sequence-to-sequence modeling, where LLM receives a sequence of bytes and then outputs the mutated byte sequence. FuzzCoder is fine-tuned on the created instruction dataset (Fuzz-Instruct), where the successful fuzzing history is collected from the heuristic fuzzing tool. FuzzCoder can predict mutation locations and strategies locations in input files to trigger abnormal behaviors of the program. Experimental results show that FuzzCoder based on AFL (American Fuzzy Lop) gain significant improvements in terms of effective proportion of mutation (EPM) and number of crashes (NC) for various input formats including ELF, JPG, MP3, and XML.

[Arxiv](https://arxiv.org/abs/2409.01944)