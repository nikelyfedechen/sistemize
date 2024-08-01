# 🎨 Design System

**É importante saber**: Design system não é uma documentação e sim um PRODUTO que serve outros produtos. É um produto onde contém componentes reutilizáveis e mostra como aplicar cada um deles.

## Itens essenciais para um Design System:

- Introdução;
- Princípios;
- Instalação: Comunicação com Designers e Devs;
- Fundação (Foundation):
    - Cores;
    - Tipografias;
    - Sombras / Camadas de layers;
    - Grid;
    - Sons.
    - Ícones
- Recursos.

## A importância

- As equipes envolvidas no produto podem usar os padrões já estabelecidos;
- O time consegue colaborar mais;
- Consistência.

## Quando usar

- Principalmente para empresas grandes;
- Múltiplos produtos sem padrão visual;
- Necessidade de documentar escolhas visuais.

## Design System vs Style Guide (Guia de Estilo)

O Design system é mais robusto que o style guide. Ele documenta cada componente, enquanto o style guide apenas lista as decisões visuais para utilização.

### Style Guide

O style guide é um dos componentes do design system. É um documento que orienta o estilo visual de um projeto de design de interface. Nele consta as informações sobre cores, tipografia, ícones, grids, imagens e outras informações julgadas como importantes. É um projeto curto, pouco escalável, e que visa principalmente os aspectos visuais de uma interface.

## Tipos de Design System

- Estrito
    - Não flexível com extensa documentação;
    - Padrões devem ser mantidos;
    - Deve cobrir muitos cenários.
- Solto
    - Uso opcional;
    - Tem maior possibilidades de experimentação;
    - Deve ser mantido o equilíbrio entre estrito e variável demais.
- Modular
    - Tem partes intercambiáveis e reutilizáveis;
    - Maior dificuldade para implementação;
    - Ótimo para produtos extensos.

## O que pode ter em um Design System

O conteúdo de um Design system pode incluir guia de estilo, tom de voz da marca, princípios de conteúdo, padrões de de e-mail, biblioteca de componentes, trechos de código, etc.

## Atomic Design (Brad Frost)

É uma linha de raciocínio/metodologia formada por átomos moléculas, organismos, templates e páginas. Átomos são os primeiros elementos e os mais simples de uma interface. Ele pode ser os elementos de fundação como cor, tipografia, sombra e também de código html, como o input de texto.

## Hierarquia lógica de taxonomia

D**efine os grupos de organismos biológicos e dá nomes a eles com base em características comuns**. Para os profissionais da área, essa técnica de organização é importante porque estabelece uma hierarquia para os tipos encontrados na natureza.

## Tokens

São nomes que damos aos componentes (cores, tipografia, ícones, espaçamentos…) que contém no nosso design system. Os tokens devem levar em consideração alguns elementos para que seu nome seja significativo.

### Design Tokens (por Jina Anne, na época designer da SalesForce)

É a forma como vamos nos referir a todos os elementos de uma interface. São um tipo de variável que engloba vários elementos de estilo e que podem ser adicionados ao código como um arquivo de dados;

## 8 point grid

Esse tipo de espaçamento é largamente utilizado em construção de interface e é conhecido como 8 Point Grid, ou Grid de 8 pontos. Quando é utilizado esse padrão para construção da interface, é possível definir módulos de espaçamentos diferentes e aplicá-los nos espaços da interface. Dessa forma, é possível criar layouts muito consistentes.

## Elevação dos elementos

Elevação é resultante da variação de posicionamento de elementos no eixo Z, que demonstra quais elementos estão mais próximos à superfície e quais estão mais afastados. A sombra é o meio gráfico utilizado para representar essa elevação.

## Estilos

- neumorfismo
- esqueumorfismo
- flat design

## Componentes

- São elementos que se repetem na interface.
- Componentes bases e complexos;

### Estados dos componentes (Types of states)

Os estados comunicam o status dos elementos da UI ao usuário. Cada estado deve ser visualmente semelhante e não alterar drasticamente um componente, mas deve ter recursos claros que o diferenciam de outros estados e do layout ambiente.

## Organismos

Organismos são elementos que possuem agrupamentos de componentes diferentes.

## Auto-layout

O auto layout é uma propriedade que você pode adicionar a quadros e componentes no Figma. Ele permite que você crie designs que se adaptem à medida que seu conteúdo muda, sem a necessidade de redesign. Sendo assim, o auto layout no Figma facilita muito a vida de designers.

## Convenções

Uma convenção é um conjunto de acordos, padrões estipulados ou geralmente aceitos, normas, ou critérios, que nos países anglo-americanos frequentemente assume a forma de um costume.

## Typografia

Evitar o FOUC ou Flash of Unstyled Content.

### Escalas modulares (para tipografias)

É uma sequência de números que se relacionam uns com os outros de maneira significativa. Tem como base as proporções. Um bom uso das proporções é utilizar as menores. O ideal é utilizar a proporção na entrelinha também. A definição desta proporção será dada a partir de testes. Colocar em porcentagem é mais fácil.

### Fontes de sistemas

Android utiliza a fonte Roboto, o iOS usa a SF UI, o Windows usa a Segoe.

### Dica

- Para uma boa leitura, é recomendado que a linha de um parágrafo contenha de 60 a 100 caracteres. Mais que isso, a leitura se torna cansativa.

## Handoff

É o momento em que um profissional finaliza seu serviço numa parte do projeto e para para outro poder continuar a produção.

### Principais causas:

- falhas de comunicação;
- falta de documentação;
- falta de canais de conversa;
- não entender as limitações do outro;
- promover empatia entre as equipes;

### Princípios para colaboração

- o dev tbm é seu usuário;
- flexibilidade;
- o trabalho de design nunca termina;

### Melhores práticas

- envolver as equipes desde o início;
- usar canais de comunicação;
- fornecer recursos;

### Roteiro

- Gerais:
-- Cores;
-- Estilos tipográficos;
-- Componentes.
- Específico:
-- Especificações;
-- Funcionamento;
-- Fluxo navegável;
-- Protótipo;
-- Assets.
