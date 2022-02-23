FROM odoo:14.0

USER root

RUN apt-get update || true && apt install --assume-yes --no-install-recommends  \
    git python3-dev gcc libc-dev libffi-dev

RUN pip3 install --upgrade pip
# RUN pip install -r requirements.txt
RUN pip3 install -U debugpy
RUN pip3 install -U cryptography

USER odoo