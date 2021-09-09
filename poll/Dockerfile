FROM python:3.8.5
WORKDIR /poll
COPY . /poll
ADD requirements.txt /poll/
RUN pip install -r requirements.txt
EXPOSE 80
CMD [ "flask", "run", "--host=0.0.0.0", "--port=80"]