# 🔥 News

- *2026.03*: I joined Bytedance <img src='./images/bytedance.jpg' style='width: 6em;'> as a Research Intern, working on Agentic MLLMs
- *2026.03*: 🎉 One paper is accepted by CVPR 2026, keywords: MLLMs, Visual Perception, Pretraining. See you in Denver!
- *2026.03*: 🎉 One paper is accepted by TMM, keywords: Incremental Learning
- *2025.10*: 🎉 One paper is accepted by TMM, keywords: GCD, Fine-grained, SSL
- *2025.10*: 🎉 One paper is accepted by TCSVT, keywords: Continual Self-supervised Learning
- *2025.09*: 🎉 One paper is accepted by NeurIPS 2025, keywords: GUI Agent, RL
- *2025.06*: 🎉 One paper is accepted by TMM, keywords: GCD, SSL

<details class="news-details">
<summary class="view-all-button">
  View All News...
</summary>

<div style="margin-top: 5px;" markdown="1">

- *2025.03*: I joined Tencent Youtu Lab <img src='./images/youtu.png' style='width: 4.8em;'> as a Research Intern, working on MLLMs
- *2025.02*: 🎉 One paper is accepted by CVPR 2025, keywords: GCD, VLM. See you in Nashville!
- *2024.12*: 🎉 One paper is accepted by TCSVT, keywords: OOD, SSL
- *2024.07*: 🎉 One paper is accepted by ECCV 2024, keywords: Incremental Learning, Semantic Segmentation
- *2024.04*: 🎉 One paper is accepted by IJCAI 2024, keywords: GCD, SSL

</div>
</details>

<style>
/* 1. 基础按钮样式：蓝色、下划线、隐藏默认三角 */
.view-all-button {
  cursor: pointer;
  color: #003399;
  text-decoration: underline;
  font-weight: bold;
  margin: 10px 0 10px 25px;
  list-style: none;
  outline: none;
  display: inline-block;
  position: relative;
}

.view-all-button::-webkit-details-marker {
  display: none;
}

/* 2. 使用伪元素添加自定义动态三角形 */
.view-all-button::before {
  content: "▶"; /* 默认折叠状态：向右的小三角 */
  display: inline-block;
  margin-right: 8px;
  font-size: 12px;
  text-decoration: none !important; /* 三角形不需要下划线 */
  transition: transform 0.2s ease;  /* 添加平滑旋转动画 */
}

/* 3. 当父级 details 处于 open 状态时，改变三角形 */
.news-details[open] .view-all-button::before {
  content: "▼"; /* 展开状态：向下的三角形 */
}

.view-all-button:hover {
  color: #001a66;
}
</style>
