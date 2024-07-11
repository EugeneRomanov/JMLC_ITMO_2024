# Junior ML Contest
Данный репозиторий содержит информацию по проекту для соревнования Junior ML Contest.

## Актуальность проблемы: 

Каждую минуту мир теряет участок леса размером с 48 футбольных полей. Наиболее остро проблема вырубки лесов выражена в бассейне Амазонки, что способствует сокращению биоразнообразия, изменению климата и другим разрушительным последствиям в этом регионе. Зачастую вырубка лесов является несогласованным и незаконным процессом, который наносит ущерб природе и государству. Использование ИИ позволило бы государствам оперативно отслеживать вырубку леса и эффективно реагировать на такие ситуации. 

В работе рассматривается реализация модели машинного обучения для классификации спутниковых снимков, способную идентифицировать участки незаконной вырубки лесов в бассейне Амазонки. 

## Структура работы:

Работа состоит из двух частей: modelling и service. 

#### 1. Modeling.

Данный репозиторий предоставляет гибкий код, который позволяет быстро и эффективно обучить модель для решения поставленной задачи, при этом осуществляя логирование каждого эксперимента. 

Лучший эксперимент можно посмотреть [здесь](https://app.clear.ml/projects/6af89bf5de40410faba201b8130632ce/experiments/07ff5733d5034edea427f7fae84914b2/output/execution).

Основные технологии: Pytorch, OpenCV, Augmentation, Pytorch Lightning, Clear ML, DVC, Flake8. 

#### 2. Service.

Данный репозиторий позволяет создать и задеплоить сервис, который будет использовать разраработанную модель. 

Разработанный сервис: http://91.206.15.25:1001/docs

Основные технологии: FastAPI, Docker, Flake8, Pytest, Gitlab CI/CD, DVC.

