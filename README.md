# Carros — Gestão de Carros com Django

🇬🇧 **Summary:** Django project built during a course module on Django architecture and the framework itself: car management, user accounts and an OpenAI integration module.

🇧🇷 Projeto do **curso de Django**, em um dos módulos principais, onde aprendi a arquitetura e o framework.

## Módulos (apps)

| App | Função |
|---|---|
| `cars` | Cadastro e gestão de carros |
| `accounts` | Contas de usuário |
| `openai_api` | Integração com a API da OpenAI |

## Tecnologias

Python, Django, uWSGI (arquivos de configuração incluídos)

## Como rodar

```bash
git clone https://github.com/JeannAlves12/carros-django
cd carros-django
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

> A integração com a OpenAI exige uma chave de API própria, configurada por variável de ambiente (nunca no código).
