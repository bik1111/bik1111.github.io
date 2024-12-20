---
permalink: /
title: "Jincheol Jung"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello, I am Jincheol Jung. I am a student majoring in Software Convergence at Kyung Hee University. During my time as a research intern at the [System software LAB](https://ss.korea.ac.kr/), I conducted studies on container virtualization/orchestration and custom metric-based scaling. Additionally, I gained practical experience in real-time data processing through research on smart healthcare applications at the [BIGDATA LAB](http://allbigdata.khu.ac.kr/).

My research interests include cloud/edge computing, learning-based resource allocation and optimization, and federated learning. I aim to build intelligent cloud platform systems capable of meeting the performance requirements of next-generation services such as autonomous driving, automation, and AR/VR.

## Research Projects

<style>
  .container {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 50px; /* 컨테이너 간격 추가 */
    padding: 20px;
    max-width: 1600px; /* 전체 컨테이너의 최대 너비를 더 넓게 설정 */
    margin: 0 auto;
  }
  .main-content {
    flex: 5; /* Main content takes up 5 parts of the container */
    margin-right: 30px; /* 오른쪽 간격 추가 */
  }
  .sidebar {
    flex: 1; /* Sidebar takes up 1 part of the container */
    max-width: 300px;
    background-color: #f9f9f9;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    position: sticky; /* 스크롤 시 고정 */
    top: 20px;
  }
  .project {
    display: flex;
    align-items: flex-start;
    margin-bottom: 40px; /* 프로젝트 간 간격을 넓게 설정 */
  }
  .project img {
    max-width: 180px; /* 이미지 크기 축소 */
    height: auto;
    margin-right: 20px;
    border-radius: 5px; /* 이미지 둥근 테두리 */
  }
  .project-content {
    flex: 1; /* 설명 텍스트를 가능한 넓게 사용 */
  }
  .news-item {
    margin-bottom: 15px;
    font-size: 14px;
  }
</style>

<div class="container">
  <!-- Main Content: Research Projects -->
  <div class="main-content">
    <div class="project">
      <img src="images/ACK-2024.png" alt="Metric-Based Scaling Project Image">
      <div class="project-content">
        <h3>
          <strong>Performance Analysis of Metric-Based Scaling in Kubernetes Environments</strong>
          <a href="https://kips.or.kr/ack2024/" target="_blank" style="color: orange; text-decoration: none;">[ACK'24]</a>
        </h3>
        <p><strong>Jincheol Jung</strong></p>
        <p>
          This study compares CPU-based and custom metric-based scaling methods in Kubernetes, showing that custom metrics tailored to application needs can enhance scalability and efficiency.
        </p>
        <div class="project-buttons">
          <a href="files/ACK-2024.pdf" class="btn">PDF</a>
          <a href="files/ACK_PPT.pdf" class="btn">SLIDES</a>
          <a href="https://www.manuscriptlink.com/society/kips/conference/ack2024/programBook/presentation/streaming/mv/KIPS_C2024B0377" class="btn">VIDEO</a>
        </div>
      </div>
    </div>

    <!-- Second Project -->
    <div class="project">
      <img src="images/FL.png" alt="Federated Learning Project Image">
      <div class="project-content">
        <h3>
          <strong>Federated Learning and RAG Integration: A Scalable Approach for Medical Large Language Models</strong>
          <a href="https://icaiic.org/" target="_blank" style="color: orange; text-decoration: none;">[ICAIIC'25]</a>
        </h3>
        <p><strong>Jincheol Jung</strong>, Hongju Jeong, and Eui-Nam Huh</p>
        <p>
          This study evaluates the performance of domain-specific Large Language Models (LLMs) for the medical field by integrating Retrieval-Augmented Generation (RAG) systems within a federated learning framework.
        </p>
        <div class="project-buttons">
          <a href="files/FL.pdf" class="btn">PDF</a>
        </div>
      </div>
    </div>

    <!-- Third Project -->
    <div class="project">
      <img src="images/chat.png" alt="Chat Project Image">
      <div class="project-content">
        <h3>
          <strong>Performance Comparison Analysis of gRPC and zeroMQ for Efficient Library Selection in Chat Service Development</strong>
          <a href="http://m.kiise.or.kr/academyEng/main/getContent.faEng?content_no=10&MENU_ID=020200" target="_blank" style="color: orange; text-decoration: none;">[KCC'24]</a>
        </h3>
        <p><strong>Jincheol Jung</strong>, Sungwon Lee</p>
        <p>
          This paper compares gRPC and ZeroMQ for distributed chat service development, addressing the challenge of balancing performance and cost efficiency.
        </p>
        <div class="project-buttons">
          <a href="files/chat.pdf" class="btn">PDF</a>
          <a href="https://drive.google.com/file/d/1qC0XT3fMjy7yqZvTG9sH1nHAEo0xO28K/view?usp=sharing" class="btn">SLIDES</a>
        </div>
      </div>
    </div>
  </div>

  <!-- Sidebar: News -->
  <div class="sidebar">
    <h2>News</h2>
    <div class="news-item">
      <p><strong>Aug 2024:</strong> Joined RPI as Assistant Professor.</p>
    </div>
    <div class="news-item">
      <p><strong>Aug 2024:</strong> Serving as TPC for Mobicom'25, IEEE MSN'24, and IEEE ICASSP'25.</p>
    </div>
    <div class="news-item">
      <p><strong>Mar 2024:</strong> Presented BeamArmor at Hotmobile'24.</p>
    </div>
    <div class="news-item">
      <p><strong>Mar 2023:</strong> Hotmobile'23 Best Poster Runner-up awarded on delay-phased array research.</p>
    </div>
    <div class="news-item">
      <p><strong>Jan 2023:</strong> Infocom'23 paper accepted on mmFlexible: Flexible Directional Frequency Multiplexing for Multi-user mmWave Networks.</p>
    </div>
    <div class="news-item">
      <p><strong>Jun 2022 - Aug 2022:</strong> Joined VMWare for summer internship. Worked on developing intelligent applications on VMWare RIC.</p>
    </div>
  </div>
</div>