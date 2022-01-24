# py-precommithooks


```bash
touch .pre-commit-config.yaml
pip install pre-commit pyupgrade pyupgrade safety black flake8 dead pylint autopep8 autoflake8 isort nbstripout nbqa
pre-commit install
pre-commit autoupdate
```


Reference:
* https://github.com/asottile/pyupgrade
* https://commitizen-tools.github.io/commitizen/
* https://speakerdeck.com/leew/commitizen-tools-what-can-we-gain-from-crafting-a-git-message-convention-at-taipey-dot-py?slide=37
* https://github.com/Lucas-C/pre-commit-hooks-safety
* https://github.com/Lucas-C/pre-commit-hooks-bandit
* https://github.com/kynan/nbstripout/
* https://github.com/nbQA-dev/nbQA?ref=pythonrepo.com