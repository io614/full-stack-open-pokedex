# Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by google.

Chosen language: python

Linting: flake8, pylint, pyflakes, pycodestyle, pydocstyle, bandit, mypy

Code analysis and formatting: Mccabe, radon, black, isort

Testing:  pytest, pyunit, selenium

Building: pybuilder, setuptools

# What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask google!

Travis, CircleCI, Bamboo, Gitlab, Azure pipelines

# Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

- Since the team is relatively small (6 people) I would lean towards a managed CI/CD service for the ease of setup
- Other considerations include featureset, license cost and team familiarity with the tooling
