# **Casos de uso**

## **Introdução**

Um caso de uso é uma representação visual e textual de um conjunto de interações entre um sistema e seus atores (usuários externos) para atingir um objetivo específico. Casos de uso são uma técnica amplamente utilizada na engenharia de requisitos de software para documentar e compreender os requisitos funcionais de um sistema de software.

## **Metodologia**
Um diagrama de caso de uso é uma representação visual de casos de uso, atores e suas interações em um sistema de software. Esses diagramas são uma parte importante da modelagem de requisitos no processo de desenvolvimento de software e ajudam a representar de forma clara como os atores (usuários ou sistemas externos) interagem com o sistema para realizar tarefas específicas. Os diagramas de caso de uso são uma parte fundamental da UML (Unified Modeling Language), uma linguagem de modelagem amplamente utilizada na engenharia de software.


| Nome | Função | Elemento
|------|------|:-------:
| Ator | O ator é representado por um ícone, geralmente um stick figure, e representa uma entidade externa ao sistema que interage com ele. | <figure class="usecaseElement" style="width: 20%; display: flex;">![actor](../assets/ator.png)</figure>
| Caso de Uso | Os casos de uso são representados por elipses e descrevem as diferentes funcionalidades ou ações que o sistema pode realizar em resposta a interações com os atores. Cada caso de uso tem um nome que descreve a ação que representa. | <figure class="usecaseElement" style="width: 40%; display: flex;">![elipse](../assets/caso-de-uso.png)</figure>
| Sistema | Os sistemas são representados por retângulos. Eles contêm os casos de uso relacionados | <figure class="usecaseElement" style="width: 40%; display: flex;">![retangulo](../assets/sistema.png)</figure>
| Relações | As relações são represetadas por linhas de associação (setas) que conectam atores aos casos de uso ou relações entre casos de uso. | <figure class="usecaseElement" style="width: 40%; display: flex;">![flechas](../assets/relacoes.png)</figure>

<font size="2"><p style="text-align: center"><b>Tabela 1: Elementos do diagrama de casos de uso (Fonte: <a href="https://github.com/caioalvesbraga">BRAGA, Caio)</a></b></p></font>

<br><br>

É importante ressaltar que no contexto de diagramas de caso de uso, "extends" e "include" são tipos de relações que descrevem como os casos de uso interagem entre si em um sistema de software. Ambas as relações têm finalidades diferentes e são usadas para modelar diferentes tipos de comportamento no sistema.

- Relação de "Include" (Inclusão):
        A relação de "include" é usada para indicar que um caso de uso inclui outro caso de uso como parte de sua funcionalidade.
        Isso significa que o caso de uso base (o que inclui) sempre executa o caso de uso incluído como parte de sua própria execução.
        O caso de uso incluído é executado de forma transparente ao usuário do caso de uso base.
        A relação "include" é geralmente representada por uma seta tracejada, com um rótulo que indica "include".
        É usada para dividir a funcionalidade em partes menores e mais gerenciáveis que podem ser reutilizadas em vários contextos.

Exemplo de "include": Considere um caso de uso principal "Realizar Pagamento". Esse caso de uso pode incluir o caso de uso "Selecionar Método de Pagamento", que é uma parte essencial da ação de realizar um pagamento.

- Relação de "Extend" (Extensão):
        A relação de "extend" é usada para representar comportamentos opcionais e condicionais em um caso de uso, que podem ser estendidos além do fluxo básico.
        Isso significa que o caso de uso estendido é opcional e só ocorre sob certas condições específicas.
        A relação "extend" é geralmente representada por uma seta tracejada, com um rótulo que indica "extend".
        Ela permite modelar cenários alternativos sem poluir o fluxo básico de um caso de uso.

Exemplo de "extend": Em um caso de uso "Reservar Quarto de Hotel", pode haver uma extensão para lidar com "Atualização de Reserva", que só ocorre se o cliente desejar modificar a reserva após a confirmação.

<br>

## **Diagrama de Casos de Uso**

A figura 1 demonstra o diagrama de casos de uso.

<font size="3"><p style="text-align: center"></p></font>

<img src="../assets/diagrama-caso-de-uso.png" class="usecaseElement">

<font size="2"><p style="text-align: center"><b>Figura 1: Casos de uso do app BRB Mobilidade (Fonte: <a href="https://github.com/caioalvesbraga">BRAGA, Caio)</b></a></font>


## **Casos de Uso & Especificação**

 UC -> Caso de Uso

Modelo de tabela de Caso de Uso:

<center>


|**UC0X**|Titulo do UC|
| :----------: |:-----------|
|Autores|Autores do UC|
|Descrição|Descrição do UC|
|Atores|Atores do UC|
|Pré Condições|Pré Condições do UC|
|Fluxo Principal|Fluxo Principal do UC em topicos|
|Fluxo Alternativo|Fluxo Altenativo do UC em topicos|
|Fluxo de Exceção|Fluxo de exceção do UC em topicos|
|Pós Condições| Pos condições do UC|
|Rastreabilidade| Rastreabilidade do UC|

