# IEEE Humanoids Robot Skill Versatility Challenge (RSCV) Track

![rsvc_banner4.jpeg](../imgs/rsvc_banner4.jpeg)

## Overview
Alongside the Loco-Manipulation Challenge track several tables will offer a circuit of popular benchmark manipulation tasks referred to as the Robot Skill Versatility Challenge for competition participants and robot vendors to attempt during the conference. Attempts are graded pass/fail and differentiated by execution time. The robot team with the most completed tasks and fastest times for the RSVC track will be recognized on stage during the final day of the conference and highlighted by the on-site media team. 

The RSVC circuit manipulation tasks include the following test stations:

| Station | Benchmark Task Description                                               | Instructions  | Scoring |   |
|---------|--------------------------------------------------------------------------|---------------|---------|---|
|    1    | Robothon Electronic Task Board (eTB2021): Battery Removal                | [Test Protocol](../imgs/eTB2021_Robot-Human_Protocol.jpeg) | 20      |   |
|    2    | Robothon Electronic Task Board (eTB2023): Multimeter Use                 | [Test Protocol](../imgs/eTB2023_Robot-Human_Protocol.jpeg) | 20      |   |
|    3    | Robothon Electronic Task Board (eTB2025): Reaction Time, Screen/Tool Use | [Test Protocol](../Robothon2025_eTB_Instructions.pdf) | 20      |   |
|    4    | NIST Assembly Task Board ATB#1: Insertion                                | Test Protocol | 20?     |   |
|    5    | NIST Assembly Task Board ATB#2: Pulleys                                  | Test Protocol | 20?     |   |
|    6    | Transport Tray with Cups                                                 | [Test Protocol](../imgs/Transport-Cup.png) | 20?     |   |
|    7    | Transport Cardboard Box                                                  | [Test Protocol](../imgs/Transport-Box.png) | 20?     |   |
|    8    | Transport Weighted Tote Bag                                              | [Test Protocol](../imgs/Transport-ToteBag.png) | 20?     |   |

## Rules and Test Procedures

The manipulation tasks will be provided on dedicated tables where teams can approach each set up with their robot platform for their trial attempt. Each test artifact has a fixed test protocol to be executed by the robot either via teleoperation or autonomously. Autonomous solutions are preferred and therefore, receive a 2X multiplier in scored points. 

The electronic task board (eTB) manipulation benchmarks model industrial use cases and provide a streamlined platform for comparing human and robot manipulation performance with automated scoring. Each eTB has integrated performance circuits to electronically verify, score, and report trial attempts. Task board sensor values, protocol progress, and task completion are available as ROS2 messages over a local WiFi network. Learn more on the trial protocols on the [Electronic Task Board project repository](https://github.com/peterso/robotlearningblock/)

NIST Prototype Assembly Task Boards (ATBs) are manipulation and assembly benchmarks representing endorsed by NIST. Learn more about the test protocol and scoring details on the [NIST ATB project website](https://www.nist.gov/el/intelligent-systems-division-73500/robotic-grasping-and-manipulation-assembly/assembly). 

The transport tasks involve picking the readily available objects, including a food serving tray with cups filled with foam cubes, cardboard boxes, and a tote bag, from a demarcated start region with the goal to move them to a target goal region and will be scored based on success rate and timing. A designated test area will be set up for the transport tasks alongside the Loco-Manipulation track. See the schedule below. 

Here is an overall RSVC score card to record the best performance of each team. 

## Planned Schedule
The benchmark artifacts will be mounted on tables directly next to the Loco-Manipulation competition to be used by participating teams throughout the duration of the conference. All trial attempts to be considered for stage recognition, with the exception for the transport tasks, must be completed and verified by a judge by Wednesday morning (12:00pm cutoff). The transport tasks will be demonstrated during designated time slot on Wednesday afternoon live in front of a jury. Top performing teams will be informed ahead of their stage appearance at the award ceremony on Wednesday at 17:30. See the [conference program](https://2026.ieee-humanoids.org/program-overview/) for the latest information.

## Participation
Participating teams need to bring their own robot or use a conference robot provided by the competitions sponsor, Ultimate Bots. Teams may register in advance or on-site at the conference by complete the [RSVC Team Participation Form](https://docs.google.com/forms/d/e/1FAIpQLSdpcd9YQFgipDDQ5jbZhp9j81TaBrushN6hIw2Kll1YkBkNKA/viewform?usp=publish-editor). 

## History of the Benchmark Artifacts
The Internet-connected electronic task boards debuted at the [Robothon Grand Challenge](https://automatica-munich.com/en/munich-i/robothon/) at the automatica trade show (2021-2025) as a distributed competition reference device. Additional appearances were made at the [Tactile Manipulation Hackathon](https://franka.de/news/franka-emika-hosts-hackathon-at-european-robotics-forum-2022) at the European Robotics Forum 2022 and at the [Manipulation Skill Versatility Challenge](https://sites.google.com/view/eurobin-msvc/) at the IROS 2024 in Abu Dhabi. The [Robothon Grand Challenge Archive](https://github.com/peterso/robothon-grand-challenge) holds a collection of community contributed robot solutions for each electronic task board design. 

## Additional Questions
If you have any additional questions about the competition, please contact the conference competition chairs at humanoids2026-cc@ieee.org.
