# 日报 · 2026-09-28 ~ 2026-10-27

- 最近生成时间：2026-10-27 08:16:39 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：25
- 精读区：17
- 速读区：8

## 今日简报（AI）
本期日报梳理了25篇论文，其中精读17篇，重点看两篇满分研究：TopoEP从拓扑感知角度优化专家并行MoE训练负载均衡，RailWave做专家并行通信的自适应时空调度。最值得关注的是专家并行MoE训练与通信调度这个方向，速读中GPU发起的通信和MoE推理受拓扑、并行度、拥塞控制联合影响的研究也可作为背景。普通读者可先读TopoEP和RailWave，再按需补充速读材料。

## 精读区
1. [TopoEP: Topology-Aware Load Balancing for Expert-Parallel MoE Training](/20260928-20261027/2609.35481v1-topoep-topology-aware-load-balancing-for-expert-parallel-moe-training) （10.0/10）
2. [RailWave: Adaptive Spatial and Temporal Scheduling for Expert-Parallel Communication](/20260928-20261027/2610.03415v1-railwave-adaptive-spatial-and-temporal-scheduling-for-expert-parallel-communication) （10.0/10）
3. [Expert Coupling in MoE Pretraining: Reducing All-to-All Overhead with Correlated Placement and Token Shuffling](/20260928-20261027/2610.09372v1-expert-coupling-in-moe-pretraining-reducing-all-to-all-overhead-with-correlated-placement-and-token-shuffling) （10.0/10）
4. [Accelerating MoE Training through Expert Placement and Replica Coordination](/20260928-20261027/2610.14798v1-accelerating-moe-training-through-expert-placement-and-replica-coordination) （10.0/10）
5. [HOCCL: Offloading Collective Communication from GPU Cores to Accelerate Distributed Training](/20260928-20261027/2609.34334v1-hoccl-offloading-collective-communication-from-gpu-cores-to-accelerate-distributed-training) （9.0/10）
6. [VarioPath: Workload-Aware All-to-All Communication for PCIe GPU Clusters](/20260928-20261027/2609.34340v1-variopath-workload-aware-all-to-all-communication-for-pcie-gpu-clusters) （9.0/10）
7. [Mixture-of-Kittens: MoE Megakernel for NVL72s](/20260928-20261027/2609.36070v1-mixture-of-kittens-moe-megakernel-for-nvl72s) （9.0/10）
8. [Purlin: Separating Orchestration from the Datapath of Collectives](/20260928-20261027/2609.36954v1-purlin-separating-orchestration-from-the-datapath-of-collectives) （9.0/10）
9. [Cobalt: Leveraging Expert Co-activation for Efficient Distributed MoE Training](/20260928-20261027/2609.36959v1-cobalt-leveraging-expert-co-activation-for-efficient-distributed-moe-training) （9.0/10）
10. [Efficient Expert-Parallel Communication on PCIe-Connected Consumer GPUs](/20260928-20261027/2609.40093v1-efficient-expert-parallel-communication-on-pcie-connected-consumer-gpus) （9.0/10）
11. [MegaFlux: Skew-Resilient MoE Megakernels via Pipelined Expert Replication](/20260928-20261027/2610.00671v1-megaflux-skew-resilient-moe-megakernels-via-pipelined-expert-replication) （9.0/10）
12. [AFORE: Attention-FFN Disaggregation with Overlapped Reconfiguration of Experts](/20260928-20261027/2610.03203v1-afore-attention-ffn-disaggregation-with-overlapped-reconfiguration-of-experts) （9.0/10）
13. [T-CCL: Resource Efficient and Performant Collective Communication using Tensor Memory Accelerator](/20260928-20261027/2610.07098v1-t-ccl-resource-efficient-and-performant-collective-communication-using-tensor-memory-accelerator) （9.0/10）
14. [Memory-Efficient Expert Routing for Distributed MoE Training](/20260928-20261027/2610.07333v1-memory-efficient-expert-routing-for-distributed-moe-training) （9.0/10）
15. [Democratizing MoE inference on commodity GPUs with CoMoE](/20260928-20261027/2610.09424v2-democratizing-moe-inference-on-commodity-gpus-with-comoe) （9.0/10）
16. [Zepp: Accelerating Distributed MoE Serving under Relaxed Balance Constraints](/20260928-20261027/2610.11158v2-zepp-accelerating-distributed-moe-serving-under-relaxed-balance-constraints) （9.0/10）
17. [DualColl: Throughput-Optimal Bandwidth-Bound Collective Communications via Fractional Tree Packing](/20260928-20261027/2610.15704v1-dualcoll-throughput-optimal-bandwidth-bound-collective-communications-via-fractional-tree-packing) （9.0/10）

## 速读区
1. [Joint Effects of GPU Server Topology, Parallelism, and Congestion Control on MoE Inference: A Controlled Simulation Study](/20260928-20261027/2609.37828v1-joint-effects-of-gpu-server-topology-parallelism-and-congestion-control-on-moe-inference-a-controlled-simulation-study) （8.0/10）
2. [MoSE: Mode-Switching Expander for Mixed LLM Training and Inference](/20260928-20261027/2609.39138v1-mose-mode-switching-expander-for-mixed-llm-training-and-inference) （8.0/10）
3. [GPU-Initiated Communication: Dissecting Down to the Bone](/20260928-20261027/2610.01380v1-gpu-initiated-communication-dissecting-down-to-the-bone) （8.0/10）
4. [AutoLoCo: Communication Efficient Distributed LLM Training via Adaptive Synchronization](/20260928-20261027/2609.36662v1-autoloco-communication-efficient-distributed-llm-training-via-adaptive-synchronization) （7.0/10）
5. [BSIPipe: Bidirectional Sequence-Level Interleaved Pipeline Parallelism for Long-Sequence Large Language Model Training](/20260928-20261027/2610.14935v1-bsipipe-bidirectional-sequence-level-interleaved-pipeline-parallelism-for-long-sequence-large-language-model-training) （7.0/10）
6. [HAPMoE: Heterogeneity-Aware Automatic Parallelism Planning for Mixture-of-Experts Models Training](/20260928-20261027/2609.39350v1-hapmoe-heterogeneity-aware-automatic-parallelism-planning-for-mixture-of-experts-models-training) （6.0/10）
7. [RapidMoE: Exploiting Cross-Asymmetry via Adaptive Residual Offloading for Large-Scale MoE Inference](/20260928-20261027/2610.01265v1-rapidmoe-exploiting-cross-asymmetry-via-adaptive-residual-offloading-for-large-scale-moe-inference) （6.0/10）
8. [Characterizing Parallelism Strategies in LLM Inference: Fundamental Compute-Communication Trade-offs](/20260928-20261027/2610.05305v1-characterizing-parallelism-strategies-in-llm-inference-fundamental-compute-communication-trade-offs) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
