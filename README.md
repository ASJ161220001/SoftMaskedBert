# SoftMaskedBert

Soft-Masked Bert 复现论文:https://arxiv.org/pdf/2005.07421.pdf

我来解释一下这个仓库：


Soft-Masked Bert论文阅读记录
论文地址
Soft-Masked Bert

论文介绍
文本纠错，是自然语言处理领域检测一段文字是否存在错别字、以及将错别字纠正过来的技术，一般用于文本预处理阶段，同时能显著缓解智能客服等场景下语音识别（ASR）不准确的问题。

Soft-Masked Bert的大致原理是基于Bert从句子中的每一个字的候选字组中找到正确的候选字进行纠错。Soft-Maked Bert将文本的纠错任务分为检测网络和纠错网络两个部分，纠错网络的输入来自检测网络的输出，通过soft masking 将检测网络的输出字符特征添加mask embedding进行纠错。

更详细的介绍请看：
https://blog.csdn.net/qq_33599158/article/details/106683235
