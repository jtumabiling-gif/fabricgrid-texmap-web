# fabricgrid-texmap-web
For Part B: Midterm Exam

A. Branching Strategy (Feature Branch Workflow)
The repository will strictly follow a structured branching model to protect the production code and organize development efforts.

main branch: The production-ready state of the application. No direct commits are allowed here.

develop branch: The active integration branch where all completed features are merged before final testing.

feature/<feature-name>: Created from develop for new features (e.g., feature/map-ui, feature/booking-system).

bugfix/<issue-name>: Created for resolving specific errors or bugs (e.g., bugfix/login-crash).


B. Commit Message Strategy (Conventional Commits)
To maintain a clean and readable development history, all team members will use the Standard Conventional Commits format (type: description).

feat: For introducing a new feature (e.g., feat: integrate Google Maps for shop locations).

fix: For bug fixes (e.g., fix: resolve crash on payment screen).

docs: For documentation updates (e.g., docs: update README with setup instructions).

refactor: For code changes that neither fix a bug nor add a feature.

ui: For user interface and styling updates.


C. Team Collaboration & Pull Request (PR) Workflow

No Direct Merges: Developers must push their feature branches to GitHub and open a Pull Request (PR) against the develop branch.

Code Review: Every PR requires at least one peer review from a team member before it can be merged.

Meaningful PRs: Each Pull Request must include a clear description of what was added, changed, or fixed, along with screenshots if the UI was modified.
