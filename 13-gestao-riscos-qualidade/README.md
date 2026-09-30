# Case 13 — Gestão de Riscos Aplicada à Qualidade de Software

## Visão geral

Este case apresenta uma iniciativa de gestão de riscos conduzida no contexto de Qualidade de Software, com participação multidisciplinar de QA, Produto, Desenvolvimento, Arquitetura e Privacidade.

A iniciativa teve como objetivo ampliar a análise de riscos relacionados às entregas e incorporar essa visão ao planejamento e à estratégia de testes.

O fórum esteve ativo entre **18 de março de 2025 e dezembro de 2025**.

> **Nota sobre confidencialidade:** nomes de sistemas, produtos, clientes e informações internas foram omitidos ou generalizados.

---

## Contexto

Com a evolução da atuação de QA, a análise de qualidade passou a considerar não apenas a execução dos testes, mas também os riscos envolvidos em cada entrega.

Embora a análise de riscos já fizesse parte do raciocínio aplicado ao planejamento e à execução dos testes, surgiu a necessidade de ampliar essa discussão para outras áreas envolvidas nas decisões de produto e tecnologia.

Foi então criado um fórum multidisciplinar de riscos, realizado por meio de reuniões no Microsoft Teams.

Participavam profissionais de:

- Produto;
- Desenvolvimento;
- Arquitetura;
- Privacidade;
- Qualidade de Software.

---

## Problema ou desafio

Os riscos relacionados às entregas podiam surgir sob diferentes perspectivas:

- regras de negócio;
- arquitetura;
- dependências técnicas;
- privacidade;
- integrações;
- comportamento funcional;
- impacto em produção;
- capacidade de validação antes da entrega.

Quando essas análises permanecem restritas a uma única área, existe o risco de decisões serem tomadas sem uma visão completa do impacto.

O desafio era promover uma discussão mais ampla e antecipada dos riscos, conectando diferentes perspectivas à estratégia de qualidade.

---

## Abordagem adotada

O fórum foi estruturado como um espaço de discussão multidisciplinar.

Durante as reuniões, os participantes avaliavam riscos relacionados às iniciativas e entregas, considerando diferentes perspectivas técnicas e de negócio.

De forma simplificada, o processo seguia a lógica:

**Identificação do risco → discussão multidisciplinar → avaliação de impacto → definição de ação ou tratamento → reflexo no planejamento e nas validações**

<p align="center">
  <img
    src="./docs/images/gestao-riscos-fluxo.png"
    alt="Representação anonimizada do fluxo de gestão de riscos"
    width="90%"
  />
</p>

> **Representação visual anonimizada:** a imagem acima foi recriada para demonstrar a lógica do processo, sem reproduzir informações internas ou confidenciais.

---

## Risco como parte da estratégia de testes

A gestão de riscos não ficou restrita ao fórum.

A análise de risco também fazia parte do planejamento e da execução dos testes, orientando decisões sobre profundidade, prioridade e tipo de validação.

Dependendo do contexto, um risco poderia levar a ações como:

- ampliação da cobertura de testes;
- priorização de cenários críticos;
- realização de testes exploratórios;
- regressão direcionada;
- validação de integrações;
- revisão de regras de negócio;
- alinhamento com Produto ou Desenvolvimento;
- execução de smoke tests antes da homologação;
- maior atenção a determinados fluxos antes da liberação.

O objetivo era utilizar os testes também como mecanismo de **mitigação de risco**.

---

## Risco e resposta de teste

O modelo abaixo representa exemplos da relação entre risco identificado e possíveis respostas de teste.

<p align="center">
  <img
    src="./docs/images/gestao-riscos-resposta-testes.png"
    alt="Representação anonimizada da relação entre riscos e respostas de teste"
    width="90%"
  />
</p>

A imagem deve representar relações como:

| Situação de risco | Possível resposta de Qualidade |
|---|---|
| Regra de negócio crítica | Maior cobertura e validação direcionada |
| Critério de aceite incompleto | Refinamento, alinhamento e testes exploratórios |
| Dependência entre sistemas | Validação de integração |
| Alteração em fluxo sensível | Regressão focada |
| Incerteza funcional | Exploração e alinhamento com Produto |
| Risco próximo à liberação | Smoke test e validação direcionada |

> Essa representação não corresponde a uma matriz formal utilizada pela empresa. Ela foi criada para demonstrar a lógica de análise e resposta aplicada ao processo.

---

## O que não chegou a ser implementado

A iniciativa não evoluiu para uma matriz formal de riscos ou para um processo institucional permanente.

O fórum foi interrompido em dezembro de 2025 em um contexto de mudanças organizacionais.

Por isso, este case representa:

- uma prática efetivamente realizada;
- aprendizados obtidos durante sua utilização;
- uma abordagem que estava em evolução;
- e não um framework corporativo finalizado.

---

## Resultados observados

Durante o período em que esteve ativo, o fórum contribuiu para:

- ampliar a discussão de riscos além do time de QA;
- aproximar diferentes áreas na análise das entregas;
- incorporar diferentes perspectivas à tomada de decisão;
- aumentar a atenção sobre impactos antes da validação;
- reforçar o uso de risco como critério no planejamento de testes;
- fortalecer a visão de Qualidade como responsabilidade compartilhada.

Não foram estabelecidas métricas quantitativas específicas para medir o impacto isolado do fórum.

---

## Competências demonstradas

- Gestão de riscos;
- testes baseados em risco;
- estratégia de testes;
- planejamento de testes;
- análise crítica;
- análise de impacto;
- comunicação;
- colaboração multidisciplinar;
- liderança de QA;
- governança;
- melhoria contínua.

---

## Aprendizados

A experiência reforçou que riscos de Qualidade raramente pertencem exclusivamente ao QA.

Produto pode identificar impactos de negócio.

Desenvolvimento pode identificar limitações técnicas.

Arquitetura pode antecipar dependências e impactos estruturais.

Privacidade pode identificar riscos relacionados à utilização de dados.

QA pode conectar essas informações à estratégia de validação.

O principal aprendizado foi que **quanto mais cedo o risco é discutido, maiores são as possibilidades de mitigá-lo antes que ele se transforme em um problema na entrega**.

---

## Observação sobre as imagens

As representações visuais deste case foram recriadas e anonimizadas com base no processo realizado.

Elas não reproduzem documentos internos, atas de reunião, telas ou informações confidenciais da organização.
