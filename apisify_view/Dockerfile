FROM python:3.9

ENV APP_HOME /apisifyview
WORKDIR $APP_HOME
COPY . /apisifyview

RUN pip install -r requirements.txt

EXPOSE 8501

CMD ["streamlit", "run", "main.py", "--server.port", "8501"]
