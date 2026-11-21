# BarbeariaB2B

Prototipo navegavel de uma plataforma de agendamento e gestao para barbearias.

Projeto Interdisciplinar Pratico e Extensao II — Bacharelado em Engenharia de Software, UnIntegracao.
Instituicao atendida: Barbearia B2B — Jardim Munhoz Junior, Osasco (SP).

## Acesso

https://gitleviss.github.io/barbearia-b2b/

## O que o prototipo demonstra

- **Fluxo do cliente** (7 telas): entrar, escolher servico, escolher profissional, escolher data e horario, confirmar, comprovante e meus agendamentos.
- **Painel da barbearia** (4 telas): agenda do dia, servicos, equipe e indicadores.
- **Modelagem**: fluxo de navegacao, modelo de dados e arquitetura em camadas.

Os horarios ja reservados aparecem riscados e nao podem ser selecionados, o que demonstra a regra que elimina o conflito de agenda.

## Tecnologias

HTML5, CSS3 e JavaScript, sem dependencias externas. Os diagramas sao SVG autoral.
O backend projetado usa ASP.NET Core com Entity Framework Core e SQL Server, em arquitetura de camadas
(`BarbeariaB2B.Api`, `BarbeariaB2B.Domain`, `BarbeariaB2B.Infrastructure`).

Os dados exibidos sao ficticios e servem para demonstrar o comportamento da solucao.