<font size="2"><p style="text-align: center"><b>Tabela 2: Modelo de tabela de Caso de Uso (Fonte: <a href="https://github.com/GuilhermeBES">BASILIO, Guilherme)</a></b></p></font>

</center>

Explicação dos elementos:

- **Atores:** Representa os atores, podendo ser pessoas, instituições ou até sistemas do site ou app, que interagem com o caso de uso diretamente<br>
- **Pré Condições:** Indica as condições para que pelo menos um dos fluxos seja atendido completamente <br>
- **Fluxo Principal:** Representa o fluxo que ocorrerá com mais frequência quando o usuário utilizar tal recurso representado no caso de uso<br>
- **Fluxo Alternativo:** Representa o fluxo mais relevante que ocorrerá com menos frequencia que o fluxo principal<br>
- **Fluxo de Exceção:** Representa a exceção do recurso representado no caso de uso, normalmente sendo a recusação da funcionalidade ou saída da mesma<br>
- **Pós Condições:** Indica as condições que obrigatoriamente ocorrerão após a realização de cada fluxo<br>
- **Rastreabilidade:** Indica a rastreabilidade utilizada pra criação do caso de uso<br>



### **UC01 - Fazer Login**

 A especificação de cada caso de uso pode ser observado a seguir na Figura 1.

 <center>

Tabela 1 – UC01

|**UC01**|**Fazer Login**|
| :----------: |:-----------|
|Autor|Guilherme Basilio|
|Descrição|Fazer Login no BRBMobilidade|
|Atores|> Usuário <br> > BRBMobilidade|
|Pré Condições|> Estar deslogado|
|Fluxo Principal|> Usuário acessa o BRBMobilidade <br> > Usuário clica no botão "Autenticação Interna" <br> > Usuário digita seu CPF <br> > Usuário digita sua senha <br> > Usuário ficará logado até sair|
|Fluxo Alternativo|> Usuário acessa o BRBMobilidade <br> > Usuário seleciona qual tipo de cartão possui <br> > Usuário clica no botão "Login" <br> > Usuário ficará logado até sair|
|Fluxo de Exceção|**Fluxo de Exceção 1 - CPF inválido** <br> > Aplicativo avisa que não foi possível realizar o login <br> **Fluxo de Exceção 2 - Esquecer a Senha** <br> > Usuário clica em "Esqueceu a Senha?" <br> Usuário recebe um e-mail para recuperar |
|Pós Condições|Usuário fica logado e pode realizar todas as ações|
|Rastreabilidade|RF10, IS11|

<font size="2"><p style="text-align: center"><b>Tabela 3: Fazer login (Fonte: <a href="https://github.com/GuilhermeBES">BASILIO, Guilherme)</a></b></p></font>

</center>

### **UC02 - Realizar recarga**

<center>

|**UC02**|**Realizar recarga**|
| :----------: |:-----------|
|Autor|Guilherme Basilio|
|Descrição|Adicionar crédito ao cartão BRB Mobilidade|
|Atores|> Usuário <br> > BRB Mobilidade|
|Pré Condições|> Ter um cartão cadastrado |
|Fluxo Principal|> Usuário acessa o BRB Mobilidade <br> > Usuário clica no botão "Realizar recarga" <br> > Usuário selecionar o método de pagamento <br> > Usuário digita quanto quer recarregar <br> > Usuário recarrega o cartão |
|Fluxo Alternativo|> Não possui fluxo alternativo |
|Fluxo de Exceção|**Fluxo de Exceção 1 - Você ainda não tem cartões vinculados** <br> > Aplicativo avisa que o usuário não tem cartões vinculados |
|Pós Condições| Usuário volta para a tela de inicio |
|Rastreabilidade| OBS03, IS03, IS08 |

<font size="2"><p style="text-align: center"><b>Tabela 4: Realizar recarga (Fonte: <a href="https://github.com/GuilhermeBES">BASILIO, Guilherme)</a></b></p></font>

</center>

### **UC03 - Visualizar linhas e horários**

<center>

|**UC03**|**Visualizar linhas e horários**|
| :----------: |:-----------|
|Autor|Guilherme Basilio|
|Descrição| Visualizar linhas e horários de ônibus|
|Atores|> Usuário <br> > BRB Mobilidade|
|Pré Condições|> Estar logado |
|Fluxo Principal|> Usuário acessa o BRB Mobilidade <br> > Usuário clica no botão "Linhas e horários" <br> > Usuário digita a linha ou o destino <br> > Usuário  visualiza as linhas e horários |
|Fluxo Alternativo|> Não possui fluxo alternativo |
|Fluxo de Exceção| --- |
|Pós Condições| Usuário irá ver o itinerário do ônibus desejado |
|Rastreabilidade| IS02, IS05, OBS02, OBS04 |

<font size="2"><p style="text-align: center"><b>Tabela 5: Visualizar linhas e horários (Fonte: <a href="https://github.com/GuilhermeBES">BASILIO, Guilherme)</a></b></p></font>

