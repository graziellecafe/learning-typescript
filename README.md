# Learning Typescript

# Sumário
1. [Seção 1: Introdução](#introducao) 
2. [Seção 2: Fundamentos do Typescript](#fundamentos)
3. [Seção 3: Avançando em Tipos](#avancando-em-ts)
4. [Seção 4: Narrowing - Verificação de tipos e de dados]()
5. [Seção 5: Funções com Typescript]()
6. [Seção 6: Entendendo os Object Types]()
7. [Seção 7: Criação de tipos]()
8. [Seção 8: Classes com Typescript]()
9. [Seção 9: Módulos com TS]()
10. [Seção 10: Decorators]()
11. [Seção 11: React com Typescript]()
12. [Seção 12: Projeto: To do list React com Typescript]()
13. [Seção 13: Express com Typescript]()
14. [Seção 14: Projeto: API RESTful com Typescript, Express, MongoDB e mais recursos]()
15. [Apêndice A: Revisão Javascript Moderno](#apendice-javascript) 


<div id='introducao'/> 


## Seção 1: Introdução 
### O que é Typescript
- Typescript é um superset para a linguagem de Javascript
- Ou seja, adiciona funções ao Javascript, como a **declaração de tipos** de variável 
- Pode ser utilizado em frameworks/libs como: Express e React 
- Precisa ser compilado em Javascript, ou seja, não executamos TS
- Desenvolvido e mantido pelo Microsoft



### Porque Typescript? 
- Adiciona confiabilidade ao programa  (tipos)
- Provê novas funcionalidades a JS, como interfaces
- Com TS podemos verificar os erros antes da execução do código, ou seja, no desenvolvimento 
- Deixa JS mais explícito, diminuindo a quantidade de bugs
- Por estes e outros motivos perdemos menos tempo com debug 


### O que é Node.JS
O Node.js pode ser definido como um ambiente de execução Javascript server-side.

Isso significa que com o Node.js é possível criar aplicações Javascript para rodar como uma aplicação standalone em uma máquina, não dependendo de um browser para a execução, como estamos acostumados.

A principal característica que diferencia o Node.JS de outras tecnologias, como PHP, Java, C#, é o fato de sua execução ser single-thread. Ou seja, apenas uma thread é responsável por executar o código Javascript da aplicação, enquanto que nas outras linguagens a execução é multi-thread.

Como usar: digitar node no terminal

### Instalando o Typescript
- Para instalar o Typescript vamos utilizar o npm 
- O nome do pacote é typescript
- E vamos adicionar de forma global com a **flag -g** 
- A partir da instalação temos como executar/compilar TS em qualquer local da nossa máquina com o comando **tsc**
- `npm -v`
- ``sudo npm install typescript -g``
-  `tsc -v`

Para rodar o arquivo ts: `tsc index.ts`

### Primeiro programa com ts
- O intuito é entender como compilar e executar o arquivo gerado pelo processo de compilação.