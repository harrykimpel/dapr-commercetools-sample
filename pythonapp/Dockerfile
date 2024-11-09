FROM python:3.10.15-alpine
WORKDIR /app
COPY . /app
RUN rm -rf ./components
RUN pip install requests
ENTRYPOINT ["python"]
CMD ["app.py"]
