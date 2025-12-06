# Contributing to UniversalSearch-Bulk-Term-Web-App

Thank you for considering contributing to `UniversalSearch-Bulk-Term-Web-App`! We welcome all contributions, from bug reports and feature requests to code contributions.

This project adheres to the Apex Technical Authority standards, ensuring high velocity, zero defects, and future-proof architecture.

## 1. Code of Conduct

This project adheres to a Contributor Covenant Code of Conduct. Please read the [CODE_OF_CONDUCT.md](https://github.com/chirag127/UniversalSearch-Bulk-Term-Web-App/blob/main/CODE_OF_CONDUCT.md) file for details.

## 2. How to Contribute

### 2.1 Reporting Bugs

We use GitHub Issues to track bugs. Please report any bugs you find using the provided `bug_report.md` template. Include as much detail as possible, such as:

*   A clear and concise description of the bug.
*   Steps to reproduce the bug.
*   The environment you are using (browser, OS, etc.).
*   Any relevant screenshots or console logs.

### 2.2 Suggesting Enhancements

You can suggest new features or improvements by opening an issue and choosing the 'Enhancement' label. Please be descriptive about the proposed functionality and its benefits.

### 2.3 Pull Requests

We welcome pull requests! Follow these steps to submit a pull request:

1.  **Fork the repository:** Click the "Fork" button on the top right of the GitHub page.
2.  **Clone your fork:**
    bash
    git clone https://github.com/chirag127/UniversalSearch-Bulk-Term-Web-App
    cd UniversalSearch-Bulk-Term-Web-App
    
3.  **Set upstream remote:**
    bash
    git remote add upstream https://github.com/chirag127/UniversalSearch-Bulk-Term-Web-App
    
4.  **Create a new branch:** Always work on a new branch for your feature or fix.
    bash
    git checkout -b feature/your-feature-name
    
    or
    bash
    git checkout -b fix/your-bug-fix
    
5.  **Make your changes:** Add new features, fix bugs, and ensure your code adheres to the project's standards.
6.  **Test your changes:** Run the test suite to ensure everything is working as expected.
    bash
    # Commands will vary based on the project stack. Refer to README.md for setup.
    # Example for a JavaScript project:
    npm test
    
7.  **Lint and format your code:** Ensure code style consistency.
    bash
    # Example for a JavaScript project using Biome:
    npx @biomejs/biome format --write .
    npx @biomejs/biome lint --apply .
    
8.  **Commit your changes:** Write clear and descriptive commit messages.
    bash
    git commit -m "feat: Add new search engine integration"
    # or
    git commit -m "fix: Resolve issue with term appending"
    
9.  **Push to your fork:**
    bash
    git push origin feature/your-feature-name
    
10. **Open a Pull Request:** Go to your fork on GitHub and click the "Compare & pull request" button. Ensure the "base repository" is `chirag127/UniversalSearch-Bulk-Term-Web-App` and the "head repository" is your fork. Write a clear description of your changes.

### 2.4 Development Setup

Refer to the [README.md](https://github.com/chirag127/UniversalSearch-Bulk-Term-Web-App) for detailed instructions on setting up the development environment.

## 3. Architectural Principles

This project follows Apex's **Zero-Defect, High-Velocity, Future-Proof** philosophy. Contributions should align with:

*   **SOLID Principles:** Ensure single responsibility, open/closed, Liskov substitution, interface segregation, and dependency inversion.
*   **DRY (Don't Repeat Yourself):** Avoid redundant code.
*   **KISS (Keep It Simple, Stupid):** Favor simplicity where possible.
*   **YAGNI (You Ain't Gonna Need It):** Implement only what is necessary now.

## 4. Technology Stack

This project is a **Web Application**. As per Apex standards (Late 2025), the stack is expected to be:

*   **Language:** JavaScript (with potential for TypeScript).
*   **Build Tool:** Vite 7 (or similar modern bundler).
*   **Styling:** TailwindCSS v4 (or similar utility-first CSS framework).
*   **Framework:** React, Vue, or Svelte (as determined by project needs).
*   **Linting/Formatting:** Biome (for speed and comprehensive checks).
*   **Testing:** Vitest (for unit testing) and Playwright (for E2E testing).

Contributions should adhere to these technologies and best practices.

## 5. AI AGENT DIRECTIVES

This repository is managed and enhanced by AI agents according to the directives in [AGENTS.md](https://github.com/chirag127/UniversalSearch-Bulk-Term-Web-App/blob/main/AGENTS.md). Ensure your contributions are compatible with AI-driven development processes.

## 6. License

This project is licensed under the **CC BY-NC 4.0 License** - see the [LICENSE](https://github.com/chirag127/UniversalSearch-Bulk-Term-Web-App/blob/main/LICENSE) file for details.

--- 

By contributing, you agree that your contributions will be licensed under the project's license.
