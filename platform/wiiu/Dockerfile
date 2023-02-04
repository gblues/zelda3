FROM wiiuenv/devkitppc:20221228

RUN apt-get update && \
    apt-get install -y python3-pip && \
    python3 -m pip install pip --upgrade && \
    pip install Pillow PyYAML

WORKDIR project

