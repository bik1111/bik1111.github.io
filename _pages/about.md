---
permalink: /
title: "Jincheol Jung"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---
<style>
  p {
    font-size: 14px; /* 원하는 크기로 설정 (예: 12px, 14px, small 등) */
    line-height: 1.5; /* 줄 간격 조절 */
  }
</style>

Hello, I am Jincheol Jung, a student majoring in Software Convergence at Kyung Hee University. During my time as a research intern at the [System software LAB](https://ss.korea.ac.kr/), I conducted studies on container virtualization/orchestration and custom metric-based scaling. Additionally, I gained practical experience in real-time data processing through research on smart healthcare applications at the [BIGDATA LAB]( http://allbigdata.khu.ac.kr/)

My research interests include cloud/edge computing, learning-based resource allocation and optimization, and federated learning. I aim to build intelligent cloud platform systems capable of meeting the performance requirements of next-generation services such as autonomous driving, automation, and AR/VR.

## Research Projects

<div class="project">
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 1;">
      <img src="images/ACK-2024.png" alt="CommRad Project Image" style="max-width: 100%; border-radius: 5px;">
    </div>
    <div style="flex: 2; margin-left: 20px;">
      <h3>
        <strong>Performance Analysis of Metric-Based Scaling in Kubernetes Environments</strong>
        <a href="https://kips.or.kr/ack2024/" target="_blank" style="color: orange; text-decoration: none;">[ACK'24]</a>
      </h3>
      <p>
        <strong>Jincheol Jung</strong>
      </p>
      <p>
      This study compares CPU-based and custom metric-based scaling methods in Kubernetes, showing that custom
      metrics tailored to application needs can enhance scalability and efficiency. Findings reveal that, at certain scaling
      thresholds under dynamic network traffic, custom metrics reduce average latency by 85% to 87% compared to
      CPU-based scaling.
      </p>
      <div style="margin-top: 10px;">
        <a href="files/ACK-2024.pdf" class="btn" style="margin-right: 10px;">PDF</a>
        <a href="files/ACK_PPT.pdf" class="btn" style="margin-right: 10px;">SLIDES</a>
        <a href="https://www.manuscriptlink.com/society/kips/conference/ack2024/programBook/presentation/streaming/mv/KIPS_C2024B0377" class="btn">VIDEO</a>
      </div>
    </div>
  </div>

  <!-- Second Project -->
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 1;">
      <img src="images/FL.png" alt="Second Project Image" style="max-width: 100%; border-radius: 5px;">
    </div>
    <div style="flex: 2; margin-left: 20px;">
      <h3>
        <strong>Federated Learning and RAG Integration: A Scalable Approach for Medical Large Language Models</strong>
        <a href="https://icaiic.org/" target="_blank" style="color: orange; text-decoration: none;">[ICAIIC'25]</a>
      </h3>
      <p>
        <strong>Jincheol Jung</strong>, Hongju Jeong, and Eui-Nam Huh
      </p>
      <p>
      This study evaluates the performance of domain-specific Large Language Models (LLMs) for the medical field by integrating Retrieval-Augmented Generation (RAG) systems within a federated learning framework. By preserving data privacy and enabling distributed computation, federated learning enhances the effectiveness of RAG-integrated models under varying client configurations. Experimental results show consistent outperformance over non-integrated models, demonstrating a scalable, privacy-preserving approach to improving text generation for medical applications.      </p>
      <div style="margin-top: 10px;">
        <a href="files/FL.pdf" class="btn" style="margin-right: 10px;">PDF</a>
      </div>
    </div>
  </div>
</div>

  <!-- Third Project -->
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 1;">
      <img src="images/chat.png" alt="Third Project Image" style="max-width: 100%; border-radius: 5px;">
    </div>
    <div style="flex: 2; margin-left: 20px;">
      <h3>
        <strong>Performance Comparison Analysis of gRPC and zeroMQ for Efficient Library Selection in Chat Service Development</strong>
        <a href="http://m.kiise.or.kr/academyEng/main/getContent.faEng?content_no=10&MENU_ID=020200" target="_blank" style="color: orange; text-decoration: none;">[KCC'24]</a>
      </h3>
      <p>
        <strong>Jincheol Jung</strong>, Sungwon Lee
      </p>
      <p>
      In the growing chat service market, real-time open chat platforms focused on specific topics are gaining traction, prompting IT companies to enhance open chat features to boost community engagement. This paper compares gRPC and ZeroMQ for distributed chat service development, addressing the challenge of balancing performance and cost efficiency. Our findings aim to guide the design of efficient chat systems to improve user satisfaction.
      </p>
      <div style="margin-top: 10px;">
        <a href="files/chat.pdf" class="btn" style="margin-right: 10px;">PDF</a>
        <a href="https://drive.google.com/file/d/1qC0XT3fMjy7yqZvTG9sH1nHAEo0xO28K/view?usp=sharing" class="btn" style="margin-right: 10px;">SLIDES</a>
      </div>
    </div>
  </div>