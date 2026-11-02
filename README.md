<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg">
  <img src="assets/banner-light.svg" width="100%" alt="Rwxzxy · 具身智能 · 机器人策略 · 世界模型">
</picture>

<a href="mailto:2728836780@qq.com"><img src="https://img.shields.io/badge/Email-2728836780%40qq.com-2563eb?style=flat-square&logo=qq&logoColor=white" alt="Email: 2728836780@qq.com"></a>
<a href="https://github.com/Rwxzxy"><img src="https://img.shields.io/badge/GitHub-Rwxzxy-2563eb?style=flat-square&logo=github&logoColor=white" alt="GitHub: Rwxzxy"></a>

</div>

## 研究方向

- **具身智能**：在 RoboTwin 仿真中做闭环评估，用同任务、同初始条件的配对回合比较不同策略。
- **机器人策略**：改进 SmolVLA 策略的推理调度方式，提升闭环任务成功率。
- **世界模型**：研究世界模型的训练方式（PRISM），让在其上训练的策略在信号灯任务中红灯停车、绿灯通行。

## 项目展示

<table>
<tr>
<td>

### 机器人策略推理｜RoboTwin · SmolVLA

<b>111 / 196</b> 改进策略 &nbsp;vs&nbsp; <b>96 / 196</b> 均匀两步基线 &nbsp;·&nbsp; 配对评估回合

<p align="center"><img src="assets/robot_policy_comparison.gif" width="100%" alt="同一机器人任务的基线失败与改进策略成功对照"></p>

同一任务、同一初始条件：基线未完成交接，改进策略完成任务。196 个配对评估回合中，改进策略成功 **111 次**，均匀两步基线成功 **96 次**。

<details>
<summary>查看结果图</summary>
<br>
<p align="center"><img src="assets/robot_results.png" width="100%" alt="SmolVLA机器人闭环策略比较：均匀两步基线96/196，改进策略111/196"></p>
</details>

</td>
</tr>
</table>

<table>
<tr>
<td>

### PRISM｜信号灯任务中的世界模型

<b>72.0%</b> PRISM &nbsp;vs&nbsp; <b>35.4%</b> 标准训练 &nbsp;·&nbsp; 强对照 MotionJEPA <b>73.1%</b>

<p align="center"><img src="assets/prism_traffic_light.gif" width="72%" alt="同一信号灯回合中，基线闯红灯，改进模型红灯停车、绿灯通行"></p>

同一环境种子下，基线闯红灯，PRISM 红灯停车、绿灯通行。结果汇总自 **3 个世界模型种子 × 3 个策略训练种子**：成功率 **72.0%**，标准训练基线 **35.4%**；强对照 **MotionJEPA 为 73.1%**，高出 1.1 个百分点。

<details>
<summary>查看结果图</summary>
<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/prism_results-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/prism_results-light.svg">
  <img src="assets/prism_results-light.svg" width="100%" alt="信号灯任务成功率：标准训练35.4%，PRISM 72.0%，MotionJEPA强对照73.1%">
</picture>
</details>

</td>
</tr>
</table>

## 技术栈

<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch">
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face">
<img src="https://img.shields.io/badge/NVIDIA_CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="NVIDIA CUDA">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" alt="Linux">
</p>

---

<sub>项目代码与完整实验记录暂未公开。可通过邮箱联系，获取项目介绍或演示。</sub>
