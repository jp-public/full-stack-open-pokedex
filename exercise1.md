#Python project

There are many linters and formatters that you can use for Python, there is also style guide called PEP8 that these normally enforce.
Some examples of linters: Pylint, Flake8 & mypy. And formatters: Black, isort & autopep8. Linters and formatters can be enforced early with pre-commit hooks and/or run as part of GitHub Actions for example. Codespell is another tool that is kind of like linter but for spelling mistakes that you can use in similar way. For testing most popular frameworks are Robot, PyTest and Unittest. Application is in python that is interpreted language so it doesn't have to be compiled. Nowadays you often want to build your app into Docker image.

Some pretty direct alternatives to GitHub Actions are Gitlab CI and Bitbucket pipelines. Other tools that are more like Jenkins include Bamboo, CircleCI & Buddy.

Best set-up depends on many factors. For smaller project cloud-based environment is probably best as it is very easy to start using GitHub Actions for example as most people are already very familiar with Git and Github. Configurating GitHub Actions for basic use is also really simple. For larger set of projects run at large company some tailored self-hosted solution might be better. For businesses cost is also very important metric so choice is highly effected by pricing of the products.
