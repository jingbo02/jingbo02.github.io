<!-- ===== Publications with Domain Filter ===== -->

<!-- 1) Title -->
<h1>📃 Publications</h1>
<p><strong>&dagger; Equal Contribution</strong></p>

<!-- 2) Filter Bar -->
<div class="pub-filter" role="tablist" aria-label="Filter publications by domain">
  <button class="pub-filter__btn is-active" role="tab" aria-selected="true" data-filter="all">All</button>
  <button class="pub-filter__btn" role="tab" aria-selected="false" data-filter="De novo Peptide Sequencing">De novo Peptide Sequencing</button>
  <button class="pub-filter__btn" role="tab" aria-selected="false" data-filter="Graph Neural Networks">Graph Neural Networks</button>
  <button class="pub-filter__btn" role="tab" aria-selected="false" data-filter="AI Virtual Cell">AI Virtual Cell</button>
  <span class="pub-filter__count" aria-live="polite"></span>
</div>

<!-- 3) Styles -->
<style>
  .pub-filter {
    display: flex;
    align-items: center;
    gap: .5rem;
    flex-wrap: wrap;
    margin: 1rem 0 1.25rem;
  }
  .pub-filter__btn {
    padding: .4rem .8rem;
    border: 1px solid #e2e2e2;
    border-radius: 999px;
    background: #fff;
    font-size: .9rem;
    cursor: pointer;
    transition: transform .04s ease-in-out, background .2s, border-color .2s;
  }
  .pub-filter__btn:is(:hover,:focus-visible) {
    transform: translateY(-1px);
    border-color: #cfcfcf;
    outline: none;
  }
  .pub-filter__btn.is-active {
    background: #111;
    color: #fff;
    border-color: #111;
  }
  .paper-box.is-hidden {
    display: none !important;
  }
  .pub-filter__count {
    margin-left: auto;
    font-size: .9rem;
    color: #666;
  }
</style>

<!-- 4) Publication Cards (add data-domain) -->

<!-- De novo Peptide Sequencing -->
<div class='paper-box' data-domain="De novo Peptide Sequencing">
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2024</div>
      <img src="../images/nips24/novobench.png" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://arxiv.org/abs/2406.11906"><strong> NovoBench: Benchmarking Deep Learning-based <em>De Novo</em> Sequencing Methods in Proteomics</strong></a></dd>
    <dd><strong><u>Jingbo Zhou&dagger;</u></strong>, Shaorong Chen&dagger;, Jun Xia&dagger;, Sizhe Liu, Tianze Ling, Wenjie Du, Yue Liu, Jianwei Yin, Stan Z. Li</dd>
  </div>
</div>

<!-- Graph Neural Networks -->
<div class='paper-box' data-domain="Graph Neural Networks">
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2024</div>
      <img src="../images/nips24/psnr.png" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://neurips.cc/virtual/2024/poster/94864"><strong> Deep Graph Neural Networks via Posteriori-Sampling-based Node-Adaptative Residual Module</strong></a></dd>
    <dd><strong><u>Jingbo Zhou&dagger;</u></strong>, Yixuan Du&dagger;, Ruqiong Zhang&dagger;, Jun Xia, Zhizhi Yu, Zelin Zang, Di Jin, Carl Yang, Rui Zhang, Stan Z. Li </dd>
  </div>
</div>

<!-- De novo Peptide Sequencing -->
<div class='paper-box' data-domain="De novo Peptide Sequencing">
  <div class='paper-box-image'>
    <div>
      <div class="badge">NeurIPS 2024</div>
      <img src="../images/nips24/adanovo.PNG" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://arxiv.org/abs/2403.07013"><strong> AdaNovo: Adaptive <em>De Novo</em> Peptide Sequencing with Conditional Mutual Information</strong></a></dd>
    <dd> Jun Xia&dagger;, Shaorong Chen&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Xiaojun Shan, Wenjie Du, Zhangyang Gao, Cheng Tan, Bozhen Hu, Jiangbin Zheng, Stan Z. Li </dd>
  </div>
</div>

<!-- De novo Peptide Sequencing -->
<div class='paper-box' data-domain="De novo Peptide Sequencing">
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src="../images/nips24/searchnovo.PNG" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://openreview.net/pdf?id=MfphfLFhD4"><strong> Bridging the Gap between Database Search and <em>De Novo</em> Peptide Sequencing with SearchNovo</strong></a></dd>
    <dd> Jun Xia&dagger;, Sizhe Liu&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Shaorong Chen, hongxin xiang, Zicheng Liu, Yue Liu, Stan Z. Li  <p style="color: red;"> 🔥 NeurIPS 2024 AIDrugX Spotlight </p></dd>
  </div>
</div>

