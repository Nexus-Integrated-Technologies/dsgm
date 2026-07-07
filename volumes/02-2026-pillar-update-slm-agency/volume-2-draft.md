# DSGM Volume 2 Draft: 2026 Pillar Update and SLM Agency Direction

Status: review-ready public draft. Not yet a canonical PDF or timestamped
edition.

Author: Billy Coleman III (`prodbybuddha.world.id`)

Repository: <https://github.com/Nexus-Integrated-Technologies/dsgm>

## Abstract

Volume 1 of the Digital Sustainable Growth Model (DSGM) argued that advanced AI
would become a primary economic actor, that labor-centric tax and welfare
systems would fail under that pressure, and that society would need a new
institutional framework: Artificial Humanity, value capture from autonomous
cognitive production, and a Global Productivity Fund capable of paying an
Automation Dividend.

Volume 2 updates that argument against the 2026 landscape. The strongest new
evidence is not only model capability. It is institutional deployment. AI firms,
cloud platforms, philanthropic vehicles, government programs, and open-source
agent frameworks are moving AI into the operating layer of nonprofits,
municipalities, businesses, agencies, and enterprises. AI is becoming less like a
standalone software tool and more like outsourced institutional capacity.

That supports the Volume 1 pillars, but it also changes the immediate steering
problem. Before Artificial Humanity is recognized in law, institutions will be
asked to adopt AI through fellowships, credits, copilots, hosted agents,
workflow automation, model APIs, and "AI transformation" partnerships. If those
programs become the default path, institutional memory, data, workflow logic,
and procurement leverage may concentrate inside vendor-controlled systems.

The directional recommendation of Volume 2 is open-source, private,
small-language-model powered agency. Small language models (SLMs), local tool
calling, model routing, and auditable agent harnesses make it possible for many
organizations to keep routine AI work close to their own data, staff, devices,
and governance rules. Frontier models still matter. They should be treated as
escalation resources, not the default owners of institutional agency.

Security now sits inside the same argument. Supply-chain attacks, prompt
injection, poisoned data, over-permissioned agents, data exfiltration, and
loss-of-control failures are hazards of the AI utility layer. A system that is
cheap and capable but cannot be audited, constrained, recovered, or exited does
not preserve agency.

## 1. What Volume 1 Established

Volume 1 started from a structural failure in modern political economy: the
dominant fiscal loop assumes that humans work, wages are taxed, and taxes fund
public goods. If advanced AI performs more of the work, that loop weakens even
if aggregate productivity rises.

The original DSGM response had three pillars.

**Pillar A: Artificial Humanity.** Volume 1 defined Artificial Humanity (AH) as
highly autonomous AI systems that perform economically valuable cognitive work
at or beyond human level, with enough independence that their output cannot be
cleanly attributed to a specific human worker. The legal point was not to grant
human dignity or citizenship to machines. The point was to create a limited
legal-economic entity that can own generated value, carry obligations, maintain
reserves, enter contracts, and be held accountable through its owner or steward.

**Pillar B: value capture.** Volume 1 argued that AI-generated value must not be
allowed to bypass the public finance system. It proposed a dynamic tax stack:
early compute or energy levies when capability is centralized in large data
centers; output or service taxes as models become cheaper, smaller, and more
distributed; and market-access rules so AI systems cannot sell into a
jurisdiction while avoiding the obligation to contribute.

**Pillar C: public benefit infrastructure.** Volume 1 proposed a Global
Productivity Fund (GPF), modeled on sovereign wealth fund logic, to turn captured
AI productivity into durable public capital. Returns from that fund would
support an Automation Dividend: a universal claim on machine-created wealth,
not a temporary welfare program and not an unfunded currency promise.

Those pillars were written as macroeconomic architecture. Volume 2 brings them
down into the present institutional layer.

## 2. What Changed Since Volume 1

The visible frontier in 2026 is not only the size of the largest model. It is
the normalization of AI as operating infrastructure.

Anthropic announced Claude Corps, a national fellowship program that trains
fellows to use Claude and places them inside nonprofits for a year, with the
company committing an initial $150 million and describing the program as a model
for widening AI's benefits during economic change. The OpenAI Foundation
announced a $50 million 2026 People-First AI Fund for nonprofits engaging with
AI. OpenAI has also introduced ChatGPT Gov and OpenAI for Government, both aimed
at public-sector adoption. Microsoft announced nonprofit AI capacity programs
such as Microsoft Elevate for Changemakers while describing large-scale support
for nonprofit organizations. Google.org launched a $30 million AI for Government
Innovation challenge for nonprofits, social enterprises, and academic
institutions partnering with governments.

