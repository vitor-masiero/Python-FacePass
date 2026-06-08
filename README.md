# Python FacePass

Sistema backend para controle de acesso com reconhecimento facial, desenvolvido com Django REST Framework, OpenCV/MediaPipe/Dlib e PostgreSQL.

## Objetivo

Gerenciar pessoas, empresas, faces cadastradas e tentativas de acesso, permitindo validar entradas por reconhecimento facial.

## Stack

- Python
- Django 5
- Django REST Framework
- PostgreSQL
- OpenCV
- MediaPipe
- Dlib / face-recognition
- CORS Headers

## Módulos principais

- Usuários
- Empresas
- Endereços
- Faces cadastradas
- Tentativas de acesso
- Alertas
- Relatórios

## Segurança

Este repositório usa variáveis de ambiente para configurações sensíveis. Não versionar `.env`.

Crie um arquivo `.env` local com base em `.env.example`.

## Como rodar localmente

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

No Windows, ative a venv com:

```bash
.venv\Scripts\activate
```

## Status

Projeto em evolução para estudo de backend, visão computacional e controle de acesso.
