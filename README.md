# Automation with Django
> 
> Celery as a task queu and Redis as the message broker

## Build Setup

``` bash
# install dependencies
pip install -r requirements.txt
# Run server[Redis server,client and django]
python manage.py runserver
on another terminal window - redis-server and redis-cli
# Run celery
python -m celery -A django_celery worker -l info

```
