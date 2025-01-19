---
date: 2013-03-28
tags: frontend
authors: oliveira-mark
title: Guia Incompleto Testes no Frontend
---

Você teste já fez testes no frontend? À primeira vista, pode parecer desnecessário testar interfaces e componentes. Afinal, você mesmo pode clicar em um botão e ver que ele está funcionando, certo? rs

Sim, mas existem situações em que configurar testes pode impedir que você cometa erros e quebre parte de sua aplicação. Veja alguns exemplos:

- **Alterações em componentes:** é comum surgir demandas de alteração ou criação de componentes que podem impactar o funcionamento de outros.
- **Simular uma API:** caso a API ainda não esteja pronta ou simplesmente para evitar requests desnecessárias, você pode usar mocks.
- **Simulação de cenários:** para garantir que sua aplicação funcione corretamente, você pode configurar seus testes para diferentes cenários.
- **Segurança e escalabilidade:** os testes dão a segurança de que as novas funcionalidades não vão quebrar sua aplicação.

São muitos benefícios. Para mim, o maior deles é a consciência tranquila ao fazer deploy.

> Este post tem como objetivo registrar os aprendizados que venho adquirindo sobre testes no frontend ao longo dos anos. Vou atualizar este material constantemente para que sirva como base de consulta sempre que eu precisar relembrar algo.

---

## Diferença entre Testes Unitários, de Integração e E2E

- **Testes de Unidade:** precisam ser simples e isolados do restante da aplicação. São usados com mais frequência no dia a dia e destinados a testar um componente, uma função ou elemento específico.

- **Testes de Integração:** têm como objetivo verificar o funcionamento correto da comunicação entre partes da sua aplicação. São especialmente úteis para testar integrações externas, como APIs, bancos de dados e outros serviços.

- **Testes E2E:** são os mais completos e custosos. Eles simulam a interação de um usuário com sua aplicação. Por exemplo: criando uma conta, fazendo login, salvando alterações.

Neste material, irei explorar as características, vantagens, ferramentas e exemplos de código dessas três modalidades de teste no frontend.

> Existem testes para o backend, que podem usar as mesmas ferramentas abordadas nesta publicação. Porém, testes no backend não são o foco deste material.

---

## 1. Testes de Unidade (ou Unitários)

Testes de unidade são uma boa prática de desenvolvimento que consiste em testar individualmente unidades, funções, métodos ou qualquer lógica da sua aplicação. Testam seu funcionamento de forma isolada e reportam possíveis erros.

No frontend, esses testes geralmente se concentram em garantir que componentes, como botões, formulários ou funções, funcionem conforme esperado.

Para facilitar esse processo, temos ferramentas como **Jest**, **Vitest**, **React Testing Library**, entre outras. Vou explicar melhor o uso dessas ferramentas ainda neste texto.

### Qual a vantagem do Teste de Unidade em relação aos outros?

A principal vantagem é a **rapidez e praticidade**. Depois de configurar os testes em todas as unidades necessárias, você pode rodar verificações sempre que fizer alguma alteração, garantindo que todas as unidades estejam funcionando.

Graças a essa simplicidade, a manutenção nos componentes e em seus respectivos testes é muito mais simples e prática em comparação com outros modelos que vamos apresentar ainda neste texto.

---

### Vamos ver na prática?

Agora vou te apresentar algumas ferramentas que facilitam o dia a dia de desenvolvimento com testes unitários. Além de explicar seus pontos fortes, irei mostrar sua configuração inicial e alguns exemplos de código.

#### Jest

- em breve

#### Vitest

- em breve

#### React Testing Library

- em breve
