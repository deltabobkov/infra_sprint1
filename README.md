# Проект Kittygram

![Python](https://img.shields.io/badge/Python-313131?style=flat&logo=Python&logoColor=white&labelColor=306998)
![Django](https://img.shields.io/badge/Django-313131?style=flat&logo=django&labelColor=092e20)
![SQLite](https://img.shields.io/badge/SQLite-313131?style=flat&logo=sqlite&logoColor=ffffff&labelColor=033b55)
![NGINX](https://img.shields.io/badge/NGINX-313131?style=flat&logo=nginx&labelColor=009639)
![Gunicorn](https://img.shields.io/badge/Gunicorn-313131?style=flat&logo=gunicorn&logoColor=ffffff&labelColor=499848)
![React](https://img.shields.io/badge/React-313131?style=flat&logo=React&logoColor=ffffff&labelColor=61DBFB)
![Visual Studio](https://img.shields.io/badge/VS%20Code-313131?style=flat&logo=visualstudiocode&logoColor=ffffff&labelColor=0098FF)


## Проект Kittygram - это простой аналог Инстаграма для ваших котиков! Постите фото своих питомцев и пишите про их привички.


### Как запустить проект:

1. Клонировать репозиторий и перейти в него в командной строке:

```
git clone https://github.com/deltabobkov/infra_sprint1.git

cd infra_sprint1/
```

2. Cоздать и активировать виртуальное окружение:

```
python3 -m venv venv

source venv/scripts/activate
```

3. Установить зависимости из файла requirements.txt:

```
python3 -m pip install --upgrade pip

pip install -r requirements.txt
```

4. Выполнить миграции:

```
python manage.py migrate
```

5. Запустить проект:

```
python manage.py runserver 0:8080
```
  
**Проект будет доступен по адресу:**  
http://localhost:8080/
