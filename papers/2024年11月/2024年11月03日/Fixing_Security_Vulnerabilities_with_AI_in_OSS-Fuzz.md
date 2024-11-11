# 使用人工智能在 OSS-Fuzz 中修复安全漏洞

发布时间：2024年11月03日

`LLM应用`

> Fixing Security Vulnerabilities with AI in OSS-Fuzz

# 摘要

> 关键的开源软件系统以冗长的模糊测试活动的形式进行了大量的验证。模糊测试活动通常在程序输入的域上进行有偏差的随机搜索，以找到使软件系统崩溃的输入。这种模糊测试通常有助于增强软件系统的安全性，因为即使是闭源软件也可能使用开源组件。因此，测试开源软件至关重要。目前，OSS-Fuzz 是用于持续验证开源系统的最重要和广泛使用的基础设施。不幸的是，尽管 OSS-Fuzz 在 1000 多个软件项目中发现了超过 10,000 个漏洞，但检测到的漏洞可能仍未修补，因为在实践中漏洞修复通常是手动的。在这项工作中，我们依靠大型语言模型（LLM）代理在自主程序改进（包括错误修复）方面的最新进展。我们为修复安全漏洞定制了著名的 AutoCodeRover 代理。这是因为像 AutoCodeRover 这样的 LLM 代理通过代码搜索从问题描述中修复错误。而对于安全补丁，我们依靠利用输入的测试执行来提取与修复相关的代码元素。我们对 OSS-Fuzz 漏洞数据的经验表明，与无代理等控制流固定的方法相比，LLM 代理的自主性对于成功的安全补丁很有用。更重要的是，我们的发现表明，我们不能通过补丁与参考代码的代码相似度（如 VulMaster 中使用的 CodeBLEU 分数）来衡量补丁的质量，因为具有高 CodeBLEU 分数的补丁在给定的利用输入下仍然无法通过。我们的发现表明，安全补丁的正确性需要考虑像测试执行这样的动态属性，而不是依赖标准的文本/代码相似度指标。

> Critical open source software systems undergo significant validation in the form of lengthy fuzz campaigns. The fuzz campaigns typically conduct a biased random search over the domain of program inputs, to find inputs which crash the software system. Such fuzzing is useful to enhance the security of software systems in general since even closed source software may use open source components. Hence testing open source software is of paramount importance. Currently OSS-Fuzz is the most significant and widely used infrastructure for continuous validation of open source systems. Unfortunately even though OSS-Fuzz has identified more than 10,000 vulnerabilities across 1000 or more software projects, the detected vulnerabilities may remain unpatched, as vulnerability fixing is often manual in practice. In this work, we rely on the recent progress in Large Language Model (LLM) agents for autonomous program improvement including bug fixing. We customise the well-known AutoCodeRover agent for fixing security vulnerabilities. This is because LLM agents like AutoCodeRover fix bugs from issue descriptions via code search. Instead for security patching, we rely on the test execution of the exploit input to extract code elements relevant to the fix. Our experience with OSS-Fuzz vulnerability data shows that LLM agent autonomy is useful for successful security patching, as opposed to approaches like Agentless where the control flow is fixed. More importantly our findings show that we cannot measure quality of patches by code similarity of the patch with reference codes (as in CodeBLEU scores used in VulMaster), since patches with high CodeBLEU scores still fail to pass given the given exploit input. Our findings indicate that security patch correctness needs to consider dynamic attributes like test executions as opposed to relying of standard text/code similarity metrics.

[Arxiv](https://arxiv.org/abs/2411.03346)