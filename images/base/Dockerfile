FROM google/cloud-sdk:slim

RUN curl -v -L -O https://github.com/GoogleCloudPlatform/gcsfuse/releases/download/v0.23.0/gcsfuse_0.23.0_amd64.deb && \
    dpkg -i gcsfuse_0.23.0_amd64.deb || echo fixing dependencies && \
    apt-get install -f -y
