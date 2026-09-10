<div align="center">

<img src="./assets/terminal.svg" width="100%" alt="Animated Linux terminal introduction" />

</div>

## `vipul@github:~$ cat ~/about`

```text
Interested in backend systems, Linux, networking and distributed systems.
I like building things that make me look underneath the abstraction instead
of only using it.

Linux is more than a development environment for me. I genuinely enjoy
exploring the OS, processes, networking, services and the machinery that
keeps a system running.

Arsenal: nvim | arch | tmux
```

## `vipul@github:~$ ls ~/stack`

```text
backend/        Python · FastAPI · Django · Flask · SQLAlchemy
systems/        Linux · Processes · Sockets · Networking
infrastructure/ Docker · Redis · RabbitMQ · PostgreSQL · Git
ai/             RAG · LLM APIs · LangChain · Vector Databases
```

## `vipul@github:~$ ls ~/projects`

```text
IMP.PASS/
Logalyser/
LinkedIn-Handler/
```

## `vipul@github:~$ cat ~/projects/IMP.PASS/README`

```text
IMP.PASS
────────
A password manager built to explore how credentials can be stored and
transported securely instead of treating security as a black box.

It uses AES-256 encryption, password-based key derivation and authenticated
access, with a Python backend and persistent credential storage.

The project became an excuse to dig into encryption, authentication,
client-server communication and secure application design.

Stack: Python · PyCryptodome · ExpressJS · MariaDB
```

## `vipul@github:~$ cat ~/projects/Logalyser/README`

```text
Logalyser
─────────
A log monitoring and incident analysis system built around independent
watcher processes and an event-driven backend.

Configured watchers monitor targets as separate processes and publish events
through Redis Streams. Workers consume those events without coupling the
monitoring workload to the API server.

FastAPI and SQLAlchemy provide the management layer, while PostgreSQL and
Alembic handle persistent watcher configuration and schema migrations.
The frontend provides a view into watchers and the events they produce.

Stack: Python · FastAPI · SQLAlchemy · PostgreSQL · Alembic · Redis · Docker
```

## `vipul@github:~$ cat ~/projects/LinkedIn-Handler/README`

```text
LinkedIn Handler
────────────────
A developer activity pipeline that watches source repositories and turns
meaningful code changes into material for technical LinkedIn posts.

It observes filesystem changes, aggregates multi-file Git diffs and feeds
them into an LLM-assisted analysis pipeline to explain what changed and why
it matters before generating post material.

Stack: Python · Git · Watchdog · LLM APIs
```

## `vipul@github:~$ echo $CURRENT_GOAL`

```text
Build systems that force me to understand what is happening underneath.
```

<div align="center">

`vipul@github:~$ █`

</div>
