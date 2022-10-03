# 11.1 Warming up

For the CI setup of a Python application , there are many tools available. Pylint, Flake8, Autopep8 and Black are some common linting tools. For testing, Pytest, Mypy and Locust can be used. While Python is an interpreted language and there is no need for a build step, a builder tool is not compulsory. However, PyBuilder and Buildout can be used to construct build life cycles or compile python scripts to EXE on windows.

The alternatives to set up the CI besides Jenkins and GitHub Actions are GitLab CI, Azure Pipelines, CircleCI, Buildkite, Buddy, CruiseControl, Integrity, GoCD, IBM Urbancode, TeamCity, Wercker, Bitrise, Bamboo and Strider CD.

Since the Python application is being worked on by a team of about 6 people, this software project is not very large. It is also assumed that it doesn't have any special requirements (e.g. a need for a graphics card to run tests). As the application is in active development and will be released soon, time may not be sufficient for a complex CI config setup. Therefore, a cloud-based CI solution is preferred due to the project size and time constraints. The cloud-based configuration is simpler than any self-hosted alternative because only a config file is needed instead of setting up the entire system.
