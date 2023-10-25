## **Casos de uso**

## **Introdução**

Um caso de uso descreve uma série de passos realizados pelo sistema, resultando em um resultado que é valioso e perceptível para uma pessoa específica que interage com o sistema. Cada caso de uso deve proporcionar um propósito significativo para o indivíduo que está usando o sistema.

## **Metodologia**

Para desenvolver os casos de uso, foram examinados e analisados os documentos que coletam os requisitos, e personas foram usadas para garantir e confirmar a validade dos casos de uso. Com base nesses dados, os casos de uso foram criados usando a ferramenta Lucidchart.

Legenda:

- UC -> Caso de Uso

Modelo de tabela de Caso de Uso:

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

<font size="2"><p style="text-align: center"><b>Tabela 1: Modelo de tabela de Caso de Uso (Fonte: <a href="https://github.com/GuilhermeBES">Guilherme Basilio)</a></b></p></font>

Explicação dos elementos:

- **Atores:** Representa os atores, podendo ser pessoas, instituições ou até sistemas do site ou app, que interagem com o caso de uso diretamente<br>
- **Pré Condições:** Indica as condições para que pelo menos um dos fluxos seja atendido completamente <br>
- **Fluxo Principal:** Representa o fluxo que ocorrerá com mais frequência quando o usuário utilizar tal recurso representado no caso de uso<br>
- **Fluxo Alternativo:** Representa o fluxo mais relevante que ocorrerá com menos frequencia que o fluxo principal<br>
- **Fluxo de Exceção:** Representa a exceção do recurso representado no caso de uso, normalmente sendo a recusação da funcionalidade ou saída da mesma<br>
- **Pós Condições:** Indica as condições que obrigatoriamente ocorrerão após a realização de cada fluxo<br>
- **Rastreabilidade:** Indica a rastreabilidade utilizada pra criação do caso de uso<br>

## **Casos de Uso & Especificação**

### **UC01 - Fazer Login**

 A especificação de cada caso de uso pode ser observado a seguir na Figura 1.

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

<font size="2"><p style="text-align: center"><b>Tabela 2: Fazer login (Fonte: <a href="https://github.com/GuilhermeBES">Guilherme Basilio)</a></b></p></font>

### **UC02 - Realizar recarga**

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

<font size="2"><p style="text-align: center"><b>Tabela 3: Realizar recarga (Fonte: <a href="https://github.com/GuilhermeBES">Guilherme Basilio)</a></b></p></font>

### **UC03 - Visualizar linhas e horários**

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

<font size="2"><p style="text-align: center"><b>Tabela 4: Visualizar linhas e horários (Fonte: <a href="https://github.com/GuilhermeBES">Guilherme Basilio)</a></b></p></font>

### **UC04 - Visualizar saldo**

### **UC05 - Vizualizar extrato de uso do cartão**

## **Bibliografia**

>[1] BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

>[2]SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 11;

>[3]UML Use Case Diagrams. UML Diagrams. Disponível em:  https://www.uml-diagrams.org/use-case-diagrams.html. Acesso em: 24/10/2023.

## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de Casos de uso |  Guilherme Basilio  |   24/10/2023   | Joel Soares |       dd/mm/yyyy      |
|  1.1   | Adição da metodologia e Modelo de tabela |  Guilherme Basilio  |   24/10/2023   | Joel Soares |       dd/mm/yyyy      |