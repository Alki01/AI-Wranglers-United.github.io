# Contributing to AI-Wranglers-United

Thank you for your interest in contributing! We welcome bug reports, feature requests, documentation improvements, and code enhancements. This guide will walk you through our preferred workflow.

## 1. Getting Started

1. Fork the repository on GitHub.  
2. Clone your fork locally:  
   ```bash
   git clone https://github.com/<your-username>/<repo>.git
   cd <repo>
   ```  
3. Create and switch to a new branch for your work:  
   ```bash
   git checkout -b your-feature-branch
   ```

## 2. Filing Issues

- **Bug Report:** Use `.github/ISSUE_TEMPLATE/bug_report.md`.  
- **Feature Request:** Use `.github/ISSUE_TEMPLATE/feature_request.md`.  

Fill out the template fully—steps to reproduce, expected behavior, and any context.

## 3. Developing & Testing

- Follow existing code style (indentation, naming conventions).  
- Write or update tests if you add or fix functionality.  
- Keep changes focused: one feature or fix per branch/PR.  

## 4. Submitting a Pull Request

1. Push your branch to your fork:  
   ```bash
   git push origin your-feature-branch
   ```  
2. Open a Pull Request against the `main` branch of the upstream repo.  

In your PR description, include:

- Summary of changes  
- Issue number (if applicable)  
- Any special instructions to test  

## 5. Commit Message Guidelines

Use the following style:

```
TYPE(scope): Short description
```

More detailed explanatory text, if necessary.  
TYPE can be `feat`, `fix`, `docs`, `style`, `refactor`, `test`, or `chore`.  
Keep the subject under 72 characters.

## 6. Review & Merge

- Project maintainers will review your PR and may suggest changes.  
- Address feedback promptly.  
- Once approved, a maintainer will squash-merge your PR.  

## 7. Code of Conduct

By participating, you agree to abide by our Code of Conduct.

Thank you for helping make AI-Wranglers-United a thriving, respectful community! 🎉

---

### Where to place:

- Copy **CODE_OF_CONDUCT.md** and **CONTRIBUTING.md** into the root of each repository (next to `README.md`).  
- Your issue templates already live under `.github/ISSUE_TEMPLATE/`.  
- Contributors will automatically see these guidelines when they open issues or PRs.  
