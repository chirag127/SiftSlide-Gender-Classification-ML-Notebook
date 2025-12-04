# Contributing to SiftSlide-Gender-Classification-ML-Notebook

Thank you for considering contributing to `SiftSlide-Gender-Classification-ML-Notebook`! We welcome all contributions, from code improvements to documentation updates and issue reporting.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please read the full [CODE_OF_CONDUCT.md](https://github.com/chirag127/SiftSlide-Gender-Classification-ML-Notebook/blob/main/CODE_OF_CONDUCT.md) to understand what is expected of you and what is expected of the community.

## 2. How to Contribute

### 2.1 Reporting Bugs

If you find a bug, please submit an issue using the **Bug Report** template. Be sure to include:

*   A clear and concise title.
*   A detailed description of the bug.
*   Steps to reproduce the bug.
*   Any relevant error messages or logs.
*   The environment in which the bug occurred (e.g., Python version, OS).

### 2.2 Feature Requests

If you have an idea for a new feature or an improvement, please submit an issue using the **Feature Request** template.

### 2.3 Submitting Changes (Pull Requests)

We accept contributions via pull requests. Please follow these steps:

1.  **Fork the repository:** Click the "Fork" button on the top right of the GitHub page.
2.  **Clone your fork:**
    bash
    git clone https://github.com/chirag127/SiftSlide-Gender-Classification-ML-Notebook.git
    cd SiftSlide-Gender-Classification-ML-Notebook
    
3.  **Create a new branch:** Use a descriptive name for your branch.
    bash
    git checkout -b feature/your-new-feature
    # or for a bug fix:
    git checkout -b fix/bug-description
    
4.  **Make your changes:** Implement your feature or fix the bug.
5.  **Install dependencies and development tools:**
    bash
    # Assuming uv is installed and configured as per AGENTS.md
    uv pip install -r requirements-dev.txt
    
6.  **Run linters and formatters:** Ensure your code adheres to our standards.
    bash
    # Assuming ruff is configured as per AGENTS.md
    ruff check .
    ruff format .
    
7.  **Run tests:** Ensure all tests pass.
    bash
    # Assuming pytest is configured as per AGENTS.md
    pytest
    
8.  **Commit your changes:**
    bash
    git add .
    git commit -m "feat: Add awesome new feature"
    # or for a fix:
    git commit -m "fix: Resolve critical bug in classification"
    
9.  **Push to your fork:**
    bash
    git push origin feature/your-new-feature
    
10. **Open a Pull Request:** Go to the original repository (`chirag127/SiftSlide-Gender-Classification-ML-Notebook`) and click "New Pull Request". Compare your branch to `main` and describe your changes.

## 3. Development Guidelines (Apex Standards - Late 2025)

This project follows the **Apex Technical Authority** standards, emphasizing professionalism, efficiency, and future-proofing.

*   **Language:** Python 3.10+.
*   **Package Management:** `uv`.
*   **Linting & Formatting:** `Ruff`.
*   **Testing:** `Pytest`.
*   **Architecture:** Modular Monolith.
*   **AI Integration:** While this notebook is primarily for exploration, any new code contributions should consider modularity and testability, aligning with broader project architectural principles.

### 3.1 Testing

All code contributions must include relevant tests. Ensure tests are:

*   **Comprehensive:** Covering edge cases and typical scenarios.
*   **Fast:** To maintain high-velocity development.
*   **Readable:** Well-structured and easy to understand.

Run tests using `pytest`.

### 3.2 Linting and Formatting

Code must be linted and formatted using `Ruff`. Run these commands before committing:

bash
ruff check .
ruff format .


## 4. Pull Request Process

*   **PR Title:** Follow conventional commits (e.g., `feat:`, `fix:`, `docs:`, `refactor:`).
*   **PR Description:** Clearly explain the changes, the problem they solve, and how to test them. Reference any related issues.
*   **CI/CD:** Ensure the GitHub Actions workflow passes successfully.

## 5. Questions?

If you have any questions or need clarification, please don't hesitate to open an issue.

---
