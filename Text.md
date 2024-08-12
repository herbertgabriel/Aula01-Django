### Gerenciando Dependências com Virtualenv
#### Criando um Ambiente Virtual

Para isolar as dependências do seu projeto, você pode usar o virtualenv. Ele cria um ambiente virtual, que é como um "sandbox" para o seu projeto, garantindo que as bibliotecas instaladas nele não interfiram com outros projetos ou com o ambiente global do Python.

Para criar um ambiente virtual, use o comando:
undefined

virtualenv nome_do_ambiente

Por exemplo, para criar um ambiente chamado "venv", use:
undefined

virtualenv venv

Ativando o Ambiente Virtual

Após criar o ambiente virtual, você precisa ativá-lo para começar a usar as bibliotecas instaladas dentro dele. Para ativar o ambiente, use o comando:
bash

source nome_do_ambiente/bin/activate

No caso do ambiente "venv", o comando seria:
bash

source venv/bin/activate

Após ativar o ambiente, você verá o nome do ambiente entre parênteses no início do prompt do terminal.
Desativando o Ambiente Virtual

Para desativar o ambiente virtual, basta usar o comando:
undefined

deactivate

Exercício:

Crie um ambiente virtual chamado "my_project" e ative-o. Depois, desative o ambiente.

Dica: Use o comando ls para listar os arquivos e pastas dentro do diretório do seu projeto e verificar se o ambiente virtual foi criado corretamente.

Lembre-se de que o virtualenv é uma ferramenta essencial para organizar seus projetos Python e evitar conflitos entre as bibliotecas. 

pip install django


para mostrar todas as dependencias utilizamos:
pip freeze 


para disponibilizar um arquivo txt com as dependencias podemos usar
pip freeze > requirements.txt

para iniciar projeto:
django-admin startproject nome .

é uma boa pratica colocar nome como config ou setup

python manage.py runserver

sobe um servidor local

pip install python-dotenv