
# Challenge Submission Guide

Follow the steps below to submit your solution for the FeenixDV challenge.

## 1. Fork the Repository

- Open the challenge GitHub repository.
- Click the **Fork** button.
- Create a fork under your GitHub account.

## 2. Create a Solution Branch

- Open your forked repository.
- Create a new branch for your solution.

```bash
git checkout -b fix/your-name-solution
```

## 3. Update and Push Your Solution

- Make the required changes to resolve the challenge.
- Commit and push your changes to your fork.

```bash
git add .
git commit -m "Fix: challenge solution"
git push origin fix/your-name-solution
```

## 4. Create a Pull Request

- Open your forked repository on GitHub.
- Click **Contribute → Open pull request**.
- Select the following PR configuration:

| Field | Value |
|---|---|
| Base repository | feenixdvacademy/challenge-k8s-troubleshooting |
| Base branch | submissions |
| Head repository | Your forked repository |
| Compare branch | Your solution branch |

- Click **Create pull request**.
- Provide a meaningful title and description.
- Submit your PR.

**Important:** Do not select `main` as the base branch. Always target the `submissions` branch.

## 5. Root Cause Analysis

For every identified issue, document:

- Observed symptom
- Diagnostic command
- Evidence or output
- Root cause
- Corrective action

## 6. Changes Made

List the files changed and briefly explain why each change was required.

## 7. Validation Evidence

Include relevant command outputs or screenshots demonstrating:

- Pod readiness
- Deployment status
- Service endpoints
- Successful HTTP response

## 8. Security and Best Practices

Explain any relevant security, reliability, or Kubernetes best practices considered in your solution.

## 9. Final Summary

Briefly describe:
- What was failing?
- How did you fix it?
- What did you learn?

## 10. Automated Evaluation

- GitHub Actions will automatically validate your submission.
- Check the **Checks** section of your Pull Request for evaluation results.
- If validation fails, fix the issue and push updated code to the same solution branch.
- Your existing PR will automatically update with the latest changes.

**Happy Learning & Happy Troubleshooting!**

— Team FeenixDV Academy
