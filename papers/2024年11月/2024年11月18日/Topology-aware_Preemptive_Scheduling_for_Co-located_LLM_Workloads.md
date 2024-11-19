# 针对共置的 LLM 工作负载的拓扑感知抢占式调度

发布时间：2024年11月18日

`LLM应用` `云计算` `资源调度`

> Topology-aware Preemptive Scheduling for Co-located LLM Workloads

# 摘要

> 通过在统一资源池中进行共置来托管多样化的大型语言模型工作负载，成本效益显著。比如，长期运行的聊天服务一般遵循昼夜流量规律，这促使批处理作业与之共置，以填补连续峰值之间的资源低谷，从而在整个集群范围内实现资源分配的饱和。这些不同的工作负载往往有着不同的业务优先级，所以可以利用抢占来实现资源弹性。但工作负载通常也有各异的拓扑偏好。低优先级实例释放的资源可能无法满足通常对延迟敏感的高优先级在线服务的要求。这种不匹配的根本原因在于资源调度器缺乏拓扑意识，尤其是在抢占过程中。为了弥补这一差距，我们开发了一种细粒度的拓扑感知方法用于混合工作负载的抢占式调度。该方法能保证被抢占任务释放的资源以有保障或尽力而为的方式满足高优先级抢占者的拓扑亲和性需求。这种动态对齐极大地提高了抢占效率，使 LLM 工作负载的总体调度性能提升了 55％。

> Hosting diverse large language model workloads in a unified resource pool through co-location is cost-effective. For example, long-running chat services generally follow diurnal traffic patterns, which inspire co-location of batch jobs to fulfill resource valleys between successive peaks, and thus to saturate resource allocation in cluster-wide scope. These heterogeneous workloads often have different business priorities, and therefore preemption can be leveraged for resource elasticity. However, workloads often have distinct topology preferences as well. The resources released by lower-priority instances may fail to meet the requirements of high-priority online services which are usually latency-sensitive. The root cause behind such mis-match is a lack of topology awareness of resource scheduler, especially during preemption. To bridge this gap, we develop a fine-grained topology-aware method for preemptive scheduling of hybrid workloads. The method ensures that the resources freed by preempted tasks adhere to the topological affinity needs of high-priority preemptors in a guaranteed or best-effort manner. This dynamic alignment significantly increases the efficiency of preemption and improves overall scheduled performance for LLM workloads by $55\%$.

[Arxiv](https://arxiv.org/abs/2411.11560)