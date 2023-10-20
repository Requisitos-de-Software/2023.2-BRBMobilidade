# **Introspecção**

## **Introdução**

<p style="text-align: justify;">
&emsp;&emsp;O BRB Mobilidade representa uma peça fundamental na mobilidade urbana, desempenhando um papel crucial no transporte do Distrito Federal. Para garantir o sucesso de seu desenvolvimento, a introspecção de requisitos de software surge como uma prática essencial. Neste documento, propomos uma análise abrangente que aborde os objetivos específicos do projeto, esclareça os requisitos funcionais e não-funcionais essenciais, considere possíveis restrições, avalie os riscos pertinentes e estabeleça um cronograma estruturado. Através dessa abordagem reflexiva, buscamos oferecer um guia sólido para o desenvolvimento eficiente do BRB Mobilidade.
</p>

## **Metodologia**

<p style="text-align: justify;">
&emsp;&emsp;A introspecção foi feita individualmente pelos integrantes *Guilherme Basilio* e *Miguel de Frias*. Após cada membro do grupo ter realizado a análise individual e a introspecção de requisitos para a plataforma, os resultados foram consolidados em uma tabela, contemplando os Requisitos Funcionais e os Requisitos Não-Funcionais. Concluída essa etapa, procedemos a uma revisão do aplicativo escolhido pelo grupo, verificando se os requisitos elicitados durante o processo estavam ou não incorporados no sistema. Esse exercício de avaliação permitiu uma análise abrangente da adequação do aplicativo em relação às necessidades identificadas, fornecendo insights valiosos para o desenvolvimento contínuo da BRB Mobilidade.
</p>

## **Tabelas de Requisitos**

<p style="text-align: justify;">
&emsp;&emsp;As tabelas abaixo apresentam os requisitos de software identificados durante a introspecção do projeto BRB Mobilidade. Cada requisito recebeu uma identificação específica no formato 'IS' seguido por um número, e foi detalhadamente descrito. Além disso, cada requisito foi categorizado como um dos seguintes:
</p>


RFx: Requisitos Funcionais nºx - Refere-se ao comportamento ou funcionalidade que o software deve exibir para atender às necessidades dos usuários.

RNFx: Requisitos Não-Funcionais nºx - Refere-se a atributos que o software deve possuir, como desempenho, segurança e usabilidade, sem descrever diretamente o comportamento do software.

ISx: Requisito nºx elicitado pela introspecção.

### **Tabela dos Requisitos Funcionais**

| Tipo   | Funcionalidade                                       | ID   | Implementado |
| :---:  | :--------------------------------------------------: | :---: | :----------: |
| RF01   | Consultar saldo e extrato de uso do cartão de mobilidade. | IS01 | Sim |
| RF02   | Acessar itinerários detalhados de ônibus, facilitando o planejamento de viagens. | IS02 | Sim |
| RF03   | Realizar recargas de créditos no cartão. | IS03 | Sim |
| RF04   | Interagir com um chatbot para esclarecer dúvidas e solicitar serviços relacionados ao transporte público. | IS04 | Sim   |
| RF05   | Suportar informações em tempo real sobre o status dos transportes públicos. | IS05 | Sim     |
| RF06   | Integrar funcionalidades de navegação e mapas para otimizar rotas e facilitar a localização de paradas de ônibus. | IS06 | Sim    |
| RF07   | O aplicativo deve permitir cadastrar métodos de pagamento. | IS08 | Sim     |
| RF08   | Deve ser possível personalizar a aparência da interface do usuário. | IS09 |  Não    |
| RF09   | O usuário deve ser capaz de realizar cadastro | IS10 |    Sim          |
| RF10   | O usuário deve ser capaz de realizar login | IS11 |        Sim      |
| RF11   | O usuário deve fornecer sua localização | IS12 |      Sim        |

<div style="text-align: center">
    <p> <b>Tabela 1</b>: Tabela dos Requisitos Funcionais Elicitados. (Fonte: Miguel de Frias e Guilherme Basilio, 2023).</p>
</div>

### **Tabela dos Requisitos Não Funcionais**
| Tipo   | Funcionalidade                                       | ID   | Implementado |
| :---:  | :-------------------------------------------------: | :---: | :----------: |
| RNF12  | Garantir compatibilidade com sistemas operacionais Android e iOS.                                       | IS13 |       Sim       |
| RNF13  | Oferecer uma instalação e uso do aplicativo intuitivos e de fácil compreensão.                            | IS14 |     Sim         |
| RNF14  | Apresentar uma interface de usuário amigável e intuitiva para facilitar a navegação.                    | IS15 |    Sim          |
| RNF15  | Fornecer feedback ao usuário sobre a recarga e outras interações relevantes.        | IS16 |      Não        |
| RNF16  | Implementar medidas de segurança robustas para proteger a privacidade dos usuários durante as interações no aplicativo. | IS17 |      Sim        |
| RNF17  | Deve ser de código aberto e gratuito.                                                                  | IS18 |      Sim        |

<div style="text-align: center">
    <p> <b>Tabela 2</b>: Tabela dos Requisitos Não Funcionais Elicitados. (Fonte: Miguel de Frias e Guilherme Basilio, 2023).</p>
</div>

## **Bibliografia**

- SALES, André Barros. Plano de ensino da disciplina. Disponível em: <<https://aprender3.unb.br/pluginfile.php/2692717/mod_resource/content/1/Exemplo%20de%20Cronograma.pdf>>. Acesso em 01 de outubro de 2023.
- 1library. Engenharia de Requisitos. Disponívem em: <<https://1library.org/article/an%C3%A1lise-de-documentos-t%C3%A9cnicas-para-elicita%C3%A7%C3%A3o-de-requisitos.qor9dxjq>>. Acesso em: 03 de outubro 2023.


## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criando o artefato |  Miguel de Frias, Guilherme Basilio  |  01/10/2023  | Doan Filho | 04/10/2023 |

