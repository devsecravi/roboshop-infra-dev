FROM python:3.0
EXPOSE 8080
WORKDIR /app
COPY payment.ini .
COPY *.py .
COPY requirements.txt .
RUN pip3 install -r requirements.txt
CMD ["vwsgi", "--ini", "payment.ini"]
