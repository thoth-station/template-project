# template-project

This is a Template for any Python based project, it contains what Project Thoth and the AI CoE need:

1. GitHub defaults and Templates for issues.
2. Configuration for Coala and Black (code formating) are done using [`prow`](https://github.com/kubernetes/test-infra/tree/master/prow) with `pre-commit` and `mypy`.
3. Zuul is no longer suppported. Instead [AICOE-CI](https://github.com/AICoE/aicoe-ci) is used for basic configuration.
4. We have a public service configuration now accessible for everyone.
5. If you are writing a Python module, [Kebechet](https://github.com/marketplace/khebhut) could manage the releases of your packages for you.
6. If credentials are provided, Python module releases could be published to [`PyPI`](https://pypi.org/) by [Kebechet](https://github.com/marketplace/khebhut).

Dependencies should be managed using `pipenv` (`Pipfile`, and the `Pipfile.lock` could be created by `thamos advise`), `pip3` and a `requirements.txt` files could be used.
