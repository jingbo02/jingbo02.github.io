<h1>⚛️ Open Source Projects</h1>

<style>
  .project-box {
    display: flex;
    flex-direction: column;
    margin: 1rem 0;
    border: 1px solid #e2e2e2;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 2px 6px rgba(0,0,0,0.05);
    transition: transform 0.15s ease-in-out;
  }
  .project-box:hover {
    transform: translateY(-3px);
  }
  .project-box-image {
    position: relative;
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
    <img src="../images/opensource/hpdex.png" alt="hpdex project preview" width="100%">
  </div>
  <div class="project-box-text">
    <p>
      <a href="https://github.com/AI4Cell/hpdex" target="_blank" rel="noopener noreferrer">
        <strong>hpdex: High-performance differential expression analysis for single-cell data</strong>
      </a>
    </p>
    <p><strong>Vita Team</strong></p>
  </div>
</div>
