# HallEase

Hall Management prototype for FCT

## Installation

To install the HallEase on your local machine, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/zaplink/HallEase.git
   ```
2. Navigate to the project directory:
   ```bash
   cd HallEase
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open your browser and visit `http://localhost:5173` to view the homepage.

## Documentation

This project includes comprehensive documentation to help you understand the key requirements and development plan. You can find the following documents in the `docs/` directory:

- **[Project Requirements](docs/requirements.md)**: This file outlines all the functional and technical requirements for the project. It covers the features, specifications, and dependencies necessary for successful implementation.
- **[Project Plan](docs/plan.md)**: This file details the roadmap and timeline for the project's development. It includes milestones, tasks, and deliverables to help track progress throughout the project lifecycle.

Please refer to these documents for in-depth information regarding the project scope and its development strategy.

## Branching Strategy

This project follows a Git branching model where:

- **Main branch (`main`)**: Contains the stable, production-ready code. This is the branch that gets deployed.
- **Development branch (`develop`)**: This branch is used for ongoing development. It serves as an integration branch for features, bug fixes, and other changes before they are merged into `main`.

### Contribution Workflow

When contributing to the project, follow this workflow:

1. **Start from `develop`**: Make sure you're working on the `develop` branch. Run:

   ```bash
   git checkout develop
   ```

   Before you begin working, ensure that you have the latest updates from the remote repository:

   ```bash
   git pull origin develop
   ```

2. **Create a new branch**: For your work, create a new branch using the appropriate naming convention:

- **Feature branches**: Use `feature/<feature-name>` for new features.

  - Example: `feature/add-login-functionality`

- **Bug fix branches**: Use `fix/<bug-description>` for bug fixes.

  - Example: `fix/fix-login-error`

- **Documentation changes**: Use `docs/<description>` for documentation updates.

  - Example: `docs/update-setup-guide`

- **Chore tasks**: Use `chore/<description>` for maintenance tasks (e.g., updating dependencies).
  - Example: `chore/update-dependencies`

3. **Make a Pull Request (PR)**: Once your work is completed and tested, submit a pull request to merge your branch into the `develop` branch.

- All new development should be merged into `develop`, **not** `main`.
- Ensure your PR description clearly explains the changes you've made.

By following this branching strategy and naming conventions, we maintain a smooth development workflow and ensure stable releases.
