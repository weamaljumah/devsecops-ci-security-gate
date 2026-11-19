# DevSecOps CI Security Gate

## Project Overview
A beginner-friendly DevSecOps project that demonstrates
automated Python security scanning using GitHub Actions
and Bandit.

The project applies the Shift-Left Security concept by
detecting insecure code early in the development process.

## Tools Used
- GitHub Actions
- Python 3.12
- Bandit 1.9.4

## How It Works
1. A developer pushes code to GitHub.
2. GitHub Actions automatically starts the workflow.
3. Bandit scans the Python file.
4. The workflow fails when security findings are detected.

## Security Checks
Bandit performs Static Application Security Testing (SAST)
to identify potentially insecure Python code.

Command:
`bandit app.py`

## Test Results
- Safe Python code: PASS
- Insecure subprocess usage (B602): FAIL
- Fixed Python code: PASS

## What I Learned
- Basic GitHub Actions workflows.
- Automated security scanning.
- Python static code analysis.
- Shift-Left Security fundamentals.
- Understanding CI security gates.
