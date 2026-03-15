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

# 🤖 About me

<div class="pub-authors" markdown="1">

I am Jun Chen, currently pursuing a Master's degree at the School of Information and Communication Engineering, University of Electronic Science and Technology of China (UESTC). My research and project interests currently lie primarily in the field of Embodied AI, with a specific focus on Vision-Language-Action (VLA) models, imitation learning, and dual-arm robotic manipulation. Additionally, I am interested in embedded applications and multi-view learning. 

If you are interested in my work and projects, please feel free to [contact me](mailto:junchen@std.uestc.edu.cn) to discuss further.

I am currently looking for opportunities to apply for Fall 2027 PhD programs.

</div>

{% comment %}
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
{% endcomment %}


# 🔥 News

<div class="pub-authors" markdown="1">

- *2025.06*: &nbsp;🎉🎉 [Our team wins a first prize in RoboTwin Dual-Arm Collaboration Challenge of CVPR2025 (Real-world Track)!](https://miaa.cc/2025-06-19-robotwin-challenge/). 
- *2025.05*: &nbsp;🎉🎉 [Our team wins a silver medal in RoboTwin Dual-Arm Collaboration Challenge of CVPR2025(Simulation Round 1)!](https://miaa.cc/2025-05-08-robotwin-challenge/). 

</div>


# 📖 Education

<div class="edu-entry">
  <div class="edu-logo"><img src="images/uestc.png" alt="UESTC"></div>
  <div class="edu-text">
    <div class="pub-title">
      <span style="color: #004a99;">University of Electronic Science and Technology of China (UESTC)</span>
    </div>
    <div class="pub-authors">
      School of Information and Communication Engineering
    </div>
    <div class="pub-authors">
      M.S. in Electronic Information
    </div>
    <div class="pub-links">
      2024.09 - 2027.06 (expected) &nbsp;|&nbsp; Star of Innovation, 2025.
    </div>
  </div>
</div>

<div class="edu-entry">
  <div class="edu-logo"><img src="images/whut.png" alt="WHUT"></div>
  <div class="edu-text">
    <div class="pub-title">
      <span style="color: #004a99;">Wuhan University of Technology (WHUT)</span>
    </div>
    <div class="pub-authors">
      School of Information Engineering
    </div>
    <div class="pub-authors">
      B.E. in Electronic Information Engineering
    </div>
    <div class="pub-links">
      2020.09 - 2024.06 &nbsp;|&nbsp; Outstanding Graduates, 2024.
    </div>
  </div>
</div>


# 💻 Research Experience

<div class="edu-entry">
  <div class="edu-logo"><img src="images/lumos_logo.png" alt="Lumos Robotics"></div>
  <div class="edu-text">
    <div class="pub-title">
      <span style="color: #004a99;">Lumos Robotics</span>
    </div>
    <div class="pub-authors">
      Innovative AI Lab
    </div>
    <div class="pub-authors">
      VLA Algorithm Intern
    </div>
    <div class="pub-links">
      2026 - Present &nbsp;|&nbsp; Focused on building VLA models for manipulation tasks.
    </div>
  </div>
</div>

<div class="edu-entry">
  <div class="edu-logo"><img src="images/scut.png" alt="scut"></div>
  <div class="edu-text">
    <div class="pub-title">
      <span style="color: #004a99;">South China University of Technology</span>
    </div>
    <div class="pub-authors">
      MIAA Lab
    </div>
    <div class="pub-authors">
      Research Intern
    </div>
    <div class="pub-links">
      2025 - Present &nbsp;|&nbsp; Focused on Robot Skill Learning.
    </div>
  </div>
</div>




# 📝 Publications 
\* equal contribution. † Corresponding author.

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/arxiv-framwork.png' alt="DASL" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">Dual-Process Atomic Skill Learning for Long-Horizon Manipulation Tasks</span>
    </div>
    <div class="pub-authors">
      <strong>Jun Chen*</strong>, Erdemt Bao*, Wenlong Dong, Jierui Liu, Hao Wan, Jing Liang, Shaopeng Li, Weijun Qin, Huiping Zhuang†.
    </div>
    <div class="pub-venue">
      Under Review
    </div>
    <div class="pub-links">
      <a href="https://hatakekaka.github.io/DASL/">Project Page</a> / 
      <a href="#">Paper</a> / 
      <a href="#">arXiv</a> / 
      <a href="#">Code</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/fig-hao.png' alt="AMRT-Net" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">AMRT-Net: Aspect Manifold Regularization Transfer Network under Incomplete Aspect Coverage for HRRP Recognition</span>
    </div>
    <div class="pub-authors">
      Hao Wan, <strong>Jun Chen</strong>, Xu Si, Jing Liang†.
    </div>
    <div class="pub-venue">
      Under Review
    </div>
    <div class="pub-links">
      <a href="#">Paper</a> 
    </div>
  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <video src='videos/MEIS.mp4' autoplay loop muted controls style='width:100%; max-width:100%;'></video>
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">Benchmarking Generalizable Bimanual Manipulation: RoboTwin Dual-Arm Collaboration Challenge at CVPR 2025 MEIS Workshop</span>
    </div>
    <div class="pub-authors">
      All Participants.
    </div>
    <div class="pub-venue">
      Technical Report of the CVPR 2025 RoboTwin Challenge at the MEIS Workshop
    </div>
    <div class="pub-links">
      <a href="https://robotwin-benchmark.github.io/cvpr-2025-challenge/">Project Page</a> / 
      <a href="https://arxiv.org/pdf/2506.23351">Paper</a> / 
      <a href="https://arxiv.org/abs/2506.23351">arXiv</a> / 
      <a href="https://mp.weixin.qq.com/s/qxqs9vvvHsAJ-0hoYANYzQ/">量子位</a> 
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/TSK.png' alt="TSK" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">Multi-view HRRP target recognition based on unified anchor subspace learning and TSK fuzzy logic</span>
    </div>
    <div class="pub-authors">
      <strong>Jun Chen</strong>, Hao Wan, Jing Liang†.
    </div>
    <div class="pub-venue">
      IRC 2025
    </div>
    <div class="pub-links">
      <a href="#">Paper</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/wevj.png' alt="wevj" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">An FPGA-Based Hardware Low-Cost, Low-Consumption Target-Recognition and Sorting System</span>
    </div>
    <div class="pub-authors">
      Yulu Wang, Yi Han, <strong>Jun Chen</strong>, Zhou Wang, Yi Zhong. <span style="color:#666;">(Second Student Author)</span>
    </div>
    <div class="pub-venue">
      World Electric Vehicle Journal 2023
    </div>
    <div class="pub-links">
      <a href="https://www.mdpi.com/2032-6653/14/9/245">Paper</a>
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <video src='videos/whut.mp4' autoplay loop muted controls style='width:100%; max-width:100%;'></video>
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">3D Object Fusion Detection Method for Complex Scenarios in Embedded Systems</span>
    </div>
    <div class="pub-authors">
      Xiaoxu Wei, <strong>Jun Chen</strong>, Yongsheng Wang, Chang Zhang, Minghao Hou. <span style="color:#666;">(First Student Author)</span>
    </div>
    <div class="pub-venue">
      Journal Of Wuhan University Of Technology 2023
    </div>
    <div class="pub-links">
      <a href="http://whlgdxxb.magtech.org.cn/CN/Y2023/V45/I6/153">Paper</a> 
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/yolov5.png' alt="yolov5" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">Classification and Positioning of Circuit Board Components Based on Improved YOLOv5</span>
    </div>
    <div class="pub-authors">
      <strong>Jun Chen†</strong>, Erdemt Bao, Jingyu Pan.
    </div>
    <div class="pub-venue">
      IISA 2022
    </div>
    <div class="pub-links">
      <a href="https://www.sciencedirect.com/science/article/pii/S1877050922015265">Paper</a>
    </div>
  </div>
</div>



# 🧵 Engineering Projects

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <video src='videos/CIMC.mp4' autoplay loop muted controls style='width:100%; max-width:100%;'></video>
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">ReChip: E-Waste Dismantling and Recycling Technology and Process Management System</span>
    </div>
    <div class="pub-authors">
      <strong>Team: Green Core</strong>
    </div>
    <div class="pub-venue">
      Three-time National Award Winner
    </div>
    </div>
  </div>



# 🎖 Honors and Awards

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/real.png' alt="CVPR Real-World" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">CVPR 2025 RoboTwin Dual-Arm Collaboration Challenge: Real-World Track</span>
    </div>
    <div class="pub-authors">
      <strong>Team: Digital Dynamos</strong>
    </div>
    <div class="pub-venue">
      Gold Medal 🥇
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/sim.png' alt="CVPR Simulation" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99; white-space: nowrap;">CVPR 2025 RoboTwin Dual-Arm Collaboration Challenge: Simulation Round 1</span>
      </div>
    <div class="pub-authors">
      <strong>Team: Digital Dynamos</strong>
    </div>
    <div class="pub-venue">
      Silver Medal 🥈
    </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/UM-MCTS.png' alt="UM MCTS" width="100%">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">UM - Game-Playing Strength of MCTS Variants</span>
    </div>
    <div class="pub-authors">
      <strong>Team: WShatake</strong>
    </div>
    <div class="pub-venue">
      Bronze Medal 🥉
    </div>
  </div>
</div>

<div class="pub-authors" markdown="1">

- **Top 10% Globally**, IEEEXtreme 19.0 & 18.0 Programming Competition, 2025 & 2024.
- **National Grand Prize (3rd Place Overall)**, The 16th "Siemens Cup" China Intelligent Manufacturing Challenge (CIMC), 2022.
- **National 1st Prize**, The 16th National University Student Social Practice and Science Contest on Energy Saving & Emission Reduction, 2023.
- **National 2nd Prize**, The 5th National Undergraduate FPGA Innovation Design Competition, 2022.
- **National 2nd Prize**, The 20th China Graduate Electronics Design Competition, 2025.
- **National 2nd Prize**, The 3rd China Graduate 'Dual-Carbon' Innovation and Creativity Competition, 2024.
- **National 3rd Prize**, The 7th National Undergraduate IC Innovation and Entrepreneurship Competition, 2024.

</div>


<span class='anchor' id='-open-source-projects'></span>
# ⚙️ Open source Projects
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <img src='images/Skill-Learning.png' alt="Awesome-Robotics-Skill-Learning" 
           style="width: 100%; object-fit: contain;">
    </div>
  </div>
  <div class='paper-box-text'>
    <div class="pub-title">
      <span style="color: #004a99;">Awesome-Robotics-Skill-Learning</span>
    </div>
    <div class="pub-authors">
      <strong>Co-Project Lead & Co-First Author</strong>
    </div>
    <div class="pub-links">
      <a href="https://github.com/erdemtbao/Awesome-Robot-Skill-Learning">GitHub Repository</a>
    </div>
  </div>
</div>

