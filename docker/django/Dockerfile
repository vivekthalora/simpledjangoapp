FROM python:3.6
COPY the_weather /the_weather
COPY requirements.txt /the_weather/
WORKDIR /the_weather
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
