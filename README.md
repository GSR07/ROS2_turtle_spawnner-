# 🐢 Turtlesim Bot in ROS 2 – Exploring Robotics with Python 🤖

Welcome to the **Turtlesim Bot ROS 2** project! This is a hands-on demonstration of robotics development using **Robot Operating System 2 (ROS 2)** and the **Turtlesim simulator**, designed to reinforce core ROS concepts through practical coding in Python.

[![Watch the Demo](https://img.youtube.com/vi/4x6qxieF2jQ/0.jpg)](https://youtu.be/4x6qxieF2jQ)

---

## 📌 Overview

This project was developed to revisit and apply key ROS 2 concepts such as:

- 🔹 **Publishers** – Commanding movement
- 🔹 **Subscribers** – Monitoring the turtle’s pose
- 🔹 **Services & Clients** – Enabling reset and teleportation
- 🔹 **Topics** – Inter-node communication
- 🔹 **Nodes** – Modular functional components

It’s an ideal starting point for those transitioning from ROS basics to structured ROS 2 development.

---

## 🎯 Key Learnings

- Refreshed and applied theoretical knowledge of ROS 2
- Designed custom ROS 2 nodes in Python
- Implemented **publisher-subscriber** and **client-service** models
- Gained hands-on experience with **message exchange via topics**
- Strengthened understanding of **robotic software architecture**

---

## 🧠 Concepts Covered

| ROS Concept   | Implementation |
|---------------|----------------|
| Publisher     | Sends velocity commands to move turtle (`/turtle1/cmd_vel`) |
| Subscriber    | Listens to turtle’s pose on `/turtle1/pose` |
| Service/Client| Uses `/clear` and `/teleport_absolute` |
| Topics        | Communicates between controller and turtle |
| Nodes         | Divides logic into clean, manageable components |

---

## 📁 Project Structure

```
turtle_catch_all/
├── resource/
│ └── turtle_catch_all
├── test/
│ ├── test_copyright.py
│ ├── test_flake8.py
│ ├── test_pep257.py
├── turtle_catch_all/
│ ├── init.py
│ ├── turtle_controller.py
│ ├── turtle_spawner.py
├── README.md
├── package.xml
├── setup.cfg
├── setup.py
```




---

## 🛠️ Requirements

- ROS 2 Humble (or newer)
- Python 3.8+
- `turtlesim` package installed

