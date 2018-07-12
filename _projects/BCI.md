---
title: "BCI"
image: 
  path: /assets/images/project/BCI/main.png
  thumbnail: /assets/images/project/BCI/main_400_200.png
  caption: "Photo from [Pexels](https://www.pexels.com)"
---

## What is the BCI?

BCI(Brain-Computer Interface)는 우리가 진행하고 있는 과제의 약칭이며 과제명 전문은 다음과 같습니다.

### **"생각만으로 실생활 기기 및 AR/VR 디바이스를 제어하는 비침습 BCI 통합 뇌인지컴퓨팅 SW 플랫폼 기술 개발"**



우리 연구실은 위 과제에서 원격 로봇 BCI 제어 및 로봇 지능화 기술 개발 부분에 대해 연구중입니다.

Determination of Local Goal for a Mobile Robot with Sporadic Human Commands of Tele-operation

This study is a probabilistic approach to overcome time delay for a mobile robot. The robot receives sporadic user input when using brain-computer interface. Related studies have been considered about various strategies to control the robot as intended. However, the most of experiments heavily depend on the driving environment because of the low information transfer rate. To solve this problem, we propose a probabilistic local goal determination method. Our approach accumulates user input sequence, and specifies it as a feasible path. Simulations in the room and on the track are provided. As a result, we show that the proposed method is robust to long time delay, and achieves the mission with fewer inputs.

## System Architecture

![image]({{ site.url }}/assets/images/project/BCI/system_architecture.png){: width="900"}

![image]({{ site.url }}/assets/images/project/BCI/system_architecture_2.png){: width="900"}

<br>

## 이동 로봇 제어 기술 개발

### 이동 로봇 기능 설계

![image]({{ site.url }}/assets/images/project/BCI/functional_design.png){: width="900"}<br>

### 이동 로봇 제어 기술 개발 (새로운 접근법)

![image]({{ site.url }}/assets/images/project/BCI/kist_approach.png){: width="900"}<br>

### BCI를 고려하여 시간지연에 강인한 이동 로봇 제어 기술 개발

- 기존의 연구들은 입력에 따라 일정거리/일정각도만 움직임
- 위에 나열한 접근법들은 로봇의 움직임을 제한하여 적은 데이터 전송량 혹은 시간지연에 대응하도록 함
  - 일단 전진하고, 정면에 장애물이 있으면 정지하는 전략을 사용
  - 시간지연을 예측하고, 시간지연이 길어지면 속도를 낮추어 사용자가 원격지의 상황에 따라올 수 있도록 함

효율적인 BCI 경로계획을 위한 연구 필요

왼쪽 부터 차례대로 

1. Millan, Jd R., et al. "Noninvasive brain-actuated control of a mobile robot by human EEG." IEEE Transactions on biomedical Engineering 51.6 (2004): 1026-1033.
2. Escolano, Carlos, Javier Mauricio Antelis, and Javier Minguez. "A telepresence mobile robot controlled with a noninvasive brain?computer interface." IEEE Transactions on Systems, Man, and Cybernetics, Part B (Cybernetics) 42.3 (2012): 793-804.
3. Carlson, Tom, and Jose del R. Millan. "Brain-controlled wheelchairs: a robotic architecture." IEEE Robotics & Automation Magazine 20.1 (2013): 65-73.
4. Akce, Abdullah, et al. £¢A brain?machine interface to navigate a mobile robot in a planar workspace: enabling humans to fly simulated aircraft with EEG.£¢ Ieee transactions on neural systems and rehabilitation engineering 21.2 (2013): 306-318.
5. Mostefa, Masmoudi, L. Kaddour El Boudadi, and J. Vareille. £¢Safe and efficient mobile robot teleoperation via a network with communication delay.£¢ International Journal on Interactive Design and Manufacturing (IJIDeM) (2017): 1-11.

### 로봇 상태 관리 기능 개발

<br>

![image]({{ site.url }}/assets/images/project/BCI/user_interface.png){: width="900"}

<br>

------

### Reference Video

<html>
<head></head>
<body>
<iframe width="640" height="360" src="https://youtu.be/embed/L7DKpeUkO6Y" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
</body>
</html>
<br>

### Reference Repository(Private)

if you are interested in these sources, Please send a mail to the following address.

- Naviation, [Github-Repository](https://github.com/Taemin0707/navigation)

### Contact

[Jinhong Noh](https://shri-lab-kist.github.io/people/jinhong) & [Taemin Choi](https://shri-lab-kist.github.io/people/taemin)