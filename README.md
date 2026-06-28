# Stronghold Strategy Game

## Overview

**Stronghold Strategy Game** is a console-based medieval kingdom simulation developed in **C++** using Object-Oriented Programming principles. Players manage the military, economy, politics, banking, population, and resources while making strategic decisions that determine the kingdom's success. The project demonstrates advanced C++ concepts through modular design and interconnected game mechanics.

---

## Features

- Kingdom management simulation
- Army recruitment and training
- Population and social class management
- Resource management
---

## Technologies Used

- C++
- Object-Oriented Programming (OOP)
- STL
- Templates
- File Handling
- Exception Handling
- Dynamic Memory Management
- Visual Studio

---

## Core Game Mechanics

### Main Menu

The application provides a menu-driven console interface that allows players to access all major game systems, including population management, military operations, banking, leadership, resources, and game state management.

<img width="887" height="955" alt="Main Menu" src="https://github.com/user-attachments/assets/efa4d2ef-41b6-403c-98ba-1c040f042ff9" />

---

### Population Management

The population system manages peasants, nobles, and other social classes. Population growth and stability directly influence taxation, workforce availability, and military recruitment.

<img width="910" height="939" alt="Population Management" src="https://github.com/user-attachments/assets/e117d238-a2cf-42c7-9fff-617c8457be3d" />

---

### Army Management

The military system supports soldier recruitment, training, salary management, and army status tracking. Military strength depends on available population and economic resources.

<img width="571" height="949" alt="Army Management" src="https://github.com/user-attachments/assets/9a650dd1-394b-4768-8ebb-dd30c2aa09bd" />

---

### Banking System

The banking module allows players to request and repay loans, perform financial audits, and manage the kingdom's treasury.

<img width="697" height="509" alt="Banking System" src="https://github.com/user-attachments/assets/250d4524-67c7-4ed6-850c-9e0d0c5d37ee" />

---

### Leadership & Politics

Players can hold elections, monitor leadership status, and respond to political instability, including attempted coups.

<img width="810" height="438" alt="Leadership System" src="https://github.com/user-attachments/assets/2c5a929f-bbcc-404d-a4fa-ef2312f56592" />

---

### Resource Management

The resource management system enables players to collect, consume, and trade essential resources required for the kingdom's development.

<img width="854" height="479" alt="Resource Management" src="https://github.com/user-attachments/assets/9cabc774-84c6-4e70-bc77-259c9594931d" />

---

### Random Events

Random events introduce unpredictable challenges such as disasters, economic crises, and political instability, making gameplay more strategic.

<img width="1049" height="445" alt="Random Events" src="https://github.com/user-attachments/assets/c19a9b95-ef40-4300-837a-bbfd83b4b378" />

---

### Save and Load Game

The game supports saving and loading progress using file handling, allowing players to continue their kingdom management at any time.

<img width="792" height="385" alt="Save and Load Game" src="https://github.com/user-attachments/assets/d36cfc17-ca40-4439-a656-4548d19c1c8f" />

---

## OOP Concepts Implemented

- Classes and Objects
- Inheritance
- Polymorphism
- Encapsulation
- Abstraction
- Templates
- Exception Handling
- Dynamic Memory Management
- File Handling

---

## Project Structure

```text
Stronghold/
│
├── main.cpp
├── Stronghold.h
├── Army.cpp
├── Bank.cpp
├── Economy.cpp
├── EventManager.cpp
├── Leadership.cpp
├── PopulationManager.cpp
├── ResourceManager.cpp
├── SocialClass.cpp
├── game_save.txt
├── score.txt
├── Stronghold2.sln
├── Stronghold2.vcxproj
└── x64/
```

---

## How to Run

1. Clone the repository.
2. Open `Stronghold2.sln` in Visual Studio.
3. Build the solution.
4. Run the project using **Ctrl + F5** or the **Run** button.
