# **Cenários**

## **Introdução**

Cenários são descrições evolutivas de situações em um ambiente composto por um conjunto ordenado de interações entre seus participantes, realizadas por usuários ou sistemas externos [2]. Diante disso, os cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos [2]. Portanto, é uma estratégia para elicitar a parte comportamental do software[1].

## **Modelo de Cenário**

Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste documento será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente [2], tal modelo pode ser observado a seguir na Tabela 1.

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Finalidade do cenário                                                                        |
| Contexto   | Descrição de pré-condições, local (físico) e tempo                                           |
| Recursos   | Objetos passivos com os quais os atores interagem                                            |
| Episódios  | Ação realizada por um ou vários atores com participação de outros atores utilizando recursos |
| Exceção    | Tratamento para uma situação excepcional ou de erro                                          |

<div style="text-align: center">
<p> Tabela 1: Modelo texto estruturado para descrição de cenários (Fonte: [2], 2022).</p>
</div>

## **Cenários identificados**

### **Cenário 1: Realizar recarga**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Realizar recarga do cartão através do aplicativo                                                                        |
| Contexto   | Local: Em qualquer lugar, Tempo: durante o dia (de 4:00 até 22:00), Pré-condições: acesso à internet, ter o aplicativo instalado, possuir um cartão cadastrado em sua conta.                                           |
| Recursos   | Smartphone, internet                                            |
| Episódios  | Usuário deseja recarregar seu saldo; O usuário alcança seu celular; Entra no aplicativo BRB Mobilidades; Efetua o Login com suas credenciais; seleciona a opção de realizar recarga; escolhe a maneira que desejará realizar a recarga; O usuário seleciona a opção de pix ou de boleto; O usuário efetua a recarga; |
| Exceção    |Smartphone descarregado; Perda de conexão com a internet; Não possuir cadastro no aplicativo; Não possuir cartões vinculados; Não possuir saldo em sua conta bancária|

<div style="text-align: center">
<p> Tabela 2: Descrição do cenário 1: "realização de recarga" - (Fonte: SOARES, Joel).</p>
</div>

### **Cenário 2: Visualização de linhas e horários**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Visualização de linhas e horários no aplicativo BRB Mobilidade                                                                     |
| Contexto   | Local: Em qualquer lugar, Tempo: durante o dia (de 4:00 até 22:00) <br> Pré-condição - Ter um celular <br> Pré-condição - Ter o aplicativo instalado <br> |
| Recursos   | Smartphone, internet                                            |
| Episódios  | Usuário deseja acompanhar o trajeto do seu ônibus; O usuário alcança seu celular; Entra no aplicativo BRB Mobilidades; Efetua o Login com suas credenciais; seleciona a opção linhas e horários; O usuário digita a linha ou o nome do destino; O usuario visualiza as linhas e horários; |
| Exceção    |Smartphone descarregado; Perda de conexão com a internet; Não possuir cadastro no aplicativo|

<div style="text-align: center">
<p> Tabela 3: Descrição do cenário 2: "Visualização de linhas e horários" - (Fonte: BASILIO, Guilherme).</p>
</div>


## **Bibliografia**

[1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 22 nov. 2023.

## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de cenarios |   Joel Soares   |   22/10/2023   |  |       dd/mm/yyyy      |
|  1.1   | Adição do cénario visualização de linhas |   Guilherme Basilio   |   24/10/2023   |  |       dd/mm/yyyy      |