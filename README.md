# sensor_fault_detection
This is a fault detection project using sensor reading.


for linux:
$(pwd)/airflow/dags

for windows"
%cd%\airflow\dags

docker run -p 8080:8080 -v "/home/milanbeherazyx/Data Science/sensor_fault_detection/airflow/dags:/app/airflow/dags" sensor:latest

docker run -p 8080:8080 -v "/home/milanbeherazyx/Data Science/sensor_fault_detection/airflow/dags:/app/airflow/dags" -e "mongodb+srv://milanbeherazyx:zSR1HZte2oPjMeKe@cluster0.wui6u7y.mongodb.net/?retryWrites=true&w=majority" sensor:latest 


docker run -p 8080:8080 -v $(pwd)/airflow/dags:/app/airflow/dags -e "mongodb+srv://milanbeherazyx:zSR1HZte2oPjMeKe@cluster0.wui6u7y.mongodb.net/?retryWrites=true&w=majority" sensor:latest 



Github Secrets:
```
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=
AWS_ECR_LOGIN_URI=
ECR_REPOSITORY_NAME=
BUCKET_NAME=
MONGO_DB_URL=
```