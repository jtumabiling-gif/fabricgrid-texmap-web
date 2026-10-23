## Version Control & Collaboration Strategy

To ensure a smooth, collaborative development process for the **FabricGrid: TexMap** application, the team follows a structured version control and documentation strategy.

---

### A. Branching Strategy (Feature Branch Workflow)
The repository strictly follows a structured branching model to protect production code and organize development efforts:

*   **`main`**: The production-ready state of the application. **No direct commits are allowed here.**
*   **`develop`**: The active integration branch where all completed features are merged before final testing.
*   **`feature/<feature-name>`**: Created from `develop` for new features.
    *   *Examples:* `feature/map-ui`, `feature/booking-system`
*   **`bugfix/<issue-name>`**: Created for resolving specific errors or bugs.
    *   *Examples:* `bugfix/login-crash`

---

### B. Commit Message Strategy (Conventional Commits)
To maintain a clean and readable development history, all team members must follow the **Standard Conventional Commits** format (`type: description`):

*   `feat`: Introducing a new feature
    *   *Example:* `feat: integrate Google Maps for shop locations`
*   `fix`: Resolving a bug
    *   *Example:* `fix: resolve crash on payment screen`
*   `docs`: Updating documentation
    *   *Example:* `docs: update README with setup instructions`
*   `refactor`: Code restructuring that neither fixes a bug nor adds a feature
*   `ui`: User interface and styling updates

---

### C. Team Collaboration & Pull Request (PR) Workflow

*   **No Direct Merges:** Developers must push their feature branches to GitHub and open a Pull Request (PR) targeted at the `develop` branch.
*   **Code Review:** Every PR requires at least one peer review from a team member before it can be merged.
*   **Meaningful PRs:** Each Pull Request must include a clear description detailing what was added, changed, or fixed, along with screenshots if UI updates were made.
