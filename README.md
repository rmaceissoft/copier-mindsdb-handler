# Copier MindsDB Handler

[Copier](https://github.com/copier-org/copier) template
for developers willing to implement new handlers for [MindsDB](https://mindsdb.com/). It generates the boilerplate code so you can focus on what really matters and speed up the implementation process

Note: For now it's only supported to generate the boilerplate code for [MindsDB Application Handlers](https://docs.mindsdb.com/contribute/app-handlers), mainly because there is a high amount of [opened issues](https://github.com/mindsdb/mindsdb/issues?q=is%3Aopen+is%3Aissue+label%3Aapp-integration) waiting for contributors who wish to support


# Requirements

To use this Copier template, you will need:

- [git v2](https://git-scm.com/)
- [Python 3](https://www.python.org)
- [Copier](https://copier.readthedocs.io/en/stable/)

To install Copier, use `pip`
or [`pipx`](https://pipxproject.github.io/pipx/):

```bash
pip install --user copier
```

```bash
pip install --user pipx
pipx install copier
```

# Usage

Make sure you are placed into the mindsdb's root directory. Then:

```bash
copier copy "https://github.com/rmaceissoft/copier-mindsdb-handler.git" .
```

Or even shorter:

```bash
copier copy "gh:rmaceissoft/copier-mindsdb-handler" .
```