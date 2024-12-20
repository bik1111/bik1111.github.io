---
permalink: /
title: "Jincheol Jung"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello, I am Jincheol Jung, a student majoring in Software Convergence at Kyung Hee University. During my time as a research intern at the [System software LAB](https://ss.korea.ac.kr/), I conducted studies on container virtualization/orchestration and custom metric-based scaling. Additionally, I gained practical experience in real-time data processing through research on smart healthcare applications at the [BIGDATA LAB]( http://allbigdata.khu.ac.kr/)

My research interests include cloud/edge computing, learning-based resource allocation and optimization, and federated learning. I aim to build intelligent cloud platform systems capable of meeting the performance requirements of next-generation services such as autonomous driving, automation, and AR/VR.

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jincheol Jung</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 20px;
    }
    h2 {
      color: #333;
      margin-bottom: 20px;
    }
    .container {
      display: flex;
      justify-content: space-between;
      gap: 20px; /* 간격 추가 */
    }
    .main-content {
      width: 70%; /* 메인 콘텐츠 폭 */
    }
    .sidebar {
      width: 28%; /* 사이드바 폭 */
      padding: 10px;
      border-left: 1px solid #ccc; /* 분리선 추가 */
    }
    .project {
      display: flex;
      align-items: flex-start; /* 위쪽으로 정렬 */
      margin-bottom: 40px;
    }
    .project img {
      max-width: 100%;
      border-radius: 5px;
    }
    .project-content {
      flex: 2;
      margin-left: 20px;
    }
    .project-content h3 {
      margin: 0 0 10px;
    }
    .project-content p {
      margin: 5px 0;
    }
    .project-buttons a {
      margin-right: 10px;
      text-decoration: none;
      color: white;
      background-color: #007BFF;
      padding: 5px 10px;
      border-radius: 5px;
    }
    .project-buttons a:hover {
      background-color: #0056b3;
    }
    .news-item {
      margin-bottom: 15px;
    }
    .news-item p {
      margin: 0;
      font-size: 14px;
      line-height: 1.4;
    }
  </style>
</head>
<body>

<!-- Main Container -->
<div class="container">
  <!-- Main Content: Research Projects -->
  <div class="main-content">
    <h2>Research Projects</h2>

    <!-- First Project -->
    <div class="project">
      <div style="flex: 1;">
        <img src="images/ACK-2024.png" alt="Metric-Based Scaling Project Image">
      </div>
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
      <div style="flex: 1;">
        <img src="images/FL.png" alt="Federated Learning Project Image">
      </div>
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
      <div style="flex: 1;">
        <img src="images/chat.png" alt="Chat Project Image">
      </div>
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

</body>
</html>