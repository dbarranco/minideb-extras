FROM bitnami/minideb-extras:jessie

ENV PATH="/opt/bitnami/git/bin:$PATH"

RUN install_packages build-essential pkg-config unzip
RUN bitnami-pkg install git-2.16.2-0 --checksum ea0470e23a705692acca15c6b46ddc4d7c039943732e937c0d627328d5b0f09d
