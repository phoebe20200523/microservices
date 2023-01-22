[![Python application test with Github Actions](https://github.com/phoebe20200523/microservices/actions/workflows/devops.yml/badge.svg)](https://github.com/phoebe20200523/microservices/actions/workflows/devops.yml)
# microservices

## Scaffold

<img width="344" alt="Screen Shot 2023-01-21 at 3 20 23 PM" src="https://user-images.githubusercontent.com/65870261/213885719-7dea24bf-7ae5-4932-b599-8f26f76837b1.png">

1. Create a Python Virtual Environment `python3 -m venv ~/.venv` or 'virtualenv ~/.venv`
2. Create empty files: `Makefile`, `requirements.txt`, `main.py`, `Dockerfile`, `mylib/__init__.py`
3. Populate `Makefile`
4. Setup Continuous Integeration, i.e. check code for issues like lint errors
<img width="1493" alt="lint-failure" src="https://user-images.githubusercontent.com/65870261/213890317-11c29a80-54b3-4703-8b03-15d0e1cd7bdf.png">

5. Build cli using Python Fire libraray ' ./cli-fire.py --help` to test logic