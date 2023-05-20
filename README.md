# portal

## For running kafka (on windows):
* `cd kafka-ui && docker compose -f documentation/compose/kafka-ui.yaml up`

## For running Rabbitmq:
* `docker run -it rabbitmq`

## Run celery on windows:
* `celery -A main.celery worker --loglevel=info -Q universities,university --pool=eventlet`