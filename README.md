# CoffeShopTiaRosa
CoffeShopTiaRosa

Informações do (site Coffee Shops Tia Rosa)

import sqlite3  para salvar os dados
from datetime import datetime

def => é uma função , e função  é o que você que exibir na pagina

Função para linha decorativa

Criação das tabelas:
banco_clientes()
banco_produtos()
banco_pedidos()


Comecei com um  Banco de dados: criação de tabelas

Cadastro de produto com a função (def cadastro_produto  e conexões)

Cadastro de cliente com a função (def cadastro_clientes e conexões )

Novo pedido com fução (def novo_pedido)
    . Dentro da fução pedidos usei condicionais para dizer se faria a identificação do cliente ou não.
    . Criado o  bloco com função try onde será  colocado o código se houver um erro, o except entra em
    ação e faz algo para resolver ou informar sobre o problema. (Nesse caso é se for digitado um usuário
    ou produto invalido ou inexistente

Lista de clientes com fução (def lista_clientes)
    . Usado condicionais if e else para dizer se o cliente está ou não cadastrado
    .Usado A função SELECT  e FROM (variável local, de referência ou com  correlação de ID da lista de clientes)

Lista de produtos com função (def lista_produtos):
    . Usado a mesma lógica de lista_clientes

Menu principal:
   .Usado While True
   .Função para linha decorativa
   . menu com opções de 1 a 6
   .print para imprimir o comoando desejado
   .input para o usuário digitar a opção e informações desejadas
