---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


#  😀About me
Hi 👋, I’m Han Feng(Darren), a Rice University master’s student in Electrical & Computer Engineering who loves turning cutting-edge algorithms into tangible robotic systems.

<div class="about-me-content">
    <p>My toolbox spans **C/C++, Python, ROS, OpenCV, CUDA, STM32, Linux kernel modules, SPI/I²C/UART**, and a healthy curiosity for anything involving sensors and real-time constraints. Whether it’s robotics, embedded AI, or GPU acceleration, I enjoy bridging the gap between elegant code and reliable hardware.</p>
    <p>Current focus: applying embedded ML and edge computing to healthcare and assistive robotics. If you’d like to chat about collaborative projects, internships, or just geek out over motor controllers, feel free to reach out!</p>
</div>



# 🔥 News
- *Mar 2025*: &nbsp;🎉🎉 Partnered with The Floow on designing a next-generation platform for predictive health analytics and proactive illness prevention. 

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Patent</div>
    <img src="images/ROPEHANDLE.png" alt="Patent Image" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**ROPE-DRIVEN OPERATION HANDLE**](https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2024087920&_cid=P22-MAZV88-24496-1)

**Inventors:** MA Gan, FENG Yongxuan, HUANG Haojia, **FENG Han**, KUANG Shaolong, ZHANG Wenwei  
*Patent Application Number:* WO2024087920  
*Filed:* 2024 · *Status:* International Application (PCT)
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Patent</div>
    <img src="images/MOBILERobot.png" alt="Patent Image" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**MOBILE ROBOT END-EFFECTOR POSITIONING STRUCTURE**](https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2024088030&_cid=P22-MAZVJW-31687-1)

**Inventors:** MA Gan, FENG Yongxuan, HUANG Haojia, **FENG Han**, KUANG Shaolong, ZHANG Wenwei  
*Patent Application Number:* WO2024088030  
*Filed:* 2024 · *Status:* International Application (PCT)
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Patent</div>
    <img src="images/LABORATORY.png" alt="Patent Image" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**LABORATORY EQUIPMENT MANAGEMENT SYSTEM AND APPLICATION**](https://patentscope.wipo.int/search/en/detail.jsf?docId=CN403537080&_cid=P22-MAZVOR-34727-1)

**Inventors:** YANG Xu, WU Kelin, MU Keqiang, LIN Jiafeng, **FENG Han**  
*Publication Number:* CN116452385  
*Filed:* Apr 2023 · *Published:* Jul 2023 
</div>
</div>


# 🎖 Honors and Awards
- *Sept 2024*  ECE Future Star Scholarship from George R. Brown School of Engineering and Computing, Rice University — **$18,000**. 
- *Dec 2023*  Coffee Robot Master development funding — **¥200,000** awarded by WIK Group. 
- *Dec 2022*  Third Prize of Craftsmanship for Outstanding Individual of SZTU in 2021-2022. 
- *Jul 2022*  Silver Award in the SZTU Trials of the 2022 “Internet+” College Students Innovation and Entrepreneurship Competition. 
- *Jun 2022* Third Prize in Guangdong Province of the 2022 National College Mechanical Innovation Competition. 
- *Dec 2021* Second Prize of Craftsmanship for Outstanding Individual of SZTU. 
- *Jun 2021* Bronze Award in the SZTU Trials of the 2021 “Internet+” College Students Innovation and Entrepreneurship Competition. 
- *Dec 2020* Excellence Award in the 2020 SZTU Entrepreneurship Park Business Proposal Competition. 

# 📖 Educations
- *Aug 2024 - Dec 2025*, Master in Electrical and Computer Engineering, Rice University, Houston, TX, USA. 
- *Sept 2020 - Jun 2024*, Bachelor in electronic science and technology, Shenzhen Technology University, Shenzhen, Guangdong, China. 

# 💻 Internships
- *May 2023 - Oct 2023*, Integration Process Engineer, Siemens Healthineers, Shenzhen, China.
- *Nov 2020 - Jan 2021*, Research and Development Engineer, Shenzhen Wo'erchuang Technology Co., Ltd. Shenzhen, China.


# 🔬 Projects
<!-- Autonomous RC Car -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Project</div>
    <img src="images/rc-car.png" alt="Autonomous RC Car" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**Autonomous Vision-Based RC Car**](https://www.hackster.io/skyrover-team4/skyrover-a6f1b5)  
**Role:** Embedded Engineer & Project Lead  
**Location:** Houston, Texas, USA | **Mar 2025 – May 2025**  
- Built a real-time lane detection and navigation system using **Raspberry Pi 4**, **OpenCV**, and a **PD controller**, achieving stable tracking within 160×120 resolution constraints.  
- Added HSV-based stop-box detection and **YOLOv5** for obstacle/traffic-light recognition.  
- Integrated **GPIO motor control**, webcam, and optical encoder to synchronize perception and actuation.

</div>
</div>

<!-- CUDA Hole Compaction -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Project</div>
    <img src="images/cuda.png" alt="CUDA Hole Compaction" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**Data-Parallel Hole Compaction in CUDA**](https://github.com/rice-hpc/a4-2025-gpu-hole-compaction-shiroganejunmiyuki)  
**Role:** Software Engineer  
**Location:** Houston, Texas, USA | **Apr 2025 – May 2025**  
- Designed a GPU-based hole-filling algorithm using **CUDA**, **shared memory**, and a recursive **Blelloch scan** to preserve data order in large arrays.  
- Demonstrated up to **83× CPU speedup** on 400M-entry datasets with a three-stage `flag → scan → scatter` pipeline.  
- Validated correctness and optimized memory efficiency for magnetic confinement fusion simulation data.

</div>
</div>

<!-- Robotic Coffee Master -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Project</div>
    <img src="images/coffee-robot.png" alt="Robotic Coffee Master" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**Robotic Coffee Master**](https://github.com/DarrenFeng-dev/DarrenFeng-dev.github.io/blob/main/images/coffee master video.mp4)  
**Role:** Embedded Software Engineer & Manager  
**Location:** Shenzhen, Guangdong, China | **May 2022 – Sept 2022**  
- Led the end-to-end development of a robotic barista using **Digital Twin (Real2Sim2Real)** methods to brew 4+ coffee types and draw 6+ latte-art patterns.  
- Built a 6-DOF kinematics system in **Python + Panda3D**; delivered a live demo and secured **¥200K** in funding.  
- As project manager, coordinated cross-functional teams, resolved integration issues, and ensured on-time delivery.

  </div>
</div>

<!-- Portable Robotic Arm -->
<div class='paper-box'>
  <div class='paper-box-image'>
    <div class='badge'>Project</div>
    <img src="images/robotic-arm.png" alt="Robotic Arm Development" width="75%">
  </div>
  <div class='paper-box-text' markdown="1">

[**Multi-Functional Portable Robotic Arm Development**](#)  
**Role:** Embedded Engineer & Project Lead  
**Location:** Shenzhen, Guangdong, China | **Oct 2023 – May 2024**  
- Created a vision-enabled robotic arm using **C++**, **Python**, **OpenCV**, **PWM servo control**, **inverse kinematics**, and **PID regulation**.  
- Simulated motion accuracy and stability in **3ds Max** and **Unity3D** prior to deployment.  
- Designed a custom **PCB board** using SPI/I²C, with **Raspberry Pi** as coordinator and **STM32** for motor control.

</div>
</div>



# 📔 Blogs
-📝 [C/Cpp blog](https://docs.qq.com/doc/DZExFdHpFTG5HVFVQ)  