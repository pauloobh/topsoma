# TopSoma
http://topsoma.com.br/

## Obter Token
`Post http://topsoma.com.br/v1/token`

## Obter Produtos
`Get http://topsoma.com.br/v1/produtos`
### Parametros:
api_token: string
### Retorno:
{
  "ean": "string",
  "Produto": "string"
}

## Enviar Vendas
`Post http://topsoma.com.br/v1/lancador`
