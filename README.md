# locust-loadtest

Teste de carga com o [Locust](https://locust.io/).

## Instalação das dependências

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Como executar

### API

```
python app.py
```

### Teste de carga

```
locust --host http://localhost:5000
```

Após isso, acessar a interface do Locust em: [http://localhost:8089](http://localhost:8089)