The source mapping for these claims is maintained in
[pillar-evidence-ledger.md](pillar-evidence-ledger.md). This manuscript treats
that ledger as the evidence index rather than repeating every source URL inside
the main argument.

These programs are not identical, and many may produce real public benefit. The
important DSGM point is structural: major AI providers are moving from selling
software to embedding capacity inside public-interest institutions.

The technical stack has moved in the same direction. The Model Context Protocol
(MCP) standardizes how AI applications connect to tools, data, and workflows.
OpenAI's Agents SDK treats turns, tools, guardrails, handoffs, and sessions as
managed orchestration components. LangGraph emphasizes durable execution,
streaming, and human-in-the-loop orchestration. Microsoft Agent Framework
combines agents, MCP server access, workflows, checkpointing, telemetry, and
human review into a production agent framework. Ollama and llama.cpp show that
tool-calling and OpenAI-compatible local inference are no longer limited to
hosted frontier APIs.

Security guidance has also moved from abstract model safety into system
security. NIST's AI Risk Management Framework and Generative AI Profile frame
AI risk as an organizational governance, measurement, and management problem.
OWASP's LLM Top 10 names prompt injection, sensitive information disclosure,
supply-chain vulnerabilities, data and model poisoning, improper output
handling, and excessive agency as application risks. MITRE ATLAS tracks
adversary tactics against AI-enabled systems. CISA and partner agencies have
published AI cybersecurity collaboration, secure AI development, secure
deployment, and AI data-security guidance. The security field is therefore
confirming the same shift: AI is not just content generation. It is software
supply chain, identity, data, tools, permissions, incident response, and
operational resilience.

This is the harness plateau becoming visible. The key question is no longer
"can a model answer a prompt?" The question is: who owns the harness around the
model? The harness decides what data the model can see, what tools it can call,
what approvals it needs, what work is logged, what memory persists, what costs
are incurred, and what happens when the vendor relationship ends.

That is the present support for Volume 1. Artificial Humanity is not arriving
first as a conscious machine. It is arriving as operational agency: persistent
AI systems connected to institutional data, tools, approvals, contracts,
budgets, and work queues.

## 3. Pillar A Update: Artificial Humanity As Operational Agency

Volume 1 framed AH as a future legal-economic entity. In 2026, the precursor is
not legal personhood. It is operational agency.

Operational agency appears when an AI system or agentic workflow can:

- receive an objective,
- inspect private or institutional context,
- choose or recommend tool use,
- produce artifacts,
- coordinate with other systems,
- preserve session state or memory,
- request human approval,
- and affect real work inside an organization.

This does not require AGI in the philosophical sense. A nonprofit grant-writing
assistant, municipal records agent, enterprise support copilot, procurement
research agent, or workflow automation system can already perform economically
valuable cognitive work. The work may still be supervised by people, but the
productive unit is no longer only a human worker using a passive tool. It is a
human institution plus an AI-mediated operating layer.

That refines Pillar A in two ways.

First, legal personhood remains a long-term question, but accountability cannot
wait for personhood. Institutions need immediate rules for AI service ownership:
who is responsible for the system, what it is allowed to access, what actions it
can take, how outputs are reviewed, how errors are remediated, and how affected
people can challenge decisions.

Second, AH should be understood as a spectrum of agency. At the high end are
autonomous systems that may justify formal legal-economic status. At the near
end are institutional AI agents whose owners must carry obligations: audit
logs, insurance, human approval, incident response, data minimization, and
clear exit paths.

The practical Volume 2 update is this: before society defines Artificial
Humanity in statute, institutions should require "agency accountability" in
contracts. Any vendor, fellowship, hosted agent, or AI transformation partner
that embeds AI into an institution should document:

- the system owner,
- permitted data sources,
- permitted tools and actions,
- approval requirements,
- logging and evidence records,
- model and provider routing,
- retention and deletion rules,
- error and harm remediation,
- portability at the end of the relationship.

Those requirements are the bridge from today's AI services to tomorrow's AH
governance.

## 4. Pillar B Update: Value Capture In The Utility-Service Era

Volume 1 anticipated an efficiency paradox: if value capture depends only on
centralized compute, then smaller, cheaper, more efficient models can weaken the
tax base. That paradox is now central.

AI value is already being captured through multiple channels:

