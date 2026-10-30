# 🛡️ SeniorShield

> A simple, user-friendly mobile app that helps older adults protect themselves against digital scams, phishing attacks, and online privacy risks.

**Course project:** Cybersecurity, EUE (Foundation Year)  
**Project type:** Team project with a rotating **Project Manager** role in each phase  
**Status:** Phase 1 (Proposal) → Phase 2 (Plan, Execute and Test App) → Phase 3 (Final Presentation and Reflection)

---

## 📖 Table of Contents

- [Project Overview](#️-project-overview)
- [Target Users and Real Client](#-target-users-and-real-client)
- [The Problem and the Gap](#-the-problem-and-the-gap)
- [Key App Features](#-key-app-features)
- [Why SeniorShield?](#-why-seniorshield)
- [Phase-by-Phase Roadmap](#️-phase-by-phase-roadmap)
- [Tech Stack](#-tech-stack)
- [Repository Structure](#-repository-structure)
- [Building the LaTeX Reports](#️-building-the-latex-reports)
- [Running the App](#-running-the-app)
- [User Testing and Acceptance](#-user-testing-and-acceptance)
- [Team](#-team)
- [License](#-license)

---

## 🛡️ Project Overview

**SeniorShield** is a simplified, user-friendly mobile application designed to help **older adults** protect themselves against **digital scams**, **phishing attacks**, and **online privacy risks**.

Instead of technical jargon, SeniorShield uses clear visuals, high-contrast screens, and short step-by-step guidance. This helps seniors **recognise** threats, **respond** quickly when something goes wrong, and **secure** their devices.

## 👵 Target Users and Real Client

| | |
|---|---|
| **Target audience** | Older adults (seniors) and elderly people who are not comfortable with technology |
| **Real users / client** | A group of senior relatives or community members who will **confirm the initial need** in Phase 1 and **test the completed app** in Phase 2 |

## ❗ The Problem and the Gap

### The Problem
Seniors are frequent targets of:
- 📞 **Scam calls**
- 💬 **Phishing text messages (SMS)**
- 📧 **Fraudulent emails**

This is mainly due to **low digital literacy** and limited experience with recognising online threats.

### The Gap in Existing Solutions
Current cyber-safety apps and security guides are:
- **Too technical** and full of jargon
- Designed for **IT professionals** rather than elderly users
- Not built with accessibility (large text, high contrast, simple navigation) in mind

**SeniorShield fills this gap** by offering cybersecurity guidance designed specifically for seniors.

## ✨ Key App Features

These features form the **Phase 2 deliverable**:

| Feature | Description |
|---|---|
| 🧩 **Interactive Scam Spotter Quiz** | Visual, high-contrast scenarios that show real examples of **scam texts vs. safe texts**, so users learn to spot the warning signs. |
| 🆘 **Emergency Scam Helper** | A simple **two-tap guide** on what to do if the user thinks they clicked a bad link or shared private information. |
| ✅ **Device Security Checklist** | Step-by-step guidance for setting up **passcodes**, **screen locks**, and **basic privacy settings**. |
| 📊 **Simple Security Score** | A clear, visual indicator of the user's **device security habits** (often called "device hygiene"). |

**Design principles:** large text, high contrast, minimal steps, plain language, and no technical jargon.

## 🏆 Why SeniorShield?

In Phase 1 the team evaluated **three candidate ideas** and chose SeniorShield using weighted decision scoring:

| Criterion   | Weight |
|-------------|:------:|
| User Need   | 30%    |
| Feasibility | 25%    |
| Gap Left    | 20%    |
| Mobile Fit  | 15%    |
| Risk        | 10%    |
| **Total**   | **100%** |

### Why this idea helps the team succeed

- **⚙️ High feasibility:** The app focuses on **UI screens**, **data stored on the phone**, and **simple interactive logic**. This makes it manageable for foundation-year students to build within **6 weeks**.
- **🧪 Easy user testing:** Getting feedback from older family members or relatives is straightforward and produces clear qualitative results for the **Phase 2 sign-off**.
- **🌍 Strong social impact:** It makes a clear **business and social case**, which carries high value in academic scoring.

> ✏️ _TODO: Add the scores for each candidate idea:_

| Idea             | User Need | Feasibility | Gap Left | Mobile Fit | Risk | **Weighted Score** |
|------------------|:---------:|:-----------:|:--------:|:----------:|:----:|:------------------:|
| **SeniorShield** |     –     |      –      |    –     |     –      |  –   |       **–**        |
| Idea 2           |     –     |      –      |    –     |     –      |  –   |         –          |
| Idea 3           |     –     |      –      |    –     |     –      |  –   |         –          |

## 🗓️ Phase-by-Phase Roadmap

### 📌 Phase 1: Project Proposal and Presentation (Due Week 6)

**Deliverables**
- 6–8 page report written in **LaTeX** (submitted through GitHub)
- 10-minute team presentation

**Key content**
1. Overview of **3 candidate ideas** and why **SeniorShield** was chosen
2. Literature search on **elderly cyber vulnerability** and a **feature comparison matrix** of existing solutions
3. Weighted decision scoring: User Need (30%), Feasibility (25%), Gap Left (20%), Mobile Fit (15%), Risk (10%)
4. **Business case**, **SWOT analysis**, and **project brief**

### 📌 Phase 2: Plan, Execute and Test App (Due Week 12)

**Deliverables**
- 10–14 page **Management Plan**
- A working, tested **mobile app**
- **Closure and Acceptance** records

**Key content**
1. **Project Charter**, **WBS** (Work Breakdown Structure), **Gantt Chart**, and **Risk Management Plan**
2. Mobile app development in **Flutter / React Native / Android Studio**
3. **User testing with real seniors** and a formal **acceptance sign-off**

### 📌 Phase 3: Final Presentation and Reflection (Exam Weeks)

**Deliverables**
- Final team presentation
- Individual **500-word reflection** from each team member

**Key content**
1. Whole-project breakdown: **why** the project was chosen, **how** it ran, a **live app demo**, and **lessons learned**
2. Individual reflection on each member's role as **Project Manager** during their phase

## 🧰 Tech Stack

| Area               | Technology                                              |
|--------------------|---------------------------------------------------------|
| Mobile app         | _Flutter / React Native / Android Studio (Kotlin/Java)_ |
| Data storage       | Data stored on the phone (no backend server needed)     |
| Reports            | LaTeX                                                   |
| Project management | Project Charter, WBS, Gantt Chart, Risk Register        |
| Version control    | Git and GitHub                                          |

> ✏️ _TODO: Keep only the mobile framework your team chooses._

## 📁 Repository Structure

> ✏️ _Suggested layout. Update it to match your actual files._

```text
MyFirstDarApp/
├── phase1-proposal/
│   ├── report/             # LaTeX source for the 6–8 page proposal
│   └── presentation/       # Slides for the 10-minute presentation
├── phase2-management/
│   ├── report/             # LaTeX source for the 10–14 page Management Plan
│   ├── charter/            # Project Charter
│   ├── wbs/                # Work Breakdown Structure
│   ├── gantt/              # Gantt Chart
│   ├── risk/               # Risk Management Plan / Risk Register
│   └── closure/            # Closure and Acceptance records, sign-off forms
├── phase3-final/
│   ├── presentation/       # Final team presentation
│   └── reflections/        # Individual 500-word reflections
├── app/                    # SeniorShield mobile app source code
├── testing/                # User-testing scripts, consent forms, results
└── README.md
```

## 🛠️ Building the LaTeX Reports

**Option A: Overleaf**  
Upload a `report/` folder to [Overleaf](https://www.overleaf.com/) and compile `main.tex`.

**Option B: Local build** (requires a TeX distribution such as [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/))

```bash
cd phase1-proposal/report    # or phase2-management/report
latexmk -pdf main.tex
```

The compiled PDF is created as `main.pdf` in the same folder.

## 📱 Running the App

> ✏️ _Keep only the section for the framework you use._

**Flutter**
```bash
cd app
flutter pub get
flutter run
```

**React Native**
```bash
cd app
npm install
npx react-native run-android
```

**Android Studio (native)**  
Open the `app/` folder in Android Studio, let Gradle sync, then click **Run ▶** on an emulator or a connected device.

## 🧪 User Testing and Acceptance

SeniorShield will be tested with **real senior users**, such as older family members, relatives, or community members, to check usability, accessibility, and how useful each feature is.

- **Participants:** _number and age range of testers_
- **Method:** testers complete tasks with each feature (Scam Spotter Quiz, Emergency Scam Helper, Security Checklist, Security Score) while the team observes, then answer a short feedback questionnaire
- **Metrics:** _for example, task success rate, time on task, ease-of-use rating, quiz score improvement_
- **Ethics:** informed consent is collected from every participant, and no personal data is stored beyond what the study needs
- **Outcome:** a formal **acceptance sign-off** from the real users

Results and sign-off forms are stored in `testing/` and `phase2-management/closure/`.

## 👥 Team

| Name        | Phase as Project Manager | Main Responsibilities | GitHub      |
|-------------|:------------------------:|-----------------------|-------------|
| _Your Name_ | _Phase 1 / 2 / 3_        | _e.g., Research and Report_ | _@username_ |
| _Member 2_  | _Phase 1 / 2 / 3_        | _e.g., App Development_     | _@username_ |
| _Member 3_  | _Phase 1 / 2 / 3_        | _e.g., Testing and Presentation_ | _@username_ |

**Supervisor:** _Dr. / Eng. Name_

## 📄 License

This project was created for academic purposes as part of a cybersecurity course at EUE.
> ✏️ _TODO: Add a license (for example, MIT) if you plan to make the project public._
