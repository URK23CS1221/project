FROM python:3.13
WORKDIR /project
COPY req.txt .
RUN pip install -r req.txt
COPY . .
EXPOSE 5000
CMD ["python", "app.py"]