<!-- De novo Peptide Sequencing -->
<div class='paper-box' data-domain="De novo Peptide Sequencing">
  <div class='paper-box-image'>
    <div>
      <div class="badge">ICLR 2025</div>
      <img src="../images/iclr25/ReNovo.png" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://openreview.net/forum?id=uQnvYP7yX9&referrer=%5Bthe%20profile%20of%20Jingbo%20Zhou%5D(%2Fprofile%3Fid%3D~Jingbo_Zhou2)"><strong> ReNovo: Retrieval-Based <em>De Novo</em> Mass Spectrometry Peptide Sequencing</strong></a></dd>
    <dd> Shaorong Chen&dagger;, Jun Xia&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Lecheng Zhang, Zhangyang Gao, Bozhen Hu, Cheng Tan, Wenjie Du, Stan Z. Li </dd>
  </div>
</div>

<!-- De novo Peptide Sequencing -->
<div class='paper-box' data-domain="De novo Peptide Sequencing">
  <div class='paper-box-image'>
    <div>
      <div class="badge">IJCAI 2025</div>
      <img src="../images/ijcai25/NovoSurvey.png" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://github.com/jingbo02/jingbo02.github.io"><strong> A comprehensive and systematic review for deep learning-based de novo peptide sequencing</strong></a></dd>
    <dd> Jun Xia&dagger;, <strong><u>Jingbo Zhou&dagger;</u></strong>, Shaorong Chen&dagger;, Tianze Ling&dagger;, Stan Z. Li </dd>
  </div>
</div>

<!-- AI Virtual Cell -->
<div class='paper-box' data-domain="AI Virtual Cell">
  <div class='paper-box-image'>
    <div>
      <div class="badge">IJCAI 2025</div>
      <img src="../images/ijcai25/Grape.png" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://github.com/jingbo02/jingbo02.github.io"><strong> GRAPE: Heterogeneous Graph Representation Learning for Genetic Perturbation with Coding and Non-Coding Biotype</strong></a></dd>
    <dd> Changxi Chi, Xia Jun, <strong><u>Jingbo Zhou</u></strong>, Jiabei Cheng, Chang Yu, Stan Z. Li </dd>
  </div>
</div>

<!-- Graph Neural Networks -->
<div class='paper-box' data-domain="Graph Neural Networks">
  <div class='paper-box-image'>
    <div>
      <div class="badge">Preprint</div>
      <img src="../images/preprint/NodeReg.png" alt="sym" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">
    <dd><a href="https://github.com/jingbo02/jingbo02.github.io"><strong> NodeReg: Mitigating the Imbalance and Distribution Shift Effects in Semi-Supervised Node Classification via Norm Consistency</strong></a></dd>
    <dd> Shenzhi Yang, Jun Xia, <strong><u>Jingbo Zhou</u></strong>, Xingkai Yao, Xiaofang Zhang </dd>
  </div>
</div>

<!-- 5) Script -->
<script>
(function () {
  const buttons = Array.from(document.querySelectorAll('.pub-filter__btn'));
  const cards = Array.from(document.querySelectorAll('.paper-box'));
  const counter = document.querySelector('.pub-filter__count');
  const TOTAL = cards.length;

  function normalizeDomains(domStr) {
    return (domStr || '')
      .split(',')
      .map(s => s.trim().toLowerCase())
      .filter(Boolean);
  }

  function applyFilter(filter) {
    const key = filter.toLowerCase();
    let visible = 0;

    cards.forEach(card => {
      const domains = normalizeDomains(card.getAttribute('data-domain'));
      const match = key === 'all' || domains.includes(key);
      card.classList.toggle('is-hidden', !match);
      if (match) visible++;
    });

    buttons.forEach(btn => {
      const active = btn.dataset.filter.toLowerCase() === key;
      btn.classList.toggle('is-active', active);
      btn.setAttribute('aria-selected', String(active));
    });

    if (counter) {
      counter.textContent = `${visible}/${TOTAL}`;
    }
  }

  function initFromURL() {
    const params = new URLSearchParams(location.search);
    const domain = params.get('domain');
    if (!domain) return null;
    const candidate = buttons.find(b => b.dataset.filter.toLowerCase() === domain.toLowerCase());
    if (candidate) {
      applyFilter(candidate.dataset.filter);
      return candidate.dataset.filter;
    }
    return null;
  }

  buttons.forEach(btn => {
    btn.addEventListener('click', () => {
      const f = btn.dataset.filter;
      applyFilter(f);
      const url = new URL(location.href);
      if (f.toLowerCase() === 'all') {
        url.searchParams.delete('domain');
      } else {
        url.searchParams.set('domain', f);
      }
      history.replaceState(null, '', url.toString());
    });
  });

  const synced = initFromURL();
  if (!synced) applyFilter('all');
})();
</script>
<!-- ===== End Publications with Domain Filter ===== -->