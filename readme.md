# CS698 Final Project - Virtual Tennis Robot Simulation

This project is an Unreal Engine 5 project built mainly with Blueprints.  
It presents a virtual tennis training environment with a robot assistant that can serve, collect, and interact with tennis balls in a simulated court.

The project is developed as a Human-Robot Interaction course project. Instead of building a physical robot, this project uses a virtual environment to explore whether a robot assistant could improve the tennis training experience.

---

## Project Overview

The goal of this project is to create a virtual testbed for evaluating a tennis training robot concept.

In the simulation, the user can interact with a tennis court environment where a robot assistant is placed on the opposite side of the court. The robot is designed to support multiple behaviors, such as:

- Serving tennis balls
- Moving inside the court area
- Collecting tennis balls
- Switching between different working modes
- Interacting with the player through a simple control menu

This project focuses on the feasibility of testing robot-assisted tennis training in a virtual environment before building physical hardware.

---

## Main Features

- Unreal Engine 5 tennis court environment
- Blueprint-based robot logic
- Tennis ball spawning and launching system
- Basic tennis ball physics and collision behavior
- Player-controlled ball interaction
- Robot working mode switching
- UI menu for controlling robot behavior
- Modular robot blueprint structure
- Git LFS support for Unreal Engine assets

---

## Project Purpose

From a Human-Robot Interaction perspective, this project explores how a virtual robot assistant could support tennis practice.

The main research idea is:

> Can a robot assistant improve the training experience by reducing the player's need to manually collect balls and manage serving tasks?

The project uses Unreal Engine as a simulation platform to test this interaction concept. This allows the design to be evaluated in a virtual environment without the cost and limitations of building a real robot prototype.

---

## Requirements

To open and run this project, you need:

- Unreal Engine 5  
  - Please use the same UE version as the original project if possible.
- Git
- Git LFS

If the project is later converted to a C++ project, you may also need:

- Visual Studio 2022
- Desktop development with C++ workload
- Windows SDK

Currently, this project is mainly Blueprint-based.

---

## How to Clone and Set Up the Project

### 1. Install Git LFS

Before cloning the project, make sure Git LFS is installed.

```bash
git lfs install