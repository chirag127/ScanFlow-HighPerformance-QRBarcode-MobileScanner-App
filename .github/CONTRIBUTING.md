# Contributing to ScanFlow-HighPerformance-QRBarcode-MobileScanner-App

Thank you for considering contributing to `ScanFlow-HighPerformance-QRBarcode-MobileScanner-App`! We aim to maintain an elite, zero-defect, high-velocity, and future-proof codebase, reflecting the standards of the Apex Technical Authority.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please review the [CODE_OF_CONDUCT.md](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/blob/main/CODE_OF_CONDUCT.md) file for details on expected behavior.

## 2. Core Principles (Apex Standard)

*   **Zero-Defect:** Strive for the highest quality code with comprehensive testing.
*   **High-Velocity:** Efficient development cycles, clear communication, and robust CI/CD.
*   **Future-Proof:** Design for scalability, maintainability, and adaptability to evolving technologies.
*   **Professionalism:** Maintain a high standard of documentation, naming conventions, and architectural integrity.

## 3. Getting Started

### 3.1. Prerequisites

Before you can contribute, ensure you have the following installed:

*   **Node.js:** Version 20.x or higher (for React Native and Expo).
*   **npm or Yarn:** Package manager.
*   **Expo CLI:** `npm install -g expo-cli` or `yarn global add expo-cli`.
*   **Platform-Specific SDKs:** Xcode (for iOS development) and Android Studio (for Android development).

### 3.2. Fork and Clone

1.  Fork the repository: `https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/fork`
2.  Clone your forked repository:
    bash
    git clone https://github.com/YOUR_USERNAME/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App.git
    cd ScanFlow-HighPerformance-QRBarcode-MobileScanner-App
    

### 3.3. Install Dependencies

Install project dependencies using your preferred package manager:

bash
# Using npm
npm install

# Or using Yarn
yarn install


## 4. Development Workflow

### 4.1. Branching Strategy

*   Create a new branch for every feature or bug fix.
*   Branch names should follow a convention: `feature/your-feature-name`, `bugfix/issue-number-short-description`.
*   Keep branches short-lived.

### 4.2. Running the App

*   **Development Server:**
    bash
    # Using npm
npx expo start

# Or using Yarn
yarn start

    This will start the Metro bundler and provide QR codes to open the app on an emulator or physical device via the Expo Go app.

*   **Platform-Specific Builds (Optional, for advanced testing):
    bash
    # For Android
npx expo run:android

# For iOS
npx expo run:ios


### 4.3. Linting and Formatting

We use **Biome** for ultra-fast linting and formatting to ensure code consistency. Before committing, run:

bash
# Format code
npx @biomejs/biome format --write .

# Lint code
npx @biomejs/biome lint .


*   **Note:** If your IDE has Biome integration, it can format and lint on save.

### 4.4. Testing

Automated tests are crucial for maintaining a zero-defect standard. We use **Vitest** for unit and component testing and **Playwright** for end-to-end testing.

*   **Run Unit Tests:**
    bash
    npx vitest
    

*   **Run End-to-End Tests:**
    bash
    npx playwright test
    

## 5. Making a Contribution

### 5.1. Contribution Workflow

1.  **Start a Discussion:** For significant changes, please open an issue or a discussion first to explain your proposal and get feedback.
2.  **Branch:** Create a new branch for your changes (see Section 4.1).
3.  **Code:** Implement your changes, adhering to the project's coding standards and principles.
4.  **Test:** Write new tests or update existing ones to cover your changes. Ensure all tests pass.
5.  **Lint & Format:** Run the linters and formatters (see Section 4.3).
6.  **Commit:** Write clear, concise commit messages. Follow conventional commit messages if possible.
7.  **Push:** Push your branch to your fork: `git push origin your-branch-name`.
8.  **Pull Request (PR):** Open a Pull Request against the `main` branch of the original repository (`chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App`).
    *   Provide a clear description of your changes.
    *   Reference any related issues.

### 5.2. Pull Request Guidelines

*   **Single Responsibility:** PRs should ideally focus on a single feature or bug fix.
*   **Clear Title and Description:** Explain *what* the PR does and *why*.
*   **Link Issues:** Use keywords like `Closes #123` to automatically close issues.
*   **Self-Review:** Before submitting, review your own code and the changes in the PR.

## 6. Architectural Decisions & Guidelines

This project follows the **Apex Technical Authority's** architectural standards for mobile applications, emphasizing performance, scalability, and maintainability.

*   **Framework:** React Native with Expo.
*   **Language:** TypeScript (with strict typing enabled).
*   **Styling:** Tailwind CSS v4 (or equivalent utility-first CSS framework).
*   **State Management:** Utilize React Context API or a lightweight library like Zustand for efficient state management.
*   **Architecture:** Feature-Sliced Design (FSD) principles are encouraged for modularity and separation of concerns.
*   **Performance:** Prioritize efficient rendering, optimized image loading, and native module integration where performance is critical (e.g., for the scanner).
*   **Computer Vision:** Leverage optimized libraries like `react-native-vision-camera` or Expo's barcode scanning capabilities, ensuring minimal overhead.

Refer to the [AGENTS.md](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/blob/main/AGENTS.md) file for detailed AI agent directives and operational standards.

## 7. Reporting Issues

If you find a bug or have a feature request, please use the provided issue templates:

*   **Bug Report:** [New Bug Report](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/issues/new?template=bug_report.md)
*   **Feature Request:** [New Feature Request](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/issues/new?template=feature_request.md)

Provide as much detail as possible, including steps to reproduce the issue, environment details, and screenshots/recordings if applicable.

## 8. Community & Support

Join our community to discuss, ask questions, and share your ideas.

*   **GitHub Discussions:** [Discussions](https://github.com/chirag127/ScanFlow-HighPerformance-QRBarcode-MobileScanner-App/discussions)

We appreciate your contributions to making `ScanFlow-HighPerformance-QRBarcode-MobileScanner-App` an elite and reliable mobile scanning solution!
