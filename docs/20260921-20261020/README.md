# 日报 · 2026-09-21 ~ 2026-10-20

- 最近生成时间：2026-10-20 09:16:26 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：25
- 精读区：0
- 速读区：25

## 今日简报（AI）
2026-09-21至10-20共速读25篇论文，其中三篇MoE分布式训练研究均获满分。最值得关注的是专家并行负载均衡与专家共激活优化，前者用拓扑感知调度降低通信瓶颈，后者利用共激活模式提升训练效率。普通读者可优先从TopoEP和Cobalt入手，理解MoE训练中“专家放置与通信开销”这一核心矛盾。

## 精读区
- 本次无精读推荐。

## 速读区
1. [TopoEP: Topology-Aware Load Balancing for Expert-Parallel MoE Training](/20260921-20261020/2609.35481v1-topoep-topology-aware-load-balancing-for-expert-parallel-moe-training) （10.0/10）
2. [Cobalt: Leveraging Expert Co-activation for Efficient Distributed MoE Training](/20260921-20261020/2609.36959v1-cobalt-leveraging-expert-co-activation-for-efficient-distributed-moe-training) （10.0/10）
3. [Expert Coupling in MoE Pretraining: Reducing All-to-All Overhead with Correlated Placement and Token Shuffling](/20260921-20261020/2610.09372v1-expert-coupling-in-moe-pretraining-reducing-all-to-all-overhead-with-correlated-placement-and-token-shuffling) （10.0/10）
4. [Zepp: Accelerating Distributed MoE Serving under Relaxed Balance Constraints](/20260921-20261020/2610.11158v2-zepp-accelerating-distributed-moe-serving-under-relaxed-balance-constraints) （10.0/10）
5. [Accelerating MoE Training through Expert Placement and Replica Coordination](/20260921-20261020/2610.14798v1-accelerating-moe-training-through-expert-placement-and-replica-coordination) （10.0/10）
6. [Exact Quantile Balancing and Load-Error Injection for Mixture-of-Experts](/20260921-20261020/2609.28053v1-exact-quantile-balancing-and-load-error-injection-for-mixture-of-experts) （9.0/10）
7. [CascadeEP: Asynchronous Expert Execution for MoE Prefill under Attention Imbalance](/20260921-20261020/2609.33252v1-cascadeep-asynchronous-expert-execution-for-moe-prefill-under-attention-imbalance) （9.0/10）
8. [HOCCL: Offloading Collective Communication from GPU Cores to Accelerate Distributed Training](/20260921-20261020/2609.34334v1-hoccl-offloading-collective-communication-from-gpu-cores-to-accelerate-distributed-training) （9.0/10）
9. [VarioPath: Workload-Aware All-to-All Communication for PCIe GPU Clusters](/20260921-20261020/2609.34340v1-variopath-workload-aware-all-to-all-communication-for-pcie-gpu-clusters) （9.0/10）
10. [Mixture-of-Kittens: MoE Megakernel for NVL72s](/20260921-20261020/2609.36070v1-mixture-of-kittens-moe-megakernel-for-nvl72s) （9.0/10）
11. [HAPMoE: Heterogeneity-Aware Automatic Parallelism Planning for Mixture-of-Experts Models Training](/20260921-20261020/2609.39350v1-hapmoe-heterogeneity-aware-automatic-parallelism-planning-for-mixture-of-experts-models-training) （9.0/10）
12. [Efficient Expert-Parallel Communication on PCIe-Connected Consumer GPUs](/20260921-20261020/2609.40093v1-efficient-expert-parallel-communication-on-pcie-connected-consumer-gpus) （9.0/10）
13. [MegaFlux: Skew-Resilient MoE Megakernels via Pipelined Expert Replication](/20260921-20261020/2610.00671v1-megaflux-skew-resilient-moe-megakernels-via-pipelined-expert-replication) （9.0/10）
14. [AFORE: Attention-FFN Disaggregation with Overlapped Reconfiguration of Experts](/20260921-20261020/2610.03203v1-afore-attention-ffn-disaggregation-with-overlapped-reconfiguration-of-experts) （9.0/10）
15. [RailWave: Adaptive Spatial and Temporal Scheduling for Expert-Parallel Communication](/20260921-20261020/2610.03415v1-railwave-adaptive-spatial-and-temporal-scheduling-for-expert-parallel-communication) （9.0/10）
16. [T-CCL: Resource Efficient and Performant Collective Communication using Tensor Memory Accelerator](/20260921-20261020/2610.07098v1-t-ccl-resource-efficient-and-performant-collective-communication-using-tensor-memory-accelerator) （9.0/10）
17. [Memory-Efficient Expert Routing for Distributed MoE Training](/20260921-20261020/2610.07333v1-memory-efficient-expert-routing-for-distributed-moe-training) （9.0/10）
18. [NCCL M2N: A Layout- and Topology-Aware Collective for Distributed Tensor Resharding](/20260921-20261020/2610.07516v1-nccl-m2n-a-layout--and-topology-aware-collective-for-distributed-tensor-resharding) （9.0/10）
19. [Democratizing MoE inference on commodity GPUs with CoMoE](/20260921-20261020/2610.09424v1-democratizing-moe-inference-on-commodity-gpus-with-comoe) （9.0/10）
20. [DualColl: Throughput-Optimal Bandwidth-Bound Collective Communications via Fractional Tree Packing](/20260921-20261020/2610.15704v1-dualcoll-throughput-optimal-bandwidth-bound-collective-communications-via-fractional-tree-packing) （9.0/10）
21. [SP-Allreduce: Symmetric Tree Schedules for Tori and Beyond](/20260921-20261020/2610.16387v1-sp-allreduce-symmetric-tree-schedules-for-tori-and-beyond) （9.0/10）
22. [GPU-Initiated Communication: Dissecting Down to the Bone](/20260921-20261020/2610.01380v1-gpu-initiated-communication-dissecting-down-to-the-bone) （8.0/10）
23. [FastEEP: Fast Intra-Instance Elastic Scaling for Expert-Parallel MoE Serving](/20260921-20261020/2610.18451v1-fasteep-fast-intra-instance-elastic-scaling-for-expert-parallel-moe-serving) （8.0/10）
24. [Efficient CPU-GPU collaborative MoE inference via Adaptive Expert Assignment](/20260921-20261020/2610.23006v1-efficient-cpu-gpu-collaborative-moe-inference-via-adaptive-expert-assignment) （8.0/10）
25. [Triple Overlap in Pipelined Krylov Methods on Multi-GPU Systems](/20260921-20261020/2610.25058v1-triple-overlap-in-pipelined-krylov-methods-on-multi-gpu-systems) （8.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
