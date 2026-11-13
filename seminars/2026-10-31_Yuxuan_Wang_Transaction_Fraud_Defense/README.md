# Transaction Fraud Defense in the Wild

**FinHorizons Seminar 03**

- **Speaker:** Yuxuan Wang, industry practitioner, US financial services
- **Date:** Saturday 31 October 2026, 14:00 GMT (10:00 ET), online on Zoom
- **Recording:** [YouTube](https://www.youtube.com/watch?v=si9EXc-wFdA)
- **Slides:** [PDF](./Yuxuan_Wang_Transaction_Fraud_Defense_in_the_Wild.pdf)

## Abstract

Fraud models in production live inside a transaction's round trip: every decision has to fit a strict latency budget, a bounded compute bill and a serving stack that keeps state. This talk walks through what those constraints mean for how the models are built. It follows the money first, showing where the model sits in the transaction flow and what that implies for features, labels and feedback. It then turns to the serving clock: inference under compute, state and cost limits. The third part covers training at scale, including iteration speed, experiment fidelity and release cadence when the data is non-stationary. The talk closes with what carries over: a summary of design considerations for anyone building models that have to run inside real systems.

## About the speaker

Yuxuan Wang is a Principal Associate, Data Science at a large US financial institution, where he leads R&D for a transaction fraud detection sequence model and an agentic self-evolving feature mining system. His work focuses on event sequence modeling under non-stationarity, adaptive retraining, and production deployment. Previously, he worked on model validation and challenger modeling, and conducted research at Wharton, NYU Stern TOPS, and Penn NLP. Yuxuan holds an M.S.E. in Data Science from UPenn and a B.S. in Computer Science and Mathematics from RPI. He has published at the ACL SustaiNLP workshop on dense retriever efficiency, co-authored an ICRA paper on robot manipulation learning, and contributed to open source, including Haystack’s in-memory BM25 search and a lightweight geometric algebra transformer library. His research interests broadly cover information retrieval, event sequence modeling, and robotics.

## Recording chapters

| Time | Section |
|---|---|
| 0:00 | Introduction and outline |
| 1:25 | Follow the money: one coffee, one round trip |
| 5:03 | Decision is model plus policy |
| 6:32 | The model is not the system |
| 7:32 | Throughput matters too |
| 9:04 | At scale, modeling becomes a system problem |
| 9:36 | The serving clock: the model has a deadline |
| 11:01 | Latency is the first system constraint |
| 13:08 | Streaming turns history into state |
| 14:03 | Hot accounts live in RAM |
| 16:42 | Hot state is not object storage |
| 17:56 | Space can be harder than time |
| 19:08 | Training at scale: the loop sets the pace |
| 20:44 | The target keeps moving |
| 21:58 | The design space explodes |
| 23:30 | One year is a storage problem |
| 26:05 | The bottleneck is time to a defensible decision |
| 27:29 | What carries over: feasible, viable, worth switching |
| 29:33 | Choosing an operating point |
| 32:44 | Open questions, all the way down |

---

FinHorizons Foundation is an open research community advancing responsible AI in finance. Upcoming seminars and registration: [finhorizons.org](https://finhorizons.org)
