### Um encurtador de URLS
Antes de começar gostaria de pedir desculpas pela apresentação do frontend porém imagino que esse não é o objetivo principal.
Edmar de Oliveira Sa Filho   


## Como testar localmente
Clone o repositório e acesse a pasta:
```shell
git clone https://github.com/edmargar/shortener.git
cd mobi2buy
```

Crie um ambiente virtual e ative-o:
```shell
python3 -m venv venv
source venv/bin/activate 
```

Instale as bibliotecas:
```shell
pip3 install -r requirements.txt
```

Rode as migrações:
```shell
python3 manage.py makemigrations
python3 manage.py migrate
```

Inicie o *webserver*:
```shell
python3 manage.py runserver
```

Vá para `http://localhost:8000/` e utilize.

os endpooint da api são:
```shell
http://localhost:8000/api/shotener/
http://localhost:8000/redirect/
```
