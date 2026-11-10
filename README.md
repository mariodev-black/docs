# Documentação SkalePayments

Projeto oficial da documentação pública da API SkalePayments, desenvolvido com Mintlify.

## Desenvolvimento local

Requisitos: Node.js 20.17 ou superior.

```bash
npm install -g mint
mint dev
```

A visualização local ficará disponível em `http://localhost:3000`.

## Validação

```bash
mint openapi-check openapi.yaml
mint validate
mint broken-links
```

## Publicação

Conecte este repositório ao projeto Mintlify e configure o domínio customizado `docs.skalepayments.com.br`. Alterações na branch de produção serão publicadas pelo fluxo configurado no painel Mintlify.

Não armazene API Keys, segredos de webhook ou dados reais de clientes neste repositório.
