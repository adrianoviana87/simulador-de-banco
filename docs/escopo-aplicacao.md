# Escopo da Aplicação

## Prioridade

Esse projeto visa criar um simulador de caixa eletrônico.

## Operações permitidas

As seguintes operações serão permitidas no simulador:

* Autentidcar
  * Digitar usuário e senha (Isso vai substituir o cartão)
* Visualizar o saldo
* Sacar dinheiro
* Depositar
* Transferir

## Autenticação

Para se autenticar deve-se informar o CPF e uma senha de 4 dígitos (numérico).

## Visualizar Saldo

Mostra o saldo da conta corrente do usuário que está autenticado.

## Sacar Dinheiro

Para sacar um valor, deve-se executar as seguintes validações antes:

* O usuário **deve** ter saldo maior ou igual ao valor desejado.
* O valor a ser sacado deve respeitar as notas disponíveis no caixa eletrônico.
  * Não é possível sacar R$ 25,00 se o caixa só tem notas de 20 e 50.

## Cédulas

O caixa eletrônico possui uma quantidade **finita** de cédulas. Deve-se guardar a quantidade de cada cédula e diminuir o contador a medida em que as pessoas vão sacando o dinheiro.

### Estado inicial do caixa eletrônico

Quando o simulador é iniciado, deve conter as seguintes cédulas com as seguintes quantidades.

| Cédula   | Quatidade  |
| -------- |:----------:|
| R$ 5,00  | 4  |
| R$ 10,00 | 4  |
| R$ 20,00 | 3  |
| R$ 50,00 | 5  |