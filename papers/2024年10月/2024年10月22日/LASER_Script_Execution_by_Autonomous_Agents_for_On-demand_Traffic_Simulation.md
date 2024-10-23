# LASER：自主代理按需执行脚本，实现交通模拟

发布时间：2024年10月22日

`Agent` `自动驾驶`

> LASER: Script Execution by Autonomous Agents for On-demand Traffic Simulation

# 摘要

> 自动驾驶系统 (ADS) 需要多样且关键的交通场景进行有效训练和测试，但现有数据生成方法难以满足灵活与扩展需求。我们推出 LASER，一个利用大型语言模型 (LLM) 基于自然语言输入进行交通模拟的创新框架。LASER 分两步走：先从用户描述生成脚本，再由自主代理实时执行。经 CARLA 模拟器验证，LASER 成功打造复杂按需驾驶场景，大幅提升 ADS 训练与测试数据生成效率。

> Autonomous Driving Systems (ADS) require diverse and safety-critical traffic scenarios for effective training and testing, but the existing data generation methods struggle to provide flexibility and scalability. We propose LASER, a novel frame-work that leverage large language models (LLMs) to conduct traffic simulations based on natural language inputs. The framework operates in two stages: it first generates scripts from user-provided descriptions and then executes them using autonomous agents in real time. Validated in the CARLA simulator, LASER successfully generates complex, on-demand driving scenarios, significantly improving ADS training and testing data generation.

[Arxiv](https://arxiv.org/abs/2410.16197)