# **NFR Framework**

## **Introdução**

De acordo com Chung et al<a id="anchor_1" href="#REF1"><sup>1</sup></a>, o NFR Framework auxilia os desenvolvedores na abordagem dos requisitos não funcionais, permitindo sua expressão explícita, tratamento sistemático e utilização como diretrizes para conduzir o processo de desenvolvimento de forma racional. O NFR Framework emprega requisitos não funcionais (RNFs) para orientar o processo de design geral, dando prioridade aos requisitos não funcionais. Seu principal propósito é fornecer uma estrutura de representação para armazenar o design e a lógica por trás do desenvolvimento de requisitos.

### **O que é um softgoal?**

Os softgoals consistem em objetivos que não possuem uma definição clara nem prcisão nos critérios de satisfação. Eles são utilizados para representar os requisitos não funcionais e podem apresentar uma inter-relação, expressando como um softgoal influencia em outro<a id="anchor_2" href="#REF2"><sup>2</sup></a>.

### **Tipos de Softgoals**

Existem três categorias de softgoals conhecidas como: Softgoals NFR, Softgoals de Operacionalização e Softgoals de Afirmação. Cada uma delas é explicada a seguir:
<br><br>
<center>
<img src="../assets/tiposSoftgoals.png" width= "700px">
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
<img src="../assets/decomposicao.png" width= "700px">
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

## **Requisitos não-funcionais** 

De acordo com Sommerville <a id="anchor_3" href="#REF3"><sup>3</sup></a> (2011, p. 63), "Os requisitos não funcionais descrevem como o sistema faz algo, em oposição ao quê ele faz. Eles incluem critérios de desempenho, segurança, confiabilidade, usabilidade e outros aspectos que impactam a qualidade do sistema, mas não estão diretamente ligados às funcionalidades específicas do software."

Os requisitos não funcionais são originados a partir das necessidades dos usuários, restrições orçamentárias, políticas organizacionais, necessidade de interoperabilidade com outros sistemas de software ou hardware, bem como de influências externas, como regulamentos de segurança e legislações de privacidade.


Antes de aplicar o framework NFR, é necessário contextualizar o leitor acerca do que são requisitos não funcionais e quais foram elicitados no projeto. Abaixo, a tabela com esses requisitos:

