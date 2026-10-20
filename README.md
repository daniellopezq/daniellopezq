# Daniel Lopez Quezada

**Technical Operations, Systems Integration & Applied AI**: I turn messy business operations into production systems.

I build systems that connect operations, data, APIs, telephony, automation and AI. Most of my work sits where a business process meets software. Leads have to be routed, calls placed and recorded, appointments scheduled, contractors paid and reports trusted, and all of it has to keep working when a provider fails or the data disagrees with itself.

My technical background came before modern AI tools. I started in operations, data, SQL, GIS and workflow systems, then moved into Python, APIs, backend services, telephony, automation and production infrastructure. That path shaped how I work. I begin with the operational problem and the outcome it needs, and the technology comes after.

I work across functions: operations, data, integrations, product and engineering. I'm usually the person who understands the business rule and also ships the system that enforces it.

---

## Selected Work

### Helios
**Production operations platform for a home-services business**

Lead management, outbound/inbound telephony, appointments, contractor workflows, SMS, call recordings, transcription, billing, reporting and applied AI, all in one system that a live business runs on every day.

The engineering problems are mostly about reliability. Distributed state across dialers, carriers and the database. Reconciliation when providers disagree. Background workers for jobs that must not run twice. Integrations with telephony, SMS, payment and AI providers that fail in their own ways.

`Python` · `PostgreSQL` · `FreeSWITCH` · `VICIdial` · `Twilio / SignalWire` · `Reflex` · `Linux / systemd`

### Course Platform
**Production Django/React platform that replaced a WordPress membership stack**

Payments, subscriptions, entitlements, CRM and SMS integrations, private content delivery, admin workflows and background jobs. I owned the system end to end. That covered modeling how the business actually sells and grants access, and turning it into rules the platform enforces, so nobody has to fix things by hand.

`Django` · `DRF` · `React` · `PostgreSQL` · `Celery` · `Redis` · `Square` · `Twilio` · `GoHighLevel` · `Pipedrive`

### Local Business Classifier
**Python desktop app for evidence-backed business classification with local LLMs**

It processes CSV/XLSX lead lists, researches each business's website, and classifies the business with local models through LM Studio. Each result keeps the evidence it was based on. Processing can resume after interruption, it recovers from failures, deduplicates records and has a test suite. Model inference stays local, and business data is not sent to a cloud LLM.

`Python` · `LM Studio` · `Local LLMs` · `pytest`

### Tablet Dashboard
**Self-hosted home dashboard built for Android 4.4 / Chrome 50 hardware**

Weather, maps, Google Calendar, an AI assistant and Whisper voice input, running on a tablet most software has stopped supporting. Because of that constraint, every feature degrades gracefully. Old hardware gets reused instead of thrown out, and the self-hosted design keeps personal data private.

`JavaScript (ES5)` · `Python` · `Whisper` · `Google Calendar API`

---

## How I Work

- **AI-assisted, human-accountable.** I use AI coding and reasoning tools extensively. I own the requirements, business rules, architecture decisions, validation, deployment and production outcomes.
- **Requirements first.** I settle what the system must do, and what it must never do, before writing code.
- **Business rules and data ownership.** Every rule has one source of truth. Every table has a clear owner and a defined writer.
- **Deterministic before probabilistic.** Where rules, SQL or plain logic solve the problem, I use them. LLMs go where judgment over unstructured input actually adds value.
- **Testing and validation.** Changes are verified against real data and real failure modes, not just the happy path.
- **Production responsibility.** I deploy, monitor and fix what I build, and I write down why it broke.

---

## Primary Areas

**Solutions Engineering · Technical Integration · AI Systems · Technical Product · Technical Operations**
