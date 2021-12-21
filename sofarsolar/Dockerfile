FROM python:2.7

ADD inverter /inverter
ADD run.sh /

RUN pip install paho-mqtt anyconfig==0.9.8

CMD [ "/run.sh" ]
