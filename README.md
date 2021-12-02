# Release Engineering Challenge 

  

## Sobre o Desafio:  

  

Esse é um teste feito para conhecer um pouco mais de cada candidato. Não é um teste objetivo e não há apenas uma solução que consideramos correta. O intuito é ser um estudo de caso com o propósito de conhecer o seu modo de trabalhar. 

  

## Introdução 

  

Temos neste repositório uma aplicação em Kotlin simples com uma API REST que responde um "Hello World" quando recebe um GET na porta 8080. (ex: curl http://localhost:8080/) 

  
 
* Crie uma pipeline no gitlab com as seguintes etapas: 
  - build 
  - teste1 
  - deploy2 

* 1 A etapa de testes consiste somente em execução de ferramentas de análise de código. Não é requerido a escrita de testes unitário, integração ou e2e para a aplicação. 

* 2 Deverá ser realizado em uma plataforma PaaS, ou em uma EC2 ou EKS na AWS, mas em todos os casos deverá o endpoint ficar de acesso público (DNS não é necessário). 

Requisitos não funcionais serão avaliados como: qualidade, segurança e observabilidade. 
As ferramentas de build, teste e deploy são de livre escolha, mas deverão ser defendidas durante o review do teste. 
Para mitigar eventuais custos utilize os planos free-tier das plataformas escolhidas. 

  

## Algumas dicas que podem ser importantes: 

  

* Invista tempo em escrever uma documentação de qualidade 

* Empregue quaisquer boas práticas que achar conveniente  

* Organize seu código 

* Seja eficiente e simples 

  

## Entrega do desafio: 

  

Clone esse repositório e realize todas as modificações, depois que terminar, compacte o repositorio e nos envie. Mantenha o .git no arquivo compactado, queremos analisar os seus commits. 

  

**Versão do Gradle: 4.10** 
