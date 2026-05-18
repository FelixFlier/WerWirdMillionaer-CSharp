# Who Wants to Be a Millionaire — C# Edition

> A Windows Forms desktop recreation of the classic "Who Wants to Be a Millionaire" TV quiz show. Built in C# with a clean three-layer architecture, lifelines, and progressive prize tiers from €100 to €1,000,000.

![C#](https://img.shields.io/badge/C%23-239120?logo=c-sharp&logoColor=white) ![.NET](https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white) ![License](https://img.shields.io/badge/license-MIT-green.svg)

## 🎯 What this is

A small but cleanly engineered desktop quiz game written in C#. Built as a learning project to practice three-layer architecture, unit testing, and Windows Forms UI development.

## ✨ Features

- Multiple-choice questions with four options
- 15-second timer per question
- Progressive prize ladder: €100 → €1,000,000
- Two lifelines:
  - **50:50** — removes two wrong answers
  - **Safe answer** — reveals the correct option
- Real-time visual feedback
- Cash-progress tracker

## 🏗 Architecture

Three-layer separation:

| Layer | Responsibility |
|---|---|
| **Presentation (UI)** | Windows Forms, real-time updates, user interaction |
| **Business logic** | Game flow, question handling, scoring, timer |
| **Data** | Question storage, game-state management, score tracking |

## 🛠 Tech stack

- **Language:** C#
- **UI:** Windows Forms
- **Testing:** xUnit (see `QuizManagerTests` project)
- **Build:** .NET Framework / .NET Core

## 🎮 How to play

1. Launch the game
2. Read each question carefully
3. Select an answer within the 15-second timer
4. Use lifelines strategically — each one is single-use
5. Climb the prize ladder
6. Try to reach the million

## 🚀 Setup

Clone, open the solution in Visual Studio, build, run.

```bash
git clone https://github.com/FelixFlier/WerWirdMillionaer-CSharp.git
```

Then open the `.sln` file in Visual Studio and press F5.

## 📝 License

MIT
