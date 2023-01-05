# Hands-on Airflow exercises

[Running Airflow in Docker](https://airflow.apache.org/docs/apache-airflow/stable/howto/docker-compose/index.html) for the exercises

Exercises:

`user_processing.py`: An implementation of an ETL pipeline to:

1. extract mock user data from https://randomuser.me/
2. transform the data to fit certain data schema
3. load the data to the postgres database

`group_dag.py`: A demo for grouping the tasks in the dag.

`parallel_dag.py`: A demo for creating a parallel dag.

`elastic_dag.py`: A demo for incorporating elasticsearch in a dag by making a hook from Airflow's BaseHook for it.
