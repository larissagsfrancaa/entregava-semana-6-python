Sistema Bancário com Programação Orientada a Objetos
Sobre o projeto

Este projeto foi desenvolvido em Python para praticar os conceitos de Programação Orientada a Objetos (POO).

O sistema permite cadastrar clientes e contas bancárias, realizar depósitos e saques, validar dados e calcular resultados diferentes conforme o tipo de conta.

Tecnologias utilizadas

Python 3
Programação Orientada a Objetos
Git e GitHub
Diagrama de classes


Conceitos aplicados

Abstração: a classe Conta define um modelo geral.
Encapsulamento: propriedades protegem os atributos.
Herança: ContaCorrente e ContaPoupanca herdam de Conta.
Polimorfismo: cada tipo de conta implementa seu cálculo.
Composição: clientes possuem contas associadas.
Métodos especiais: uso de init, str, repr e eq.
Validações

O sistema impede saldos negativos, depósitos e saques inválidos, tarifas negativas, taxas fora do intervalo permitido e e-mails em formato inválido.

As propriedades validam os dados antes de armazená-los.

Como executar

Instale o Python 3.
Clone ou baixe este repositório.
Abra a pasta no terminal.
Execute:
python main.py
Testes e demonstração

O programa cria dez clientes e dez contas, demonstra o polimorfismo e trata exceções com try/except.

Autoria

Projeto acadêmico desenvolvido para praticar POO em Python.
