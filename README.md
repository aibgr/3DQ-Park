# 3DQ-Park  
**A Unified Trigonometric Kinematic Model + Guided 3D Q-Learning Framework**  
**One equation → All parking maneuvers (parallel both sides, perpendicular, angled) + overtaking**

[![GitHub stars](https://img.shields.io/github/stars/aibgr/3DQ-Park?style=social)](https://github.com/aibgr/3DQ-Park/stargazers)
[![IEEE T-IV submitted](https://img.shields.io/badge/IEEE%20T--IV-Submitted Nov 2025-blue)](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7274857)
[![Webots 2023](https://img.shields.io/badge/Simulated-Webots%202023-orange)](https://cyberbotics.com)

> First paper of the **3DQ Series** submitted to **IEEE Transactions on Intelligent Vehicles** – Nov 2025  
> First-round decision expected: Dec 2025 – Jan 2026  
> Full source code will be released immediately after acceptance.

### Key Features
- Single kinematic equation for **all** parking + overtaking maneuvers  
- Guided 3D Q-Learning with hierarchical 8-cube search  
- < 40 episodes average convergence  
- Real-time capable (< 15 ms inference on CPU)  
- Full 3D mechanical simulation in Webots with accurate BMW i3 dynamics  
- Successfully parks on **both left and right side** of the road

### Results (Webots R2023b)

<table>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/e302219c-2ff0-46a6-abd4-5eb52be8848e" alt="Training convergence & α-space exploration"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/54cb8169-4038-44db-b170-c880763b6fad" alt="Left-side parallel parking"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/f2fa273d-29b5-4580-bc75-e5dee4ebf25b" alt="Right-side parallel parking"></td>
  </tr>
  <tr>
    <td align="center"><img src="https://github.com/user-attachments/assets/bbdb739e-1bce-4d0a-a72b-338ebad27f05" alt="Complete parking sequence"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/01623380619-... (اگر داشتی بذار، یا این یکی رو حذف کن و فقط ۲×۲ بذار)"></td>
    <td align="center"><img src="https://github.com/user-attachments/assets/any-other-good-one.jpg" alt="Another view"></td>
  </tr>
</table>

<p align="center">
  <img src="https://github.com/user-attachments/assets/bbdb739e-1bce-4d0a-a72b-338ebad27f05" width="95%" alt="Full autonomous parking sequence (right side)"/>
  <br><em>Complete autonomous parking sequence – detection → decision → execution → final pose inside blue box</em>
</p>

### Upcoming
- 3DQ-Overtaking (in preparation)  
- Real-world deployment on our full-scale autonomous vehicle (LiDAR + camera + ultrasonics)  
- ROS2 + Jetson implementation

### Author
**Ali Bagheri**  
B.Sc. Mechanical Engineering & Computer Engineering (Minor) – IUST 2025  
Email: AliBagheri79.ab@gmail.com  
LinkedIn: [ali-bagheri](https://www.linkedin.com/in/ali-bagheri-)  
GitHub: [@aibgr](https://github.com/aibgr)

**Supervisor:** Dr. Hassan Zabihi – Iran University of Science and Technology

اگر کار برات مفید بود لطفاً ⭐ بده  
بعد از پذیرش مقاله، کل سورس‌کد عمومی می‌شه

**More exciting stuff coming very soon!**
