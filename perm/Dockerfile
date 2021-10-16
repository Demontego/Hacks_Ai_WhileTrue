FROM bitnami/pytorch:latest
ENV PYTHONUNBUFFERED=1

WORKDIR /code
COPY requirements.txt /code/
USER root
RUN pip install -r requirements.txt && chmod 777 /.cache
CMD [ "python", "/code/main.py" ]
USER 1000