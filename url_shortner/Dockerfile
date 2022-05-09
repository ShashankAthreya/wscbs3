FROM python:3.9

ADD url-shortener.py .
ADD requirements.txt .
ADD run.sh .

RUN python3 -m venv ./venv
ENV PATH = "./venv/bin/$PATH"
RUN pip3 install -r requirements.txt

CMD ["bash", "./run.sh"]