<h1 align="center">EryyynIT</h1>

<p align="center">
  Michael Barkalov · Backend developer
</p>

<p align="center">
  <a href="https://go.dev/"><img src="https://img.shields.io/badge/Go-007D9C?style=for-the-badge&amp;logo=go&amp;logoColor=white" alt="Go"></a>
  <a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-B7410E?style=for-the-badge&amp;logo=rust&amp;logoColor=white" alt="Rust"></a>
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&amp;logo=python&amp;logoColor=1F2937" alt="Python"></a>
</p>

<p align="center">
  <a href="https://eryyynit.github.io">Website &amp; resume</a> ·
  <a href="https://www.fl.ru/users/barkalovmisha/">FL.ru</a> ·
  <a href="https://freelance.ru/michaelbarkalov">Freelance.ru</a>
</p>

I write backend services, Telegram bots and developer tools. This is also where I work on my own projects and learn by building things.

## What I'm building

### [rise](https://github.com/EryyynIT/rise)

[![crates.io version](https://img.shields.io/crates/v/rise-cli?style=flat-square&color=B7410E)](https://crates.io/crates/rise-cli)
[![License](https://img.shields.io/github/license/EryyynIT/rise?style=flat-square&color=007D9C)](https://github.com/EryyynIT/rise/blob/main/LICENSE)

A project generator for Rust. Pick a stack in the interactive wizard or use CLI flags to generate a web app, CLI, library, game or embedded project. Supports custom templates too.

```sh
cargo install rise-cli --locked
rise new myapp --kind web --yes
```

### [workaly](https://github.com/EryyynIT/workaly)

![In development](https://img.shields.io/badge/status-in_development-FFD43B?style=flat-square&labelColor=24292F)

My long-term project: a freelance and job platform. I'm using it to work through microservice architecture in practice, with Go and Rust services, gRPC and Kafka. Still in development, not a launched product.

## Telegram bots

**[MailingTGBot](https://github.com/EryyynIT/MailingTGBot)** is a Python / aiogram 3 bot for announcements to registered users. It supports receipt confirmations and separate admin, sub-admin and moderator roles.

## Test assignments

Both projects below were built as test assignments for developer positions.

- **[Async payment processing service](https://github.com/EryyynIT/async-payment-processing-service)** · Python, FastAPI, PostgreSQL, RabbitMQ. Simulated payment processing with idempotency keys, an outbox and webhook retries. Docker Compose for local setup; GitHub Actions for linting and tests.
- **[Queue broker](https://github.com/EryyynIT/queue)** · Go, standard library only. In-memory FIFO queues with an HTTP API, blocking reads, timeouts and concurrency tests.

---

I'm open to backend roles and freelance projects. My [website](https://eryyynit.github.io) has my resume and contact details; you can also reach me on [FL.ru](https://www.fl.ru/users/barkalovmisha/) and [freelance.ru](https://freelance.ru/michaelbarkalov).
