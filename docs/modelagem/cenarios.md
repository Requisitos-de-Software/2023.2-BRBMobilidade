# **Cenários**

## **Introdução**

&emsp;&emsp;Cenários são descrições evolutivas de situações em um ambiente composto por um conjunto ordenado de interações entre seus participantes, realizadas por usuários ou sistemas externos [2]. Diante disso, os cenários são utilizados para descrever as situações de uso do sistema pelos seus usuários e os relacionamentos entre o sistema em desenvolvimento e outros sistemas externos, auxiliando no entendimento e na descoberta de novos requisitos [2]. Portanto, é uma estratégia para elicitar a parte comportamental do software[1].

## **Modelo de Cenário**

&emsp;&emsp;Existem cinco formas para se descrever cenários, são elas texto narrativo, texto estruturado, diagramas, imagens e animações ou simulações. A forma selecionada para apresentação dos cenários presentes neste documento será a de texto estruturado, a qual valida-se da utilização de linguagem natural semi-estruturada para melhor entendimento de cada cenário e validação dos requisitos por parte do cliente [2], tal modelo pode ser observado a seguir na Tabela 1.

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
<p> Tabela 2: Descrição do cenário 1: "Realização de recarga" - (Fonte: SOARES, Joel).</p>
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


### **Cenário 3: Consultar saldo disponível**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Consultar saldo disponível no aplicativo BRB Mobilidade                                                                     |
| Contexto   | Local: Tela do cartão no app, Tempo: durante o dia (de 4:00 até 24:00) <br> Pré-condição - Ter um celular <br> Pré-condição - Ter o aplicativo instalado <br> Pré-condição - Ter um cartão BRB Mobilidade|
| Recursos   | Smartphone, internet, cartão BRB mobilidade                                            |
| Episódios  | Usuário deseja visualizar saldo do cartão; O usuário alcança seu celular; Entra no aplicativo BRB Mobilidade; Efetua o Login com suas credenciais; seleciona a opção consultar saldo do cartão; O usuário seleciona o cartão desejado; O usuario visualiza seu saldo; |
| Exceção    |Smartphone descarregado; Perda de conexão com a internet; Não possuir cadastro no aplicativo; Não possuir cartão|

<div style="text-align: center">
<p> Tabela 4: Descrição do cenário 3: "Visualização de saldo" - (Fonte: LELIS, Caio).</p>
</div>



### **Cenário 4: Solicitar 2ªvia do cartão**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Deseja emitir a segunda via do cartão estudantil através do app                                                                    |
| Contexto   | Local – Selecionar o serviço de segunda via através da interface de acompanhamento do cadastro e cartão <br> Pré-condição - Ter um celular com acesso a internet <br> Pré-condição - Ter o aplicativo instalado <br> Pré-condição - Ter um cartão cadastrado |
| Recursos   | Smartphone, Internet   |
| Episódios  | O usuário entra o aplicativo; <br>  O usuário escolhe acompanhar o seu cartão; <br>  O usuário seleciona a opção de pedir segunda via do cartão |
| Exceção    |  É necessário que o usuário já tenha tido a 1ª via do cartão em algum momento; Celular sem suporte ao aplicativo; Celular sem bateria e internet |

<div style="text-align: center">
<p> Tabela 5: Descrição do cenário 4: "Solicitar 2ªvia do cartão" - (Fonte: BARBOSA, Gabriel).</p>
</div>

### **Cenário 5: Consultar pontos de recarga**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Acessar pontos de recarga fisicos do cartão|                                                                    |
| Contexto   | Local: Faculdade Tempo: durante o dia e noite  (de 05:30 a 23:30 ) <br> Pré-condição - Ter um celular <br> Pré-condição - Ter o aplicativo instalado <br> Pré-condição - Ter um cartão BRB Mobilidade|
| Recursos   | Smartphone, internet, cartão BRB mobilidade |                                           |
| Episódios  | Estudante ou usuário está usando seu cartão e deseja carrega-lo em algum local fisico pois só possui dinheiro em mãos<br> Estudante pega o celular <br>Estudante abre o aplicativo<br>Estudante faz login<br>Estudante clica em menu<br>Estudante clica em pontes de recarga<br>Estudante acessa algum local próximo|
| Exceção    |Smartphone descarregado; Perda de conexão com a internet; Não possuir cadastro no aplicativo; Não possuir cartão|

