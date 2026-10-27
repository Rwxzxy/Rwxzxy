<div align="center">

# Rwxzxy

具身智能 · 机器人策略 · 世界模型

[联系邮箱](mailto:2728836780@qq.com) · [GitHub](https://github.com/Rwxzxy)

</div>

## 项目展示

### 机器人策略推理｜RoboTwin · SmolVLA

<p align="center"><img src="assets/robot_policy_comparison.gif" width="100%" alt="同一机器人任务的基线失败与改进策略成功对照"></p>

同一任务、同一初始条件：基线未完成交接，改进策略完成任务。196 个配对评估回合中，改进策略成功 **111 次**，均匀两步基线成功 **96 次**。

<p align="center"><img src="assets/robot_results.png" width="100%" alt="SmolVLA机器人闭环策略比较：均匀两步基线96/196，改进策略111/196"></p>

### PRISM｜信号灯任务中的世界模型

<p align="center"><img src="assets/prism_traffic_light.gif" width="72%" alt="同一信号灯回合中，基线闯红灯，改进模型红灯停车、绿灯通行"></p>

<p align="center"><img src="assets/prism_results.png" width="100%" alt="信号灯任务成功率：标准训练35.4%，PRISM 72.0%，MotionJEPA强对照73.1%"></p>

同一环境种子下，基线闯红灯，PRISM 红灯停车、绿灯通行。结果汇总自 **3 个世界模型种子 × 3 个策略训练种子**：成功率 **72.0%**，标准训练基线 **35.4%**；强对照 **MotionJEPA 为 73.1%**，高出 1.1 个百分点。

---

项目代码与完整实验记录暂未公开。可通过邮箱联系，获取项目介绍或演示。
