FROM tiangolo/uvicorn-gunicorn-fastapi:python3.9

ENV APP_HOME /apisifytrade
WORKDIR $APP_HOME
COPY . /apisifytrade

RUN pip install -r requirements.txt

EXPOSE 8080

CMD ["uvicorn", "main:app", "--reload", "--host", "0.0.0.0", "--port", "8080"]
