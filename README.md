# Project Name

A brief description of what this project does and who it's for.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

Describe how to install dependencies, using your stack’s tools (e.g., `pip install -r requirements.txt` or `npm install`).

## Usage

Examples of how to use the project. Provide basic usage commands or code examples.

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.


## Project Resources

- [Pull Request Template](.github/PULL_REQUEST_TEMPLATE.md)
- **Issue Templates:**
  - [Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)
  - [Feature Request](.github/ISSUE_TEMPLATE/feature_request.md)

---

## License

Distributed under the [MIT License](LICENSE).

## Contact

Your Name — [your.email@example.com](mailto:your.email@example.com)

## Best Practices
> **Note:**  
> This "Best Practices" section is intended as internal team guidance. There is no need to include this section in your public `README.md` on GitHub.
### 1. Naming Conventions

- **Project Name:**  
  Use lowercase letters, with words separated by hyphens for readability.  
  Format: `projectname-subname`  
  **Examples:**  
  - `data-collector`
  - `image-processor`
  - `drone-monitoring-tool`

- **Folders & Files:**  
  - Use lowercase letters and hyphens or underscores.  
    E.g., `data_processing/`, `model-evaluation/`, `main.py`, `utils.js`

- **Variables (in code):**  
  - Use `snake_case` for Python and `camelCase` for JavaScript/TypeScript.  
    E.g., `image_path`, `userData`

- **Branches:**  
  - Use a consistent pattern:  
    - `feature/short-description`
    - `bugfix/short-description`
    - `hotfix/short-description`
    - `docs/short-description`
  - Examples:  
    - `feature/login-authentication`
    - `bugfix/image-upload`

---

### 2. Commit Messages

- **Format:**  

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
- `feat: add user login page`
- `fix: resolve crash on empty data input`
- `docs: update contributing guidelines`

- **Best Practices:**
- Use the imperative mood ("add", not "added" or "adds").
- Reference issues or pull requests when relevant (`fixes #42`).
- Write descriptive, meaningful summaries.

---

### 3. Commit Frequency

- Commit often, with **small, focused commits**.  
- Each commit should represent a single logical change.  
- Avoid large commits that mix multiple unrelated changes.

---

### 4. Pull Requests

- Create pull requests (PRs) for merging changes into `main` or `develop` branches.
- Fill out the PR template with clear explanations.
- Ensure your branch is up-to-date with the target branch before opening a PR.
- Request reviews from relevant team members.

---

### 5. Other Important Practices

- **Code Style:**  
- Follow the language/framework’s style guide. Use formatting tools (e.g., `black` for Python, `prettier` for JavaScript).

- **Documentation:**  
- Document all public classes, functions, and modules.
- Update documentation when you make changes to code behavior.

- **Testing:**  
- Write tests for all new features and bug fixes.
- Ensure tests pass before pushing or opening PRs.

- **Issues:**  
- Use clear, descriptive titles and detailed descriptions when opening issues.
- Apply appropriate labels and assignees.

---
### 6. Task & Workflow Management

- **Use GitHub Projects (Kanban):**  
  Organize your work using GitHub Projects’ Kanban board template:
  - Create a **Project Board** for your repository or organization.
  - Use columns such as **To do**, **In progress**, and **Done** to visually track the status of issues and pull requests.
  - Link issues and pull requests to cards on the board for clear traceability.
  - Update the board regularly as work progresses to keep the team aligned.
  - Prioritize and assign tasks, set deadlines, and use labels for effective project tracking.

  **Resources:**
  - [GitHub Projects documentation](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/about-project-boards)
  - [Set up a Kanban project board on GitHub](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/managing-project-boards/creating-a-project-board)

#### Summary Table

| Item            | Format/Best Practice                         |
|-----------------|---------------------------------------------|
| Project Name    | `lowercase-with-hyphens`                    |
| Branch Name     | `type/short-description`                    |
| Commit Message  | `[type]: short description` (imperative)    |
| Commit Size     | Small, focused, logical changes             |
| Documentation   | Update/readme, code comments, doc files     |
| Testing         | Add/maintain automated tests                |
| Task Management | Use GitHub Projects Kanban board for task tracking    |
---