# Especificação Suplementar

## Introdução

A **Especificação Suplementar**, na engenharia de software, é a prática que envolve a organização de requisitos de um sistema em grupos ou categorias específicas. Essa estruturação visa aprimorar o entendimento, a gestão e a priorização dos requisitos ao longo do ciclo de desenvolvimento de software.

Para a especificação de requisitos, o Grupo 03 optou por adotar o modelo **FURPS+**.


## Modelo FURPS+: 

O modelo **FURPS+** é uma ferramenta para a especificação de requisitos, sendo empregada para classificar os atributos de qualidade em um software. Essa abordagem se baseia em um acrônimo no qual cada letra representa categorias essenciais que um sistema de software deve abranger. A aplicação do modelo **FURPS+** contribui para uma elicitação abrangente do sistema, prevenindo o esquecimento de categorias cruciais para o sucesso do software.

## Explorando o Acrônimo:

- **F** - **Funcionalidade (Functionality)**: Esta categoria aborda o cerne do sistema, referindo-se às funções e capacidades que o software deve disponibilizar. Os requisitos de funcionalidade definem o que o sistema deve realizar, incluindo tarefas, operações, recursos e comportamentos.
<div style="text-align: center">
<p> Os requisitos funcionais definidos como mais importantes, estão disponíveis no artefato <a href="https://requisitos-de-software.github.io/2023.2-BRBMobilidade/Modelagem/03-casos-de-uso/">"Casos de uso"</a>.</p>
</div>

- **U** - **Usabilidade (Usability)**: A usabilidade concentra-se na experiência do usuário. Os requisitos de usabilidade englobam aspectos como facilidade de uso, design da interface, acessibilidade e qualquer elemento que influencie a experiência do usuário.

- **R** - **Confiabilidade (Reliability)**: A confiabilidade diz respeito à capacidade do sistema de funcionar de forma consistente e confiável, minimizando falhas. Isso inclui a tolerância a falhas, o tratamento de erros e a disponibilidade do sistema.

- **P** - **Desempenho (Performance)**: O desempenho está relacionado à eficiência e velocidade do sistema. Os requisitos de desempenho abrangem aspectos como tempo de resposta, capacidade de processamento e escalabilidade.

- **S** - **Suportabilidade (Supportability)**: A suportabilidade diz respeito ao suporte e manutenção do sistema ao longo do tempo. Isso inclui requisitos relacionados a atualizações, manutenção, documentação e treinamento.

- **+ (Outros)**: A categoria "+", também chamada de "Suplementar" ou "Qualidades do Sistema", pode incluir quaisquer outros requisitos que não se encaixem claramente nas categorias anteriores. Isso pode abranger requisitos legais, éticos, regulatórios, ambientais ou outros requisitos específicos do projeto.


## Especificação suplementar

A **tabela 01** mostra os requisitos não funcionais elicitados, sua funcionaliadde, a qual técnica de elicitação ele foi elicitado e a categoria relacionada ao mesmo. As categorias condizem com as da ferramenta **FURPS+**, ou seja:

- U - Usabilidade;
- R - Confiabilidade; 
- P - Desempenho;
- S - Suportabilidade;
- "+" - Outras categorias.