</center>

### **UC04 - Acompanhar cadastro/cartão**

<center>

|**UC04**|**Acompanhar cadastro de cartão específico**|
| :----------: |:-----------|
|Autor|Gabriel Barbosa|
|Descrição| Acompanhar cadastro de um cartão específico |
|Atores|> Usuário <br> > BRB Mobilidade|
|Pré Condições|> Ter feito o login no sitema <br> Ter cadastro em cartão específico |
|Fluxo Principal|> Usuário acessa o BRB Mobilidade <br> > Usuário clica no botão "Estudantil" (Um dos cartões específicos)<br> Faz login com o CPF <br> Acessa a página de acompanhamento de cadastro |
|Fluxo Alternativo|> Não possui fluxo alternativo |
|Fluxo de Exceção|**Fluxo de Exceção 1 - Você não possui cartão cadastrado** <br> > Usuário acessa o BRB Mobilidade <br> > Usuário clica no botão "Estudantil" (Um dos cartões específicos)<br> Não possui cadastro |
|Pós Condições| Usuário verá a o menu de opções que se pode fazer com o cartão específico |
|Rastreabilidade| IS10, OBS05, OBS08, OBS09 |

<font size="2"><p style="text-align: center"><b>Tabela 6: Acompanhar cadastro/cartão (Fonte: <a href="https://github.com/gabrie1barbosa">BARBOSA, Gabriel)</a></b></p></font>

</center>

### **UC05 - Vizualizar extrato de uso**

<center>

| UC02 | Informações |
| ----- | ---------- |
| Descrição | O usuário é capaz de checar o extrato de uso de determinado mês. |
| Ator | Usuário |
| Pré-condições | Acesso à internet, acesso ao app |
| Ação | O usuário acessa o seu extrato de uso |
| Fluxo principal | > O usuário acessa o aplicativo </br> > O usuário realiza o login </br> > O usuário acessa a seção "Extrato de uso" </br> > O usuário seleciona o mês desejado </br> > O usuário visualiza o extrato do mês selecionado </br>
| Fluxo alternativo |> O usuário acessa o aplicativo </br> > O usuário realiza o login </br> > O usuário acessa a seção "Menu" </br> > O usuário acessa a seção "Extrato de uso" </br> > O usuário seleciona o mês desejado </br> > O usuário visualiza o extrato do mês selecionado </br>|
| Fluxo de exceção | > O usuário acessa o aplicativo </br> > O usuário realiza o login </br> > O usuário acessa a seção "Menu" </br> > O usuário acessa a seção "Extrato de uso" </br> > O usuário seleciona o mês desejado </br> > O usuário seleciona um mês onde o cartão não foi utilizado </br> > O usuário verifica a resposta do aplicativo de que naquele mês não houve gastos</br>  |
| Pós-condições | O usuário agora está com as notificações ligadas e será notificado sobre novos eventos |
| Data de Criação | 25/10/2023 |
|Rastreabilidade| IS01, OBS01 |

<font size="2"><p style="text-align: center"><b>Tabela 7: Visualizar extrato de uso (Fonte: <a href="https://github.com/caioalvesbraga">BRAGA, Caio)</a></b></p></font>

</center>

## **Validação com o cliente**

<p>O grupo realizou uma reunião de validação com o nosso cliente, que foi gravada e está disponível para acesso <a href="https://www.youtube.com/watch?v=RNz-dVVlj0M">aqui.</a><br><br>Durante a reunião foi apresentado ao nosso cliente o nosso artefato de Casos de  Uso da aplicação, repassando cada tópico elaborado na documentação. Ao longo da videochamada foi abordado com o cliente se ele já conhecia os casos de uso oferecidos pelo aplicativo do BRB Mobilidade que estavam presentes no nosso diagrama, se o diagrama realmente reflete o uso real que ele teve com o sistema.</p>


## **Bibliografia**

>[1] BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

>[2] SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 11;

>[3] UML Use Case Diagrams. UML Diagrams. Disponível em:  https://www.uml-diagrams.org/use-case-diagrams.html. Acesso em: 24/10/2023.

>[4] Diagramas de Caso de Uso. Disponível em: https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml. Acesso em: 25/10/2023

> [5] Lucidchart. Diagrama de Caso de Uso UML. Disponível em: <<https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>>. Acesso em: 14 maio 2023.

> [6] FERNANDO, Sidney. Caso de Uso. Repositório da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/useCase/). Acesso em: 25 out. 2023.


## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de Casos de uso |  Guilherme Basilio  |   24/10/2023   | Joel Soares |       25/10/2023      |
|  1.1   | Adição da metodologia e Modelo de tabela |  Guilherme Basilio  |   24/10/2023   | Joel Soares |       25/10/2023      |
|  1.2   | Atualização metodologia e casos de uso |  Gabriel Barbosa  |   24/10/2023   | Joel Soares |       25/10/2023      |
|  1.3   | Adição de diagrama e correções pontuais |  Caio Braga  |   24/10/2023   | Joel Soares |       25/10/2023      |

