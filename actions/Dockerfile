FROM rasa/rasa-sdk:2.8.0
WORKDIR /app
COPY requirements.txt requirements.txt
COPY star_movatec_cl.crt star_movatec_cl.crt
COPY movatec.key movatec.key
USER root
RUN pip install -r requirements.txt
EXPOSE 5052
USER 1001
