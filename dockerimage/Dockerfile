FROM python
COPY helloworld.py .
COPY requirements.txt .
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["helloworld.py"]