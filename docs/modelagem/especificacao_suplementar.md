# Especificação Suplementar

## Introdução

A **Especificação Suplementar**, na engenharia de software, é a prática que envolve a organização de requisitos de um sistema em grupos ou categorias específicas. Essa estruturação visa aprimorar o entendimento, a gestão e a priorização dos requisitos ao longo do ciclo de desenvolvimento de software.

Para a especificação de requisitos, o Grupo 03 optou por adotar o modelo **FURPS+**.


## Modelo FURPS+: 

O modelo **FURPS+**,<a id = "Refb1" href = "#Ref1"><sup>1</sup></a> é uma ferramenta para a especificação de requisitos, sendo empregada para classificar os atributos de qualidade em um software. Essa abordagem se baseia em um acrônimo no qual cada letra representa categorias essenciais que um sistema de software deve abranger. A aplicação do modelo **FURPS+**, contribui para uma elicitação abrangente do sistema, prevenindo o esquecimento de categorias cruciais para o sucesso do software.

## Explorando o Acrônimo:

- **F** - **Funcionalidade (Functionality)**: Esta categoria aborda o cerne do sistema, referindo-se às funções e capacidades que o software deve disponibilizar. Os requisitos de funcionalidade definem o que o sistema deve realizar, incluindo tarefas, operações, recursos e comportamentos.

**Os requisitos funcionais definidos como mais importantes, estão disponíveis no artefato [Casos de uso](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/modelagem/casos_de_uso/)**


- **U** - **Usabilidade (Usability)**: A usabilidade concentra-se na experiência do usuário. Os requisitos de usabilidade englobam aspectos como facilidade de uso, design da interface, acessibilidade e qualquer elemento que influencie a experiência do usuário.

- **R** - **Confiabilidade (Reliability)**: A confiabilidade diz respeito à capacidade do sistema de funcionar de forma consistente e confiável, minimizando falhas. Isso inclui a tolerância a falhas, o tratamento de erros e a disponibilidade do sistema.

- **P** - **Desempenho (Performance)**: O desempenho está relacionado à eficiência e velocidade do sistema. Os requisitos de desempenho abrangem aspectos como tempo de resposta, capacidade de processamento e escalabilidade.

- **S** - **Suportabilidade (Supportability)**: A suportabilidade diz respeito ao suporte e manutenção do sistema ao longo do tempo. Isso inclui requisitos relacionados a atualizações, manutenção, documentação e treinamento.

- **+ (Outros)**: A categoria "+", também chamada de "Suplementar" ou "Qualidades do Sistema", pode incluir quaisquer outros requisitos que não se encaixem claramente nas categorias anteriores. Isso pode abranger requisitos legais, éticos, regulatórios, ambientais ou outros requisitos específicos do projeto.


## Especificação suplementar

A **tabela 01** mostra os requisitos não funcionais elicitados nos artefatos [Brainstorming](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/elicitacao/tecnicas/brainstorming/), [Introspecção](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/elicitacao/tecnicas/introspeccao/), [Observação](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/elicitacao/tecnicas/observacao/), [Questiónario](https://requisitos-de-software.github.io/2023.2-BRBMobilidade/elicitacao/tecnicas/questionario/), a sua funcionaliadde, a qual técnica de elicitação ele foi elicitado e a categoria relacionada ao mesmo. As categorias condizem com as da ferramenta **FURPS+**, ou seja:

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

| ID   | Funcionalidade                                       | Categoria   |
| -- | -------------------------------------------------- | --------- |
| IS13, BS14  | Garantir compatibilidade com sistemas operacionais Android e iOS. | U |
|  IS14 | Oferecer uma instalação e uso do aplicativo intuitivos e de fácil compreensão. | U |
|IS15, BS15  | Apresentar uma interface de usuário amigável e intuitiva para facilitar a navegação. | U |
| IS16, BS16, OBS10  | Fornecer feedback ao usuário sobre o status da consulta, recarga e outras interações relevantes. | R |
|IS17  | Implementar medidas de segurança robustas para proteger a privacidade dos usuários durante as interações no aplicativo. | R |
|  IS18 | Deve ser de código aberto e gratuito. | U |
|Q10   | O aplicativo deve fornecer segurança ao usuário com dados cadastrados. | R |
| Q12 | O aplicativo deve ser otimizado. | P |
|Q13  | O aplicativo deve possuir meios de acessibilidade para pessoas que possuam deficiências visuais, físicas ou auditivas. |  U|

<div style="text-align: center">
<p> Tabela 1: Requisitos categorizados com a ferramente FURPS+  - (Fonte: LELIS, Caio).</p>
</div>



## **Referências Bibliofgráficas**

><a id = "Ref1" href = "#Refb1">[1]</a>"Requisitos Suplementares", Disponível em[Link para acesso](https://www.cin.ufpe.br/~rls2/processo_tg/Metodologia%20S&B/guidances/concepts/supporting_requirements_C0220FE1.html#:~:text=Os%20Requisitos%20Suplementares%20s%C3%A3o%20categorizados,interface%20e%20regras%20de%20neg%C3%B3cio.), acesso em 06 de Dezembro de 2023:

## **Bibliografia** 
> [1] Especificação Suplementar. Repositório do Grupo SimpleNote da disciplina de Requisitos de Software da Universidade de Brasília, 2023. Disponível em: <https://requisitos-de-software.github.io/2023.1-Simplenote/modelagem/especificacao_suplementar/>. Acesso em: 24 de outubro de 2023.

> [2] "Vídeo youtube professor Sidartha Carvalho", Disponível em: [link](https://www.youtube.com/watch?v=FLSqAFtJ-kg), acesso em 24 de outubro de 2023


## **Histórico de Versões**

| Versão |          Descrição              |     Autor      |      Data      |   Revisor     |    Data de revisão    |  
|:------:|:-------------------------------:|:--------------:|:--------------:|:-------------:|:---------------------:|
|  1.0   | Criação do documento de especificação suplementar |   Caio Lelis   |   24/10/2023   | Gabriel Barbosa |  25/10/2023    |
|  1.1   | Trazendo refatoração e ajustes no documento |   Doan Filho   |   05/12/2023   | Gabriel Barbosa |  25/10/2023    |