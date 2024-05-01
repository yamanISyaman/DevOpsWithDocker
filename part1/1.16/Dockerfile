FROM python:3.9

EXPOSE 8080

WORKDIR /usr/src/

RUN git clone https://github.com/lmzach09/Python_ChatBot_Google.git

WORKDIR Python_ChatBot_Google

RUN pip install -r requirements.txt

CMD ["python", "server.py"]