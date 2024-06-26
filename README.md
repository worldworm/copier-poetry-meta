<h1 align="center">📋 copier-poetry-meta</h1>
<p align="center">
  <i><a href="https://github.com/copier-org/copier">Copier</a> meta template for <a href="https://github.com/python-poetry/poetry">poetry</a> projects.</i>
</p>


<!-- Place https://shields.io/ badges here -->
[![GitHub repo stars](https://img.shields.io/github/stars/worldworm/copier-poetry-meta)](https://github.com/worldworm/copier-poetry-meta)
[![License](https://img.shields.io/badge/license-MIT-green?logo=opensourceinitiative&logoColor=fff)](https://github.com/worldworm/copier-poetry-meta/blob/main/LICENSE)
[![GitHub last commit (main)](https://img.shields.io/github/last-commit/worldworm/copier-poetry-meta/main)](https://github.com/worldworm/copier-poetry-meta/commits/main/)
[![GitHub release](https://img.shields.io/github/v/release/worldworm/copier-poetry-meta)](https://github.com/worldworm/copier-poetry-meta/releases/latest)
[![GitHub commits since latest release](https://img.shields.io/github/commits-since/worldworm/copier-poetry-meta/latest/main)](https://github.com/worldworm/copier-poetry-meta/releases/latest)
[![Copier supported version](https://img.shields.io/badge/Copier-v9-blue)](https://github.com/copier-org/copier)


## Features
- 📦 [Poetry](https://github.com/python-poetry/poetry) setup with a pre-defined pyproject.toml
- 🔁 Continuous integration (CI) pipelines for Github Actions and GitLab CI/CD
- 🐳 Docker support with build and publish pipelines
- ⚙️ Settings management using [pydantic-settings](https://github.com/pydantic/pydantic-settings)
- 🗄️ Database support with [sqlmodel](https://github.com/tiangolo/sqlmodel) and mysql, postgres or sqlite configuration
- ▶️ [alembic](https://github.com/sqlalchemy/alembic) database migrations
- 🏃 [poethepoet](https://github.com/nat-n/poethepoet) task runner
- 🪝 [pre-commit](https://github.com/pre-commit/pre-commit) hooks
- 🔍 [pylint](https://github.com/pylint-dev/pylint) code linter
- 🏁 [mypy](https://github.com/python/mypy) static type checker
- 🧪 [pytest](https://github.com/pytest-dev/pytest/) unit tests
- 🛡️ [bandit](https://github.com/PyCQA/bandit) code security check
- 🎨 [autopep8](https://github.com/hhatto/autopep8) and [pydocstringformatter](https://github.com/DanielNoord/pydocstringformatter) code formatter and styling
- 🆚 [VSCode](https://github.com/microsoft/vscode) configuration


## Requirements
First install copier:<br>
([from the official installation documentation](https://copier.readthedocs.io/en/stable/#installation))
```bash
pip install copier
```


## Usage
> [!NOTE]
> This is a [meta template](https://github.com/worldworm/copier-showcase/blob/main/types/meta.md) that cannot be used directly to create a project.
> The template resulting from this meta template can be used for this purpose: [copier-poetry](https://github.com/worldworm/copier-poetry)



Make sure the requirements are met, then:
```bash
copier copy "https://github.com/worldworm/copier-poetry-meta.git" .
```

### Update
To update a template after creating a project, run:
```bash
copier update -a .project/.copier-answers.poetry-meta.yml .
```


## Explore more Copier templates
In addition to this template, there are a number of other Copier templates available. For an overview of all available templates, visit the [Templates Showcase repository](https://github.com/worldworm/copier-showcase).

---
<p align="center">
  <i>© <a href="https://github.com/worldworm">worldworm</a> 2023-2024</i>
  <br><i>Licensed under <a href="https://github.com/worldworm/copier-poetry-meta/blob/main/LICENSE">MIT</a></i>
</p>
