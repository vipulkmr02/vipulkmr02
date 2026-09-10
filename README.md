<div align="center">

<img src="./assets/terminal.svg" width="100%" alt="Animated Linux terminal introduction" />

</div>

## `vipul@github:~$ ls ~/stack`

```text
backend/        Python · FastAPI · Django · Flask · SQLAlchemy
systems/        Linux · Processes · Sockets · Networking
infrastructure/ Docker · Redis · RabbitMQ · PostgreSQL · Git
ai/             RAG · LLM APIs · LangChain · Vector Databases
```

## `vipul@github:~$ ps aux | grep projects`

```text
vipul    RUNNING    Logalyser
vipul    RUNNING    LinkedIn Handler
vipul    LEARNING   Distributed Systems
vipul    ALWAYS     Linux Experiments
```

## `vipul@github:~$ tree ~/projects/logalyser`

```text
logalyser/
├── api/              FastAPI + SQLAlchemy
├── database/         PostgreSQL + Alembic
├── watchers/         Independent monitoring processes
├── event-stream/     Redis Streams
├── workers/          Event consumers
└── frontend/         React Native
```

### `vipul@github:~$ cat ~/projects/logalyser/README`

```text
Logalyser
─────────
A distributed log monitoring and incident analysis system.

Watchers monitor configured targets as independent processes.
Events are published into Redis Streams instead of being coupled
with the API process.

Workers consume the stream for event processing and analysis.
The FastAPI service manages watcher configuration and exposes
CRUD APIs used by the frontend.

STATUS
  Backend architecture    [████████░░] building
  Watcher runtime         [██████████] working
  Redis event stream      [██████████] working
  Watcher CRUD API        [██████░░░░] building
  Mobile frontend         [████░░░░░░] building
  Incident analysis       [░░░░░░░░░░] planned
```

## `vipul@github:~$ find ~/projects -maxdepth 1 -type d`

### `~/projects/linkedin-handler`

```text
A developer activity pipeline that watches repository changes,
aggregates diffs and turns meaningful code changes into material
for technical LinkedIn posts.

Pipeline:
  repository → watcher → diff aggregation → change analysis → post generation

Focus:
  Python · Git · filesystem events · LLM-assisted change analysis
```

### `~/projects/async-worker-lab`

```text
FastAPI + Celery playground for learning asynchronous workers,
background jobs and distributed task execution.

Stack:
  FastAPI · Celery · Redis · Docker
```

## `vipul@github:~$ cat ~/about`

```text
Backend developer interested in the machinery underneath abstractions.
Building backend systems, experimenting with Linux, and learning distributed systems.

Current focus: Logalyser
Editor:        Neovim
Environment:   Linux
```

## `vipul@github:~$ git log --oneline --life`

```text
a8f3c21  learning distributed systems
72ac891  building backend systems
19df420  discovered containers
4bb01ca  started living in the terminal
0000001  hello world
```

## `vipul@github:~$ echo $CURRENT_GOAL`

```text
Build better backend systems.
Understand what's happening underneath the abstractions.
Ship useful software.
```

<div align="center">

`vipul@github:~$ █`

</div>
