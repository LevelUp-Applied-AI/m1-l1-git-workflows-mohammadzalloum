## Testing Requirements

All changes must pass `python test_environment.py` before committing.
Any updates to project setup files, documentation, or analysis workflow
must be tested locally before being pushed. If new Python source files
or test files are added later, they must run successfully and include
corresponding tests in `tests/` using `pytest tests/ -v`.

## Secrets Policy

Do not include API keys, passwords, tokens, or any personal or sensitive
hospital admission data in prompts or commits. Never commit `.env`,
`*.key`, raw dataset files, or any file containing credentials or private
data. Project data should remain outside the repository and only be placed
in the expected local data folders.

## Scope Boundaries

Agents may edit `README.md`, `AGENTS.md`, `CHANGELOG.md`, `.gitignore`,
`setup.sh`, and analysis files such as notebooks or future source files.
Do not modify `requirements.txt` unless a dependency change is necessary
and verified locally. Do not change `setup.sh` without running it and
confirming that `python test_environment.py` prints `Environment OK`.
Do not update `.gitignore` in a way that could hide required source,
documentation, or configuration files.

## Reproducibility Standard

All AI-assisted changes must be verified through local execution before
commit or push. A change is only considered complete when a new teammate
can follow the documented setup steps, run the project locally, and get
the expected result without extra explanation. AI-generated content must
be reviewed, tested, and confirmed in the actual repository environment.