FROM python:3.8-slim
WORKDIR /server
COPY dependencies.txt .
RUN pip install -r dependencies.txt
RUN pip install --upgrade flask jinja2
COPY src/ .
CMD [ "python", "server.py" ]