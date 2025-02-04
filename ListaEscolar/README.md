# OCR para Lista Escolar

Projeto usado para exemplificar o uso da Inteligência Artificial [AWS Textract](https://docs.aws.amazon.com/pt_br/textract/latest/dg/API_DetectDocumentText.html) para extração de textos em imagens simples.

## Pré requisitos

- Python
- Uv
- Conta AWS

## Configuração do ambiente

É necessário configurar um **usuário no IAM** com acesso ao serviço Textract.

## Instalação

Para instalar as dependências do projeto utilize o comando:

```sh
uv install
```

## Execução

```
uv run main.py
```

## Dependências

```
pip install -r requirements.txt
```