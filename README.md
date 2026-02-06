# OOPS Banner App

## Overview
The OOPS Banner App is a console-based Java application developed to demonstrate the progressive application of Object-Oriented Programming (OOPS) principles through structured refactoring.

The application renders the word "OOPS" as an ASCII banner. Each use case (UC1 to UC8) improves the internal code structure while maintaining the same console output, ensuring a clear evolution from basic implementation to a modular and scalable design.

---

## Objectives
- Develop a pure console-based Java application
- Render an ASCII banner for the word "OOPS"
- Apply OOPS concepts incrementally
- Refactor the same codebase across multiple use cases
- Follow industry-standard GitFlow practices
- Maintain a clean and traceable commit history

---

## Technologies Used
- Java
- IntelliJ IDEA
- Git
- GitFlow
- GitHub

---

## Use Case Progression (UC1 to UC8)

The application is implemented sequentially. Each use case refactors the previous implementation.

| Use Case | Description |
|---------|-------------|
| UC1 | Basic console output |
| UC2 | Banner rendering logic |
| UC3 | String joining and formatting |
| UC4 | Array-based looping |
| UC5 | Helper methods |
| UC6 | Encapsulation of character patterns |
| UC7 | Abstraction and modular design |
| UC8 | Map-based scalable architecture |

Important: Use cases must be implemented strictly in order.

---

## GitFlow Process (Mandatory)

Each use case follows the same GitFlow workflow.

### Step A: Implement Code
- Write code inside OOPSBannerApp
- Complete the current use case logic
- Refactor existing code for the next use case

### Step B: GitFlow Commands
```bash
git flow init

git flow feature start UC1-printOOPS
git flow feature publish UC1-printOOPS
git flow feature finish UC1-printOOPS

git push origin develop
