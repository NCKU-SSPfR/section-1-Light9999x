FROM python:3.11-slim
WORKDIR ./
COPY main.py ./
RUN pip install -r requirements.txt
EXPOSE 5000
CMD ["python", "main.py"]
