FROM python:3.13.0a3-alpine
WORKDIR /app
COPY . /app
RUN rm -rf ./components
RUN pip install requests
ENTRYPOINT ["python"]
CMD ["app.py"]
