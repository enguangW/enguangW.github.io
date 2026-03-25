# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">CVPR 2026</div><img src='images/pre.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predictive Regularization Against Visual Representation Degradation in Multimodal Large Language Models](https://arxiv.org/pdf/2603.20808) \\
**Enguang Wang**, Qiang Wang, Yuanchen Wu, Ke Yan, Xinbin Yuan, Shouhong Ding, Xialei Liu, Ming-Ming Cheng

- This paper conducts a systematic diagnosis to unveil the visual representation degradation phenomenon in MLLMs, identifying this phenomenon as a visual sacrifice driven by the singular text-generation objective.
- It introduces Predictive Regularization (PRe), a lightweight self-supervised framework that preserves core visual competence by forcing degraded intermediate features to predict initial visual anchors.
</div>
</div>






<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">CVPR 2025</div><img src='images/get.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GET: Unlocking the Multi-modal Potential of CLIP for Generalized Category Discovery](https://arxiv.org/pdf/2403.09974) \\
**Enguang Wang**, Zhimao Peng, Zhengyuan Xie, Fei Yang, Xialei Liu, Ming-Ming Cheng

- This paper introduces textual information for the GCD task. By projecting visual features into the input space of the CLIP's text encoder, it solves the problem that unlabeled data cannot be processed by the text encoder.
- Through cross-modal distillation and multi-modal joint training, GET achieves state-of-the-art results on multiple benchmarks, providing GCD a multi-modal paradigm.
</div>
</div>






<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">NeurIPS 2025</div><img src='images/segui.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Visual Grounding for GUI Agents via Self-Evolutionary Reinforcement Learning](https://arxiv.org/pdf/2505.12370) \\
Xinbin Yuan, Jian Zhang, Kaixin Li, Zhuoxuan Cai, Lujian Yao, Jie Chen, **Enguang Wang**, Qibin Hou, Jinwei Chen, Peng-Tao Jiang, Bo Li

- This paper builds a GUI agent with an RL-based framework that incorporates three core strategies: (1) seed data curation to ensure high-quality training samples, (2) a dense policy gradient that provides continuous feedback based on prediction accuracy, and (3) a self-evolutionary reinforcement finetuning mechanism that iteratively refines the model using attention maps. 
- With 3k samples, the 7B-model achieves SOTA results on three grounding benchmarks.
</div>
</div>





<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">TMM</div><img src='images/partgcd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Part Knowledge to Facilitate Category Understanding for Fine-Grained Generalized Category Discovery](https://arxiv.org/pdf/2503.16782) \\
**Enguang Wang**, Zhimao Peng, Zhengyuan Xie, Haori Lu, Fei Yang, Xialei Liu


- This paper proposes PartGCD, including 1) Adaptive Part Decomposition, which automatically extracts class-specific semantic parts via Gaussian Mixture Models, and 2) Part Discrepancy Regularization, enforcing explicit separation between part features to amplify fine-grained local part distinctions.
- Experiments demonstrate state-of-the-art performance across multiple fine-grained benchmarks while maintaining competitiveness on generic datasets.
</div>
</div>




<details class="news-details">
<summary class="view-all-button">
  View All Publications...
</summary>

<div style="margin-top: 5px;" markdown="1">




  
<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">IJCAI 2024</div><img src='images/ijcai2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Let’s Start Over: Retraining with Selective Samples for Generalized Category Discovery](https://www.ijcai.org/proceedings/2024/0532.pdf) \\
Zhimao Peng, **Enguang Wan**g, Xialei Liu, Ming-Ming Cheng

- This paper introduces a novel method using Nearest Neighbor Distance-aware Label Consistency sample selection. It creates class-consistent subsets for novel class sample clusters from the current GCD method, acting as “pseudo-labeled sets” to mitigate representation bias.
- It proposes progressive supervised representation learning with selected samples to optimize the trade-off between quantity and purity in each subset.
- The results demonstrate the superiority of the method in achieving improved performance in GCD tasks.
</div>
</div>

  
<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">TMM</div><img src='images/tmmsharp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Sharpness-aware Dynamic Anchor Selection for Generalized Category Discovery](https://arxiv.org/pdf/2512.12925) \\
Zhimao Peng, **Enguang Wan**g, Fei Yang, Xialei Liu, Ming-Ming Cheng

- This paper introduces a loss sharpness penalty into GCD, which generates more robust pseudo labels for training samples by minimizing the worst-case sharpness.
- It proposes a novel dynamic anchor selection strategy to further improve the performance by assigning hard pseudo-labels to the selected unknown classes anchors.
- Experimental results show a state-of-the-art performance
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div style="position: relative;"><div class="badge">TCSVT</div><img src='images/tcsvtood.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Predictive sample assignment for semantically coherent out-of-distribution detection](https://arxiv.org/pdf/2512.12906) \\
Zhimao Peng, **Enguang Wan**g, Xialei Liu, Ming-Ming Cheng

- This paper  analyzes the limitations of existing SCOOD methods based on the clustering-based binary In-distribution Filtering strategy and proposes to use dual-threshold ternary sample assignment to select more reliable auxiliary ID and OOD samples for the SCOOD task.
- It proposes a predictive sample assignment framework for the SCOOD task, which includes a threshold sample assignment mechanism, an ID/OOD concept contrastive representation learning loss, and an additional sample retraining process. Experiments show a state-of-the-art performance
</div>
</div>



</div>

</details>






<style>
/* 1. 基础按钮样式：蓝色、下划线、隐藏默认三角 */
.view-all-button {
  cursor: pointer;
  color: #003399;
  text-decoration: underline;
  font-weight: bold;
  margin: 5px 0 5px 25px;
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
<!-- - `AAAI 2024` [Emotion Rendering for Conversational Speech Synthesis with Heterogeneous Graph-Based Context Modeling](https://arxiv.org/abs/2312.11947), Rui Liu, Yifan Hu, **Yi Ren**, et al. [![](https://img.shields.io/github/stars/walker-hyf/ECSS?style=social&label=Code+Stars)](https://github.com/walker-hyf/ECSS) -->
