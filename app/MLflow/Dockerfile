FROM python:3
COPY ./requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt
# ENTRYPOINT ["mlflow", "server", "--host", "0.0.0.0", "--port", "5000"]