FROM python:2.7

COPY requirements.txt ./
RUN pip install -r requirements.txt

COPY bulk_write.py .
COPY settings.py .


CMD [ "sh", "-c", "tail -f /dev/null"]
