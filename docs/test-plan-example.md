# 📋 Test Plan Example – Game QA Fundamentals

## 🎯 Objective
To verify the functionality, stability, and overall quality of the game’s core mechanics.  
This test plan outlines the **scope, approach, resources, and schedule** for testing.

---

## 🖥️ Scope
- **In Scope:**  
  - Core gameplay mechanics (movement, jumping, collisions)  
  - UI navigation (menus, settings)  
  - Scoring and progress system  

- **Out of Scope:**  
  - Online multiplayer features (not implemented in current build)  
  - Localization/translation testing  

---

## 🛠️ Test Environment
- Platform: Windows 10 (64-bit)  
- Build: v1.0.2  
- Hardware: Intel i5, 8GB RAM, NVIDIA GTX 1050  
- Tools:  
  - Manual testing checklists  
  - Bug reporting template (with **PAL rule** for titles)  
  - [Optional] Selenium/PyAutoGUI for automation  

---

## ✅ Test Approach
- **Manual Testing:**  
  Execute test cases covering movement, collisions, and scoring.  
  Use exploratory testing for edge cases.  

- **Bug Reporting:**  
  All bugs will follow the **PAL naming convention**:  
  - **P** = Problem  
  - **A** = Action  
  - **L** = Location  
  Example: *Character falls through floor – Jumping – Level 1 Left Edge*  

- **Automation (Future Scope):**  
  Automate menu navigation and repeated actions using Python.  

---

## 📌 Test Cases (Sample)
| ID      |
