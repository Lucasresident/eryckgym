FROM python:3.12.2-bullseye

WORKDIR C:\Users\lucas\OneDrive\Desktop\api\eryckgym>

COPY ./requirements.txt .

RUN pip install -r requirements.txt

COPY . .

EXPOSE 8000

CMD [ "python", "manage.py", "runserver", "0.0.0.0:8000" ]