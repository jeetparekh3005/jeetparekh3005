## Jeet Parekh

I own the architecture of AI Platforms at Dailoqa, and I am still in the code.
We build multi-agent systems for banks and NBFCs across loan origination,
servicing, credit, and compliance, where a hallucination is a regulatory event,
not a bad demo.

Most agentic AI in banking does not fail on model quality. It fails on data
access, approval chains, and nobody owning the failure case. That is the part
the architecture has to answer for: orchestration that degrades safely, retrieval
over data never meant to be read by a machine, and audit trails a risk team will
actually sign.

### The platform

The pieces I design and hold together:

- **Agentic Farm** - the agents, plus the orchestration that stops them
  improvising into a compliance incident
- **Business Rules** - because not everything should be a prompt
- **Agentic Testing and Evals** - proving it works before a regulator does
- **RAG** - retrieval over documents never written for a machine to read
- **Controls** - AI governance, auth, the LLM gateway, and RBAC: who and what an
  agent is allowed to touch
- **Intelligent Extraction** - turning unstructured mess into something auditable
- **Agentic Data Interaction** - letting agents query the business without
  handing them the keys

### Before this

Close to a decade across three technology cycles - decentralised identity and
traceability on Hedera at The Hashgraph Group; CBDC, invoice financing, and
KYC/GDPR workflows at Accenture. Different stacks, identical constraints:
provenance, auditability, and designing for the failure you cannot prevent.
B.Tech CS and MBA Finance (NMIMS). TOGAF Enterprise Architecture Practitioner.

### Building and writing

- **[keel](https://github.com/jeetparekh3005/keel)** - golden-path scaffolding
  for production services across five languages: hexagonal, contract-driven,
  signed and attested.
- **[writeamp](https://github.com/jeetparekh3005/writeamp)** - a notebook on
  software architecture and the trade-offs behind every decision.
- **[design-patterns-unfolded](https://github.com/jeetparekh3005/design-patterns-unfolded)**
  - storytelling design patterns across six languages.

I write about what breaks in production, not what demos well.

### Off the clock

Powered by more coffee than any architecture review strictly requires. I collect
stories and mythology - humanity's oldest systems for making chaos legible,
which is also the day job. Strong opinions on films and far too much television.
When the agents are behaving, I am usually out of network on a trail, trading
tokens per second for metres of elevation.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/jeetparekh30/) / jeetparekh3005@gmail.com
