# **Backlog do produto**

## **Introdução**

O Backlog do Produto é um componente central da metodologia ágil, sendo uma lista dinâmica que compila as funcionalidades desejadas para um determinado produto. O responsável por sua concepção e priorização é o Dono do Produto (Product Owner).

O caráter dinâmico do Backlog do Produto se destaca à medida que ele evolui e se adapta em resposta a mudanças nos requisitos e na visão do produto. Essa adaptabilidade é fundamental para assegurar que o produto permaneça alinhado com as necessidades em constante evolução dos usuários e do mercado, garantindo que continue a ser relevante e eficaz.


## **Vídeo de entrevista com o PO**
<iframe width="560" height="315" src="https://www.youtube.com/embed/os3wIH667go?si=cxZP-nOB0j5Y03WU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


## **Metodologia**
Fizemos uma entrevista com o PO Isaque Santos, trazendo os artefatos validados e trazendo as historias de usuário 
Além disso, a rastreabilidade leva em consideração os requisitos elicitados no documento [Three Level Scale](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/prioriza%C3%A7%C3%A3o%20de%20requisitos/Three%20Level%20Scale/) construído pelo grupo. 

### **Estrutura do Product Backlog**

Para composição do Product Backlog foi feita a divisão em 3 partes:

<ol>
<li><b>Tema</b> : Corresponde o escopo do projeto;</li>
<li><b>Épico</b> : Corresponde a uma parcela significativa do trabalho que será subdividida em unidades menores, conhecidas como "Histórias de Usuário";</li>
<li><b>Feature</b> : Utilizado para descrever a funcionalidade em um nível mais abrangente.;</li>
<li><b>História de Usuário</b> : Constitui um nível de detalhamento mais profundo do item em questão.</li>
</ol>

#### **Modelo da tabela**

| Tema | Épico | Feature | Rastreabilidade | ID |História de Usuário |Prioridade|
| -------- | -------- | -------- |-------- |-------- |-------- |-------- |
| BRB-Mobilidade   | O épico a ser trabalhado   | A feature em questão   | O id do requisito presente na priorização   | USXX   | Detalhamento da história    | Baixa, Média ou Alta |

<font size="2"><p style="text-align: center"><b>Tabela 1: Modelo de tabela do Backlog (Fonte: <a href="https://github.com/GuilhermeBES">BASILIO, Guilherme)</a></b></p></font>

## **Product Backlog**

<table>
    <thead>
        <tr style="background-color: #0055B7; color: white;">
            <th style="border-style:solid;border-width:1px;text-align:center">Tema</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Épico</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Feature</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Rastreabilidade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="100%">BRB-Mobilidade</td>
        </tr>
        <tr>
              <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Consulta</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Cartão de mobilidade</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero consultar saldo e extrato de uso do cartão de mobilidade</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Itinerário detalhado de ônibus</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, desejo consultar itinerários detalhados de ônibus</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
        </tr>
            <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Recarga</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Recarga de saldo no cartão</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-14</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US03</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero fazer recarga do saldo do cartão</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
    </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Suporte</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Chatbot</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, desejo interagir com um chatbot para esclarecer dúvidas e solicitar serviços relacionados ao transporte público</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Baixa</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Estabilidade</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Informações em tempo real</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu,como usuário regular, desejo suportar informações em tempo real sobre o status dos transportes públicos</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
        </tr>
            <tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Integração</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Navegação e Mapas</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-28</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US06</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Integrar funcionalidades de navegação e mapas</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
    </tr>
    <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Pagamento</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Métodos de pagamento</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-07</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero cadastrar métodos de pagamento</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
    </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Autenticação</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Cadastro e login</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-09 e RF-10</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero realizar cadastro</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Baixa</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Consultas</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Fornecimento da localização do usuário</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-11</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US09</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero fornecer localização</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Baixa</td>
        </tr>
        <!-- <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Consultar extrato do cartão de mobilidade</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US10</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero consultar extrato do cartão de mobilidade</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
        </tr> -->
        <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Previsão de depósito de dinheiro</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-29</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US11</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero ver a previsão de depósito de dinheiro</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
    </tr>
    <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Informações</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Visualização de linhas e horários de ônibus</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-13</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US12</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero visualizar as linhas e horários de ônibus</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
    </tr>

<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Seção de comunação direta</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US15</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário, desejo ter uma seção dentro do aplicativo dedicada à comunicação direta com o suporte ao cliente para poder relatar problemas, fazer perguntas ou fornecer feedback facilmente.</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
</tr> 
    <tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="5">Pagamento</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Garantia de atualização imediata do saldo do cartão</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RNF-10</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US24</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deverá garantir atualização imediata do saldo do cartão</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Possibilidade de pagamento via pix</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-07</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US25</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Possibilitar o pagamento via pix</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
