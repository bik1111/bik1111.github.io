---
permalink: /
title: "Jincheol Jung"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello, I am Jincheol Jung, a student majoring in Software Convergence at Kyung Hee University. As a research intern at the [System software LAB](https://ss.korea.ac.kr/), I conducted research on custom metric-based autoscaling, gaining both theoretical and practical experience in container virtualization and orchestration. Additionally, at the [BIGDATA LAB](http://allbigdata.khu.ac.kr/), I utilized Azure Kinect DK for real-time data collection and analysis. Lastly, through the Individual In-Depth Study course, I conducted research on the integration of RAG systems within a federated learning environment.

My research interests include cloud/edge computing, learning-based resource allocation and optimization, and federated learning. I aim to build intelligent cloud platform systems capable of meeting the performance requirements of next-generation services such as automated driving, 6G, and AR/VR.


<style>
  .container {
    display: flex;
    justify-content: space-between; /* Research Projects와 Sidebar를 양옆으로 배치 */
    max-width: 1400px; /* 전체 컨테이너의 최대 너비 */
    margin: 0 auto; /* 화면 가운데 정렬 */
    padding: 20px;
  }

  .main-content {
    flex: 3; /* Research Projects가 더 넓게 표시되도록 설정 */
    margin-right: 30px; /* Sidebar와의 간격 */
  }

  .project {
    display: flex;
    align-items: flex-start;
    gap: 20px; /* 이미지와 텍스트 사이 간격 */
    margin-bottom: 40px; /* 프로젝트 간 간격 */
  }

  .project img {
    max-width: 250px; /* 이미지 크기 고정 */
    height: auto;
    border-radius: 5px; /* 이미지 모서리를 둥글게 설정 */
  }

  .project-content {
    flex: 1; /* 설명 부분이 남은 공간을 차지 */
    font-size: 16px; /* 텍스트 크기 */
    line-height: 1.6; /* 텍스트 줄 간격 */
  }

  .sidebar {
    flex: 1; /* Sidebar의 비율 */
    max-width: 320px; /* Sidebar의 최대 너비 */
    background-color: #f9f9f9;
    padding: 15px;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    position: sticky; /* Sidebar를 화면에 고정 */
    top: 20px; /* 상단에서 거리 */
  }

  .news-item {
    margin-bottom: 15px;
    font-size: 14px;
    line-height: 1.4;
  }
</style>

<div class="container">
  <!-- Main Content: Research Projects -->
  <div class="main-content">
    <h2>Research Projects</h2>

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
          <a href="https://arxiv.org/abs/2412.13720" class="btn">LINK</a>
        </div>
      </div>
    </div>

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

  <!-- Sidebar -->
  <div class="sidebar">
    <h2>News</h2>
    <div class="news-item">
      <p><strong> 2025:</strong> ICAIIC'25 paper accepted on Federated Learning and RAG Integration: A Scalable Approach for Medical Large Language Models</p>
    </div>
    <div class="news-item">
      <p><strong>Nov 2024:</strong> Presented Performance Analysis of Metric-Based Scaling at ACK'24 </p>
    </div>
    <div class="news-item">
      <p><strong>June 2024:</strong> Presented gRPC and ZeroMQ Comparison for Chat Services at KIISE'24. </p>
    </div>
    <div class="news-item">
      <p><strong>Dec 2023 - Sep 2024:</strong> Joined the System Software Lab as an intern. Worked on projects related to container orchestration and resource allocation/scaling. </p>
    </div>
    <div class="news-item">
      <p><strong>Dec 2022 - Feb 2023:</strong> Joined the BIGDATA Lab as an intern. Worked on data extraction and analysis using Azure Kinect DK. </p>
    </div>
  </div>
</div>