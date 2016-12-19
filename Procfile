web: newrelic-admin run-program gunicorn --pythonpath="$PWD/piedpiper" wsgi:application
worker: python piedpiper/manage.py rqworker default