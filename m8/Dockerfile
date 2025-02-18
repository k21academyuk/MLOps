
    
FROM python:3.8-slim

WORKDIR /app

ADD . /app

RUN apt-get update && apt-get install -y libgomp1

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "my_first_api.py"]    
