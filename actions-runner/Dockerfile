FROM ghcr.io/actions/actions-runner:2.313.0

USER root
RUN apt-get update -y && apt-get install -y curl build-essential gcc libssl-dev \
    libfindbin-libs-perl libasound2-dev libudev-dev pkg-config m4

USER runner