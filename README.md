# AI PDI Dashboard

> Experimento de desenvolvimento assistido por IA para estruturar, acompanhar e visualizar o desenvolvimento profissional.

## Sobre o projeto

Este projeto explora como ferramentas de Inteligência Artificial podem apoiar o desenvolvimento profissional de forma prática, desde a **estruturação de um Plano de Desenvolvimento Individual (PDI)** até a criação de uma **interface para acompanhar sua evolução ao longo do tempo**.

A proposta surgiu a partir de uma necessidade real: transformar um planejamento profissional em algo que pudesse ser acompanhado continuamente, sem depender de controles manuais complexos.

O projeto utiliza IA para acelerar etapas de **estruturação, prototipação e desenvolvimento**, mantendo a validação humana como parte importante do processo.

> O dashboard apresentado neste repositório é um exemplo de aplicação dos prompts e não pretende ser um produto oficial ou uma solução única de PDI.

---

## Objetivos

* Explorar o uso de IA no desenvolvimento de ferramentas internas e pessoais.
* Transformar uma necessidade profissional em uma solução funcional.
* Criar prompts reutilizáveis para estruturação de PDI e desenvolvimento de um dashboard.
* Avaliar os limites e as possibilidades do desenvolvimento assistido por IA.
* Documentar o processo, decisões, aprendizados e iterações.
* Facilitar a adaptação da abordagem para outros contextos profissionais.

---

## Como funciona

O experimento é dividido em duas etapas principais:

```text
Contexto profissional
        ↓
Estruturação do PDI com IA
        ↓
Planejamento de objetivos e ações
        ↓
Dashboard para acompanhamento
        ↓
Uso e atualização contínua
        ↓
Avaliação e evolução
```

A IA é utilizada como ferramenta de apoio, mas as informações, objetivos, decisões e validações permanecem sob responsabilidade da pessoa que utiliza o processo.

---

## Estrutura do repositório

```text
ai-pdi-dashboard/
├── README.md
├── prompts/
│   ├── pdi.md
│   └── dashboard.md
├── docs/
│   └── experiment.md
└── examples/
    └── ana.md
```

### `prompts/`

Contém os prompts genéricos utilizados no experimento.

* [`pdi.md`](prompts/pdi.md) — estruturação de um PDI a partir do contexto profissional informado.
* [`dashboard.md`](prompts/dashboard.md) — criação de um dashboard para acompanhar o desenvolvimento profissional.

Os prompts utilizam placeholders para que possam ser adaptados a diferentes pessoas, cargos e contextos.

### `docs/`

Contém a documentação do experimento.

* [`experiment.md`](docs/experiment.md) — contexto, abordagem, processo de desenvolvimento, iterações, aprendizados e próximos passos.

### `examples/`

Contém exemplos de aplicação dos templates.

* [`ana.md`](examples/ana.md) — exemplo de aplicação dos prompts ao contexto da autora.

---

## Como utilizar

### 1. Estruture seu PDI

Acesse o [`prompt de PDI`](prompts/pdi.md) e substitua os campos entre colchetes pelas suas informações.

Exemplo:

```text
[SEU NOME]
[SEU CARGO]
[NOME DA EMPRESA]
[DATA DE INÍCIO]
[DATA FINAL]
```

Execute o prompt em uma ferramenta de IA de sua preferência.

O resultado será uma estrutura inicial de PDI que pode ser revisada e adaptada ao seu contexto.

### 2. Crie o dashboard

Utilize o [`prompt de dashboard`](prompts/dashboard.md).

Insira o PDI gerado anteriormente no campo indicado e forneça as informações sobre seu contexto e, quando aplicável, o Design System ou identidade visual que deverá ser utilizada.

A ferramenta de IA deverá primeiro analisar o contexto fornecido antes de implementar a solução.

### 3. Valide e itere

A primeira versão não deve ser considerada o resultado final.

Utilize o dashboard, identifique problemas e faça novas iterações.

Durante esse processo, observe:

* utilidade das informações;
* facilidade de atualização;
* clareza das métricas;
* consistência dos dados;
* experiência de uso;
* qualidade da implementação;
* necessidade real de cada funcionalidade.

---

## Princípios

### IA como acelerador, não como substituto da decisão

A IA pode ajudar a estruturar ideias, gerar código e acelerar protótipos, mas as decisões sobre objetivos, prioridades e resultados devem continuar sendo humanas.

### Simplicidade antes de complexidade

O dashboard deve resolver o problema proposto sem criar processos burocráticos ou métricas desnecessárias.

### Dados reais

O sistema não deve inventar métricas, acontecimentos ou resultados.

Quando uma informação não existir, ela deve ser cadastrada posteriormente ou simplesmente não ser exibida.

### Validação contínua

A solução deve ser utilizada e revisada na prática.

O objetivo não é apenas gerar uma interface, mas entender o que funciona, o que não funciona e onde a IA precisa de orientação humana.

### Reutilização

Os prompts devem ser suficientemente genéricos para serem adaptados a diferentes pessoas e contextos.

---

## O que este experimento busca avaliar

Mais do que criar um dashboard, este projeto busca observar o processo de desenvolvimento assistido por IA.

Entre os pontos de interesse estão:

* Quanto tempo a IA consegue economizar em etapas de prototipação?
* Quais tipos de decisões ainda exigem maior intervenção humana?
* Onde a IA tende a gerar soluções desnecessariamente complexas?
* Como melhorar os prompts para obter resultados mais consistentes?
* Quais partes da abordagem podem ser reutilizadas em outros contextos?
* Até onde esse tipo de abordagem pode ser aplicado em iniciativas internas?

---

## Resultado esperado

Ao final do experimento, espera-se ter:

* um PDI estruturado;
* um dashboard funcional para acompanhamento;
* prompts reutilizáveis;
* documentação do processo;
* registro das principais iterações e aprendizados;
* uma visão mais clara sobre as possibilidades e limitações do desenvolvimento assistido por IA.

---

## Status

**Em desenvolvimento / experimento**

O projeto está sendo desenvolvido iterativamente. A estrutura, os prompts e o dashboard podem sofrer alterações conforme novos aprendizados forem incorporados.

---

## Próximos passos

* [ ] Testar o dashboard durante o uso real.
* [ ] Registrar problemas e oportunidades de melhoria.
* [ ] Refinar os prompts a partir das iterações.
* [ ] Documentar os principais aprendizados do experimento.
* [ ] Avaliar quais partes da abordagem podem ser reutilizadas.
* [ ] Avaliar a possibilidade de compartilhar o experimento com outras pessoas da organização.

---

## Contexto

Este projeto foi iniciado como um experimento de desenvolvimento assistido por IA a partir de uma necessidade de acompanhamento do desenvolvimento profissional.

A intenção é documentar não apenas o resultado final, mas também o processo de construção e os aprendizados obtidos ao longo dele.
