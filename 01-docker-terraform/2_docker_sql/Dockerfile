FROM python:3.13.1

RUN pip install pandas

WORKDIR /app

copy pipeline.py pipeline.py

ENTRYPOINT ["python","pipeline.py"]