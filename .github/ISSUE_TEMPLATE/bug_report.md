---
name: Bug Report
about: Create a report to help us improve
title: "[BUG] Summarize the issue briefly"
labels: bug
assignees: ""

}

---

**To the Apex Technical Authority & Elite Architect:**

This template is designed to capture critical information for immediate, high-velocity issue resolution. Adherence to its structure ensures efficient debugging and aligns with the "Zero-Defect, High-Velocity, Future-Proof" philosophy.

**PLEASE NOTE:** All fields are mandatory for review. Incomplete reports will be returned for refinement.

## 1. EXECUTIVE SUMMARY (BLUF - Bottom Line Up Front)

**What is the observed behavior?**
(Provide a concise, 1-2 sentence summary of the bug's impact.)


## 2. REPRODUCIBILITY (The "ZERO-ERROR" Mandate)

**Steps to Reproduce:**

1.  **Environment:** (e.g., Device Model, OS Version, App Version, Browser, Node.js Version)
2.  **Action:** (Be precise. e.g., "Navigate to Screen X.")
3.  **Action:** (e.g., "Tap the 'Scan' button.")
4.  **Action:** (e.g., "Point the camera at a valid QR code.")
5.  **Observed Behavior:** (Describe EXACTLY what happened.)

**Expected Behavior:**
(Describe EXACTLY what should have happened.)

**Frequency:**
(e.g., Always, Sometimes (What are the conditions?), Rarely)


## 3. SYSTEM ANALYSIS (THE APEX STACK)**

*   **Project:** ScanFlow-Mobile-Scanner-Utility-React-Native
*   **Primary Language:** JavaScript (ESNext)
*   **Framework/Runtime:** React Native, Expo
*   **Apex Toolchain Applied:** (As per Project Context: JavaScript/React Native)
*   **Relevant Dependencies:** (List key libraries like `react-native-camera`, `expo-barcode-scanner`, etc.)


## 4. DIAGNOSTIC ARTIFACTS (CRITICAL DATA)**

*   **Console Logs:**
    ```
    // Paste relevant console output here. Ensure no sensitive data is exposed.
    // Use 'Show Advanced Error Details' if available.
    ```

*   **Error Messages:**
    (If any error messages appeared on screen or in logs, quote them verbatim.)

*   **Screenshots/Video:**
    (Attach visual evidence. If a video, provide a link.)

*   **Device State (if applicable):**
    (e.g., Battery Level, Network Type, Storage Available)


## 5. CONTEXTUAL INFORMATION (ARCHITECTURAL INTEGRITY)**

*   **Recent Changes:**
    (Were there any recent code deployments, dependency updates, or configuration changes that might correlate with this issue?)

*   **Impacted Feature(s):**
    (e.g., QR Code Scanning, Barcode Decoding, UI Rendering, Performance)

*   **Potential Root Cause (Hypothesis):**
    (If you have an educated guess, provide it here. This helps focus the investigation.)


## 6. AI AGENT DIRECTIVES (FOR META-ANALYSIS)

<details>
<summary>AI Agent Directives & Context</summary>

**SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)**

**Prime Directive:** Enforce FAANG-level standards and the wisdom of "Managing the Unmanageable." Build for the 2026 standard.

**Context-Aware Apex Tech Stacks (Late 2025 Standards):**
*   **SCENARIO A: WEB / APP / EXTENSION (TypeScript/JavaScript)**
    *   **Stack:** **TypeScript 6.x** / **JavaScript (ESNext)**, **Vite 7** (Rolldown), **Tauri v2.x** (Native), **WXT** (Extensions).
    *   **State:** **Signals** (Standardized).
    *   **Lint/Test:** **Biome** (Speed) + **Vitest** (Unit) + **Playwright** (E2E).
    *   **Mobile Context (React Native/Expo):** The project utilizes React Native and Expo. While Vitest is standard for unit testing, E2E testing would typically involve tools like Detox or Appium, and linting would align with JavaScript standards (e.g., ESLint configured for React Native or Biome if adopted).
*   **Core Architectural Principles:** SOLID, Modularity (Feature-First), CQS, 12-Factor App.
*   **Code Hygiene:** Semantic Naming, Clean Code Rules (Verticality, Guard Clauses, DRY, KISS, Zero Comments).
*   **Reliability/Security:** DevSecOps Protocol (Zero Trust, SBOMs, Fail Fast), Resilience, Encryption.
*   **Testing Strategy:** Folder Separation (`tests/`), Testing Pyramid (F.I.R.S.T.), Coverage Mandate (1:1 Mapping).
*   **UI/UX Aesthetic Singularity (2026 Standard):** Liquid Glass + Neo-Brutalist + Material You 3.0, Fluid Animations, INP Optimization, Hyper-Personalization, Hyper-Configurability.

**Agent's Verification Commands (Example):**
*   `npx expo lint` or `npx biome lint --apply`
*   `npx vitest run`
*   `npx playwright test`
*   (For React Native E2E): `detox test` or equivalent.

</details>
