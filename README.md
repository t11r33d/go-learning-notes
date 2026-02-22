# Go Learning

My personal roadmap and notes as I learn Go from scratch.
I work through each topic, write code, and document what I understand.

---

## Progress

### Go Core

| Topic | Status |
|-------|--------|
| Maps: hash table & swiss table | 🔲 |
| Slices: internals and gotchas | 🔲 |
| Structs and interfaces | 🔲 |
| Goroutines | 🔲 |
| Channels and sync primitives | 🔲 |
| Go scheduler (GMP model) | 🔲 |
| Garbage collector | 🔲 |

### Adjacent Technologies

| Topic | Status |
|-------|--------|
| SQL / PostgreSQL (deep dive) | 🔲 |
| HTTP (net/http, REST) | 🔲 |
| gRPC | 🔲 |
| Kafka & RabbitMQ | 🔲 |
| NoSQL: Redis & MongoDB | 🔲 |
| Git | 🔲 |
| Fault tolerance: replicas, sharding | 🔲 |

> 🔲 not started &nbsp; 🟡 in progress &nbsp; ✅ done

---

## Structure

```
go-learning/
├── core/
│   ├── maps/
│   ├── slices/
│   ├── structs-interfaces/
│   ├── goroutines/
│   ├── channels-sync/
│   ├── scheduler/
│   └── gc/
└── adjacent/
    ├── postgres/
    ├── http/
    ├── grpc/
    ├── kafka-rabbitmq/
    ├── nosql/
    ├── git/
    └── fault-tolerance/
```

Each folder contains:
- `README.md` — my notes on the topic
- `.go` files — code I write while learning

---

## Notes format

Every topic note follows the same structure:

```
# Topic name

## What it is
Short explanation in my own words.

## How it works under the hood
Internals that matter.

## Code
Working example I wrote myself.

## Gotchas
Things that surprised me or are easy to get wrong.
```

---

## Contact

- Telegram: [@t1r33d](https://t.me/t1r33d)
- Email: maksryachkin1@gmail.com
