FROM jupyter/scipy-notebook:latest

USER root

RUN apt-get update && \
    apt-get install -y --no-install-recommends \
    neovim zsh

USER ${NB_USER}