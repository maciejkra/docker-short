FROM my/python

WORKDIR /usr/src/app
RUN pip install --no-cache-dir -r requirements.txt

ENV LOG_LEVEL=INFO
EXPOSE 5002

CMD [ "python", "main.py" ]
