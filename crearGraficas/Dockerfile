FROM python:3.10

WORKDIR /crearGraficas
COPY requirements.txt /crearGraficas/requirements.txt

RUN pip install --no-cache-dir --upgrade -r /crearGraficas/requirements.txt

COPY . /crearGraficas

CMD bash -c "while true; do sleep 1; done"
