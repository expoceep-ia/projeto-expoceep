# Radar de Evasão

Sistema que prevê o risco de um aluno largar a escola e mostra **por quê**. A escola coloca os
dados que já tem, frequência, notas, reprovações, idade em relação à série, e o radar avisa
antes que seja tarde. Projeto do curso de IA e Dados para a EXPOCEEP.

## Progresso

```
▱▱▱▱▱▱▱▱▱▱▱▱▱▱   0 de 6 tarefas entregues
```

Três tarefas de dados, uma de interface, uma de infra e uma de documentação. Atualizado em cada merge.

## Onde a gente trabalha

| | |
|---|---|
| Conversa | [Discord da equipe](https://discord.gg/ETpCTvchh) |
| Tarefas | [issues](../../issues), agrupadas nas [milestones](../../milestones) |

No Discord sai o briefing de segunda, o horário de dúvida e o "peguei essa issue". Dúvida no
canal, não no direct: a resposta serve pros outros também.

O porquê de cada decisão fica no Pull Request, e PR mergeado continua aberto pra leitura pra
sempre, com os comentários de linha do lado do código que mudou. Pra entender por que alguma
coisa está do jeito que está, procura o PR que mexeu nela em **Pull requests → Closed**.

## Começar

Leia o [CONTRIBUTING.md](CONTRIBUTING.md). Ele tem o passo a passo: pegar uma tarefa, criar a
branch, abrir o Pull Request.

Depois, a pasta `docs/`:

- [docs/roadmap.md](docs/roadmap.md) — o plano do MVP e as tarefas.
- [docs/course-roadmap.md](docs/course-roadmap.md) — o que aprender em cada módulo.
- [docs/PITCH-FEIRA.md](docs/PITCH-FEIRA.md) — como apresentar na ExpoCEEP: o que é o produto,
  em que ordem contar, a fala de cada um e as perguntas que os avaliadores costumam fazer.

## Estrutura

```
docs/    roadmap, roteiro do curso e pitch
```

Ainda não tem código, de propósito: criar `baixar.py`, `limpar.py`, `treinar.py` e `app.py` é o
trabalho das primeiras tarefas. Por isso não tem comando de rodar aqui, ele aparece quando a
primeira tarefa de dados entrar na `main`.

## Stack

Python, pandas e scikit-learn para o modelo (regressão logística, para dar para explicar o
resultado). Streamlit na tela da feira. Dados do dataset público UCI, nunca dados reais de
aluno (LGPD).
