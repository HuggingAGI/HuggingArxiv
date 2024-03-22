# Ax-to-Grind Urdu 是一个专门针对乌尔都语假新闻检测的基准数据集，旨在为该领域的研究提供标准参考和评估依据。

发布时间：2024年03月20日

`LLM应用` `假新闻检测` `乌尔都语`

> Ax-to-Grind Urdu: Benchmark Dataset for Urdu Fake News Detection

> 假新闻对社会的影响深远，波及公众意见、制度信任乃至国家政治前景。如今，在线平台和社交媒体上的假新闻日益猖獗，而现有的事实核查网站往往仅覆盖英文内容，对地区性语言中的假新闻涉猎甚少，导致难以通过常规途径识别乌尔都语假新闻制造者。目前，针对假新闻检测（FND）的前沿技术高度依赖充足且标注精准的大规模数据集，但在区域性和资源匮乏的语言环境下，由于数据集较小以及缺少权威词汇资源，FND进展较为滞后。有鉴于此，本文构建并首次公开发布了迄今为止最大规模的乌尔都语FND数据集——Ax-to-Grind Urdu，旨在填补当前文献中乌尔都语数据集的不足。该数据集包含了来自巴基斯坦和印度主流乌尔都语报纸和新闻频道网站的15个领域的10,083条真实与虚假新闻，涵盖了2017年至2023年的时间段，并由专业记者进行人工标注。我们采用经过多语言大型语料库训练的mBERT、XLNet和XLM RoBERTa模型对该数据集进行了基准评估，其性能指标包括F1得分、准确率、精确率、召回率以及MCC值。

> Misinformation can seriously impact society, affecting anything from public opinion to institutional confidence and the political horizon of a state. Fake News (FN) proliferation on online websites and Online Social Networks (OSNs) has increased profusely. Various fact-checking websites include news in English and barely provide information about FN in regional languages. Thus the Urdu FN purveyors cannot be discerned using factchecking portals. SOTA approaches for Fake News Detection (FND) count upon appropriately labelled and large datasets. FND in regional and resource-constrained languages lags due to the lack of limited-sized datasets and legitimate lexical resources. The previous datasets for Urdu FND are limited-sized, domain-restricted, publicly unavailable and not manually verified where the news is translated from English into Urdu. In this paper, we curate and contribute the first largest publicly available dataset for Urdu FND, Ax-to-Grind Urdu, to bridge the identified gaps and limitations of existing Urdu datasets in the literature. It constitutes 10,083 fake and real news on fifteen domains collected from leading and authentic Urdu newspapers and news channel websites in Pakistan and India. FN for the Ax-to-Grind dataset is collected from websites and crowdsourcing. The dataset contains news items in Urdu from the year 2017 to the year 2023. Expert journalists annotated the dataset. We benchmark the dataset with an ensemble model of mBERT,XLNet, and XLM RoBERTa. The selected models are originally trained on multilingual large corpora. The results of the proposed model are based on performance metrics, F1-score, accuracy, precision, recall and MCC value.

[Arxiv](https://arxiv.org/abs/2403.14037)