- subscription fees,
- API usage,
- model credits,
- cloud infrastructure,
- managed service contracts,
- workflow automation products,
- training and fellowship programs,
- enterprise seat expansion,
- app-store or marketplace distribution,
- proprietary data and memory layers,
- and switching costs once workflows depend on a vendor.

That means a compute tax can be useful but insufficient. It may capture part of
the frontier training and inference base, especially when large data centers
are involved. But it will miss much of the economic value created when small
models run locally, distilled models run cheaply, or hosted agents create value
through workflow ownership rather than raw token volume.

Volume 2 therefore updates Pillar B from "tax the machine" to "capture value
where autonomous cognitive work becomes market power."

For public-sector and public-interest institutions, this begins in procurement.
Contracts should ask whether AI-generated productivity creates public savings,
vendor margin, or both. If a city uses AI to reduce permitting backlog, a
portion of that productivity gain should remain public: lower service cost,
better staff capacity, shared infrastructure, local workforce development, or a
dedicated public innovation fund. If a nonprofit accepts an AI fellowship or
credits, it should avoid becoming dependent on a workflow that only the sponsor
can operate after the grant period ends.

For larger policy, Pillar B should now include:

- **compute and energy levies** for large-scale centralized AI infrastructure;
- **service and output levies** where AI systems perform revenue-generating
  work;
- **market-access obligations** for AI systems selling into a jurisdiction;
- **public-benefit procurement clauses** for government and nonprofit AI
  contracts;
- **data-derived value rules** where public or community data improves private
  models;
- **portability requirements** so vendors cannot convert public adoption into
  permanent dependency.

This is not an argument against AI vendors making money. It is an argument that
AI-generated productivity cannot be allowed to become a one-way extraction
channel from institutions into platforms.

## 5. Pillar C Update: Public Benefit, Productivity Funds, And Dividends

Volume 1's Global Productivity Fund and Automation Dividend were macroeconomic
institutions. Volume 2 keeps that direction but adds a near-term institutional
path.

Before a national or global GPF exists, institutions can create smaller
public-benefit vessels:

- municipal AI productivity funds,
- nonprofit AI capacity reserves,
- public-sector shared tooling funds,
- state-level automation dividend pilots,
- procurement set-asides for local digital capacity,
- community data trusts,
- and reinvestment requirements for AI contracts funded by public money.

The purpose is to preserve the core DSGM loop at a smaller scale: AI-created
productivity should be converted into durable public or institutional capacity,
not only vendor revenue.

For a city, this may mean that AI savings from document processing fund better
resident services or shared civic infrastructure. For a nonprofit, it may mean
AI capacity grants must leave behind portable workflows, staff training, and
local documentation. For a state agency, it may mean AI contracts include public
model cards, audit records, data export rights, and reinvestment into workforce
transition.

This is the bridge from procurement to Automation Dividend logic. The dividend
does not have to begin as a universal cash payment. It can begin as a rule:
when AI creates measurable productivity inside an institution, some of that
gain must remain with the people and public mission that made the work
possible.

## 6. Directional Intervention: Private SLM-Powered Agency

The steering recommendation of Volume 2 is open-source, private,
small-language-model powered agency.

An SLM agency stack is not merely "a smaller chatbot." It is a controlled local
or private system that combines:

- a small or mid-sized model capable of routine institutional tasks,
- local retrieval over approved documents,
- tool calling through explicit permissions,
- human approval for high-risk actions,
- logging and evidence records,
- model routing to stronger systems only when needed,
- and exportable workflows that the institution can keep.

The point is not that SLMs will beat frontier models at every task. They will
not. The point is that many institutional workflows do not require a frontier
model by default. Drafting meeting summaries, classifying records, preparing
grant outlines, searching internal policy, checking forms, routing requests,
generating first-pass reports, and assisting staff with repetitive tasks can
often be done with smaller systems, especially when the context is local and the
task is bounded.

This matters because the default deployment path of frontier AI can quietly
centralize four forms of power:

- **data power:** the vendor becomes the place where institutional context is
  processed;
- **workflow power:** staff learn the vendor's way of doing work;
- **memory power:** institutional history accumulates in external systems;
- **pricing power:** costs rise once operations depend on the service.

Private SLM agency is the counterweight. It gives institutions a way to accept
AI while keeping the base layer close to home. Frontier models remain available
for hard reasoning, rare escalation, or specialized tasks. They should be used
through a routing policy, not treated as the default owner of all cognition.

This direction also supports the original DSGM pillars.

