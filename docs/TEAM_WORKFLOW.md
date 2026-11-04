# Team Workflow

## Branching Strategy
- `main`: Production-ready code.
- `develop`: Integration branch for completed features.
- `feature/*`: Individual feature development branches.

## Development Process
1. Create an issue describing the task.
2. Create a feature branch from `develop`.
3. Implement and test the assigned feature.
4. Commit changes with a clear, descriptive message.
5. Push the feature branch to GitHub.
6. Open a pull request targeting `develop`.
7. Review the changes and resolve feedback.
8. Merge only after the required approvals.

## Pull Request Rules
- No direct pushes to `main` or `develop`.
- PRs targeting `develop` require at least 2 approvals.
- PRs targeting `main` require at least 3 approvals.
- Keep PRs focused and provide a summary and testing details.

## Release Process
1. Verify that `develop` contains the completed features.
2. Prepare and test the release.
3. Merge the release into `main` after required approvals.
4. Tag the release as `v1.0`.
5. Sync the release changes back into `develop`.
