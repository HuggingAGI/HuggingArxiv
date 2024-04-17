# ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。

发布时间：2024年04月16日

`分类：Agent` `视觉问答`

> ViTextVQA: A Large-Scale Visual Question Answering Dataset for Evaluating Vietnamese Text Comprehension in Images

# 摘要

> 视觉问答（VQA）任务考验着机器同时解析自然语言和图像的本领。早期研究主要关注于让机器掌握图像中物体和场景的理解。然而，图像中直接提供完整信息的文字部分却被忽略。随着人工智能的不断进步，全球范围内对VQA模型的阅读理解能力展开了广泛研究。在越南这样的发展中国家，这项任务仍面临诸多限制，有待进一步探索。为此，我们推出了首个专注于解读图像中文字的越南语大规模数据集——ViTextVQA（越南文本视觉问答数据集），包含逾16,000张图片和逾50,000个问答题。经过一系列缜密的实验，我们发现OCR文本中标记的处理和选择顺序对答案制定至关重要，这一发现极大地提高了ViTextVQA数据集上基线模型的表现。相关数据集可通过以下链接获取，以供研究之用。

> Visual Question Answering (VQA) is a complicated task that requires the capability of simultaneously processing natural language and images. Initially, this task was researched, focusing on methods to help machines understand objects and scene contexts in images. However, some text appearing in the image that carries explicit information about the full content of the image is not mentioned. Along with the continuous development of the AI era, there have been many studies on the reading comprehension ability of VQA models in the world. As a developing country, conditions are still limited, and this task is still open in Vietnam. Therefore, we introduce the first large-scale dataset in Vietnamese specializing in the ability to understand text appearing in images, we call it ViTextVQA (\textbf{Vi}etnamese \textbf{Text}-based \textbf{V}isual \textbf{Q}uestion \textbf{A}nswering dataset) which contains \textbf{over 16,000} images and \textbf{over 50,000} questions with answers. Through meticulous experiments with various state-of-the-art models, we uncover the significance of the order in which tokens in OCR text are processed and selected to formulate answers. This finding helped us significantly improve the performance of the baseline models on the ViTextVQA dataset. Our dataset is available at this \href{https://github.com/minhquan6203/ViTextVQA-Dataset}{link} for research purposes.

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x1.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x2.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/vqatool.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/vqajson.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/num_ann_img.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ques_len.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/pos_tag_ques.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ner_ques.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ans_len.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/pos_tag_ans.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ner_ans.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/fre_obj.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/obj_ques.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x3.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/timeline.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ocr_noocr_text_f1.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ocr_noocr_text_em.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/ocr_type_percent.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_f1.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_em.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_f1_ans_len.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_em_ans_len.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_f1_ques_len.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_em_ques_len.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x4.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/origin_em_size.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/remove_accent_f1.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/remove_accent_em.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/word_seg.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x5.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x6.png)

![ViTextVQA：一套大型视觉问答数据集，旨在评估图像中的越南文理解能力。](../../../paper_images/2404.10652/x7.png)

[Arxiv](https://arxiv.org/abs/2404.10652)