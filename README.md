# Trabalho-Final-Estrutura-de-Dados
Trabalho final da matéria de estrutura de dados:


1. Identificação 

Nome dos integrantes: Lucas Silva Irineu 

Nome do projeto: Sistema de Locação de Livros com Estruturas de Dados 

Link para o repositório:  https://github.com/LucasSI/Trabalho-Final-Estrutura-de-Dados.git


2. Descrição do Problema 

A gestão de empréstimos em bibliotecas escolares ou comunitárias muitas vezes é feita de maneira manual ou com sistemas muito genéricos. Isso pode levar a filas desorganizadas, perdas de histórico e dificuldades de controle das locações por usuário. 

Esse problema afeta especialmente professores, bibliotecários e estudantes, que dependem de um sistema confiável para organizar a fila de espera e garantir um histórico de empréstimos preciso. 


3. Solução Proposta 

a) Descrição do algoritmo 

O projeto implementa um sistema que permite: 

Cadastrar livros disponíveis em uma lista encadeada; 

Registrar a fila de espera por livro com uma estrutura de fila (FIFO); 

Controlar o histórico de locações dos usuários com uma pilha (LIFO); 

Exibir livros cadastrados e locados, além de permitir chamadas automáticas para o próximo da fila. 

b) Estruturas de dados utilizadas 

Lista Encadeada (Listadelivros): Para armazenar os livros de forma dinâmica, permitindo inserções no início com baixo custo. 

Fila (Filadeespera): Para organizar os usuários que aguardam a locação de um determinado livro. 

Pilha (Pilhadelocação): Para registrar o histórico de locações de cada usuário, mantendo a ordem de devolução do mais recente para o mais antigo. 

c) Justificativa 

Cada estrutura foi escolhida por sua aderência ao comportamento real: 

A lista encadeada simula bem o cadastro dinâmico de livros. 

A fila é ideal para espera: o primeiro que entra é o primeiro a ser atendido. 

A pilha ajuda a exibir o histórico mais recente com facilidade. 

d) Fluxo geral da aplicação 

Usuário acessa o menu e escolhe a operação; 

Sistema interage com as classes correspondentes; 

Livros podem ser cadastrados ou listados; 

Usuários entram na fila de um livro; 

Quando chamados, registram o empréstimo em sua pilha de locação; 

O histórico pode ser consultado a qualquer momento. 


4. Escalabilidade 

a) Comportamento com dados maiores: 
A estrutura provavelmente se comportaria bem com quantidades de dados maiores, porém há a necessidade de adicionar outras funções para maior manejo dos dados. 

b) Melhorias possíveis: 

Melhorias possíveis seriam a adição de mais funções para melhor tratamento dos dados e interface gráfica para melhor visualização e integração com banco de dados para persistência dos dados. 


5. Ferramentas de Inteligência Artificial Utilizadas 

Microsoft Copilot: 

Contribuição: Auxílio na refatoração do código, revisão de boas práticas e explicação das estruturas de dados. 

Decisões influenciadas: Estruturação das classes, validações, modularização e esta própria documentação do relatório técnico(Escalabilidade e Conclusão redigidas por mim, Lucas). 


6. Conclusão 

a) Aprendizados obtidos 

Aplicação das estruturas de dados utilizadas em cenário prático, visualização dos conceitos aprendidos, e e estruturação do código para utilização por pessoas. 

b) Possíveis desdobramentos: 

Possíveis desdobramentos seriam a implementação de outras funções e aprimoramento do código para possível utilização real. 
 

 