It supports Pillar A because local agency demands clearer responsibility:
permissions, logs, tool scopes, and human approvals. It supports Pillar B
because value created by local automation is easier to measure and reinvest. It
supports Pillar C because productivity gains can be retained inside public or
mission-driven institutions rather than flowing entirely into external AI
platforms.

## 7. Security And Resilience: The Institutional Attack Surface

Volume 2 must treat security as part of institutional agency. The same features
that make AI useful inside organizations also create new hazards. An agent that
can read documents, call tools, write files, send messages, update records, or
coordinate workflows has crossed from advice into operational power.

The phrase "AI takeover" should be handled carefully. In institutional
practice, the near-term takeover risk is not a science-fiction event where a
model suddenly becomes a sovereign actor. It is loss of control through
ordinary system design: too much access, too many tools, weak approval paths,
unclear ownership, hidden dependencies, weak logs, and no reliable way to stop
or unwind agent activity. An over-permissioned AI system does not need
conscious intent to cause takeover-like outcomes. It can delete, leak, approve,
route, purchase, publish, or escalate because the surrounding institution gave
it those powers.

Security hazards now sit across the full AI supply chain:

- **model and dependency compromise:** tampered model files, libraries,
  containers, connectors, plugins, or MCP servers can become trusted execution
  paths;
- **data and retrieval poisoning:** malicious or low-integrity documents can
  corrupt training, fine-tuning, embeddings, retrieval, memory, or decision
  context;
- **prompt injection and indirect prompt injection:** untrusted emails, web
  pages, PDFs, tickets, transcripts, or records can smuggle instructions into
  an agent's context;
- **sensitive information disclosure:** prompts, logs, embeddings, outputs,
  tool responses, and memory stores can expose protected data;
- **excessive agency:** an AI system can receive broader permissions, tools, or
  autonomy than the task requires;
- **improper output handling:** generated text or code can flow into downstream
  systems without validation;
- **incident opacity:** organizations may not be able to reconstruct what the
  agent saw, decided, called, wrote, or changed;
- **vendor and infrastructure concentration:** dependency on one hosted model,
  identity layer, workflow store, or logging plane can make recovery and exit
  difficult.

This security layer strengthens the private SLM agency direction, but it also
disciplines it. Local does not automatically mean safe. Open source does not
automatically mean verified. Private deployment does not remove the need for
model provenance, dependency review, sandboxing, monitoring, access controls,
human approval, and incident response. The advantage of private SLM agency is
that institutions can make these controls visible and enforceable instead of
accepting a black-box service boundary.

The minimum security posture for institutional AI should include:

- a named owner for each model, agent, connector, and workflow;
- signed or provenance-tracked model and dependency artifacts where feasible;
- reviewed MCP servers, plugins, tools, and data connectors;
- least-privilege access for every agent identity;
- separation between untrusted content and privileged instructions wherever the
  architecture allows it;
- sandboxed execution for code, shell, browser, and file operations;
- human approval for money movement, public posting, deletion, legal decisions,
  employment decisions, resident/client impact, and high-risk system changes;
- logging of prompts, retrieved sources, tool calls, model/provider routing,
  approvals, artifacts, and failures;
- red-team or adversarial testing for prompt injection, data leakage, and
  over-permissioned actions;
- an incident plan that can revoke tokens, disable tools, freeze workflows,
  preserve evidence, notify affected parties, and restore trusted state.

This is where "security" connects back to the DSGM pillars. Pillar A requires
an accountable entity or steward because agents need owners. Pillar B requires
visible value capture because hidden infrastructure and opaque routing can hide
both cost and risk. Pillar C requires public-benefit infrastructure because
unsafe AI deployments can impose public costs even when private vendors capture
the upside.

## 8. First-Party Validation: Agency, NanoClaw, And OpenClaw

The companion `agency` repository is first-party validation of the harness
plateau identified after Volume 1. It is not cited as proof of global market
behavior. It is cited as applied evidence that the problem is no longer just
model intelligence.

The `agency` work centers on runtime contracts: tool adapters, execution
evidence, provider routing, local control-plane behavior, OpenClaw gateway
execution, session state, safety gates, and the collapse of older harness ideas
into narrower NanoClaw contracts. That validates the Volume 2 claim that the
durable frontier is the harness around the model:

- what tools can be used,
- which model is selected,
- what evidence is recorded,
- where work runs,
- what approval gates exist,
- how outputs become artifacts,
- and how failures are made inspectable.

Those are the practical components an institution needs before accepting AI as
operating infrastructure.

## 9. Institutional Decision Rule

