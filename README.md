# Avaliação de Segurança e versionamento

Avaliação pode ser feita em dupla e com consulta

Você deverá clonar esse documento, responder as questões e versioná-lo de volta no seu repositório. Ao final deverá me mandar o link.


## Nomes:

Aluno1: Aline Nascimento Bueno Black


## Usage

```python
1 - Explique com suas palavras o que é SQL Injection:
R: A maioria do softwares usa como padrão escrita código SQL. SQL Injection é uma técnica que se aproveita das falhas de segurança
na criação de um código permitindo q o usuário possa burlar o código e se aproveitar do banco de dados de um site.
```

```python
2 - Ao ser contratado para uma empresa como consultor
de segurança, ao analisar o código qual seria a primeira falha de segurança
que você procuraria?
R: Se ele está sendo feito com um usuário root.

```

```python
3 - Escreva um exemplo de injeção de SQL que você  tentaria:
R: Usaria ‘ or 1=1 -- (porque -- é comentário em sql e tornaria a minha afirmação verdadeira e transformaria o restante em comentário) em um formulário de login.

```
```python
4 - O que você faria para resolver o problema de senhas
 em texto plano no banco de dados
do seu cliente
R: Não sei
```

```python
5  a) O que é XSS request forgery:
R: Cross-Site Request Forgery é utilizado na tentativa de um hacker de se passar por um usuário legítimo usando um formulário falso "em cima" de um verdadeiro.
"De um site para outro" na tradução literal.
    
b) Como você resolveria essa falha?
R: Utilizando sistema de senhas em token. Para cada usuário logado, um token diferente na tela.
E evitar o uso de cookies para autenticação em informações que devem ser sigilosas para que não apareçam no console do computador.

```







