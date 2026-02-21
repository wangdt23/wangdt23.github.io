---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello and Welcome! My name is **Daotan Wang**. I am a junior Mechanical Engineering student at Tsinghua University, expected to graduate in June 2027. Currently, I am a research intern at OME Lab supervised by Prof. Zhen Zhang, where I focus on applying control theory to optimize the precision and stability of mechatronic systems. Previously, I served as a research intern at RVSE Lab under the supervision of [Prof. Rui Chen](https://callmeray.github.io/homepage/), where I worked on visuo-tactile sensing and imitation learning to empower robots with dexterous manipulation capabilities.

In the future, I aspire to further my studies in robotic manipulation, aiming to enable robots to manipulate objects with greater precision and fluidity. Simultaneously, I also enjoy dismantling, assembling, and designing innovative robotic hardware.

Please click [here](\files\cv_wdt_forpage.pdf) to view my resume ~

# Publications 

 <div style="display: flex; flex-wrap: wrap; margin-bottom: 40px; align-items: flex-start;">   
     <!-- 左侧：图片或动图 -->   
     <div style="flex: 1; min-width: 250px; margin-right: 20px;">     
         <img src="images\vitamin-b.png" alt="ViTaMIn-B Project" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">   
     </div>    <!-- 右侧：文字信息 -->  
     <div style="flex: 2; min-width: 300px;">     
         <h3 style="margin-top: 0;">ViTaMIn-B: A Reliable and Efficient Visuo-Tactile Bimanual Manipulation Interface</h3>  
         <p>Chuanyu Li*,Chaoyi Liu* ,<strong>Daotan Wang</strong>,Shuyu Zhang, Lusong Li, Zecui Zeng, Fangchen Liu, Jing Xu, Rui Chen</p>    
         <p><i>IEEE Robotics and Automation Letters (RA-L)</i>, Under Review, 2025</p>         
         <!-- 按钮链接 -->    
         <style>
  /* 在这里定义一个自适应类，如果你的 markdown 渲染器支持 style 标签 */
  .pub-btn {
    display: inline-block;
    padding: 4px 12px;
    margin-right: 8px;
    margin-bottom: 8px;
    border: 1px solid currentColor; /* 关键：边框颜色跟随文字颜色 */
    border-radius: 4px;
    text-decoration: none;
    font-size: 0.85em;
    color: inherit; /* 关键：文字颜色跟随主题 */
    transition: all 0.2s ease;
  }
  .pub-btn:hover {
    background-color: rgba(128, 128, 128, 0.1); /* 鼠标悬停时有一点点阴影 */
    text-decoration: none;
  }
</style><div style="margin-top: 15px;">       
    <a href="https://arxiv.org/abs/2511.05858" style="padding: 5px 10px; background: #f0f0f0; border-radius: 4px; text-decoration: none; font-size: 0.9em; margin-right: 10px;">[Paper]</a>       
    <a href="https://chuanyune.github.io/ViTaMIn-B_page/" style="padding: 5px 10px; background: #f0f0f0; border-radius: 4px; text-decoration: none; font-size: 0.9em; margin-right: 10px;">[Project Page]</a>      
</div></div></div>

# Projects

<div style="display: flex; flex-wrap: wrap; margin-bottom: 40px; align-items: flex-start;">
<div style="flex: 1; min-width: 200px; margin-right: 20px;">
<img src="images/xy-table.png" alt="XY Motion Table" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<div style="flex: 2; min-width: 300px;">
<h3 style="margin-top: 0;">Repetitive Control of XY Precision Servo Motion Table</h3>
<p style="font-size: 0.95em; line-height: 1.6;">
I performed <strong>system identification</strong> and developed <strong>multi-loop PID controllers</strong> for a 2-DOF precision motion platform. Currently, I am focused on deploying <strong>FPGA-based repetitive control</strong> to enhance tracking accuracy for high-speed periodic trajectories.
</p>
</div>
</div>

<div style="display: flex; flex-wrap: wrap; margin-bottom: 40px; align-items: flex-start;"><div style="flex: 1; min-width: 200px; margin-right: 20px;"><img src="images/UHD_ViT.png" alt="Visual Encoder Project" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"></div><div style="flex: 2; min-width: 300px;"><h3 style="margin-top: 0;">High-Definition Visual Encoder for Intelligent Robots</h3><p style="font-size: 0.95em; line-height: 1.6;">I designed a real-time <strong>Vision Transformer (ViT)</strong> with token downsampling for high-resolution inference and deployed <strong>Diffusion Policies</strong> on physical robotic arms to facilitate multi-modal vision-tactile perception.</p></div></div>

<div style="display: flex; flex-wrap: wrap; margin-bottom: 40px; align-items: flex-start;"><div style="flex: 1; min-width: 200px; margin-right: 20px;"><img src="images/fuzzyarm.gif" alt="LLM Arm Project" style="width: 100%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"></div><div style="flex: 2; min-width: 300px;"><h3 style="margin-top: 0;">Fuzzy Voice Command Robotic Arm System based on LLM</h3><p style="font-size: 0.95em; line-height: 1.6;">I developed a robotic interaction system that integrates <strong>LLMs for ambiguous voice command interpretation</strong> with a low-level <strong>Simulink control module</strong> for trajectory planning and singularity avoidance.</p></div></div>
