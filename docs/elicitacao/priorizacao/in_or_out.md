# **In or Out**

## **Introdução**

Segundo Wiegers e Beatty (2013)<a id = "ELEM1" href = "#REF1" ><sup>1</sup></a>, a técnica de priorização de requisitos In or Out consiste em uma dos métodos mais simples de priorização. Esse procedimento consiste basicamente em reunir um conjunto de partes interessadas para determinar se cada requisito elicitado está dentro (IN) ou fora (OUT) dos planos de implementação do projeto. Busca-se listar apenas o mínimo necessário para a primeira entrega, revisitando as listas dos requisitos não prioritários no futuro e repetindo o processo novamente para eles.

## **Objetivo**

A principal meta desse artefato é listar os requisitos que possuem prioridade máxima de estarem na release inicial do projeto, abordando os requisitos que serão fundamentais para o devido funcionamento da aplicação.


## **Metodologia**

Utilizar-se-á de uma reunião com o usuário para priorizar os requisitos elicitados. Os detalhes dessa reunião podem ser verificados na tabela abaixo:

<br>

<center>

**Tabela 1:** Cronograma da Avaliação 1.


| Entrevistador(es) | Entrevistado(a) | Horário de Início | Horário de Fim |    Data    |    Local     |
| :----------------: | :-------------: | :---------------: | :------------: | :--------: | :----------: |
|  Caio Braga e Caio Lelis  |   Isaque Santos     |       15:00      |     15:30      | 06/12/2023 | Ailab(UnB)    | 

**Fonte:** BRAGA, Caio. FILHO, Doan.

</center>

## **Gravação de Priorização com o usuário**

<center>

**Vídeo 1:** Gravação da priorização In or Out

<iframe width="560" height="315" src="https://www.youtube.com/embed/S0kMXq2nVm8?si=_AaQwYTTQnr48Qrl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**Fonte:** BRAGA, Caio. LELIS, Caio. FILHO, Doan;

</center>

## **Requisitos Priorizados**

A tabela abaixo possui todos os requisitos elicitados com a sua prioridade associada.


<br>
<center>

**Tabela 1**: Requisitos não funcionais elicitados


| Identificação | Descrição | Fontes de elicitação | Prioridade |
| --- | --- | --- | --- |
| RF01 | Consultar saldo e extrato de uso do cartão de mobilidade. | IS01, BS01, OBS01, Q01 | In |
| RF02 | Acessar itinerários detalhados de ônibus, facilitando o planejamento de viagens. | IS02, BS02 | In |
| RF03 | Realizar recargas de créditos no cartão. | IS03, BS03 | In |
| RF04 | Interagir com um chatbot para esclarecer dúvidas e solicitar serviços relacionados ao transporte público. | IS04, BS04 | Out |
| RF05 | Suportar informações em tempo real sobre o status dos transportes públicos. | IS05, BS05 | In |
| RF06 | Integrar funcionalidades de navegação e mapas para otimizar rotas e facilitar a localização de paradas de ônibus para o usuário. | IS06, BS06 | In |
| RF07 | O aplicativo deve permitir cadastrar métodos de pagamento. | BS07, IS08 | In |
| RF08 | Deve ser possível personalizar a aparência da interface do usuário. | IS09 | In |
| RF09 | O usuário deve ser capaz de realizar cadastro. | BS08, IS10 | In |
| RF10 | O usuário deve ser capaz de realizar login. | IS11 | In |
| RF11 | O usuário deve fornecer sua localização. | BS09, IS12 | Out |
| RF12 | Fornecer a possibilidade de recuperar a senha do usuário. | BS10, IS07 | In |
| RF13 | O aplicativo deve permitir a visualização de linhas e horários. | OBS02 | In |
| RF14 | Deve ser possível fazer a recarga do saldo. | OBS03 | In |
| RF15 | Deve ser possível salvar rotas. | OBS04 | Out |
| RF16 | Deve ser possível alterar informações de cadastro. | OBS05 | In |
| RF17 | O aplicativo deve fornecer uma seção de comunicação direta. | OBS06 |Out |
| RF18 | O aplicativo deve fornecer ajuda com perguntas frequentes. | OBS07 | In |
| RF19 | Deve ser possível acessar informações sobre o histórico de atividades. | OBS08, BS12, Q02 | In |
| RF20 | Deve ser possível solicitar uma 2ª via do cartão desejado. | OBS09 | In |
| RF21 | O aplicativo possui mecanismo de visualização do saldo. | BS01, IS01, Q01 | In |
| RF22 | O aplicativo acessa o histórico de acessos. | Q02 | In |
| RF23 | O aplicativo tem meios de mecanismo de bloqueio de cartões. | Q03, BS11 | In |
| RF24 | O aplicativo tem meios de mecanismo de desbloqueio de cartões. | Q04 | In |
| RF25 | O aplicativo concede acesso às paradas próximas. | Q05 | In |
| RF26 | O aplicativo concede visualização a quantidade de passes. | Q06 | In |
| RF27 | O aplicativo tem opção de pagamento via cartão de crédito. | Q07 | In |
| RF28 | O aplicativo mostra ao usuário a previsão de depósito de dinheiro depositado. | Q08 | In |
| RF29 | O aplicativo mostra o histórico de transportes pegos pelo usuário ao longo do seu uso. | Q09 | In |
| RF30 | Possibilidade de favoritar linhas de ônibus. | BS13| Out |
| RNF01| Garantir compatibilidade com sistemas operacionais Android e iOS. | IS13, BS14 | In |
| RNF02| Oferecer uma instalação e uso do aplicativo intuitivos e de fácil compreensão. | IS14 | In |
| RNF03| Apresentar uma interface de usuário amigável e intuitiva para facilitar a navegação. | IS15, BS15 | In |
| RNF04| Fornecer feedback ao usuário sobre o status da consulta, recarga e outras interações relevantes. | IS16, BS16, OBS10 | In |
| RNF05| Implementar medidas de segurança robustas para proteger a privacidade dos usuários durante as interações no aplicativo. | IS17 | In |
| RNF06| Deve ser de código aberto e gratuito. | IS18 | In |
| RNF07| O aplicativo deve fornecer segurança ao usuário com dados cadastrados. | Q10 | In |
| RNF08 | O aplicativo deve rastrear os ônibus via GPS. | Q11 | Out |
| RNF09 | O aplicativo deve ser otimizado. | Q12 | In |
| RNF10 | O aplicativo deve possuir meios de acessibilidade para pessoas que possuam deficiências visuais, físicas ou auditivas. | Q13 | In |


**Fonte:** BRAGA, Caio. LELIS, Caio. FILHO, Doan. 

</center>



## **Referências bilbiográficas**

> <a id = "REF1" href = "#ELEM1" >[1]</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements (Developer Best 
Practices), 3rd Edition, Microsoft Press, 2013.



## **Histórico de versões** 

| Versão |          Descrição              |     Autor       |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:---------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criando In or Out  | Caio Braga, Caio Lelis e Doan Filho  |   03/10/2023   |  Joel Soaares  |       04/10/2023      |
