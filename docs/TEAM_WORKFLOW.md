# Team Workflow & Project Management Guidelines

## 1. Project Management Framework

We follow an **Agile/Scrum** methodology to ensure we meet the project's high standards and the **14-point minimum requirement**.

### Communication & Meetings

- **Daily Syncs**: Brief updates on progress and immediate blockers.
- **Sprint Planning**: Every week, we move tasks from the `Backlog` to `To Do`.
- **Peer Review Sessions**: Essential for ensuring everyone understands the code, as required for the final evaluation.

---

## 2. GitHub Issue Templates

We have established five specific templates to standardize our work. **Every task must start with an Issue**.

- **📋 Feature Request**: Used for mandatory parts or modules. **Requirement**: You must tick the corresponding module category and specify if it's **Major (2pts)** or **Minor (1pt)**.
- **🐛 Bug Report**: Used for reporting errors. **Mandatory**: Include console logs. The project forbids any warnings/errors in the browser console.
- **📚 Documentation**: For updating the `README.md`, API docs, or architectural diagrams.
- **🔨 Code Refactor**: To improve code quality and readability without changing functionality.
- **🔬 Technical Spike**: Research tasks (e.g., investigating WebSockets or Blockchain). Used to answer technical questions before implementation.

---

## 3. The "Definition of Done" (DoD)

A task is only marked as **Done** when it meets all these criteria:

1. **Peer Review**: At least one approval from a teammate.
2. **No Warnings**: Zero errors or warnings in the Google Chrome console.
3. **Understanding**: The author must be able to explain the logic to the team, avoiding the "Bad Practice" of copy-pasting AI code.
4. **Security**: Input validation is implemented both on frontend and backend.
5. **Documentation**: Relevant parts of the README or technical docs are updated.

---

## 4. Board Management

We use three specialized views in our GitHub Project to track progress:

1. **Dev Board**: Daily workflow (`Backlog` ➡️ `Done`).
2. **Impediments Board**: To report and resolve "Blockers" immediately.
3. **Module Tracking**: A table view to sum our current points. We must reach **at least 14 points**.

---

## 5. Git & Security Rules

- **Branch Protection**: No direct pushes to `main`. Use Pull Requests.
- **Commit Messages**: Must be clear and descriptive.
- **Secrets**: Never commit `.env` files. Use `.env.example` as a template.
