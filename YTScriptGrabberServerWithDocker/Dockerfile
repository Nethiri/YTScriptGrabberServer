FROM python:3.8

WORKDIR /code

COPY ./requirements.txt /code/requirements.txt
COPY ./main.py /code/main.py

RUN pip install --no-cache-dir --upgrade -r /code/requirements.txt

CMD ["python", "main.py", "9988", "0.0.0.0"]

#docker run -p 9988:9988 -e PYTHONUNBUFFERED=1 yt_script_grabber_docker_server
#docker build -t yt_script_grabber_docker_server .