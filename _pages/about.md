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

## Research Projects

<div class="project">
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 1;">
      <img src="images/ACK-2024.png" alt="CommRad Project Image" style="max-width: 100%; border-radius: 5px;">
    </div>
    <div style="flex: 2; margin-left: 20px;">
      <h3>
        <strong>Performance Analysis of Metric-Based Scaling in Kubernetes Environments</strong>
        <span style="color: orange;">[KIPS'24]</span>
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
</div>



  <!-- Second Project -->
  <div style="display: flex; align-items: center; margin-bottom: 20px;">
    <div style="flex: 1;">
      <img src="images/FL.png" alt="Second Project Image" style="max-width: 100%; border-radius: 5px;">
    </div>
    <div style="flex: 2; margin-left: 20px;">
      <h3>
        <strong>Federated Learning and RAG Integration: A Scalable Approach for Medical Large Language Models</strong>
        <span style="color: orange;">[ICAIIC'25]</span>
      </h3>
      <p>
        <strong>Jincheol Jung</strong>, Hongju Jeong, and Eui-Nam Huh
      </p>
      <p>
      This study analyzes the performance of domain- specific Large Language Models (LLMs) for the medical field by integrating Retrieval-Augmented Generation (RAG) systems within a federated learning framework. Leveraging the inherent advantages of federated learning, such as preserving data privacy and enabling distributed computation, this research explores the integration of RAG systems with models trained under varying client configurations to optimize performance. Experimental results demonstrate that the federated learning-based models integrated with RAG systems consistently outperform their non- integrated counterparts across all evaluation metrics. This study highlights the potential of combining federated learning and RAG systems for developing domain-specific LLMs in the medical field, providing a scalable and privacy-preserving solution for enhancing text generation capabilities.
      </p>
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
        <span style="color: orange;">[KISSE'25]</span>
      </h3>
      <p>
        <strong>Jincheol Jung</strong>, Sungwon Lee
      </p>
      <p>
      In the current chat service market, real-time chat services based on open chat formats centered on specific topics and interests are gaining popularity, with the number of open chat users steadily
      increasing. Consequently, domestic IT companies are prioritizing the expansion of open chat functionalities as a core business strategy to invigorate community engagement. However, since the performance of chat services heavily depends on the messaging system used in development, companies face challenges in selecting a library that satisfies both service performance optimization and cost efficiency. This paper compares and analyzes the performance of gRPC and ZeroMQ, which are applicable in distributed system environments, from the perspective of chat service implementation. Through this paper, we aim to contribute to the design and implementation of more efficient chat services, ultimately enhancing user satisfaction
      </p>
      <div style="margin-top: 10px;">
        <a href="files/chat.pdf" class="btn" style="margin-right: 10px;">PDF</a>
      </div>
    </div>
  </div>
</div>