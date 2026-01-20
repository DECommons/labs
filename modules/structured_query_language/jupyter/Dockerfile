FROM jupyter/minimal-notebook:python-3.11

USER root

# Install Postgres client (libpq)
RUN apt-get update && apt-get install -y \
    libpq-dev \
    postgresql-client \
    && rm -rf /var/lib/apt/lists/*

RUN rm -rf /home/jovyan/wor

USER ${NB_UID}

# Install Python Libraries
COPY requirements.txt /tmp/
RUN pip install --no-cache-dir -r /tmp/requirements.txt