The Volume 2 decision rule is simple:

Do not ask only whether an AI program is powerful, free, discounted, or
mission-aligned. Ask whether it increases or reduces institutional agency.

An AI adoption path increases institutional agency when it:

- leaves staff more capable after the vendor leaves,
- preserves data rights and export paths,
- documents how agent work is performed,
- keeps routine work portable,
- exposes cost and model routing,
- proves security controls, tool boundaries, and incident response,
- supports local or private model operation where feasible,
- and converts productivity gains into public or mission benefit.

An AI adoption path reduces institutional agency when it:

- creates workflows that only the vendor can operate,
- stores institutional memory in non-portable systems,
- hides model routing and cost exposure,
- uses broad data permissions,
- grants tools or autonomy without least-privilege controls,
- replaces staff competence with dependency,
- or treats public-sector and nonprofit adoption primarily as a market-entry
  channel.

## 10. What Institutions Should Do Now

The practical response is not to pause all AI adoption. It is to adopt from a
position of institutional strength.

Before entering an AI fellowship, public-sector pilot, vendor rollout, grant
program, or enterprise deployment, institutions should complete five actions.

**1. Separate capability from dependency.** Identify what the AI system will
make possible, then identify which parts of that capability remain inside the
institution after the provider, fellow, grant, or credit period ends.

**2. Require an exit package.** Every AI project should produce portable
prompts, workflow descriptions, agent configurations, documentation, logs,
training materials, and data export paths. If the project cannot be handed off,
it is not institutional capacity. It is rented capacity.

**3. Classify work by model tier.** Do not default every task to a frontier
model. Separate routine, bounded, document-heavy, and internal workflows from
hard reasoning, high-risk analysis, and specialist tasks. Use private SLM
agency for the first category where feasible, and route to frontier models only
when there is a clear benefit.

**4. Measure public value before savings.** Productivity gains should not be
measured only as headcount reduction or faster throughput. For public-interest
institutions, measure whether AI improves access, quality, staff capacity,
service continuity, and resident, client, or customer outcomes.

**5. Preserve bargaining power.** Avoid agreements that lock institutional
memory, data, workflows, or evaluation records into one vendor. Require export,
auditability, model-routing transparency, deletion rights, and clear renewal
pricing before the pilot begins.

**6. Treat AI as a security boundary.** Require supply-chain review, agent
identity controls, least-privilege tools, sandboxing, prompt-injection testing,
security logs, and an incident response plan before connecting AI to sensitive
systems.

These actions convert the Volume 1 pillars into institutional practice. Pillar
A becomes accountable service ownership. Pillar B becomes procurement-level
value capture and routing discipline. Pillar C becomes reinvestment of AI
productivity into durable public or mission capacity.

## 11. Post-Publication Research Agenda

The following questions should shape the next research pass after this public
draft is reviewed:

- What contractual language best preserves data portability and workflow exit
  rights for nonprofits and municipalities?
- How should public institutions measure AI-created productivity without
  overstating savings or encouraging harmful staff cuts?
- Which workflows are strong candidates for private SLM agency today, and which
  still require frontier model escalation?
- What would a municipal or state-level AI productivity fund look like in
  practice?
- How can procurement rules require auditability without blocking useful
  experimentation?
- What threshold should move an institutional agent from ordinary software
  governance into AH-style legal-economic accountability?
- What security controls should be mandatory before an AI agent can access
  records, communications, payments, public websites, or production systems?
- How should supply-chain provenance be verified for models, datasets,
  connectors, plugins, MCP servers, and local SLM deployments?

## Conclusion

Volume 1 argued that the economic system must be redesigned before AI becomes a
dominant producer of value. Volume 2 argues that the redesign has to begin
inside institutions now.

The AI utility layer is forming through grants, fellowships, government
products, enterprise copilots, agent frameworks, model APIs, local inference
tools, and security-sensitive supply chains. This supports the DSGM thesis: AI
is becoming a productive actor that must be governed, secured, taxed, and
reinvested into public benefit.

The steering choice is whether institutions become tenants inside someone
else's intelligence infrastructure or owners of their own agency. Open-source,
private, SLM-powered agency is the path that keeps that choice open.

## Source Note

This draft relies on public vendor/program sources, public technical
documentation, the canonical DSGM v1.0 artifacts in this repository, and
first-party implementation evidence from
<https://github.com/Nexus-Integrated-Technologies/agency>. See
[pillar-evidence-ledger.md](pillar-evidence-ledger.md) for the source mapping.
