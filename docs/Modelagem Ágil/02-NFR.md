# **NFR Framework**

## **Introdução**

De acordo com Chung et al<a id="anchor_1" href="#REF1"><sup>1</sup></a>, o NFR Framework auxilia os desenvolvedores na abordagem dos requisitos não funcionais, permitindo sua expressão explícita, tratamento sistemático e utilização como diretrizes para conduzir o processo de desenvolvimento de forma racional. O NFR Framework emprega requisitos não funcionais (RNFs) para orientar o processo de design geral, dando prioridade aos requisitos não funcionais. Seu principal propósito é fornecer uma estrutura de representação para armazenar o design e a lógica por trás do desenvolvimento de requisitos.

### **O que é um softgoal?**

Os softgoals consistem em objetivos que não possuem uma definição clara nem prcisão nos critérios de satisfação. Eles são utilizados para representar os requisitos não funcionais e podem apresentar uma inter-relação, expressando como um softgoal influencia em outro<a id="anchor_2" href="#REF2"><sup>2</sup></a>.

### **Tipos de Softgoals**

Existem três categorias de softgoals conhecidas como: Softgoals NFR, Softgoals de Operacionalização e Softgoals de Afirmação. Cada uma delas é explicada a seguir:
<br><br>
<center>
<img src="../assets/tiposSoftgoals.png">
</center>
<font size="3"><b><p style="text-align: center">Figura 1: Tipos de Softgoals (Fonte: CHUNG et al, 2000)</b></font>
<br><br>

**Softgoals NFR:** representam os Requisitos Não-Funcionais e podem ser interconectados. Eles são organizados em catálogos e apresentados de forma hierárquica durante o desenvolvimento do projeto (CHUNG et al., 2000).

**Softgoals de Operacionalização:** representações de soluções de implementação destinadas a atender aos softgoals NFR ou a outros softgoals de operacionalização. Essas soluções englobam operações, processos, representações de dados, estruturação e restrições no sistema-alvo, com o objetivo de atender às necessidades indicadas pelos softgoals NFR e de operacionalização (CHUNG et al., 2000).

**Softgoals de Afirmação:**  permitem que as características do domínio, como prioridades e carga de trabalho, sejam consideradas e adequadamente incorporadas ao processo de tomada de decisão. Eles servem como justificativas para apoiar ou contestar a forma como os softgoals são priorizados, refinados e os componentes são selecionados. Os softgoals de afirmação oferecem razões para as decisões de desenvolvimento, tornando mais fácil a revisão, a justificação e a modificação do sistema, bem como a melhoria da rastreabilidade (CHUNG et al., 2000).

### **Softgoal Interdependency Graph (SIG)**

O NFR framework envolve a criação de um diagrama chamado "Softgoal Interdependency Graph (SIG)" para registrar as interdependências entre softgoals. Esse gráfico contém informações sobre as decisões de desenvolvimento, incluindo Requisitos Não-Funcionais, alternativas e justificativas. Ele permite verificar se os requisitos de alto nível estão sendo atendidos por meio de um procedimento de avaliação.

### **Interdependências**

<center>
<img src="../assets/decomposicao.png">
</center>
<font size="3"><b><p style="text-align: center">Figura 2: Decomposição de Softgoals (Fonte: CHUNG et al, 2000)</b></font>
<br><br>

As interdependências estabelecem as relações entre os softgoals. São dividas em:

**Refinamentos:** no NFR framework, os refinamentos são usados para estabelecer relações entre softgoals, sendo de quatro tipos: **decomposição NFR, operacionalização**, **afirmação** e **priorização**. A **decomposição** divide softgoals principais em mais específicos, a **operacionalização** define técnicas para atingir requisitos não funcionais, a **afirmação** apoia ou nega justificativas específicas do projeto e a **priorização** refina um softgoal em outro de mesmo tipo e tópico, poŕem com uma prioridade associada. Esses refinamentos ajudam a estruturar e analisar requisitos não funcionais em projetos.

**Contribuições**: os softgoals passam por refinamentos durante o projeto, onde softgoals descendentes podem influenciar os ascendentes de várias maneiras, como positiva, negativa ou parcialmente. Isso significa que a satisfação de um softgoal não é necessariamente absoluta, mas dentro de limites aceitáveis. Esse refinamento são especificações dos softgoals e são contribuições e existem dez tipos. Esses são:

| Contribuição       | Descrição  | Notação    |  
| ------------------ | ---------- | ---------- |
| *MAKE*  | FILHO com contribuição tão positiva a ponto de satisfazer o PAI sob a perspectiva dos envolvidos. | ++     | 
| *HELP*  | FILHO com contribuição positiva parcial, que sozinho não chega a satisfazer o PAI sob a perspectiva dos envolvidos. | +     |  
| *UNKNOWN*  | FILHO não afeta o PAI. | ?    |
| *HURT*   | FILHO com contribuição negativa parcial, que sozinho não chega a negar o PAI sob a perspectiva dos envolvidos. | -| 
| *BREAK*    | FILHO com contribuição tão negativa a ponto de negar o PAI sob a perspectiva dos envolvidos| --| 
| *SOME +*   | FILHO com contribuição positiva, cuja intensidade não se pode determinar. | SOME + | 
| *SOME -*   | FILHO com contribuição negativa, cuja intensidade não se pode determinar | SOME - | 
| *AND*    | “Pai” é satisfeito se_somente_se todos os “filhos” forem satisfeitos sob a perspectiva dos envolvidos| AND|
| *OR* | “Pai” é satisfeito se_somente_se um dos “filhos” é satisfeito sob a perspectiva dos envolvidos |OR|    
| *EQUAL* | Ambos compartilham o mesmo label| =| 

<div align="center">
Tabela 1: Refinamento, Fonte: BARBOSA. Gabriel
</div>

## **Metodologia**

O NFR Framework foi usado nesta documentação para apresentar os requisitos não funcionais que foram elicitados ao longo do projeto. Os diagramas confeccionados visam alcançar as funcionalidades especificadas do BRB Mobilidade, a partir da análise de possíveis eventos, considerando as tecnologias que já foram implementadas anteriormente na aplicação. A partir do documento de especificação suplementar elaboramos os SIGs.

Conclui-se, portanto, que os requisitos do projeto buscam abranger os softgoals subsequentes:

- Confiabilidade
- Desempenho
- Suportabilidade
- Usabilidade


## **Cartões de Especificação**


## **Conclusão**

## **Bibliografia**
> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf. Acesso em: 06/11/2023

## **Referência Bibliográfica**

> <a id="REF1" href="#anchor_1">[1]</a> Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em: 03 de novembro de 2023

><a id="REF2" href="#anchor_2">[2]</a> SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 03 de novembro de 2023

## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
| 1.0 | Estrutura do documento | Gabriel Barbosa |  06/11/2023 |   |   |
| 1.1 | Adiciona texto de SIG e Metodologia | Caio Braga |  06/11/2023 |   |   |
