# Guidelines for Contributing

1. Unit tests should be added for functions which meet the following criteria:
- Used by other repositories
- Used repeatedly
- Of high importance

2. Code-owners to repositories to review PRs
- However, there's always the flexibility for code-owners to allow for merges without reviews due to tight deadlines

3. Use [gitignore.io](https://www.toptal.com/developers/gitignore) to generate .gitignore files. Should add the following systems:
- MacOS
- Windows
- Python
- PyCharm
- VSCode

4. Branch naming conventions:
```plaintext
bugfix/issue-123 – For bug fixes related to a specific issue.
feature/new-feature – For new features or enhancements.
hotfix/critical-fix – For urgent fixes to production issues.
release/version-x.y.z – For preparing and stabilizing a new release.
chore/dependency-update – For maintenance tasks like dependency updates.
refactor/module-name – For code restructuring without changing functionality.
test/improve-coverage – For improving or adding test coverage.
docs/update-readme – For documentation updates or improvements.
ci/cd-pipeline – For changes related to CI/CD pipelines and automation.
experiment/alternative-approach – For testing out new experimental ideas.
```

4. Setup CI/CD pipelines

5. Add comments to hard to understand parts of code. Variable names can be used to make simpler lines of code more obvious, without needing comments.

6. Keep README.md up-to-date and details:
- Essential information about the project
- Setup instructions
- Directory structure
