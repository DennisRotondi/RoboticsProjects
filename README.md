# Robotics Projects Showcase
The purpose of this repository is to highlight my proficiency and expertise in robotics by compiling some of my finest projects in the field. \
The following projects are the work of Dennis Rotondi, and in some cases, involve collaborative efforts. \
You can check the project repository for individual contributions.

## Model-free Control Barrier Functions for obstacle avoidance

- **Repository:** [GitHub Link](https://github.com/DennisRotondi/AMR22_FP8_Model_free_CBF)
- **Year:** 2023
- **Programming Language:** MATLAB
- **Additional Resources:** [Report](https://github.com/DennisRotondi/AMR22_FP8_Model_free_CBF/blob/master/report.pdf), [Slides](https://docs.google.com/presentation/d/1cNUM1Hq5WOP4jOX6p8fWa-TL-2o4LwJ9hxVOweNTL3Q/edit?usp=sharing), [Video](https://drive.google.com/drive/folders/1BrxUTx0JuhWMO_hbAV8zvJXK9wSYaCpP?usp=sharing)

### Description

This project is the result of the final work for the exam of [Autonomous Mobile and Robotics (AMR)](https://www.diag.uniroma1.it/oriolo/amr/) WS 2022/23, taught by Professor [Giuseppe Oriolo](https://www.diag.uniroma1.it/oriolo/) at Sapienza University of Rome. 
This project revolves around Control Barrier Functions (CBFs). A CBF is a mathematical function that represents a safety constraint. It is designed to ensure that the system stays within safe operating bounds or avoids unsafe states while achieving its control objectives (e.g. regulation). Our goal has been to implement the CBFs by exploiting the full knowledge of the Robot Dynamic Model and using only the kinematic one (also called the Model-Free approach due to the much simpler equations). The simulations (cf. additional resources) have been carried out using a point robot and a unicycle, highlighting the pros and cons of each approach.

## Gravity learning for elastic joint robots

- **Repository:** [GitHub Link](https://github.com/DennisRotondi/robotics2_project)
- **Year:** 2022
- **Programming Language:** MATLAB
- **Additional Resources:** [Report](https://github.com/DennisRotondi/robotics2_project/blob/master/Report_Rotondi_Scaparro.pdf), [Slides](https://docs.google.com/presentation/d/165GUNOE-dIQUmgw-vLpszNcTZbrL-P3V7CobsmjXhgE/edit?usp=sharing), [Video](https://drive.google.com/drive/folders/1DCEF3msvgXbq4hISgg4q9fJZa7GfT--3?usp=sharing)

### Description

This project is the result of the final work for the exam of [Robotics 2](https://www.diag.uniroma1.it/deluca/rob2_en.php) SS 2021/2022, taught by Professor [Alessandro De Luca](https://www.diag.uniroma1.it/deluca/) at Sapienza University of Rome. 
Here, we delve into the modeling of elastic joint robots, a specific category that is gaining increasing popularity, with its most extreme manifestation being soft robots. Designing a PD controller for such robots is non-trivial, and in this project, we explore and demonstrate how it is feasible to regulate the position of the end effector using an iterative gravity learning compensation term. The simulations (refer to additional resources) are conducted using a 3R elastic joint robot.

## 2D Range Only SLAM

- **Repository:** [GitHub Link](https://github.com/DennisRotondi/probabilistic_robotics_project)
- **Year:** 2022
- **Programming Language:** Octave

### Description

This project is the result of the final work for the exam of [Probabilistic Robotics](https://sites.google.com/diag.uniroma1.it/probabilistic-robotics-2021-22/home) SS 2021/2022, taught by Professor [Giorgio Grisetti](https://sites.google.com/dis.uniroma1.it/grisetti/home) at Sapienza University of Rome. Here, I have implemented backend optimization for the Simultaneous Localization and Mapping (SLAM) problem using only odometry and range measurements (distance from landmarks). Additionally, the difference between performing SLAM with this sensor fusion and working independently with only range measurements is explored.

## RoboCup Autonomous Robot Manipulation Challenge 2023

- **Repository:** [GitHub Link](https://github.com/DennisRotondi/arm_2023), [HRI Extension](https://github.com/DennisRotondi/eai_hri_project)
- **Year:** 2023
- **Programming Language:** MATLAB
- **Additional Resources:** [Report](https://github.com/DennisRotondi/eai_hri_project/blob/master/report.pdf), [Video](https://drive.google.com/file/d/1aAxM02qK1T6J0tL3uSaWgUbBY04pCLik/view)

### Description

This project is the solution proposed by the Italian team to compete against all the other countries in the RoboCup Autonomous Robot Manipulation Challenge 2023 world finals in Bordeaux, France. Participants were tasked with completing a recycling task with a robot manipulator in a dynamic environment. Our approach involves perception neural networks (YOLO) to identify the objects in the environment. The bounding boxes are then reprojected into the 3D world, and through 3D point matching techniques (iterative Closest Point algorithm), we estimated the positions of the objects to compute the optimal grasping direction. The robot has been moved by an impedance controller to guarantee safety. The challenge code has been extended and adapted with an interactive unconstrained language module to be considered as the final project for the exam of [Human-Robot Interaction](https://sites.google.com/a/dis.uniroma1.it/human-robot-interaction/) SS 2022/2023, taught by Professor [Luca Iocchi](https://sites.google.com/a/dis.uniroma1.it/iocchi/home) at Sapienza University of Rome.




