# SudoLM：借助授权对齐，掌握参数知识的访问控制艺术

发布时间：2024年10月18日

`LLM应用` `信息技术` `网络安全`

> SudoLM: Learning Access Control of Parametric Knowledge with Authorization Alignment

# 摘要

> 现有的偏好对齐机制是一刀切的，它统一屏蔽了 LLM 中所有用户的非偏好知识。然而，这些知识对高级用户可能是有价值的。为了解决这一问题，我们推出了 SudoLM 框架，通过授权对齐机制，让 LLM 根据用户凭证学习对特定知识的访问控制。SudoLM 允许授权用户使用 SUDO 密钥解锁全部知识，同时阻止非合格用户的访问。实验证明，SudoLM 在控制知识访问的同时，保持了其通用效用。

> Existing preference alignment is a one-size-fits-all alignment mechanism, where the part of the large language model (LLM) parametric knowledge with non-preferred features is uniformly blocked to all the users. However, this part of knowledge can be useful to advanced users whose expertise qualifies them to handle these information. The one-size-fits-all alignment mechanism undermines LLM's utility for these qualified users. To address this problem, we propose SudoLM, a framework that lets LLMs learn access control over specific parametric knowledge for users with different credentials via authorization alignment. SudoLM allows authorized users to unlock their access to all the parametric knowledge with an assigned SUDO key while blocking access to non-qualified users. Experiments on two application scenarios demonstrate that SudoLM effectively controls the user's access to the parametric knowledge and maintains its general utility.

[Arxiv](https://arxiv.org/abs/2410.14676)