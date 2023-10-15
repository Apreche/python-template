FROM mcr.microsoft.com/devcontainers/python:3.12-bookworm

ENV DEBIAN_FRONTEND=noninteractive
ENV PYTHONUNBUFFERED=1
ENV PYTHONFAULTHANDLER=1
ENV PYTHONDONTWRITEBYTECODE=1
ENV PIP_DISABLE_PIP_VERSION_CHECK=on

RUN apt-get update
RUN apt-get --no-install-recommends -y upgrade
RUN pip3.12 install poetry
