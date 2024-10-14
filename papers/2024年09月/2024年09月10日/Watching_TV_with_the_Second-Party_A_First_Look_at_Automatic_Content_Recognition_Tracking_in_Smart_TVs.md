# 与他人共赏电视：智能电视自动内容识别跟踪初探

发布时间：2024年09月10日

`其他` `消费电子` `隐私保护`

> Watching TV with the Second-Party: A First Look at Automatic Content Recognition Tracking in Smart TVs

# 摘要

> 摘要：智能电视通过自动内容识别（ACR）技术追踪用户的观看习惯，类似于Shazam的音乐识别功能。尽管已有研究关注智能电视中的第三方追踪，但鲜有探讨智能电视平台自身的ACR追踪。我们对此进行了黑盒审计，发现：（1）ACR追踪不受观看方式影响；（2）隐私设置能影响ACR追踪；（3）英美两国的ACR追踪方式有别。实验结果还表明，即使电视仅作为外部显示器，ACR仍能运作，而选择退出则会停止ACR服务器的网络流量。

> 
Abstract:Smart TVs implement a unique tracking approach called Automatic Content Recognition (ACR) to profile viewing activity of their users. ACR is a Shazam-like technology that works by periodically capturing the content displayed on a TV's screen and matching it against a content library to detect what content is being displayed at any given point in time. While prior research has investigated third-party tracking in the smart TV ecosystem, it has not looked into second-party ACR tracking that is directly conducted by the smart TV platform. In this work, we conduct a black-box audit of ACR network traffic between ACR clients on the smart TV and ACR servers. We use our auditing approach to systematically investigate whether (1) ACR tracking is agnostic to how a user watches TV (e.g., linear vs. streaming vs. HDMI), (2) privacy controls offered by smart TVs have an impact on ACR tracking, and (3) there are any differences in ACR tracking between the UK and the US. We perform a series of experiments on two major smart TV platforms: Samsung and LG. Our results show that ACR works even when the smart TV is used as a "dumb" external display, opting-out stops network traffic to ACR servers, and there are differences in how ACR works across the UK and the US.
    

[Arxiv](https://arxiv.org/pdf/2409.06203)