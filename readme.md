# README

## Démarrer l'application

> uvicorn main:app
> --reload # pour développer (recharge automatique l'application à chaque changement d'un fichier)

## Pytest

> python -m pytest

## Coverage

> coverage run -m pytest # remplace la commande python
> coverage html # génère le rapport en html

## Locust

> locust # nécessite d'avoir un fichier locustfile.py dans le dossier où la commande est exécuté
> locust --config=.locust.conf

## Pylint

> pylint application/ tests/