<div style="text-align: center">
<p> Tabela 6: Descrição do cenário 5: "Verificar pontos de recarga" - (Fonte: FILHO, Doan).</p>
</div>

### **Cenário 6: Consultar extrato de uso**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário consulte o consumo mensal do cartão de mobilidade|                                                                    |
| Contexto   | <p>_Local_ : Tela inicial do aplicativo</p> <p>_Tempo_: Aproximadamente 20 segundos</p> <p>_Pré-condição_ : o usuário necessita estar logado</p>|
| Recursos   | Acesso à internet<br>Aplicativo do BRB Mobilidade instalado no dispositivo<br>Cartão do BRB Mobilidade |                                           |
| Episódios  | O usuário seleciona a opção de "Extrato de uso" na página inicial.<br>O usuário seleciona o mês desejado para realizar a consulta.<br>O aplicativo filtra os usos do usuário para o mês selecionado.<br>O aplicativo exibe uma lista de usos mensais do cartão do usuário.|
| Exceção    |Erro de conexão com a internet.<br>Caso não haja nenhum uso do cartão registrado, o aplicativo deve exibir uma mensagem sinalizando que não há registros para o mês selecionado.|

<div style="text-align: center">
<p> Tabela 7: Descrição do cenário 6: "Consultar extrato de uso" - (Fonte: BRAGA, Caio).</p>
</div>

### **Cenário 7: Cadastrar método de pagamento**

| Elemento   | Descrição                                                                                    |
| ---------- | -------------------------------------------------------------------------------------------- |
| Objetivo   | Permitir que o usuário cadastre métodos de pagamento |                                                                    |
| Contexto   | Local: Tela de adicionar saldo no cartão, Tempo: durante o dia (de 4:00 até 24:00) <br> Pré-condição - Ter um celular <br> Pré-condição - Ter o aplicativo instalado <br> Pré-condição - Ter acesso à internet|
| Recursos   | Smartphone, internet, cartão BRB mobilidade <p>_Pré-condição_ : o usuário necessita estar logado</p>|                                         |
| Episódios  | O usuário dentro da opção de "Recarregar saldo",<br>  seleciona a opção método de pagamento e em seguida de cadastro de método de pagamento.<br> O usuário também pode adicionar/remover métodos de pagamento <br> ao acessar o seu perfil e entrar na seção métodos de pagamento.
| Exceção    |Erro de conexão com a internet;<br>Não possuir cadastro no aplicativo|

<div style="text-align: center">
<p> Tabela 8: Descrição do cenário 7: "Cadastrar métodos de pagamento - (Fonte: de Frias, Miguel).</p>
</div>


## **Bibliografia**

[1] Slides Requisitos - aula 10. Milene Serrano e Maurício Serrano. Elicitação, modelagem e análise.

[2] CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acesso em: 22 nov. 2023.

## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de cenarios |   Joel Soares   |   22/10/2023   | Miguel de Frias  |    24/10/2023   |
|  1.1   | Adição do cénario visualização de linhas |   Guilherme Basilio   |   24/10/2023   | Miguel de Frias |  25/10/2023 |
|  1.2   | Adição do cénario visualização de saldo disponível |   Caio Lelis   |   24/10/2023   |  |       dd/mm/yyyy      |
| 1.3   | Adição do cenário solicitar 2ªvia |  Gabriel Barbosa |  24/10/2023 |     |    dd/mm/yyyy   |
|  1.4  | Adição do cenário de pontos de recarga |   Doan Filho  |   24/10/2023   |  |       dd/mm/yyyy      |
|  1.5  | Adição do cenário de cadastrar métodos de pagamento |   Miguel de Frias |   25/10/2023   |  |       dd/mm/yyyy      |
