# Fundamentos de Arquitetura de Sistemas

## Vantagens e desenvolvimento de Web Services

### O que são Web Services
  
   Web services são soluções para que aplicações se comuniquem independente de linguagem, hardware e etc.
  São API’s que se comunicam por meio de redes sobre o protocolo http.
   As principais vantagens de uso dos webservices são a facilidade de integração, melhoria na segurança, linguagem comum e redução de custos.

<br />

### Estrutura SOAP

<br />
 SOAP - SIMPLE OBJECT ACCESS PROTOCOL

<br />
Protocolo baseado em XML para acessar serviços web principalmente por http.
SOAP é, também, uma definição de como os serviços web se comunicam. Foi desenvolvido para facilitar integrações entre aplicações.

As principais vantagens são as mesmas dos webservices

O SOAP MESSAGE possui uma estrutura única que deve sempre ser observada

A SOAP ENVELOP encapsula toda a mensagem. A SOAP HEADER possui informações de atributos e metadados da requisição. O elemento que contém os detalhes da mensagem é o SOAP BODY
<br />
<br />

### Entendendo o que é WSDL e XSD

<br />
WSDL - Web Service description language - é um documento xml que funciona como um contrato que mostra como funciona o SOAP

XSD - XML SCHEMA DEFINITION -  é um schema no formato xml que usado para definir a estrutura da dados que será validada no XML. Funciona como uma documentação que mostra como devem ser enviados dados para o serviço

<br />
<br />

### Aprenda o que são REST, API e JSON

<br />
O que é Rest?

REST -  Representational state transfer

Quando faço uma chamada rest recebo uma representação do estado da informação no momento em que fiz a requisição.

O SOAP é um protocolo, já o REST é um design de arquitetura para serviços web que roda sobre http. O rest pode trabalhar com vários formatos, o mais comum é o Json

O Rest permite integração entre aplicações, utiliza http e é de fácil leitura e compreensão.

O que é API ?

API - Application programing interface

É um conjunto de rotinas documentadas e disponibilizado por uma aplicação para que outras possam consumir suas funcionalidades.

O que é JSON?

JSON - Javascript Object Notation

Estrutura de chave e valor ou listas ordenadas para troca de mensagem entre sistemas

<br />
## Conceitos de arquitetura em aplicações para Internet
<br />

### Introdução a arquitetura de sistemas
<br />

TIPOS DE ARQUITETURA

Monolito -  aplicação única  

Gerenciamento de erros e volume de acesso
