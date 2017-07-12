FROM python

LABEL maintainer "joseangeldiazg"

RUN pip install requests  \
    && pip install tweepy \
    && pip install pymongo

COPY . /src

CMD ["python", "/src/streamlistener.py"]
