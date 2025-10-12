
# 📃 Publications 

**&dagger; Equal Contribution**  



<!-- Tabs: zero-JS -->
<style>
/* 容器 */
.tabs { margin: 12px 0; }

/* 隐藏单选框 */
.tabs input[type="radio"] { display: none; }

/* 顶部标签样式 */
.tabs .tab-label {
  display: inline-block; margin-right: 10px; padding: 6px 10px;
  font-weight: 600; cursor: pointer; color:#0066cc; border-radius: 4px;
}
.tabs input[type="radio"]:checked + .tab-label {
  background:#0066cc; color:#fff;
}

/* 面板默认隐藏 */
.tab-panel { display: none; margin-top: 10px; }
/* 选中面板显示（利用相邻选择器链） */
#tab-denovo:checked ~ #panel-denovo,
#tab-gnn:checked   ~ #panel-gnn,
#tab-aivc:checked  ~ #panel-aivc { display: block; }

/* 你已有的卡片类可继续沿用（若主题已有样式可忽略下面两条） */
.topic-section .paper-box { border-bottom: 1px solid #eee; margin-bottom: 1em; padding-bottom: 1em; display:flex; gap: 12px; }
.topic-section .paper-box-image { flex: 0 0 140px; }
</style>

<div class="tabs">
  <!-- 三个单选：默认选中 de novo -->
  <input type="radio" name="pub-tabs" id="tab-denovo" checked>
  <label class="tab-label" for="tab-denovo">De novo Peptide Sequencing</label>

  <input type="radio" name="pub-tabs" id="tab-gnn">
  <label class="tab-label" for="tab-gnn">Graph Neural Networks</label>

  <input type="radio" name="pub-tabs" id="tab-aivc">
  <label class="tab-label" for="tab-aivc">AI Virtual Cell</label>

  <!-- De novo 面板 -->
  <div id="panel-denovo" class="tab-panel topic-section">

    <!-- NovoBench -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">NeurIPS 2024</div><img src="../images/nips24/novobench.png" alt="novobench" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://arxiv.org/abs/2406.11906"><strong>NovoBench: Benchmarking Deep Learning-based <em>De Novo</em> Sequencing Methods in Proteomics</strong></a></dd>
      <dd><strong><u>Jingbo Zhou&dagger;</u></strong>, Shaorong Chen&dagger;, Jun Xia&dagger;, Sizhe Liu, Tianze Ling, Wenjie Du, Yue Liu, Jianwei Yin, Stan Z. Li</dd>
    </div></div>

    <!-- AdaNovo -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">NeurIPS 2024</div><img src="../images/nips24/adanovo.PNG" alt="adanovo" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://arxiv.org/abs/2403.07013"><strong>AdaNovo: Adaptive <em>De Novo</em> Peptide Sequencing with Conditional Mutual Information</strong></a></dd>
      <dd> Jun Xia&dagger;, Shaorong Chen&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Xiaojun Shan, Wenjie Du, Zhangyang Gao, Cheng Tan, Bozhen Hu, Jiangbin Zheng, Stan Z. Li </dd>
    </div></div>

    <!-- SearchNovo -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">ICLR 2025</div><img src="../images/nips24/searchnovo.PNG" alt="searchnovo" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://openreview.net/pdf?id=MfphfLFhD4"><strong>Bridging the Gap between Database Search and <em>De Novo</em> Peptide Sequencing with SearchNovo</strong></a></dd>
      <dd> Jun Xia&dagger;, Sizhe Liu&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Shaorong Chen, hongxin xiang, Zicheng Liu, Yue Liu, Stan Z. Li  <p style="color: red;"> 🔥 NeurIPS 2024 AIDrugX Spotlight </p></dd>
    </div></div>

    <!-- ReNovo -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">ICLR 2025</div><img src="../images/iclr25/ReNovo.png" alt="renovo" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://openreview.net/forum?id=uQnvYP7yX9&referrer=%5Bthe%20profile%20of%20Jingbo%20Zhou%5D(%2Fprofile%3Fid%3D~Jingbo_Zhou2)"><strong>ReNovo: Retrieval-Based <em>De Novo</em> Mass Spectrometry Peptide Sequencing</strong></a></dd>
      <dd> Shaorong Chen&dagger;, Jun Xia&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Lecheng Zhang, Zhangyang Gao, Bozhen Hu, Cheng Tan, Wenjie Du, Stan Z. Li </dd>
    </div></div>

    <!-- 系统综述 -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">IJCAI 2025</div><img src="../images/ijcai25/NovoSurvey.png" alt="novosurvey" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://github.com/jingbo02/jingbo02.github.io"><strong>A comprehensive and systematic review for deep learning-based de novo peptide sequencing</strong></a></dd>
      <dd> Jun Xia&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Shaorong Chen&dagger;, Tianze Ling&dagger;, Stan Z. Li </dd>
    </div></div>
  </div>

  <!-- GNN 面板 -->
  <div id="panel-gnn" class="tab-panel topic-section">
    <!-- Deep GNN -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">NeurIPS 2024</div><img src="../images/nips24/psnr.png" alt="psnr-gnn" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://neurips.cc/virtual/2024/poster/94864"><strong>Deep Graph Neural Networks via Posteriori-Sampling-based Node-Adaptative Residual Module</strong></a></dd>
      <dd><strong><u>Jingbo Zhou&dagger;</u></strong>, Yixuan Du&dagger;, Ruqiong Zhang&dagger;, Jun Xia, Zhizhi Yu, Zelin Zang, Di Jin, Carl Yang, Rui Zhang, Stan Z. Li </dd>
    </div></div>

    <!-- NodeReg -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">Preprint</div><img src="../images/preprint/NodeReg.png" alt="nodereg" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://github.com/jingbo02/jingbo02.github.io"><strong>NodeReg: Mitigating the Imbalance and Distribution Shift Effects in Semi-Supervised Node Classification via Norm Consistency</strong></a></dd>
      <dd> Shenzhi Yang, Jun Xia, <strong><u>Jingbo Zhou</u></strong>, Xingkai Yao, Xiaofang Zhang </dd>
    </div></div>
  </div>

  <!-- AIVC 面板 -->
  <div id="panel-aivc" class="tab-panel topic-section">
    <!-- GRAPE -->
    <div class='paper-box'><div class='paper-box-image'>
      <div><div class="badge">IJCAI 2025</div><img src="../images/ijcai25/Grape.png" alt="grape" width="100%"></div>
    </div><div class='paper-box-text' markdown="1">
      <dd><a href="https://github.com/jingbo02/jingbo02.github.io"><strong>GRAPE: Heterogeneous Graph Representation Learning for Genetic Perturbation with Coding and Non-Coding Biotype</strong></a></dd>
      <dd> Changxi Chi, Xia Jun, <strong><u>Jingbo Zhou</u></strong>, Jiabei Cheng, Chang Yu, Stan Z. Li </dd>
    </div></div>
  </div>
</div>
