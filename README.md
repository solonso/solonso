<!-- ===== Hero / Header ===== -->
<div align="center">

<h1>Solomon Chibuzo Nwafor</h1>

<p><strong>Robotics and Control Engineer</strong></p>
<p>Field robotics · SLAM · Mobile manipulation · Planning · Perception</p>

<!-- Action buttons (kept minimal; contact already in sidebar bio) -->
<p>
  <a href="https://nwaforsolomon.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-000000?logo=vercel&logoColor=white" alt="portfolio">
  </a>
  <a href="mailto:solomon.nwafor@unn.edu.ng">
    <img src="https://img.shields.io/badge/Email-1d72b8?logo=gmail&logoColor=white" alt="email">
  </a>
  <a href="https://www.linkedin.com/in/solomon-chibuzo-nwafor" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0a66c2?logo=linkedin&logoColor=white" alt="linkedin">
  </a>
</p>

</div>

<!-- ===== At-a-glance cards ===== -->
<table>
  <tr>
    <td width="40%" align="center">
      <img src="assets/output.gif" alt="Scout + xArm6 Robot Simulation - Gazebo" width="320">
      <br><br>
      <em>Advancing autonomy through robotics, perception, and control</em>
    </td>
    <td width="60%" valign="top">

**What I work on**  
- Field robotics autonomy with ROS  
- SLAM and state estimation (EKF, ICP scan matching)  
- Mobile manipulation (MoveIt, grasp execution, recovery logic)  
- Nonholonomic planning (Dubins constraints, sampling-based planners)  
- Medical imaging for longitudinal lesion assessment  

**Current focus**  
- End-to-end perception to action loops that keep working under noise and delays  
- RGB-D 3D pose estimation for grasping, plus point-cloud ICP for correction  
- EKF pipelines where scan matching provides the observation update  
- Finite state machines for manipulation with retries and clear failure states  
- Longitudinal dermoscopy: ΔE-based color metrics and PINN-based lesion growth modeling in iToBoS  

**Selected work**  
- Fruit recycling robot (ELTE IFRoS Lab): Scout 2.0 + xArm6 pipeline with YOLO RGB-D detection, pose filtering, MoveIt pick and place, ArUco bin IDs, and FSM retry logic  
- Pose-based EKF SLAM: wheel-encoder prediction with ICP-based relative pose updates, gating, and pose management  
- Task-priority kinematic control: recursive null-space control with inequality tasks (joint limits, obstacle avoidance)  
- Next-best-view exploration: sampling-based NBV scoring with Dubins-constrained planning and trajectory execution  
- Longitudinal dermoscopy pipeline (iToBoS): lesion segmentation and change assessment with ΔE color metrics and temporal growth modeling

    </td>
  </tr>
</table>

<!-- ===== Tech tags (compact, dark-mode friendly) ===== -->
<p>
  <img src="https://img.shields.io/badge/ROS-22314E?logo=ros&logoColor=white" alt="ros">
  <img src="https://img.shields.io/badge/Python-3776ab?logo=python&logoColor=white" alt="python">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white" alt="opencv">
  <img src="https://img.shields.io/badge/Open3D-111111" alt="open3d">
  <img src="https://img.shields.io/badge/PCL-111111" alt="pcl">
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white" alt="numpy">
  <img src="https://img.shields.io/badge/Matplotlib-0C5A5A?logo=matplotlib&logoColor=white" alt="matplotlib">
</p>

<!-- ===== GitHub Stats ===== -->
<div align="center">
  
## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=solonso&theme=dark&hide_border=false&include_all_commits=true&count_private=true)<br/>
![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=solonso&theme=dark&hide_border=false)<br/>
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=solonso&theme=dark&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

<img src="https://komarev.com/ghpvc/?username=solonso&style=flat-square" alt="Profile views">

</div>
Sorting pipeline showing Silvanus successfully detecting, picking, and sorting carrot, apple, and orange into their respective bins:

<div align="center">
  <img src="assets/demo1.gif" alt="Robot Recycling Demonstration" width="100%">
</div>

Different aspects of the recycling pipeline:
<div align="center">
  <table>
    <tr>
      <td align="center" width="33%">
        <img src="assets/output1.gif" alt="Output 1" width="100%"/>
        <br><strong>Output 1</strong>
      </td>
      <td align="center" width="33%">
        <img src="assets/output2.gif" alt="Output 2" width="100%"/>
        <br><strong>Output 2</strong>
      </td>
      <td align="center" width="33%">
        <img src="assets/output3.gif" alt="Output 3" width="100%"/>
        <br><strong>Output 3</strong>
      </td>
    </tr>
  </table>
</div>

NBV sampling based exploration + Intervention:

<div align="center">
  <img src="assets/integration.gif" alt="Robotics Integration Demo" width="100%">
</div>

<!-- End hero -->
