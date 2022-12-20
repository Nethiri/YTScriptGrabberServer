FROM python:3.8

ENV SRC_DIR /usr/bin/src/webapp/src

COPY src/* ${SRC_DIR}/

WORKDIR ${SRC_DIR}

ENV PYTHONUNBUFFERED=1

RUN pip install youtube_transcript_api

CMD ["python", "main.py"]




#ADD main.py .

#CMD ["python", "./main.py"]

