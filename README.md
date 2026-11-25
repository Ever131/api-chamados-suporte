
# API de Chamados de Suporte

**Estudante:** EVERLIR RICHARDSON DA SILVA

## Objetivo

Desenvolver a estrutura inicial de uma API de chamados de suporte utilizando Python, Flask e uv.

## Tecnologias

- Python
- Flask
- uv

## Instalação

Execute:

```bash
uv sync --locked
```

## Execução

```bash
uv run flask --app app run --host=0.0.0.0 --port=5000
```

## Rota inicial

GET /

Endereço: http://localhost:5000/

Resposta esperada:

```json
{
  "mensagem": "API de chamados em funcionamento"
}
```

Código HTTP: 200 OK.

Content-Type: application/json