</tr>
    <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Recarga do saldo do cartão</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-14</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US13</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero fazer recarga do saldo do cartão</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
    </tr>
    <tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Possibilitar o pagamento via cartão de crédito</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-28</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US20</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Possibilitar o pagamento via cartão de crédito</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
    </tr>
    <tr>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Permição de cadastro de métodos de pagamento</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">RF-07</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero cadastrar métodos de pagamento</td>
        <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
    </tr>
    <!-- <tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Compartilhamento de viagens com amigos e familiares</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US15</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário regular, quero compartilhar viagens com amigos e familiares</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
</tr> -->
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Segurança</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Segurança aos dados cadastrados</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RNF-05</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US16</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como usuário, gostaria de ter garantido a segurança aos meus dados cadastrados</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Segurança aos dados cadastrados</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RNF-07</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US21</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">O sistema deve fornecer segurança aos dados cadastrados</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="3">Notificações</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Fornecer notificações de depósito ao usuário</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-31</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US17</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Fornecer notificações de depósito ao usuário</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Outros</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Solicitar uma 2ª via do cartão de mobilidade</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-20</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US18</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Solicitar uma 2ª via do cartão de mobilidade</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Notificações</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Notificações de depósito ao usuário</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-31</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US19</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"> O sistema deve fornecer notificações de depósito ao usuário</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Segurança</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Segurança aos dados cadastrados</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-15</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US20</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">O sistema deve fornecer segurança aos dados cadastrados</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Rastreamento</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Rastreamento de ônibus via GPS</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-15</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US21</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário regular, quero rastrear os ônibus via GPS</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Desempenho</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Otimização do aplicativo</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-15</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US22</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">O aplicativo deve ser otimizado para carregar rapidamente e ter tempos de resposta rápidos.</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Cartão Mobilidade</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Atualização do saldo do cartão</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RNF-09</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US22</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Otimizar o aplicativo para uso eficiente</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Alta</td>
</tr>
<!-- <tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="1">Fornecer notificações de eventos e promoções</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle">RF-</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle">US28</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="1">Fornecer notificações de eventos e promoções</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="1">Média</td>
</tr> --> 
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="2">Histórico</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="1">Histórico de transportes do usuário</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle">RF-30</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle">US30</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="1">Eu, como usuário, gostaria de ter acesso ao meu histórico de transporteso</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="1">Baixa</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Acesso a informações sobre o histórico de atividades</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">RF-19</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">US18</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Acesso a informações sobre o histórico de atividades</td>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Média</td>
</tr>
<tr>
    <td style="border-style:solid;border-width:1px;text-align:center;vertical-align=middle" rowspan="5">Acessibilidade</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Fornecimento de suporte para deficientes visuais</td>
    <td style="border-style=solid;border-width:1px;text-align:center;vertical-align=middle">RNF-11</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle">US27</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Possibilitar o pagamento via cartão de crédito</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Alta</td>
</tr>
<tr>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Previsão de depósito de dinheiro</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle">RNF-11</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle">US28</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Mostrar ao usuário a previsão de depósito de dinheiro</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Média</td>
</tr>
<tr>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Histórico de transportes do usuários</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle">RNF-11</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle">US29</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Fornecer suporte para deficientes físicos</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Baixa</td>
</tr>

<tr>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Personalizar aparência da interface </td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowsa>RNF-11</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle">US08</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1"> Eu, como usuário, desejo poder personalizar a aparência da interface do aplicativo para tornar a experiência de uso mais agradável e adaptada ao meu gosto pessoal.</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Baixa</td>
</tr>

<tr>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Fornecimento de ajuda com perguntas frequentes </td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle">RNF-11</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle">US16</td>
    <td style="border-style=solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Eu, como usuário, desejo ter acesso a uma seção de perguntas frequentes dentro do aplicativo para encontrar respostas para dúvidas comuns sem a necessidade de entrar em contato com o suporte ao cliente</td>
    <td style="border-style:solid;border-width=1px;text-align:center;vertical-align=middle" rowspan="1">Alta</td>
</tr>

</tbody>
</table>

<div align="center">
<p> <b>Tabela 2</b>: Backlog do produto (Fonte: autores, 2023). </p>
</div>

## **Referência bibliografica**

> Milene Serrano e Maurício Serrano (2017).

## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento com introdução |   Guilherme Basilio   |   05/11/2023   | Miguel de Frias |  05/11/2023   |
|  1.1   | Adição da metodologia |   Guilherme Basilio   |  06/11/2023  | Miguel de Frias |  05/10/2023   |
|  1.2   | Elaboração do product backlog | Guilherme Basilio e Joel Soares |  06/11/2023  | Miguel de Frias |  06/11/2023 |

