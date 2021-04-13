# PytestDjangoSetup

[![codecov](https://codecov.io/gh/guilhermegouw/PytestDjangoSetup/branch/main/graph/badge.svg?token=VTRKETR8RH)](https://codecov.io/gh/guilhermegouw/PytestDjangoSetup)

Repositório criado para ser usado como modelo de configuração do Pytest no Django.

1. Criar ambiente virtual
2. Instalar o Django
3. Instalar o pytest-django
4. Criar o arquivo "pytest.ini"

Cobertura de testes

1. Instalar o pytest-cov
2. Instalar o codecov
3. Registrar a aplicação na plataforma do codecov

Esconder informações sensíveis

1. Instalar o python-decouple
2. Na raiz do projeto criar um diretório contrib, dentro dele criar um arquivo .env-sample
3. Tbm na raiz do projeto crie um arquivo .env e adicione o .env no seu .gitignore
4. No settings.py configure o Debug e Secret Key.