# MicroPython 联邦学习算法测试平台

发布时间：2024年05月15日

`Agent

这篇论文介绍了一个新的框架——MicroPython Testbed for Federated Learning Algorithms，它是一个用于联邦学习算法的测试平台，特别适用于边缘系统的去中心化与分布式应用。该框架允许在不同的网络节点上运行应用实例，包括PC和物联网设备，这表明它能够支持分布式计算环境中的智能代理（Agent）。在联邦学习中，每个参与的设备或节点都可以被视为一个代理，它们协同工作以训练共享的模型，同时保持数据的本地化。因此，这篇论文的内容与Agent的概念紧密相关，因为它涉及到了分布式系统中的智能体如何协作完成任务。` `物联网` `边缘计算`

> MicroPython Testbed for Federated Learning Algorithms

# 摘要

> Python Testbed for Federated Learning Algorithms近期崭露头角，成为一款低代码、对大型语言模型友好的框架，专为边缘系统的去中心化与分布式应用开发而设计，借助新兴AI工具，让非专业程序员也能轻松上手。该框架采用纯Python编写，轻巧易装，完美适配小型物联网设备。它支持经过正式验证的集中式与去中心化联合学习算法，以及时分复用通信中的点对点数据交换。然而，其局限在于所有应用实例仅能在一台PC上运行。本文推出的MicroPython Testbed for Federated Learning Algorithms新框架，突破了这一限制，使得各个应用实例得以在不同网络节点，如PC和物联网设备上运行，尤其适用于边缘系统。新框架延续了纯Python的精髓，基于异步I/O抽象，运行于MicroPython，与物联网及边缘系统设备完美契合。通过在包含PC和Raspberry Pi Pico W板的无线网络上进行的实验验证，新框架展示了其在前身框架基础上开发的应用示例的强大能力。

> Recently, Python Testbed for Federated Learning Algorithms emerged as a low code and generative large language models amenable framework for developing decentralized and distributed applications, primarily targeting edge systems, by nonprofessional programmers with the help of emerging artificial intelligence tools. This light framework is written in pure Python to be easy to install and to fit into a small IoT memory. It supports formally verified generic centralized and decentralized federated learning algorithms, as well as the peer-to-peer data exchange used in time division multiplexing communication, and its current main limitation is that all the application instances can run only on a single PC. This paper presents the MicroPyton Testbed for Federated Learning Algorithms, the new framework that overcomes its predecessor's limitation such that individual application instances may run on different network nodes like PCs and IoTs, primarily in edge systems. The new framework carries on the pure Python ideal, is based on asynchronous I/O abstractions, and runs on MicroPython, and therefore is a great match for IoTs and devices in edge systems. The new framework was experimentally validated on a wireless network comprising PCs and Raspberry Pi Pico W boards, by using application examples originally developed for the predecessor framework.

[Arxiv](https://arxiv.org/abs/2405.09423)