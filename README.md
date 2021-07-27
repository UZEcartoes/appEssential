# Integração APP Essential

Neste documento serão mostradas algumas das operações que podem ser feitas utilizando a API da BIZ.

<h2>Autenticação </h2>

Dados de criação do Usuário:
- Nome Completo
- CPF
- Telefone 
- E-mail
- CNPJ da Loja

Solicite os dados de autenticação através deste link : https://app.pipefy.com/public/form/fHSm6iab

Após a criação do usuário, o desenvolvedor deverá consumir a API abaixo passando a chave 'Subscription Key' para gerar o Token, após o token gerado que poderá consumir qualquer API. <br> <br>
Link da API : https://code.biz.com.br/api-details#api=authentication&operation=post-login

Obs.: Subscription Key é passada juntamente com a criação do usuário.



<h2>Documentação </h2>

A documentação da API pode ser encontrada neste link : https://code.biz.com.br/api-details#api=card

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

# Dúvidas e Acesso

Para o caso de dúvidas e acesso às credenciais entre em contato conosco através do link abaixo : 
- https://app.pipefy.com/public/form/fHSm6iab
