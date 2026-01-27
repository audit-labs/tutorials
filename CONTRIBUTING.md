# Contributing to audit-labs/tutorials

Thanks for your interest in contributing! Contributions can include new tutorial notebooks, improvements to existing notebooks, documentation, CI improvements, and environment files.

Recommended workflow
1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Make your changes (keep each notebook focused and add explanatory markdown).
4. If adding dependencies, update `environment.yml` and `requirements.txt`.
5. Run notebooks locally and ensure they execute (or add tests / CI changes).
6. Commit with descriptive messages and open a pull request describing your changes.

Coding / notebook guidelines
- Keep notebooks self-contained and add a top-level markdown header explaining purpose.
- Avoid embedding large, proprietary datasets; include links or small sample data.
- Use `nbstripout` or `pre-commit` if you want to strip outputs before committing (optional).
- When changing dependencies, mention version rationale in the PR description.

If you're unsure about scope, open an issue first to discuss the plan.