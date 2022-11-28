FROM python:3.8
LABEL maintainer="Jorge Salazar"
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE 3111
CMD [ "python", "app.py" ]
