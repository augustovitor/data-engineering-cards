FROM mcr.microsoft.com/devcontainers/python:1-3.11-bookworm

# A imagem traz um repositório do Yarn cuja chave GPG não é mais aceita;
# ele quebra o apt-get update e impede a instalação do Docker. O projeto não usa Yarn.
RUN rm -f /etc/apt/sources.list.d/yarn.list