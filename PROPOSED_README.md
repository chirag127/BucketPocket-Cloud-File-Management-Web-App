# BucketPocket: Secure Cloud File Management Web App

![BucketPocket Banner](https://raw.githubusercontent.com/chirag127/BucketPocket-Cloud-File-Management-Web-App/main/.github/assets/bucketpocket-banner.png)

[![Build Status](https://github.com/chirag127/BucketPocket-Cloud-File-Management-Web-App/actions/workflows/ci.yml/badge.svg)](https://github.com/chirag127/BucketPocket-Cloud-File-Management-Web-App/actions/workflows/ci.yml) [![Code Coverage](https://codecov.io/gh/chirag127/BucketPocket-Cloud-File-Management-Web-App/branch/main/graph/badge.svg)](https://codecov.io/gh/chirag127/BucketPocket-Cloud-File-Management-Web-App) [![Tech Stack](https://img.shields.io/badge/Stack-TS%20%7C%20React%20%7C%20Node%20%7C%20Vite%20%7C%20Tailwind-blueviolet?style=flat-square)](https://github.com/chirag127/BucketPocket-Cloud-File-Management-Web-App) [![Lint/Format](https://img.shields.io/badge/Lint/Format-Biome-informational?style=flat-square)](https://biomejs.dev/) [![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey?style=flat-square)](https://creativecommons.org/licenses/by-nc/4.0/) [![GitHub stars](https://img.shields.io/github/stars/chirag127/BucketPocket-Cloud-File-Management-Web-App?style=flat-square&color=yellow)](https://github.com/chirag127/BucketPocket-Cloud-File-Management-Web-App)


**Star ⭐ this Repo!**

BucketPocket is a cutting-edge web application designed for seamless and secure cloud file management, empowering users with intuitive tools for organization, sharing, and access to their digital assets from anywhere. Built with a modern TypeScript, React, and Node.js stack, it delivers a robust and highly performant experience for all your digital asset needs.

## 📋 Table of Contents

-   [Architecture](#architecture)
-   [Key Features](#key-features)
-   [Getting Started](#getting-started)
    -   [Prerequisites](#prerequisites)
    -   [Installation](#installation)
    -   [Running the Application](#running-the-application)
-   [Development Scripts](#development-scripts)
-   [AI Agent Directives](#ai-agent-directives)
-   [Contributing](#contributing)
-   [License](#license)
-   [Security](#security)
-   [Acknowledgements](#acknowledgements)

## 🏛️ Architecture

BucketPocket is meticulously structured using the **Feature-Sliced Design (FSD)** methodology. This robust architectural pattern ensures high modularity, scalability, and maintainability by organizing the codebase into distinct layers (App, Pages, Widgets, Features, Entities, Shared) and slices. This approach promotes clear separation of concerns, improves development velocity, and simplifies future expansions.

mermaid
graph TD
    A[App] --> P1(Pages)
    A --> W1(Widgets)
    A --> F1(Features)
    A --> E1(Entities)
    A --> S1(Shared)
    P1 --> W1
    P1 --> F1
    P1 --> E1
    W1 --> F1
    F1 --> E1
    E1 --> S1
    F1 --> S1
    W1 --> S1
    P1 --> S1
    subgraph FSD Layers
        direction LR
        S1_sub[Shared] --> E1_sub[Entities] --> F1_sub[Features] --> W1_sub[Widgets] --> P1_sub[Pages] --> A_sub[App]
    end
    style A fill:#f9f,stroke:#333,stroke-width:2px
    style P1 fill:#bbf,stroke:#333,stroke-width:2px
    style W1 fill:#bfb,stroke:#333,stroke-width:2px
    style F1 fill:#ffb,stroke:#333,stroke-width:2px
    style E1 fill:#fbb,stroke:#333,stroke-width:2px
    style S1 fill:#bbb,stroke:#333,stroke-width:2px
    linkStyle 0 stroke-width:2px,fill:none,stroke:black;
    linkStyle 1 stroke-width:2px,fill:none,stroke:black;
    linkStyle 2 stroke-width:2px,fill:none,stroke:black;
    linkStyle 3 stroke-width:2px,fill:none,stroke:black;
    linkStyle 4 stroke-width:2px,fill:none,stroke:black;
    linkStyle 5 stroke-width:2px,fill:none,stroke:black;
    linkStyle 6 stroke-width:2px,fill:none,stroke:black;
    linkStyle 7 stroke-width:2px,fill:none,stroke:black;
    linkStyle 8 stroke-width:2px,fill:none,stroke:black;
    linkStyle 9 stroke-width:2px,fill:none,stroke:black;
    linkStyle 10 stroke-width:2px,fill:none,stroke:black;


## ✨ Key Features

-   **Secure Cloud Storage:** Robust encryption and access controls to keep your files safe.
-   **Seamless File Sharing:** Effortlessly share files and folders with customizable permissions.
-   **Efficient Organization:** Intuitive interface with tagging, categorization, and powerful search capabilities.
-   **Real-time Synchronization:** Keep your files updated across all devices.
-   **Version Control:** Track changes and restore previous file versions.
-   **Cross-Platform Accessibility:** Access your files from any web-enabled device.

## 🚀 Getting Started

Follow these steps to get your local development environment up and running.

### Prerequisites

Ensure you have the following installed:

-   [Node.js](https://nodejs.org/) (LTS version recommended)
-   [npm](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/) or [uv](https://github.com/astral-sh/uv)
-   Git

### Installation

1.  **Clone the repository:**
    bash
    git clone https://github.com/chirag127/BucketPocket-Cloud-File-Management-Web-App.git
    cd BucketPocket-Cloud-File-Management-Web-App
    

2.  **Install dependencies:**
    bash
    # Using npm
    npm install

    # Or using Yarn
    # yarn install
    

### Running the Application

1.  **Start the development server:**
    bash
    npm run dev
    # Or yarn dev
    

2.  Open your browser and navigate to `http://localhost:5173` (or the port indicated in your console).

## 🛠️ Development Scripts

| Script          | Description                                         |
| :-------------- | :-------------------------------------------------- |
| `dev`           | Starts the development server with hot-reloading.   |
| `build`         | Compiles the project for production.                |
| `lint`          | Lints the codebase using Biome.                     |
| `format`        | Formats the codebase using Biome.                   |
| `test`          | Runs unit and integration tests with Vitest.        |
| `test:e2e`      | Runs end-to-end tests with Playwright.              |
| `preview`       | Serves the production build locally.                |

## 🤖 AI Agent Directives

<details>
<summary>Click to view AI Agent Directives</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

---

## 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs.
    *   **Research First:** Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

---

## 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** Detect the project type and apply the corresponding **Apex Toolchain**. This repository, `BucketPocket-Cloud-File-Management-Web-App`, is a TypeScript-based modern web application.

*   **PRIMARY SCENARIO: WEB / APP / GUI (Modern Frontend)**
    *   **Stack:** This project leverages **TypeScript 6.x (Strict)** for robust type safety, **React 19+** for a declarative UI, **Vite 7** for lightning-fast development, and **TailwindCSS v4** for utility-first styling. For potential desktop deployments, **Tauri v2.x** is integrated.
    *   **Architecture:** Adheres to the **Feature-Sliced Design (FSD)** pattern, ensuring modularity, scalability, and maintainability across features, entities, and shared layers.
    *   **Lint/Test:** Utilizes **Biome** for extremely fast linting and formatting, **Vitest** for efficient unit and integration testing, and **Playwright** for robust end-to-end browser automation and testing.
    *   **State Management:** Standardized on **React's Context API** and local state, augmented with **Signals** for global reactive state where appropriate, aligning with modern best practices.

*   **SECONDARY SCENARIO A: SYSTEMS / PERFORMANCE (Low Level) - *Not applicable for this project's primary function. Reference only for potential future performance-critical modules.***
    *   **Stack:** Rust (Cargo) or Go (Modules).
    *   **Lint:** Clippy / GolangCI-Lint.
    *   **Architecture:** Hexagonal Architecture (Ports & Adapters).

*   **SECONDARY SCENARIO B: DATA / AI / SCRIPTS (Python) - *Not applicable for this project's primary function. Reference only for potential future backend microservices or data processing.***
    *   **Stack:** uv (Manager), Ruff (Linter), Pytest (Test).
    *   **Architecture:** Modular Monolith or Microservices.
</details>

## 🤝 Contributing

We welcome contributions to BucketPocket! Please refer to our [Contributing Guidelines](.github/CONTRIBUTING.md) for details on how to get involved.

## 📜 License

This project is licensed under the [CC BY-NC 4.0 License](LICENSE).

## 🔒 Security

For information on security practices and how to report vulnerabilities, please see our [Security Policy](.github/SECURITY.md).

## 🙏 Acknowledgements

-   Inspired by the need for intuitive and secure personal cloud storage solutions.
-   Built with the power of open-source tools and frameworks.
