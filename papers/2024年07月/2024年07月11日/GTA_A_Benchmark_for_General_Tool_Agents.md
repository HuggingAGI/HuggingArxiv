# GTA：通用工具代理的评测标杆

发布时间：2024年07月11日

`Agent` `人工智能` `软件开发`

> GTA: A Benchmark for General Tool Agents

# 摘要

> 在开发通用代理的过程中，大型语言模型（LLM）与多种工具的整合备受关注，这对LLM的工具使用能力构成了挑战。然而，现有评估与实际应用之间存在显著差距。目前的评估方法多采用AI生成的查询、单一任务、模拟工具及纯文本交互，未能充分展现代理在现实问题解决中的能力。为此，我们推出了GTA基准，专注于三个核心领域：（i）真实用户查询：包含简单现实目标但需隐含工具使用的人类编写查询，要求LLM进行工具选择与解决方案规划。（ii）真实部署工具：一个集成了感知、操作、逻辑和创造力工具的评估平台，用以检验代理的实际任务执行力。（iii）真实多模态输入：包括空间场景、网页截图、表格、代码片段及印刷/手写材料等真实图像文件，作为查询背景，以贴近现实情境。我们设计了229个现实任务及可执行工具链，对主流LLM进行了评估。结果显示，现实用户查询对现有LLM构成挑战，GPT-4完成率不足50%，多数LLM完成率低于25%。此次评估揭示了LLM在实际应用中工具使用能力的局限，为未来通用工具代理的发展指明了方向。相关代码和数据集已公开于https://github.com/open-compass/GTA。

> Significant focus has been placed on integrating large language models (LLMs) with various tools in developing general-purpose agents. This poses a challenge to LLMs' tool-use capabilities. However, there are evident gaps between existing tool-use evaluations and real-world scenarios. Current evaluations often use AI-generated queries, single-step tasks, dummy tools, and text-only interactions, failing to reveal the agents' real-world problem-solving abilities effectively. To address this, we propose GTA, a benchmark for General Tool Agents, featuring three main aspects: (i) Real user queries: human-written queries with simple real-world objectives but implicit tool-use, requiring the LLM to reason the suitable tools and plan the solution steps. (ii) Real deployed tools: an evaluation platform equipped with tools across perception, operation, logic, and creativity categories to evaluate the agents' actual task execution performance. (iii) Real multimodal inputs: authentic image files, such as spatial scenes, web page screenshots, tables, code snippets, and printed/handwritten materials, used as the query contexts to align with real-world scenarios closely. We design 229 real-world tasks and executable tool chains to evaluate mainstream LLMs. Our findings show that real-world user queries are challenging for existing LLMs, with GPT-4 completing less than 50% of the tasks and most LLMs achieving below 25%. This evaluation reveals the bottlenecks in the tool-use capabilities of current LLMs in real-world scenarios, which provides future direction for advancing general-purpose tool agents. The code and dataset are available at https://github.com/open-compass/GTA.

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x1.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x2.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x3.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x4.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x5.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x6.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/egg.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/ingredient.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/warn.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/map.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/map_result.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/beer.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/menu.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/egg.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/ingredient.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/meme.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/basketball.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/pinkshirt.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/dogs.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/handwritten_math.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/print_math.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/financial_table.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/financial_bar.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/helmet.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/swan.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/orange.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence1.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence2.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/cow.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence3.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/bill.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/fishoil.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/order.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/gpu_table.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/mapotofu.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence4.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/disney.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence5.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/schedule.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/plane.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence6.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/amd.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/evidence7.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/panel.jpg)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/cake_ingredient.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/running.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/boy.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/lotus.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/orange.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/cow.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/apples.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/cola.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/x7.png)

![GTA：通用工具代理的评测标杆](../../../paper_images/2407.08713/men.jpg)

[Arxiv](https://arxiv.org/abs/2407.08713)