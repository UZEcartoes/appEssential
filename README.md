# Integração APP Essential

Neste documento serão mostradas algumas operações que podem ser feitar utilizando a API da BIZ e os dados que retornam.

<h2>Meu Cadastro </h2>

- Últimos 4 dígitos (XXXX)
- Data de validade do cartão (MM/AA)
- Nome do cliente
- Melhor dia de compra (DD/MM/AAAA)
- Valor da Fatura Atual/Aberta (R$X.XXX,XX)
- Valor do saldo disponível (R$X.XXX,XX)
- Data de vencimento da fatura (DD/MM/AAAA)

Endpoints da BIZ : 
- - https://code.biz.com.br/api-details#api=card&operation=get-accountid
- - https://code.biz.com.br/api-details#api=invoice&operation=get-accountid-current

<h2>Últimas Transações </h2>

Endpoint da BIZ : https://code.biz.com.br/api-details#api=card&operation=get-accountid-virtualcard
