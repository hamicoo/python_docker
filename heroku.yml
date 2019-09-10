FROM python:alpine3.9
RUN mkdir myapp
WORKDIR /myapp
COPY ./ ./
RUN pip install -r requirements.txt
EXPOSE 5000
CMD python 1.py