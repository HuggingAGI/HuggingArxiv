# UroBot研究展示了通过一个可解释的大型语言模型，在泌尿学委员会问题中达到超人性能，该模型巧妙地整合了欧洲泌尿学协会指南的上下文信息。

发布时间：2024年06月03日

`LLM应用

这篇论文介绍了UroBot，一个专门针对泌尿学的聊天机器人，它基于大型语言模型（如GPT-3.5、GPT-4及GPT-4o）并采用了检索增强生成技术。该研究通过与顶尖模型及泌尿科医生的对比评估，展示了UroBot在临床验证性和准确性上的优越性。这表明了LLM在特定医学领域的应用，特别是在提高问答系统的性能和临床实用性方面。因此，这篇论文属于LLM应用分类。` `泌尿学`

> Superhuman performance in urology board questions by an explainable large language model enabled for context integration of the European Association of Urology guidelines: the UroBot study

# 摘要

> 大型语言模型（LLMs）正通过广泛利用医学文献，革新医学问答领域。但这些模型的性能常因训练数据过时和缺乏透明度而受限，影响其临床应用。本研究开发并评估了专门针对泌尿学的聊天机器人UroBot，通过与顶尖模型及泌尿科医生在专业问题上的表现对比，确保其临床验证性。UroBot基于OpenAI的GPT-3.5、GPT-4及GPT-4o，采用检索增强生成技术，并遵循欧洲泌尿学协会2023年最新指南。评估涉及十轮200道欧洲泌尿学委员会在职评估题，通过平均正确答案率（RoCA）衡量性能。UroBot-4o平均RoCA达88.4%，超越GPT-4o 10.8%，得分为77.6%，且临床验证性强，运行一致性极高（Fleiss' Kappa = 0.979）。相较之下，泌尿科医生的平均表现仅为68.7%。UroBot在临床验证性和准确性上均优于现有模型及泌尿科医生，显示其在临床应用中的巨大潜力。研究还提供了UroBot进一步开发所需的代码和指南。

> Large Language Models (LLMs) are revolutionizing medical Question-Answering (medQA) through extensive use of medical literature. However, their performance is often hampered by outdated training data and a lack of explainability, which limits clinical applicability. This study aimed to create and assess UroBot, a urology-specialized chatbot, by comparing it with state-of-the-art models and the performance of urologists on urological board questions, ensuring full clinician-verifiability. UroBot was developed using OpenAI's GPT-3.5, GPT-4, and GPT-4o models, employing retrieval-augmented generation (RAG) and the latest 2023 guidelines from the European Association of Urology (EAU). The evaluation included ten runs of 200 European Board of Urology (EBU) In-Service Assessment (ISA) questions, with performance assessed by the mean Rate of Correct Answers (RoCA). UroBot-4o achieved an average RoCA of 88.4%, surpassing GPT-4o by 10.8%, with a score of 77.6%. It was also clinician-verifiable and exhibited the highest run agreement as indicated by Fleiss' Kappa (k = 0.979). By comparison, the average performance of urologists on board questions, as reported in the literature, is 68.7%. UroBot's clinician-verifiable nature and superior accuracy compared to both existing models and urologists on board questions highlight its potential for clinical integration. The study also provides the necessary code and instructions for further development of UroBot.

[Arxiv](https://arxiv.org/abs/2406.01428)