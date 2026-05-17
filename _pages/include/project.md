<h1>⚛️ Open Source Projects</h1>

<style>
  .rainbow-spotlight {
  display: inline-flex;
  font-weight: 800;
}

  .rainbow-spotlight span {
    display: inline-block;
    animation: spotlight-bounce 0.9s ease-in-out infinite;
    animation-delay: calc(var(--i) * 0.08s);
  }

  .rainbow-spotlight span:nth-child(1) { color: #ff3b30; }
  .rainbow-spotlight span:nth-child(2) { color: #ff9500; }
  .rainbow-spotlight span:nth-child(3) { color: #ffcc00; }
  .rainbow-spotlight span:nth-child(4) { color: #34c759; }
  .rainbow-spotlight span:nth-child(5) { color: #00c7be; }
  .rainbow-spotlight span:nth-child(6) { color: #007aff; }
  .rainbow-spotlight span:nth-child(7) { color: #5856d6; }
  .rainbow-spotlight span:nth-child(8) { color: #af52de; }
  .rainbow-spotlight span:nth-child(9) { color: #ff2d55; }

  @keyframes spotlight-bounce {
    0%, 100% {
      transform: translateY(0) scale(1);
    }
    50% {
      transform: translateY(-5px) scale(1.15);
    }
  }
  .project-box {
    display: flex;
    flex-direction: row;   /* 横向布局：图片在左，文字在右 */
    margin: 1rem 0;
    border: 1px solid #e2e2e2;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    transition: transform 0.15s ease-in-out;
    max-width: 900px; /* 控制卡片整体宽度 */
  }
  .project-box:hover {
    transform: translateY(-3px);
  }
  .project-box-image {
    position: relative;
    flex: 0 0 200px; /* 图片固定宽度 */
  }
  .project-box-image img {
    width: 100%;
    height: 100%;
    max-height: 200px;     /* 控制图片高度 */
    object-fit: cover;     /* 填满并裁剪 */
    border-right: 1px solid #eee;
  }
  .conference-label {
    position: absolute;
    top: 10px;
    left: -5px;
    background-color: #2c3e50;
    color: white;
    padding: 6px 12px;
    border-radius: 6px;
    font-size: 0.85em;
    font-weight: 600;
    letter-spacing: 0.5px;
    font-style: italic;
    box-shadow: 0 2px 4px rgba(0,0,0,0.2);
  }
  .conference-label:hover {
    background-color: #34495e;
    transition: background-color 0.2s ease;
  }
  .project-box-text {
    flex: 1;              /* 占据剩余空间 */
    padding: 1rem;
  }
  .project-box-text p {
    margin: .3rem 0;
  }
</style>

<!-- 示例项目 -->
<div class="project-box">
  <div class="project-box-image">
    <span class="conference-label">GitHub</span>
    <img src="../images/opensource/hpdex.png" alt="hpdex project preview">
  </div>
  <div class="project-box-text">
    <p>
      <a href="https://github.com/AI4Cell/hpdex" target="_blank" rel="noopener noreferrer">
        <strong>hpdex: High-performance differential expression analysis for single-cell data</strong>
      </a>
    </p>
    <p><strong>CAIRI</strong></p>
  </div>
</div>
