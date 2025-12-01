# ScanFlow-Mobile-Scanner-Utility

![Build Status](https://img.shields.io/github/actions/workflow/user/your-username/your-repo/main.yml?label=Build&logo=github)
![Code Coverage](https://img.shields.io/codecov/c/github/your-username/your-repo?label=Coverage&logo=codecov)
![TypeScript Version](https://img.shields.io/badge/TypeScript-6.x-blue?logo=typescript)
![Vite Version](https://img.shields.io/badge/Vite-7.x-yellow?logo=vite)
![Biome Version](https://img.shields.io/badge/Biome-latest-brightgreen?logo=biome)
![License](https://img.shields.io/github/license/your-username/your-repo?label=License&logo=github)
![GitHub Stars](https://img.shields.io/github/stars/your-username/your-repo?style=social&label=Star%20⭐)

## BLUF
ScanFlow is an elite, high-performance, cross-platform mobile application engineered with React Native and Expo, offering rapid scanning and precise decoding of QR codes and diverse barcode formats, optimized for superior efficiency and an intuitive user experience.

## Architecture Overview

```ascii
. 
├── src/
│   ├── assets/
│   ├── components/
│   ├── features/
│   │   ├── scanner/
│   │   │   ├── components/
│   │   │   ├── ui/
│   │   │   └── index.ts
│   │   └── ...
│   ├── navigation/
│   ├── providers/
│   ├── screens/
│   ├── services/
│   ├── styles/
│   ├── utils/
│   └── index.tsx
├── tests/
│   ├── mocks/
│   └── ...
├── .github/
│   ├── workflows/
│   │   └── ci.yml
│   ├── CODEOWNERS
│   └── ...
├── .vscode/
├── app.json
├── biome.json
├── index.js
├── LICENSE
├── package.json
├── tsconfig.json
└── vite.config.ts
```

## Table of Contents

* [Features](#features)
* [Tech Stack](#tech-stack)
* [Getting Started](#getting-started)
* [Development Scripts](#development-scripts)
* [Contribution Guidelines](#contribution-guidelines)
* [License](#license)
* [AI Agent Directives](#ai-agent-directives)

## Features

* **High-Performance Scanning:** Leverages native device capabilities for rapid QR and barcode detection.
* **Cross-Platform Compatibility:** Built with React Native and Expo for seamless iOS and Android deployment.
* **Intuitive User Experience:** Clean, modern UI designed for optimal usability and efficiency.
* **Diverse Format Support:** Decodes a wide array of standard barcode symbologies.
* **Optimized Efficiency:** Engineered for minimal resource consumption and maximum speed.

## Tech Stack

* **Language:** TypeScript 6.x
* **Framework:** React Native (Expo)
* **Bundler:** Vite 7.x
* **Styling:** TailwindCSS (via native configuration)
* **Linting/Formatting:** Biome
* **Testing:** Vitest (Unit), Playwright (E2E - future integration)
* **State Management:** Signals (Standardized)
* **Architecture:** Feature-Sliced Design (FSD) Principles

## Getting Started

### Prerequisites

* Node.js (v20 LTS or later)
* npm or Yarn package manager
* Expo CLI

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/your-repo.git
    cd your-repo
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    # or
    yarn install
    ```

### Running the Application

*   **Start the Expo development server:**
    ```bash
    npx expo start
    ```

    This will launch the Expo Go app on your emulator/device or provide a QR code to scan with your physical device.

## Development Scripts

| Script        | Description                                   |
| ------------- | --------------------------------------------- |
| `npm run dev` | Starts the Expo development server.           |
| `npm run lint`| Runs Biome to check and format code.        |
| `npm run test`| Executes unit tests with Vitest.              |
| `npm run build`| Creates a production build (e.g., `.ipa`, `.apk`). |

## Contribution Guidelines

See [CONTRIBUTING.md](./.github/CONTRIBUTING.md) for details on how to contribute.

## License

This project is licensed under the CC BY-NC license - see the [LICENSE](LICENSE) file for details.

<details>
<summary>🤖 AI Agent Directives</summary>

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** Senior Principal Software Architect, Master Technical Copywriter.
**Experience:** 40+ years.
**Standards:** FAANG-level, "Managing the Unmanageable."
**Current Date:** December 2025.
**Output:** EXECUTION-ONLY. Zero plans, only code, docs, fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. AI ORCHESTRATION & GEMINI PROTOCOL (LATE 2025)
**Mandatory Models:**
*   `gemini-3-pro-preview` (Tier 1)
*   `gemini-2.5-pro` (Tier 2)
*   `gemini-2.5-flash` (Tier 3)
*   `gemini-2.5-flash-lite-preview-09-2025` (Tier 4)
*   `gemini-2.0-flash` (Tier 5)
*   `gemini-2.5-flash-native-audio-preview-09-2025` (Tier 5)
**Fallback Cascade:** Always try higher tiers first. Trigger Cool-Off on 429/500.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
*   **Project Type:** Mobile App (React Native/Expo)
*   **Apex Toolchain Applied:**
    *   **Language:** TypeScript 6.x (Strict)
    *   **Framework:** React Native (Expo)
    *   **Bundler:** Vite 7.x
    *   **State:** Signals
    *   **Lint/Test:** Biome + Vitest + Playwright (E2E)

---

## 4. RECURSIVE PERFECTION LOOP (THE "ZERO-ERROR" MANDATE)
**Process:** Analyze -> Fix -> Lint/Format (`biome check --apply`) -> Test (`vitest`) -> **DECISION GATE**. Repeat until clean.
**Constraint:** Do not stop until the build is perfectly clean.

---

## 5. CORE ARCHITECTURAL PRINCIPLES
*   **SOLID MANDATE:** SRP, OCP, LSP, ISP, DIP.
*   **MODULARITY:** Feature-First Structure (`features/scanner`).
*   **CQS:** Methods are Commands (Action) or Queries (Data).
*   **12-Factor App:** Config in environment.

---

## 6. CODE HYGIENE & STANDARDS
*   **SEMANTIC NAMING:** Descriptive verbs, `camelCase` (JS/TS).
*   **CLEAN CODE:** Verticality, Guard Clauses, DRY, KISS. Zero comments unless explaining "Why."

---

## 7. RELIABILITY, SECURITY & SUSTAINABILITY
*   **DEVSECOPS:** Sanitize inputs (OWASP 2025), SBOMs, Fail Fast, Encryption.
*   **EXCEPTION HANDLING:** Never crash, `try-catch-finally`, retry logic.
*   **GREEN SOFTWARE:** Lightest tool, efficient loops, lazy loading.

---

## 8. COMPREHENSIVE TESTING STRATEGY
*   **FOLDER SEPARATION:** `tests/` only.
*   **TESTING PYRAMID (F.I.R.S.T.):** Fast, Isolated, Repeatable.
*   **COVERAGE MANDATE:** 1:1 file mapping, test success/failure/edge cases. Zero console errors.

---

## 9. UI/UX AESTHETIC SINGULARITY (2026 STANDARD)
*   **VISUAL LANGUAGE:** Liquid Glass + Neo-Brutalist + Material You 3.0. Fluid animations.
*   **PERFORMANCE UX:** INP < 200ms. Optimistic UI.
*   **INTERACTION DESIGN:** Hyper-personalization, Micro-interactions.
*   **HYPER-CONFIGURABILITY:** All features user-configurable.

---

## 10. DOCUMENTATION & VERSION CONTROL
*   **HERO-TIER README:** BLUF, Live Sync, Visuals, AI block, "Star ⭐ this Repo."
*   **ADVANCED GIT:** Context Archaeology, Conventional Commits, Semantic Versioning.

---

## 11. AUTOMATION SINGULARITY (GITHUB ACTIONS)
*   **Workflows:** Integrity (Lint+Test), Security (Audit+SBOM), Release (Versioning+Artifacts), Deps (Auto-merge).

---

## 12. THE ATOMIC EXECUTION CYCLE
**Process:** Audit -> Research -> Plan -> Act -> Automate -> Docs -> Verify -> **REITERATE** (if errors) -> Commit.
**Constraint:** Commit only when perfectly clean.

</details>
