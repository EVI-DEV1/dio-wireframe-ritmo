# Ritmo — wireframe de média fidelidade

Página única de apresentação de um planejador de estudos. O projeto explora como comunicar uma proposta de valor e um próximo passo claro para quem precisa organizar o estudo em horários limitados.

## Objetivo e recorte

O público proposto são pessoas que conciliam estudo com outras atividades e precisam começar com um plano pequeno. Isso é uma hipótese de projeto; não houve pesquisa com participantes. A página deve permitir compreender o produto, conhecer seu funcionamento e identificar a ação principal: montar um plano.

O escopo é um wireframe estático de média fidelidade para desktop. Inclui hierarquia, conteúdo representativo, agrupamento e estados ilustrativos de FAQ. Não inclui cadastro, agenda funcional, pagamento, backend ou resultados de pesquisa. As funcionalidades descritas são propostas do conceito, não serviços disponíveis.

## Arquivos

- `wireframe.svg`: desenho vetorial editável de 1440 × 1880, com texto e formas, sem imagens externas.
- `index.html`: visualização local do desenho; basta abrir no navegador junto ao SVG.
- `decisoes.md`: relação entre escolhas, princípios de usabilidade e validação planejada.
- `images/`: capturas da revisão visual no navegador.

O SVG pode ser importado em um editor vetorial ou no Figma para revisão. A versão atual foi produzida diretamente em formato vetorial; não há arquivo nativo do Figma nem alegação de que o trabalho tenha sido realizado nele.

## Estrutura da página

1. Cabeçalho com marca, navegação reduzida e chamada principal.
2. Proposta de valor com exemplo de rotina semanal.
3. Três benefícios relacionados a meta, tempo e revisão.
4. Funcionamento em três passos.
5. Reforço da ação principal.
6. Perguntas frequentes com um item aberto como exemplo.
7. Rodapé com referências às seções.

## Decisões principais

Uma ação principal se repete com o mesmo rótulo para manter consistência. A rotina ilustrativa explica o produto sem exigir que a pessoa imagine uma agenda vazia. Blocos e espaços separam assuntos; tons neutros mantêm o foco na estrutura. O conteúdo é representativo, sem depoimentos, números de desempenho ou resultados de participantes inventados.

A primeira pergunta do FAQ aparece aberta para demonstrar a relação entre pergunta e resposta. A especificação propõe permitir abrir/fechar itens independentemente. A implementação futura deverá manter estado anunciado e operação por teclado. O wireframe não executa essas ações.

## Como revisar

Abra `index.html` ou `wireframe.svg`. Confira se a proposta, o funcionamento e a chamada principal são compreensíveis. Para editar, importe o SVG em um editor que preserve formas e texto. Arial pode ser substituída se não estiver disponível; isso exige conferir novamente as quebras.

A revisão visual foi feita no navegador, cobrindo os blocos superiores e inferiores, sem sobreposição ou corte nos textos observados. Não houve teste de usabilidade com participantes, auditoria de acessibilidade do produto implementado nem adaptação real para dispositivos móveis: reduzir o SVG apenas escala o desenho.

## Próxima validação

Pedir a participantes representativos que expliquem a proposta sem orientação; identifiquem onde começariam; encontrem como ajustar horários; e descrevam o que esperam ao escolher “Montar meu plano”. Registrar evidências e revisar o fluxo. Não há resultados dessa etapa nesta entrega.

## Referências

- DIO, Formação UI/UX Designer: Arquitetura de Produtos Digitais, Arquitetura da Informação, Introdução ao UX Design e Introdução ao UI Design.
- [Enunciado do desafio](https://web.dio.me/lab/criando-um-wireframe-de-media-fidelidade/learning/9ba752d5-e4ec-48d2-8dd6-c8a50dcfa44a).
- [Dez heurísticas de usabilidade — Nielsen Norman Group](https://www.nngroup.com/articles/ten-usability-heuristics/).

Este material é um estudo de interface e pode evoluir com a validação das hipóteses.
