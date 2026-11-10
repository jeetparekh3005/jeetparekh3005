## Jeet Parekh

I'm the architect for AI Platforms at Dailoqa, and still in the code most days.
We build multi-agent systems for banks and NBFCs - loan origination, servicing,
credit, compliance - the kind of place where a hallucination is a regulatory
event, not a bad demo.

Here's what most agentic AI in banking gets wrong: it doesn't fall over on model
quality. It falls over on data access, approval chains, and nobody owning what
happens when an agent is wrong. That's the part I actually spend my time on -
making the thing degrade safely, pulling answers out of data nobody ever meant a
machine to read, and leaving an audit trail a risk team will sign without
flinching.

### The platform

The pieces I design and keep talking to each other:

- **Agentic Farm** - the agents, and the orchestration that keeps them from
  improvising their way into a compliance incident
- **Business Rules** - because not everything should be a prompt
- **Agentic Testing and Evals** - proving it works before a regulator does
- **RAG** - retrieval over documents nobody wrote for a machine to read
- **Controls** - governance, auth, the LLM gateway, RBAC; who and what an agent
  is allowed to touch
- **Intelligent Extraction** - turning unstructured mess into something you can
  audit
- **Agentic Data Interaction** - letting agents query the business without
  handing them the keys

### Before this

Close to a decade, three tech cycles. Decentralised identity and traceability on
Hedera at The Hashgraph Group. CBDC, invoice financing, and KYC/GDPR work at
Accenture. Different stack every time, same problem underneath: provenance,
auditability, and designing for the failure you can't prevent. B.Tech in CS and
an MBA in Finance from NMIMS, and a TOGAF practitioner cert somewhere in there
too.

### Building and writing

- **[keel](https://github.com/jeetparekh3005/keel)** - golden-path scaffolding
  for production services in five languages: hexagonal, contract-driven, signed
  and attested.
- **[writeamp](https://github.com/jeetparekh3005/writeamp)** - my notebook on
  software architecture and the trade-offs behind the decisions.
- **[design-patterns-unfolded](https://github.com/jeetparekh3005/design-patterns-unfolded)**
  - design patterns told as stories, across six languages.

I mostly write about what breaks in production, not what demos well.

### Off the clock

Too much coffee. I read a lot of mythology and old stories - still the best thing
we ever built for making chaos make sense. Strong opinions on films, and more
television than I will admit to. When the agents are behaving, I'm usually off on
a trail somewhere with no signal.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/jeetparekh30/) / jeetparekh3005@gmail.com
