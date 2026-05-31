# Calculadora de IMC com PyQt6

## Descrição

Este projeto consiste em uma calculadora de Índice de Massa Corporal (IMC) desenvolvida em Python utilizando a biblioteca PyQt6 para criação da interface gráfica. O sistema permite que o usuário informe seu peso e altura, realizando automaticamente o cálculo do IMC e exibindo o resultado na tela.

A aplicação foi desenvolvida com foco no aprendizado de interfaces gráficas e integração entre componentes visuais e lógica de programação.

## Funcionalidades

* Interface gráfica amigável;
* Entrada de peso e altura pelo usuário;
* Cálculo automático do IMC;
* Exibição do resultado em tempo real;
* Tratamento básico de erros para entradas inválidas.

## Tecnologias Utilizadas

* Python 3
* PyQt6
* Qt Designer (.ui)

## Objetivo do Projeto

O principal objetivo deste projeto é praticar o desenvolvimento de aplicações desktop utilizando Python e PyQt6, além de aplicar conceitos matemáticos e manipulação de eventos em interfaces gráficas.

Durante o desenvolvimento foram utilizados conhecimentos sobre:

* Programação orientada a eventos;
* Interfaces gráficas (GUI);
* Manipulação de widgets;
* Entrada e saída de dados;
* Tratamento de exceções;
* Cálculos matemáticos.

## Como Funciona

O usuário informa seu peso e altura nos campos de entrada da aplicação. Ao clicar no botão "Calcular", o sistema realiza o cálculo do Índice de Massa Corporal utilizando a fórmula:

IMC = peso / (altura × altura)

O resultado é exibido em uma etiqueta na interface. Caso os valores digitados sejam inválidos ou estejam vazios, uma mensagem de erro é apresentada ao usuário.

## Aprendizados

Este projeto permitiu desenvolver habilidades relacionadas a:

* Criação de interfaces gráficas com PyQt6;
* Utilização do Qt Designer;
* Conexão de botões a funções através de eventos;
* Manipulação de componentes gráficos;
* Tratamento de erros com `try` e `except`;
* Desenvolvimento de aplicações desktop em Python.

## Melhorias Futuras

* Classificação automática do IMC (baixo peso, normal, sobrepeso, obesidade etc.);
* Formatação do resultado com menos casas decimais;
* Validação mais detalhada dos dados;
* Histórico de cálculos;
* Personalização visual da interface;
* Geração de relatórios de acompanhamento.

Este projeto possui caráter educacional e demonstra a aplicação prática do Python no desenvolvimento de interfaces gráficas e ferramentas de cálculo para uso cotidiano.
