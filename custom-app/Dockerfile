FROM python:alpine3.7
WORKDIR /app
COPY app/* /app/
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python ./index.py &  python ./metrics.py