| ID   | Funcionalidade                                       | Categoria   |
| :--: | :--------------------------------------------------: | :---------: |
| BS11 | Oferecer uma instalação e uso do aplicativo intuitivos e de fácil compreensão. |     U       |
| BS12 | Apresentar uma interface de usuário amigável e intuitiva para facilitar a navegação. |    U        |
| BS13 | Fornecer feedback ao usuário sobre a recarga e outras interações relevantes. |    U        |
| BS16 | Deve fornecer informações quanto a obtenção do cartão |      R      |
| BS19 | Fornecer informações de contato |      U     |
| IS13 | Garantir compatibilidade com sistemas operacionais Android e iOS. |      S      |
| IS14 | Oferecer uma instalação e uso do aplicativo intuitivos e de fácil compreensão. |   U          |
| IS15 | Apresentar uma interface de usuário amigável e intuitiva para facilitar a navegação. |    U        |
| IS16 | Fornecer feedback ao usuário sobre a recarga e outras interações relevantes. |  P          |
| IS17 | Implementar medidas de segurança robustas para proteger a privacidade dos usuários durante as interações no aplicativo. |    R         |
| IS18   | Deve ser de código aberto e gratuito. |     S       |
| OBS11 | O aplicativo deve fornecer ao usuário o feedback de suas ações |      U      |
| OBS12 | Deve ser possível filtrar o extrato ao longo do tempo |      U      |
| OBS13 | Deve ser possível fazer solicitações triviais com 3 cliques |    U        |
| OBS14 | Deve ser possível acompanhar a rota e o trajeto do ônibus num período de tempo e data selecionado |       U     |
| OBS15 | Deve apresentar uma interface que facilita a prevenção de erros |      +      |
| Q11 | O aplicativo deve fornecer segurança ao usuário com dados cadastrados |        +    |
| Q12 | O aplicativo deve rastrear os ônibus via GPS |      +      |
| Q12 | O aplicativo deve ser otimizado |       P     |
| Q12 | O aplicativo deve ter atualização imediata de saldo |   U         |
| ES01 | O aplicativo deve ter o tempo de resposta de menos de 3 segundos para todas as ações realizadas pelos usuários. |      P      |
| ES02 | O aplicativo deve ser compatível com os sistemas operacionais Android e iOS. |      S      |

<div style="text-align: center">
<p> Tabela 1: Requisitos categorizados com a ferramente FURPS+  - (Fonte: LELIS, Caio).</p>
</div>

## Requisitos Especificados como + (Outros):

 **OBS15 - Deve apresentar uma interface que facilita a prevenção de erros :** 

O requisito tem a especificação de ***Requisito de interface***.

 **Q11: O aplicativo deve fornecer segurança ao usuário com dados cadastrados e Q12: O aplicativo deve rastrear os ônibus via GPS:**

Se tratam de requisitos com a especificação ***Requisito de segurança***.

Para melhor entendimento, a **tabela 02** nos mostra uma legenda para os id's dos requisitos presentes na **tabela 01.**


<div align="center">
  <table>
    <thead>
      <tr>
        <th><strong>ID</strong></th>
        <th><strong>Significado</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td align="center">B</td>
        <td align="center">Brainstorming</td>
      </tr>
      <tr>
        <td align="center">OBS</td>
        <td align="center">Observação</td>
      </tr>
      <tr>
        <td align="center">ES</td>
        <td align="center">Especificação Suplementar</td>
      </tr>
      <tr>
        <td align="center">Q</td>
        <td align="center">Questionário</td>
      </tr>
      <tr>
        <td align="center">IS</td>
        <td align="center">Introspecção</td>
      </tr>
    </tbody>
  </table>
</div>

<p style="text-align: center;">

Tabela 02 - Tabela de significado dos ID's dos requisitos. (Fonte:LELIS,Caio)

</p>


## **Referências Bibliofgráficas**
> [1] "Aprender 3", Disponivel em: [link](https://aprender3.unb.br/pluginfile.php/2692804/mod_resource/content/7/Lista%20de%20exerci%CC%81cios%20Modelagem%20de%20Requisitos%20-%20Modelagem%20de%20Requisitos-%20Use%20Case%20-%20Especificac%CC%A7a%CC%83o%20Suplementar.pdf), acesso em 24 de Outubro de 2023

> [2] "Vídeo youtube professor Sidartha Carvalho", Disponível em: [link](https://www.youtube.com/watch?v=FLSqAFtJ-kg), acesso em 24 de outubro de 2023


## **Bibliografia** 
> [1] Especificação Suplementar. Repositório do Grupo SimpleNote da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/>. Acesso em: 24 de outubro de 2023.


## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de especificação suplementar |   Caio Lelis   |   24/10/2023   | Gabriel Barbosa |  25/10/2023    |
