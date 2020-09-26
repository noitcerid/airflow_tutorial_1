# Walkthrough

### Commands
- Ran `pip install apache-airflow`
- Ran `airflow initdb` to initialize default sqlite db
- Ran `airflow webserver --debug -p 9090` (8080 is default port, overrode to 9090)
- Ran `airflow backfill tutorial -s 2020-09-01 -e 2020-09-22`