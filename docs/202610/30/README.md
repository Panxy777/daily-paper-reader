# 日报 · 2026-10-30

- 最近生成时间：2026-10-30 23:32:25 UTC
- 今日累计更新：1 次
- 今日累计推荐总数：6
- 精读区：2
- 速读区：4

## 今日简报（AI）
今日精读2篇、速读4篇，重点聚焦大模型分布式训练的通信与显存优化。最值得关注的是FSDP通信终局方案（9.0分，涉及Copy Engine、RDMA与NVSwitch的布局感知集合通信）以及显存受限节点上的MoE负载重校准（8.0分）。普通读者可优先阅读这两篇精读，再结合Muon的MoE负载均衡问题理解训练稳定性。

## 精读区
1. [The Endgame of FSDP Communication: Layout-Aware Collectives on Copy Engines, RDMA, and NVSwitch](/202610/30/2610.38228v1-the-endgame-of-fsdp-communication-layout-aware-collectives-on-copy-engines-rdma-and-nvswitch) （9.0/10）
2. [LRMoE: Demand-Side Load Re-Calibration for Efficient MoE Training on Memory-Constrained Nodes](/202610/30/2610.37720v1-lrmoe-demand-side-load-re-calibration-for-efficient-moe-training-on-memory-constrained-nodes) （8.0/10）

## 速读区
1. [MCCL: Training Pytorch models across a fleet of Macs at Skywalker Sound](/202610/30/2610.39029v1-mccl-training-pytorch-models-across-a-fleet-of-macs-at-skywalker-sound) （7.0/10）
2. [Muon Makes the First Mixture-of-Experts Layer Harder to Balance](/202610/30/2610.37914v1-muon-makes-the-first-mixture-of-experts-layer-harder-to-balance) （6.0/10）
3. [Dobb: Shard-Local Preconditioning in Block-Diagonal Eigenbases](/202610/30/2610.39412v1-dobb-shard-local-preconditioning-in-block-diagonal-eigenbases) （6.0/10）
4. [Constant-Factor Approximation for Non-Splitting Coflow Scheduling in Heterogeneous Parallel Networks via Iterative Relaxation](/202610/30/2610.39564v1-constant-factor-approximation-for-non-splitting-coflow-scheduling-in-heterogeneous-parallel-networks-via-iterative-relaxation) （6.0/10）

---
使用键盘方向键可在日报/论文之间快速切换。
