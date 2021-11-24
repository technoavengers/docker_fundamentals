FROM python:3.9.1
WORKDIR /python-flask
COPY main.py .
RUN pip install flask
EXPOSE 5000
ENTRYPOINT [ "python","main.py" ]