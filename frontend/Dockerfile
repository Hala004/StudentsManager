FROM python:3.10.13

EXPOSE 3000

WORKDIR /

COPY requirements.txt /
RUN pip install -r requirements.txt

COPY app.py /
CMD python app.py