| ID    | Requisito                  | Fonte |
| :---: | ---------------------------| :---: | 
| RNF01 | Oferecer uma instalação e uso do aplicativo intuitivos e de fácil compreensão. | [Brainstorming](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Brainstorming/) |
| RNF02 | Apresentar uma interface de usuário amigável e intuitiva para facilitar a navegação. | [Brainstorming](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Brainstorming/) | 
| RNF03 | Fornecer informações ao usuário sobre a recarga e outras interações relevantes. | [Brainstorming](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Brainstorming/) | 
| RNF04 | Deve fornecer informações quanto a obtenção do cartão | [Brainstorming](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Brainstorming/) | 
| RNF05  | O aplicativo deve fornecer ao usuário o feedback de suas ações em tempo real e rapidamente| [Observação](https://github.com/Requisitos-de-Software/2023.2-BRBMobilidade/blob/main/docs/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Observa%C3%A7%C3%A3o.md) |
| RNF06  | Deve ser possível filtrar o extrato ao longo do tempo | [Observação](https://github.com/Requisitos-de-Software/2023.2-BRBMobilidade/blob/main/docs/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Observa%C3%A7%C3%A3o.md) |
| RNF07  | Deve ser possível fazer solicitações triviais com 3 cliques | [Observação](https://github.com/Requisitos-de-Software/2023.2-BRBMobilidade/blob/main/docs/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Observa%C3%A7%C3%A3o.md) |
| RNF08 | Deve ser possível acompanhar a rota e o trajeto do ônibus num período de tempo e data selecionado | [Observação](https://github.com/Requisitos-de-Software/2023.2-BRBMobilidade/blob/main/docs/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Observa%C3%A7%C3%A3o.md)|
| RNF09  | Deve apresentar uma interface que facilita a prevenção de erros |  [Observação](https://github.com/Requisitos-de-Software/2023.2-BRBMobilidade/blob/main/docs/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Observa%C3%A7%C3%A3o.md)  |
| RNF10  | Garantir compatibilidade com sistemas operacionais Android e iOS.| [Introspecção](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Introspec%C3%A7%C3%A3o/)|
| RNF11 | Implementar medidas de segurança robustas para proteger a privacidade dos usuários durante as interações no aplicativo.|[Introspecção](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Introspec%C3%A7%C3%A3o/)|
| RNF12  | O aplicativo deve fornecer segurança ao usuário com dados cadastrados.| [Questionário](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Questionario/)|
| RNF13  | O aplicativo deve rastrear os ônibus via GPS.| [Questionário](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Questionario/)|
| RNF14  | O aplicativo deve ser otimizado.| [Questionário](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Questionario/)|
| RNF15  | O aplicativo deve ter atualização imediata de saldo.| [Questionário](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Elicita%C3%A7%C3%A3o/T%C3%A9cnicas/Questionario/)|

<div align="center">
Tabela 2: Contribuições - Fonte: BARBOSA, Gabriel. DE FRIAS, Miguel
</div>


Após analisar os requisitos elicitados, épossível perceber que os requisitos encaixam nas seguintes categorias:


- Confiabilidade
- Performance
- Portabilidade
- Usabilidade

Estes requisitos servirão como base para o uso do framework NFR.


## **Confiabilidade**

### **Sem Propagação**
<div align="center">
<img src="../assets/Conf1.png" width= "700px">
</div>
<div align="center">
Figura 6: Confiabilidade sem Propagação - Fonte: BRAGA, Caio. DE FRIAS, Miguel
</div>

### **Com Propagação**

<div align="center">
<img src="../assets/Conf2.png" width= "700px">
</div>
<div align="center">
Figura 7: Confiabilidade com Propagação - Fonte: BRAGA, Caio. DE FRIAS, Miguel
</div>

### **Cartão de Especificação**
| Classificação         | Confiabilidade | 
| ----------------------|--|
| Descrição             | Este softgoal refere-se à capacidade do sistema de fornecer um aparato de prevenção e sup te de erros e providenciar privacidade  |
| Justificativa         | A confiabilidade é fundamental para o devido funncionamento do aplicativo, uma vez que sem ela o usuário não é capaz de utilizar o software com segurança, suporte e transparência |
| Origem do requisito   | RNF11, RNF12|
| Critério de aceitação | Nenhum |
| Prioridade            | Alta prioridade |
| Conflito              | Nenhum |
| Historia              |  06 de nov. 2023 |

<div align="center">
Tabela 3: Cartão de especificação "Confiabilidade" - Fonte: BRAGA, Caio. DE FRIAS, Miguel
</div>

## **Performance**

### **Sem Propagação**
<div align="center">
<img src="../assets/Perf1.png" width= "700px">
</div>
<div align="center">
Figura 8: Performance sem Propagação - Fonte: BARBOSA, Gabriel
</div>

### **Com Propagação**

<div align="center">
<img src="../assets/Perf2.png" width= "700px">
</div>
<div align="center">
Figura 9: Performance com Propagação - Fonte: BARBOSA, Gabriel
</div>

### **Cartão de Especificação**
| Classificação         | Performance | 
| ----------------------|--|
| Descrição             | Este softgoal se refere a quão bem o sistema executa suas tarefas. Isso depende do hardware, software, carga de trabalho e outros fatores. Medimos a performance usando métricas específicas, como velocidade e latência. Otimizar a performance é importante para melhorar a eficiência e a experiência do usuário.  |
| Justificativa         | A performance é essencial para o devido funcionamento do aplicativo, uma vez que isso influencia diretamente na experiência do usuário  |
| Origem do requisito   | RNF05, RNF14, RNF15|
| Critério de aceitação | Nenhum |
| Prioridade            | Alta prioridade |
| Conflito              | Nenhum |

<div align="center">
Tabela 4: Cartão de especificação "Performance" - BARBOSA, Gabriel
</div>

## **Portabilidade**

### **Sem Propagação**
<div align="center">
<img src="../assets/Port1.png" width= "700px">
</div>
<div align="center">
Figura 10: Portabilidade sem Propagação - Fonte: BRAGA, Caio
</div>

### **Com Propagação**

<div align="center">
<img src="../assets/Port2.png" width= "700px">
</div>
<div align="center">
Figura 11: Portabilidade com Propagação - Fonte: BRAGA, Caio
</div>

### **Cartão de Especificação**
| Classificação         | Portabilidade | 
| ----------------------|--|
| Descrição             | Este softgoal refere-se à capacidade de executar ou mover o sistema de um ambiente ou plataforma para outro sem a necessidade de grandes modificações. Isso permite que o software seja utilizado em diferentes dispositivos ou sistemas operacionais, facilitando a adaptação e reutilização.  |
| Justificativa         | A portabilidade é fundamental para a experiência dos usuários, uma vez que o aplicativo será utilizados nos mais diversos dispositivos |
| Origem do requisito   | RNF10|
| Critério de aceitação | Nenhum |
| Prioridade            | Alta prioridade |
| Conflito              | Nenhum |

<div align="center">
Tabela 5: Cartão de especificação "Portabilidade" - BRAGA,  Caio
</div>



## **Usabilidade**

### **Sem Propagação**
<div align="center">
<img src="../assets/Usab1.jpg" width= "700px">
</div>
<div align="center">
Figura 12: Usabilidade sem Propagação - Fonte: DE FRIAS, Miguel
</div>

### **Com Propagação**

<div align="center">
<img src="../assets/Usab2.jpg" width= "700px">
</div>
<div align="center">
Figura 13: Usabilidade com Propagação - Fonte: DE FRIAS, Miguel
</div>

### **Cartão de Especificação**
| Classificação         | Usabilidade | 
| ----------------------|--|
| Descrição             | Este softgoal refere-se à facilidade com que os usuários podem interagir e utilizar o sistema de forma eficaz e satisfatória. Envolve elementos como a intuitividade da interface, a eficiência na realização de tarefas e a satisfação geral do usuário. É importante para garantir que os usuários tenham uma experiência positiva ao usar o sistema. |
| Justificativa         | A usabilidade é fundamental para a experiência dos usuários, uma vez que o a interface ser intuitiva e de fácil aprendizado é muito importante para a aplicação |
| Origem do requisito   | RNF01, RNF02, RNF05 E RNF09|
| Critério de aceitação | Nenhum |
| Prioridade            | Alta prioridade |
| Conflito              | Nenhum |

<div align="center">
Tabela 6: Cartão de especificação "Usabilidade" - DE FRIAS, Miguel
</div>


## **Bibliografia**
> PAIM, F. R. S., CASTRO, J. F. B. Enhancing Data Warehouse Design with the NFR Framework. Centro de Informática UFPE, Recife, 2019. Disponível em: http://wer.inf.puc-rio.br/WERpapers/artigos/artigos_WER02/paim.pdf. Acesso em: 06/11/2023

## **Referência Bibliográfica**

> <a id="REF1" href="#anchor_1">[1]</a> Chung, Lawrence; A. Nixon, Brian; Mylopoulos, John. Non-Functional Requirements in Software Engineering. Acesso em: 03 de novembro de 2023

><a id="REF2" href="#anchor_2">[2]</a> SILVA, R. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Tese (Mestrado em Engenharia de Software) - Centro de Informática, Universidade Federal de Pernambuco. Recife, p. 155. 2019. Acesso em: 03 de novembro de 2023

> <a id="REF2" href="#anchor_3">[3]</a>SOMMERVILLE, Ian. Engenharia de Software. 9ª edição. São Paulo: Pearson, 2011. Acesso em 05 de novembro de 2023



## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
| 1.0 | Estrutura do documento | Gabriel Barbosa |  06/11/2023 |  Miguel de Frias  | 06/11/2023 |
| 1.1 | Adiciona texto de SIG e Metodologia | Caio Braga |  06/11/2023 |  Miguel de Frias | 06/11/2023  |
| 1.2 | Completando documento | Caio Braga, Gabriel Barbosa e Miguel de Frias | 06/11/2023 | Gabriel Barbosa  |  06/11/2023  |