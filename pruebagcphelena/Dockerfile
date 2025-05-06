FROM python:3.10-slim
 
ENV APP_HOME /app
WORKDIR $APP_HOME
 
COPY pruebagcphelena/requirements.txt .
RUN pip install -r pruebagcphelena/requirements.txt
 
COPY . .
 
CMD ["python", "main.py"]