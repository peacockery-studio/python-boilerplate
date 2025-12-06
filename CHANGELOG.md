# CHANGELOG


## v0.1.1 (2025-12-06)

### Bug Fixes

- **ci**: Disable coverage threshold until tests are added
  ([`494924e`](https://github.com/peacockery-studio/python-boilerplate/commit/494924e5870d8d0b59db3e0e7f4d4790a51ceb5e))

- Set --cov-fail-under=0 in CI workflow - Comment out threshold in pyproject.toml with TODO to
  re-enable

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude <noreply@anthropic.com>


## v0.1.0 (2025-12-06)

### Features

- Add full project setup with security rules and developer tooling
  ([`0726dd6`](https://github.com/peacockery-studio/python-boilerplate/commit/0726dd6bcb67ade238daf483812aaeb128d1574e))

- Add .python-version (3.11) for uv/pyenv consistency - Add MIT LICENSE file - Add CHANGELOG.md for
  semantic-release - Add comprehensive ruff rules including security (bandit), naming, async, etc. -
  Add pre-commit hooks (ruff, trailing whitespace, yaml/toml checks) - Add .editorconfig for
  cross-editor consistency - Add VS Code settings with recommended extensions - Rename
  src/python-boilerplate to src/python_boilerplate (valid Python module name) - Enhance ty config
  with explicit src includes

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude <noreply@anthropic.com>

### Refactoring

- Modernize tooling with Astral stack (uv, ruff, ty, hatchling)
  ([`248e16e`](https://github.com/peacockery-studio/python-boilerplate/commit/248e16e958d4cae3261662c574a8d0efaa2064c4))

- Replace pyright with ty for type checking - Switch build backend from uv_build to hatchling -
  Consolidate ruff.toml and pyrightconfig.json into pyproject.toml - Add GitHub Actions CI/CD
  workflows (lint, typecheck, test, release) - Configure semantic-release for conventional commits -
  PyPI and Codecov disabled by default (see TODO comments to enable)

🤖 Generated with [Claude Code](https://claude.com/claude-code)

Co-Authored-By: Claude <noreply@anthropic.com>
