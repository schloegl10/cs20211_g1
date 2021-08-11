<div align=center>
  <img src="./imagens/INFVertical.jpg">
</div>

###### Nome do Sistema: TGCredit

###### Estória de Usuário: 1

###### Sprint: 1

###### Nome: Registrar um cartão de crédito

## Histórico

| **Versão** | **Data**   | **Alteração no Documento** | **Autor**          |
| ---------- | ---------- | -------------------------- | ------------------ |
| 1.0        | 11/08/2021 | 11/08/2021                 | Guilherme Faleiros |

**Como:** possível cliente da TGCredit

**Eu quero:** ser capaz de registrar um cartão de crédito.

**Para:** realizar compras com o mesmo.

<br>

**Cenário 1:** registrar um cartão de crédito dentro do limite permitido;

**Dado:** que eu tenha uma renda mensal;

**E:** e o limite que eu desejo seja igual ou menor que 40% da minha renda;

**Quando:** eu acessar o sistema disponível em <url do sistema>;

**E:** informar os seguintes dados: CPF, CEP, RG, nome completo, data de nascimento, e-mail, endereço, telefone, profissão, renda mensal, bandeira do cartão e limite desejado;

**E:** clicar sobre o botão confirmar;

**Então:** o sistema deverá analisar meu pedido de cartão e aprová-lo.

**E:** enviar um email com os dados do cartão e do pedido.

<br>

**Cenário 2:** registrar um cartão de crédito com as bandeiras fornecidas

**Dado:** que eu tenha uma renda fixa

**E:** e o limite que eu desejo seja igual ou menor que 40% da minha renda

**E:** a bandeira escolhida deverá será entre as disponibilizadas pela empresa: FiveCard, GCard e PontoCard.

**Quando:** eu acessar o sistema disponível em <url do sistema>;

**E:** informar os seguintes dados: CPF, CEP, RG, nome completo, data de nascimento, e-mail, senha do cartão, endereço, telefone, profissão, renda mensal, data de fechamento da fatura mensal, bandeira do cartão e limite desejado;

**E:** clicar sobre o botão confirmar;

**Então:** o sistema deverá analisar meu pedido de cartão e aprová-lo.

**E:** enviar um email com os dados do cartão e do pedido.

<br>

###### Nome do Sistema: TGCredit

###### Estória de Usuário: 2

###### Sprint: 1

###### Nome: Registrar compras pagas com o cartão

## Histórico

| **Versão** | **Data**   | **Alteração no Documento** | **Autor**          |
| ---------- | ---------- | -------------------------- | ------------------ |
| 1.0        | 11/08/2021 | 11/08/2021                 | Guilherme Faleiros |

**Como:** cliente do TGCredit

**Eu quero:** ver o histórico de compras realizadas com o meu cartão.

**Para:** fazer controle financeiro.

<br>

**Cenário 1:** checar o valor gasto no mês e histórico de compras realizados;

**Dado:** que eu tenha um cartão operado pela emitido pela TGCard;

**E:** e o mesmo esteja ativo.

**Quando:** eu acessar o sistema disponível em <url do sistema>;

**E:** informar o número do cartão e a senha;

**E:** clicar sobre o botão confirmar;

**Então:** o sistema deverá trazer o histórico de compras dos últimos 15 dias juntamente com o valor gasto no mês até então.

<br>

###### Nome do Sistema: TGCredit

###### Estória de Usuário: 3

###### Sprint: 1

###### Nome: Fechar fatura mensal

## Histórico

| **Versão** | **Data**   | **Alteração no Documento** | **Autor**          |
| ---------- | ---------- | -------------------------- | ------------------ |
| 1.0        | 11/08/2021 | 11/08/2021                 | Guilherme Faleiros |

**Como:** cliente do TGCredit

**Eu quero:** definir uma data para fechamento da fatura do cartão.

<br>

**Cenário 1:** alterar data de fechamento da fatura do cartão;

**Dado:** que eu tenha um cartão operado pela emitido pela TGCard;

**E:** e o mesmo esteja ativo.

**Quando:** eu acessar o sistema disponível em <url do sistema>;

**E:** informar o número do cartão e a senha;

**E:** escolher uma das possíveis datas: dia 20 ao 25 de cada mês;

**Então:** o sistema deverá realizar a alteração da data de fechamento e aplicá-la a partir do próximo mês.

**E:** enviar um email notificando a possível mudança.

###### Nome do Sistema: TGCredit

###### Estória de Usuário: 4

###### Sprint: 1

###### Nome: Registrar o pagamento de uma fatura

## Histórico

| **Versão** | **Data**   | **Alteração no Documento** | **Autor**          |
| ---------- | ---------- | -------------------------- | ------------------ |
| 1.0        | 11/08/2021 | 11/08/2021                 |    Andrey Dias     |

**Como:** cliente do TGCredit

**Eu quero:** Realizar o pagamento de uma fatura do TGCard;

<br>

**Cenário 1:** Pagar uma fatura do TGCard;

**Dado:** Que eu tenha realizado alguma compra com o TGCard;

**E:** a fatura não tenha vencido;

**Quando:** eu acessar as informações de minha conta;

**E:** acessar a área de pagamento de fatura;

**E:** optar entre o pagamento online e pagamento por emissão de boleto;

**Então:** Após o recebimento do pagamento, o sistema deve notificar o cliente e liberar o limite novamente;
</DIV>
