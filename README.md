## A basic DAG script to connect a gcloud instance

**PURPOSE**

- start a remote instance named shobdokutir-gpu-2
- run tactron2 till 5 epochs 
- create an output file as a text formate
- move output file to local
- stop instance

**how to run**

1. install airflow from [here](https://youtu.be/46YEL47ieQE) if not installed 
2. download ***remote_run.sh*** in local
3. download ***run.sh*** in gcloud instance
4. go to your airflow directory
5. download ***gcloud_run.py***  and copy it to *dags* folder
6. open a terminal in airflow directory and run ***airflow initdb*** 
7. then run ***airflow webserver --port 8080*** 
8. open another terminal in airflow directory and run ***airflow scheduler*** 
9. then in a browser *localhost:8080* 
