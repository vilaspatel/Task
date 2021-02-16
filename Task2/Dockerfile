FROM python:3.9.1
WORKDIR /usr/src/app
EXPOSE 80
COPY requirements.txt .
RUN pip install -qr requirements.txt
COPY server.py .
CMD ["python3", "./server.py"]
