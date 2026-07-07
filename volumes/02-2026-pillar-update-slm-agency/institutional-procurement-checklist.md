# Institutional AI Procurement Checklist

Use this checklist before accepting an AI fellowship, grant-funded AI program,
government AI product, enterprise copilot, hosted agent, workflow automation
platform, or model API deployment.

The central question is not "Is this AI useful?" The central question is: does
this adoption path increase or reduce institutional agency?

## 1. Mission Fit

- What specific public, community, customer, or operational problem will this
  AI system address?
- What work will remain human-led even if the AI system performs well?
- Who is accountable for deciding whether the AI output is acceptable?
- What would make this pilot a failure, even if the tool works technically?
- Does the deployment strengthen the institution's mission, or mainly increase
  dependence on an external product?

## 2. Data Rights And Boundaries

- What data will the AI system access?
- Is any data sensitive, regulated, privileged, confidential, or community-owned?
- Will prompts, files, outputs, embeddings, metadata, or feedback be used to
  train or improve vendor models?
- Can the institution opt out of model training and secondary data use?
- Where is data stored, for how long, and under which jurisdiction?
- Can all institutional data be exported in usable formats?
- What deletion guarantees exist when the contract, grant, or fellowship ends?

## 3. Workflow Ownership

- Which workflows will be created or modified by the vendor, fellow, consultant,
  or AI system?
- Are workflow instructions, prompts, agent definitions, tool schemas, and
  automations exportable?
- Can staff run the workflow without the vendor after the pilot?
- Is there a documented handoff package?
- Are there internal staff who understand how the workflow works?
- What happens if prices rise, credits expire, or the provider changes terms?

## 4. Model And Provider Routing

- Which models are used for which tasks?
- Can routine tasks run on local, private, open-source, or smaller models?
- When is a frontier model required?
- Is there a written escalation policy for hard reasoning, high-risk decisions,
  or sensitive work?
- Are token usage, model selection, provider, cost, and fallback events logged?
- Can the institution change providers without rebuilding the entire workflow?

## 5. Tool Use And Permissions

- What tools can the AI system call?
- Can it read files, write files, send messages, browse the web, update
  databases, make purchases, or trigger public actions?
- Does every AI agent have its own identity, or does it borrow a human or
  shared service account?
- Which actions require human approval?
- Are permissions scoped by role, department, project, and risk level?
- Are tool calls logged in a way that staff can review?
- Can tool access be disabled immediately during an incident?

## 6. Auditability And Evidence

- Is there an auditable record of inputs, outputs, tool calls, approvals, model
  choices, and artifacts?
- Can the institution reconstruct what happened during an AI-assisted decision?
- Are logs understandable to non-engineering leadership?
- Are high-risk outputs reviewed before use?
- Is there a process to correct, retract, or contest AI-assisted work?
- Does the vendor provide incident reports for system failures, data exposure,
  or unsafe behavior?

## 7. Security And Supply Chain

- What model files, APIs, packages, containers, connectors, plugins, MCP
  servers, datasets, and retrieval indexes are part of the system?
- Are models, dependencies, and connectors pinned, reviewed, and provenance
  tracked?
- Can the vendor provide a software bill of materials or equivalent dependency
  inventory for the AI workflow?
- How are training, fine-tuning, embeddings, retrieval sources, memory stores,
  and feedback protected against poisoning or unauthorized modification?
- How does the system handle prompt injection or indirect prompt injection from
  emails, web pages, PDFs, tickets, chats, transcripts, images, or records?
- Are code execution, shell, browser, file, payment, messaging, and database
  tools sandboxed?
- Can the institution revoke tokens, disable tools, rotate credentials, freeze
  workflows, and preserve evidence during an incident?
- Are logs monitored for unusual tool calls, data access, privilege escalation,
  model-routing changes, or abnormal spend?
- What security testing has been performed against prompt injection, data
  leakage, supply-chain compromise, and excessive agency?

## 8. Cost And Value Capture

- What is free now, and what becomes paid later?
- Are model credits, discounted seats, fellow labor, or cloud grants temporary?
- What is the cost after the pilot or grant period ends?
- Which productivity gains remain with the institution?
- Will savings be reinvested into staff capacity, public service, local
  infrastructure, or community benefit?
- Does the contract prevent the vendor from converting public or nonprofit
  adoption into permanent dependency?

## 9. Public Benefit And Governance

- For public-sector or nonprofit work, what public benefit is created beyond
  adoption of the vendor's tool?
- Does the agreement require public-interest reporting, accessibility,
  transparency, or community oversight?
- Are affected residents, clients, customers, or staff informed when AI is used?
- Is there a human appeal path for AI-assisted decisions?
- Are equity and language-access impacts tested?
- Does the institution retain enough knowledge to govern the system itself?

## 10. Private SLM Agency Assessment

Before defaulting to a hosted frontier model, ask whether the workflow can run
through a private small-language-model agency stack.

- Is the task routine, bounded, repetitive, or document-heavy?
- Can the required context stay inside local files, a private database, or a
  controlled cloud workspace?
- Would retrieval plus a smaller model be sufficient?
- Can an open-source model handle first drafts, classification, summaries,
  routing, or form checks?
- Can the system escalate only difficult cases to a frontier model?
- Can the institution keep prompts, workflows, logs, and artifacts locally?
- Can the workflow run during a vendor outage or contract transition?
- Can local models and connectors be updated securely without silently changing
  behavior, permissions, or provenance?

## 11. Exit Plan

No AI pilot should begin without an exit plan.

- What files, workflows, prompts, agent configs, and logs will be delivered at
  the end?
- What staff training is required before handoff?
- What data must be deleted from vendor systems?
- What functions stop working if the vendor relationship ends?
- What local or alternate provider can take over?
- How long would migration take?
- What is the cost of leaving?
- How will credentials, tokens, logs, memory, embeddings, and retained data be
  revoked, preserved, migrated, or destroyed?

## Red Flags

- "Free" credits without a post-credit cost model.
- No export path for workflows, memory, prompts, or logs.
- Broad data-use rights that allow vendor model improvement by default.
- AI agents with tool access but no approval policy.
- AI agents using shared credentials, broad permissions, or unreviewed tools.
- No model, data, connector, plugin, or dependency provenance.
- No plan for prompt injection, retrieval poisoning, or data exfiltration.
- No clear owner for errors or harms.
- Staff are trained only to use a vendor interface, not to understand the
  workflow.
- Productivity savings flow entirely to budget cuts or vendor expansion.
- The system cannot be evaluated without trusting vendor dashboards.
- The vendor resists local, private, or open-source alternatives for routine
  work.

## Minimum Adoption Standard

An institution should not proceed unless it can answer yes to all of the
following:

- We know what data the system can access.
- We know what actions the system can take.
- We know who is accountable for its outputs.
- We can export our data and workflows.
- We can review logs and evidence.
- We know the system's supply chain and security controls.
- We can disable agent tools and preserve evidence during an incident.
- We know the cost after the initial program ends.
- We have a human review process for high-risk work.
- We have considered private SLM agency for routine tasks.
- We have an exit plan.

## Preferred Direction

Use hosted frontier systems where they are necessary and justified. Build the
base layer of institutional AI around portable workflows, private or local
models where feasible, auditable tool use, staff competence, and public value
capture. The institution should become more capable after adopting AI, not more
dependent.
