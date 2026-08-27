<div align="center">

# 🤖 Hi there, I'm Chananya Meepayung (I-Aun) 👋

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=00B4D8&center=true&vCenter=true&width=620&lines=Robotics+Software+Engineer;ROS+2+(Humble+%2F+Jazzy)+Specialist;Autonomous+Navigation+%26+SLAM;Embedded+Systems+%26+Zephyr+RTOS" alt="Typing SVG" />
</a>

<p align="center">
  <b>Passionate about developing intelligent robotic systems, autonomous mobile robots (AMR), and real-time embedded control.</b>
</p>

<!-- Social & Contact Badges -->
<p align="center">
  <a href="https://www.linkedin.com/in/chananya-meepayung-b39335356/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:chananyaaun123@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <img src="https://img.shields.io/badge/Location-Thailand-2ea44f?style=for-the-badge&logo=google-maps&logoColor=white" alt="Location" />
</p>

</div>

---

### 👨‍💻 About Me

- 🔭 **Current Focus:** Autonomous Mobile Robots (AMR), ROS 2 Navigation Stack (Nav2), and SLAM mapping algorithms.
- 🦾 **Robotics Software:** Architecting modular ROS 2 nodes, multi-robot communication, simulation modeling, and hardware interfaces.
- ⚡ **Embedded & IoT:** Developing firmware for microcontrollers utilizing **Zephyr RTOS**, **micro-ROS**, and **Modbus TCP** communication protocols.
- 💬 **Ask Me About:** ROS 2 (Humble / Jazzy), Mecanum 4-Wheel Kinematics, Gazebo Simulation, and C++/Python development.

---

### 🎓 Education & Research

```
🎓 Mechatronics Engineering Technology (MtET)
├── 📜 Thesis: Autonomous Mobile Robot Mecanum Four Wheels with ROS 2
├── 🔬 Research Focus: Mobile Robot Kinematics, SLAM, Nav2, Sensor Fusion
└── ⚙️ Core Knowledge: Control Systems, Industrial Automation, Embedded Real-Time OS
```

---

### 🤖 Autonomy & System Architecture

```mermaid
graph LR
    subgraph Perception_Hardware ["🔌 Hardware & Sensing"]
        LIDAR["LiDAR / Sensors"]
        MCU["MCU / Zephyr RTOS"]
    end

    subgraph Middleware ["🔄 Communication"]
        COMM["micro-ROS / Serial / Modbus TCP"]
    end

    subgraph ROS2_Stack ["🤖 ROS 2 Autonomy Stack"]
        SLAM["SLAM Toolbox / Cartographer"]
        NAV["Nav2 Navigation Stack"]
        KIN["Mecanum Kinematics Controller"]
    end

    subgraph Actuation ["⚙️ Actuation"]
        MOTORS["4-Wheel Mecanum Motors"]
    end

    LIDAR --> COMM
    MCU --> COMM
    COMM --> SLAM
    SLAM --> NAV
    NAV --> KIN
    KIN --> MOTORS
```

---

### 🛠️ Tech Stack & Skills

#### 🤖 Robotics & Simulation
<p>
  <img src="https://img.shields.io/badge/ROS_2_(Humble/Jazzy)-22314E?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/Gazebo_Sim-FF6F00?style=for-the-badge&logo=gazebo&logoColor=white" />
  <img src="https://img.shields.io/badge/SLAM_%26_Nav2-00599C?style=for-the-badge&logo=navigation&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/RViz2-181717?style=for-the-badge&logo=visual-studio-code&logoColor=white" />
</p>

#### 💻 Programming Languages
<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black" />
  <img src="https://img.shields.io/badge/Bash_Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white" />
</p>

#### 🔌 Embedded, Hardware & Industrial IoT
<p>
  <img src="https://img.shields.io/badge/Zephyr_RTOS-7014E8?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" />
  <img src="https://img.shields.io/badge/Modbus_TCP-FF9900?style=for-the-badge&logo=ethernet&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux_(Ubuntu_24.04)-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" />
</p>

#### 🧰 Tools & Frameworks
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
</p>

---

### 🚀 Highlighted Projects

| Project | Description | Tech Stack |
| :--- | :--- | :--- |
| 🛡️ [**mecanum-4-wheel-ros2**](https://github.com/iaun123/mecanum-4-wheel-ros2) | **Autonomous Mobile Security Robot (MtET Thesis)**<br>Featuring 4-wheel Mecanum drive kinematics, ROS 2 Nav2 autonomous navigation, and 2D/3D SLAM mapping. | `ROS 2` `Python` `SLAM` `Nav2` `Gazebo` |
| ⚙️ [**mini-project-MtET64**](https://github.com/iaun123/mini-project-MtET64) | **Mechatronics & Robotics System Suite**<br>Comprehensive engineering projects covering robotics algorithms, automation control, and modern C++. | `C++` `Robotics` `Algorithms` `Control` |
| 💡 [**app**](https://github.com/iaun123/app) | **Weather Lamp Application**<br>Interactive IoT & smart device application combining environmental monitoring with ambient control. | `Python` `Flask` `IoT` |
| 📚 [**book_shelf**](https://github.com/iaun123/book_shelf) | **Digital Book & Knowledge Collection**<br>Curated technical resources and engineering reference management. | `Markdown` `Documentation` |

---

### 📊 GitHub Activity & Analytics

<div align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=iaun123&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=iaun123&layout=compact&theme=tokyonight&hide_border=true" width="45%" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=iaun123&theme=tokyonight&hide_border=true" width="94%" alt="Streak Stats" />
</div>

---

### 🐍 Contribution Activity

<div align="center">
  <img src="https://raw.githubusercontent.com/iaun123/iaun123/output/github-contribution-grid-snake-dark.svg" alt="Snake Animation" />
</div>

---

<div align="center">
  <i>"Building the bridge between hardware precision and intelligent software."</i><br>
  <sub>Designed & Developed by <a href="https://github.com/iaun123">Chananya Meepayung</a></sub>
</div>
