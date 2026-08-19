# Introduction to Playwright - course🎭

Welcome to the beginner-friendly introduction repository for [Microsoft Playwright](https://playwright.dev/). This project serves as a starting point to learn modern end-to-end (E2E) web testing, browser automation, and reliable locator strategies.

## Content
* **Setup & Architecture:** Initializing Playwright and navigating its basic configurations.
* **Core Assertions:** Writing stable, auto-waiting test validations that minimize flakiness.
* **Locators API:** Finding web elements effectively using user-facing accessibility roles.
* **Basic Workflows:** Simulating user actions like filling forms, clicking buttons, and handling links.

## Prerequisites
Before running this project, ensure you have the following installed locally:
* [Node.js](https://nodejs.org) - v18 or higher
* [Visual Studio Code](https://visualstudio.com) -VScode or your prefered editor

## Getting Started

### 1. Clone the Repository into your laptop
```bash
git clone https://github.com/Alicade123/tau-intro2playwright.git
cd tau-intro2playwright
```

### 2. Install Project Dependencies
Run this command to download the node modules:
```bash
npm install
```

### 3. Install Playwright Browsers
Download the required browser binaries (Chromium, Firefox, WebKit):
```bash
npx playwright install
```

## Running the Tests

Execute the default end-to-end test suite using the terminal:
```bash
npx playwright test
```

### Helpful Test Commands
* _Run in UI Mode (Interactive):_ `npx playwright test --ui`
* _Run a Specific Test File:_ `npx playwright test tests/example.spec.ts`
* _Run in Headed Mode:_ `npx playwright test --headed`
* _View HTML Test Report:_ `npx playwright show-report`

## 📁 Repository Structure
```text
├── .github/workflows/   # Optional: GitHub Actions CI workflow config
├── tests/               # Folder containing all test specification files
│   └── example.spec.ts  # Introductory test script samples
├── playwright.config.ts # Core Playwright engine configuration
├── package.json         # Project manifests and external scripts
└── README.md            # Documentation guide
```

## 🤝 Contributing
*Contributions, issue reports, improvement suggestions, and feature pull requests are welcome!*
Feel free to [fork](https://github.com/Alicade123/tau-intro2playwright.git) the repository and practice your automated scripts.
