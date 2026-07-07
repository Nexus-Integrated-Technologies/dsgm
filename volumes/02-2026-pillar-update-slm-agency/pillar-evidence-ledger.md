# Pillar Evidence Ledger

Status: review-ready public draft support ledger for DSGM Volume 2.

This ledger maps current evidence to the three pillars of Volume 1:

- **Pillar A:** Artificial Humanity as legal-economic entity.
- **Pillar B:** value capture from autonomous cognitive production.
- **Pillar C:** Global Productivity Fund and Automation Dividend.

The ledger separates public external evidence from first-party implementation
evidence. Public sources support claims about the market and institutional AI
landscape. First-party sources support claims about the harness/runtime
direction that Volume 2 recommends.

## Public Institutional AI Evidence

| Evidence | What it shows | DSGM pillar mapping | Institutional implication |
| --- | --- | --- | --- |
| [Anthropic: Introducing Claude Corps](https://www.anthropic.com/news/claude-corps) | Anthropic announced a national fellowship program to train fellows on Claude and place them inside nonprofits, backed by an initial $150 million commitment. | Pillar A, Pillar C | AI firms are embedding AI capacity directly inside mission-driven organizations; public-benefit claims should be paired with institutional independence and durable capacity requirements. |
| [Anthropic: Claude Corps host FAQ](https://www.anthropic.com/claude-corps/host) | The host-facing framing presents AI fellows as hands-on support for nonprofit operational challenges. | Pillar A | The AI service layer is not only software licensing; it includes people, training, workflow design, and lasting systems. |
| [OpenAI Foundation: 2026 People-First AI Fund](https://openaifoundation.org/news/2026-people-first-ai-fund) | OpenAI Foundation announced a $50 million 2026 commitment for nonprofits engaging with AI. | Pillar C | Philanthropic AI funding can build community capacity, but grants should leave behind portable workflows, staff capability, and public value. |
| [OpenAI: ChatGPT Gov](https://openai.com/global-affairs/introducing-chatgpt-gov/) | OpenAI introduced a government-focused ChatGPT offering for U.S. agencies, including deployment in Azure commercial or government cloud. | Pillar A, Pillar B | AI is being packaged as government operating infrastructure; procurement must address data rights, compliance, pricing, and exit paths. |
| [OpenAI: OpenAI for Government](https://openai.com/global-affairs/introducing-openai-for-government/) | OpenAI consolidated public-sector offerings around access to capable models, secure environments, hands-on support, and government planning. | Pillar A, Pillar B | AI providers are moving toward full-service government adoption, not just API access. |
| [Microsoft: Empowering the nonprofit sector](https://blogs.microsoft.com/on-the-issues/2026/03/25/empowering-the-nonprofit-sector-to-meet-tomorrows-challenges/) | Microsoft announced nonprofit AI credentials, community support, role-based capacity resources, and large-scale nonprofit discounts/donations/grants. | Pillar A, Pillar C | AI adoption is becoming a sector-level capacity program; institutions should make sure capacity remains with the institution. |
| [Google.org: AI for Government Innovation](https://google.org/impact-challenges/ai-government-innovation) | Google.org describes a $30 million initiative supporting generative and agentic AI projects for public services through nonprofits, social enterprises, and academic partners. | Pillar A, Pillar C | Public-service AI is a formal funding category; public benefit should include governance, portability, and local stewardship. |
| [U.S. Census Bureau: AI Use at U.S. Businesses](https://www.census.gov/library/stories/2026/05/ai-use-businesses.html) | Census BTOS reporting shows measurable AI use among U.S. businesses in 2026, with larger firms adopting at higher rates. | Pillar A, Pillar B | AI adoption is no longer purely speculative; institutional planning should assume uneven but measurable diffusion across firms. |
| [OMB M-25-21: Accelerating Federal Use of AI](https://www.whitehouse.gov/wp-content/uploads/2025/02/M-25-21-Accelerating-Federal-Use-of-AI-through-Innovation-Governance-and-Public-Trust.pdf) | The current federal AI-use memo sets governance expectations for agency AI adoption and replaces earlier federal guidance. | Pillar A, Pillar C | Public agencies need AI governance, risk ownership, inventory, and public-trust mechanisms as operating requirements. |
| [OMB M-25-22: Driving Efficient Acquisition of AI](https://www.whitehouse.gov/wp-content/uploads/2025/02/M-25-22-Driving-Efficient-Acquisition-of-Artificial-Intelligence-in-Government.pdf) | The federal acquisition memo addresses how agencies should buy AI efficiently and responsibly. | Pillar B, Pillar C | Procurement is now a primary value-capture and agency-preservation surface. |
| [GSA: AI Guide for Government](https://coe.gsa.gov/coe/ai-guide-for-government/print-all/index.html) | GSA provides implementation guidance for government AI projects. | Pillar A | Agencies need practical operating playbooks, not only abstract AI policy. |
| [New York City AI Action Plan](https://www.nyc.gov/assets/oti/downloads/pdf/reports/artificial-intelligence-action-plan.pdf) | NYC published a municipal AI action plan for city-level governance and deployment. | Pillar A, Pillar C | Municipal AI adoption is becoming a formal operating agenda; local public value and resident accountability must be designed in. |
| [California GenAI Guidelines](https://cdt.ca.gov/wp-content/uploads/2024/07/3a-GenAI-Guidelines.pdf) | California issued state guidance for generative AI procurement, use, and training. | Pillar A, Pillar B | State AI deployment requires procurement controls, staff training, and risk management before tools become embedded. |

## Public Agent And SLM Infrastructure Evidence

| Evidence | What it shows | DSGM pillar mapping | Institutional implication |
| --- | --- | --- | --- |
| [Model Context Protocol documentation](https://modelcontextprotocol.io/docs/getting-started/intro) | MCP is an open standard connecting AI applications to data sources, tools, and workflows. | Pillar A | Tool-connected AI is becoming standardized; institutions need permission, logging, and security policies for connected agents. |
| [Anthropic: Introducing the Model Context Protocol](https://www.anthropic.com/news/model-context-protocol) | Anthropic framed MCP as a way to build secure two-way connections between data sources and AI-powered tools. | Pillar A | AI systems are becoming action-capable through standard connectors, strengthening the operational agency argument. |
| [OpenAI Agents SDK documentation](https://openai.github.io/openai-agents-python/agents/) | The Agents SDK manages turns, tools, guardrails, handoffs, and sessions. | Pillar A | Agent orchestration is now packaged as a developer primitive, making accountability and evidence records necessary. |
| [OpenAI Agents SDK: running agents](https://openai.github.io/openai-agents-python/running_agents/) | The SDK supports long-running agents, human-in-the-loop workflows, handoffs, and progress preservation through integrations. | Pillar A | Long-running AI work needs durable state, approval points, and auditable execution history. |
| [LangGraph overview](https://docs.langchain.com/oss/python/langgraph/overview) | LangGraph focuses on durable execution, streaming, and human-in-the-loop orchestration. | Pillar A | Agent reliability is now a systems problem, not just a model-quality problem. |
| [Microsoft Agent Framework overview](https://learn.microsoft.com/en-us/agent-framework/overview/) | Microsoft Agent Framework supports agents, tool and MCP server calls, graph workflows, type-safe routing, checkpointing, and human-in-the-loop support. | Pillar A, Pillar B | Enterprise agent platforms are turning model use into managed workflow infrastructure. |
| [Microsoft Agent Framework at Build 2026](https://devblogs.microsoft.com/agent-framework/microsoft-agent-framework-at-build-2026-announce/) | Microsoft describes the agent harness as the layer where model reasoning meets real execution, including shell/file access, approvals, and context management. | Pillar A | The harness plateau is now explicit in mainstream platform language. |
| [Ollama tool support](https://ollama.com/blog/tool-support) | Ollama supports local tool calling with popular models. | Pillar A | Local models can participate in agent workflows, supporting private SLM agency. |
| [Ollama streaming tool calling](https://ollama.com/blog/streaming-tool) | Ollama supports streaming responses with tool calling and lists multiple tool-calling model families. | Pillar A | Local agent UX and tool use are improving beyond static chat. |
| [llama.cpp server README](https://github.com/ggml-org/llama.cpp/blob/master/tools/server/README.md) | llama.cpp server supports OpenAI-style function calling and OpenAI-compatible local serving patterns. | Pillar A, Pillar B | Institutions can run local or private inference behind familiar API surfaces, reducing default dependence on hosted frontier APIs. |
| [Microsoft Phi small language models](https://azure.microsoft.com/en-us/products/phi) | Microsoft positions Phi models as small, efficient models for local, edge, and cloud use cases. | Pillar A, Pillar B | Smaller models can support bounded institutional workflows at lower marginal cost. |
| [Google Gemma documentation](https://ai.google.dev/gemma/docs) | Gemma provides open models with multiple sizes and deployment patterns. | Pillar A, Pillar B | Open-weight models give institutions more routing and deployment choices than hosted frontier-only architectures. |
| [Meta: Introducing Llama 3.1](https://ai.meta.com/blog/meta-llama-3-1/) | Meta describes open models across sizes, including smaller variants suitable for local and private adaptation. | Pillar A, Pillar B | Open model families make private SLM agency more realistic for routine work. |
| [Stanford CRFM: Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html) | Alpaca demonstrated low-cost instruction-following adaptation for smaller models in a research context. | Pillar A, Pillar B | The SLM direction has roots in the efficiency and adaptation curve, not only in 2026 platform packaging. |

## Public AI Security And Resilience Evidence

| Evidence | What it shows | DSGM pillar mapping | Institutional implication |
| --- | --- | --- | --- |
| [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) | NIST frames AI risk management through governance, mapping, measurement, and management across organizational contexts. | Pillar A, Pillar C | AI adoption needs formal risk ownership and ongoing management, not only model selection. |
| [NIST AI RMF Generative AI Profile](https://www.nist.gov/publications/artificial-intelligence-risk-management-framework-generative-artificial-intelligence) | NIST identifies generative AI risks including information security, data privacy, information integrity, and incident response. | Pillar A, Pillar C | Institutions should evaluate generative AI systems as socio-technical risk systems before deployment. |
| [OWASP Top 10 for LLM Applications](https://owasp.org/www-project-top-10-for-large-language-model-applications/) | OWASP lists application risks such as prompt injection, sensitive information disclosure, supply-chain vulnerabilities, data/model poisoning, improper output handling, and excessive agency. | Pillar A, Pillar B | AI agents need least privilege, tool boundaries, input/output controls, and supply-chain review. |
| [MITRE ATLAS](https://atlas.mitre.org/) | MITRE ATLAS is a knowledge base of adversary tactics and techniques against AI-enabled systems based on real-world observations. | Pillar A | Institutions should threat-model AI systems as attackable infrastructure, not neutral productivity tools. |
| [CISA AI Cybersecurity Collaboration Playbook](https://www.cisa.gov/resources-tools/resources/ai-cybersecurity-collaboration-playbook) | CISA provides guidance for AI providers, developers, and adopters to share AI-related cybersecurity information. | Pillar A, Pillar C | AI incidents and vulnerabilities need reporting paths, collaboration, and recovery processes. |
| [CISA and UK NCSC secure AI system development guidelines](https://www.cisa.gov/news-events/alerts/2023/11/26/cisa-and-uk-ncsc-unveil-joint-guidelines-secure-ai-system-development) | CISA and partners recommend secure-by-design AI development across design, development, deployment, and operations. | Pillar A, Pillar B | Procurement should require secure development, deployment, monitoring, and supply-chain practices. |
| [NSA/CISA/FBI AI data security guidance](https://www.cisa.gov/news-events/alerts/2025/05/22/new-best-practices-guide-securing-ai-data-released) | Joint guidance highlights data security across the AI lifecycle, including the data supply chain and protection against unauthorized modification. | Pillar A, Pillar B | Data provenance, integrity, and protection are prerequisites for trustworthy AI outputs. |
| [UK NCSC: Prompt injection is not SQL injection](https://www.ncsc.gov.uk/blog-post/prompt-injection-is-not-sql-injection) | NCSC warns that prompt injection should be treated as an "inherently confusable" deputy problem where risk and impact must be reduced rather than assumed fully fixable. | Pillar A | Institutions should limit agent power, isolate untrusted content, and avoid use cases that cannot tolerate residual prompt-injection risk. |
| [International AI Safety Report 2026](https://internationalaisafetyreport.org/publication/international-ai-safety-report-2026) | The international safety report treats advanced loss-of-control scenarios as serious but uncertain frontier risks requiring continued evaluation. | Pillar A, Pillar C | Institutional planning should translate "takeover" into governable operational loss-of-control hazards while avoiding unsupported claims about present machine intent. |

## Public Labor, Productivity, And Public-Finance Evidence

| Evidence | What it shows | DSGM pillar mapping | Institutional implication |
| --- | --- | --- | --- |
| [IMF: AI Will Transform the Global Economy](https://www.imf.org/en/blogs/articles/2024/01/14/ai-will-transform-the-global-economy-lets-make-sure-it-benefits-humanity) | IMF frames AI as a large labor-market and productivity shock with distributional consequences. | Pillar B, Pillar C | Productivity gains require policy design if they are to become broadly shared public benefit. |
| [IMF: Broadening the Gains from Generative AI](https://www.imf.org/en/publications/staff-discussion-notes/issues/2024/06/11/broadening-the-gains-from-generative-ai-the-role-of-fiscal-policies-549639) | IMF analyzes fiscal-policy options for sharing GenAI gains and managing disruption. | Pillar B, Pillar C | DSGM's value-capture and fund logic should be framed as a fiscal-policy proposal under uncertainty. |
| [ILO: Generative AI and Jobs](https://www.ilo.org/sites/default/files/2024-07/WP96_web.pdf) | ILO emphasizes task exposure and augmentation rather than a single full-displacement forecast. | Pillar B | Institutions should measure affected tasks and gains, not rely on simplistic job-replacement claims. |
| [OECD: AI and work](https://www.oecd.org/en/topics/sub-issues/ai-and-work.html) | OECD tracks AI's labor-market effects, including productivity, skills, job quality, and distributional risks. | Pillar B, Pillar C | Adoption rules should include workforce transition, skills, privacy, and bargaining considerations. |
| [CBO: AI and potential effects on the economy and federal budget](https://www.cbo.gov/publication/61147) | CBO treats AI productivity and budget effects as important but uncertain. | Pillar B, Pillar C | DSGM should present dividends and productivity funds as policy architecture, not as guaranteed fiscal arithmetic. |
| [Alaska Permanent Fund Corporation](https://apfc.org/) and [Alaska Permanent Fund Dividend Division](https://pfd.alaska.gov/) | Alaska provides a real fund-and-dividend precedent tied to resource rents. | Pillar C | Automation Dividend design can learn from existing public-asset dividend mechanisms while recognizing AI is not oil. |
| [Norway Government Pension Fund](https://www.regjeringen.no/en/topics/the-economy/the-government-pension-fund/id1441/) | Norway provides a sovereign wealth precedent for converting strategic resource returns into long-term public capital. | Pillar C | The Global Productivity Fund can be framed as an AI-era adaptation of intergenerational public wealth logic. |
| [World Bank: Exploring Universal Basic Income](https://www.worldbank.org/en/topic/socialprotectionandjobs/publication/exploring-universal-basic-income-a-guide-to-navigating-concepts-evidence-and-practices) | World Bank surveys UBI design tradeoffs and implementation considerations. | Pillar C | Automation Dividend design should distinguish universal claims on productivity from ordinary welfare program design. |

## First-Party Implementation Evidence

| Evidence | What it shows | DSGM pillar mapping | Institutional implication |
| --- | --- | --- | --- |
| [Nexus agency README](https://github.com/Nexus-Integrated-Technologies/agency/blob/master/README.md) | The `agency` repository describes a Rust runtime substrate moving older Agency harness ideas into NanoClaw contracts, with OpenClaw gateway execution and runtime evidence. | Pillar A | First-party work validates that the key frontier is the runtime harness around models: tools, routing, evidence, state, and approval. |
| [Agency capability adoption ledger](https://github.com/Nexus-Integrated-Technologies/agency/blob/master/docs/agency-capability-adoption-ledger.md) | The ledger classifies old harness capabilities into active, foundation, runtime, parked, or replacement decisions, including execution evidence and tool contracts. | Pillar A, Pillar B | Harness capability must be governed before it becomes active infrastructure; this mirrors the accountability bridge proposed in Volume 2. |
| [Agency provider routing roadmap](https://github.com/Nexus-Integrated-Technologies/agency/blob/master/docs/provider-routing-roadmap.md) | The roadmap describes backend routing, fallbacks, cost-aware model tiers, and evidence fields for provider calls. | Pillar B | Model choice is an economic routing problem; value capture and cost discipline depend on visible provider/model/usage records. |
| [Agency foundation model](https://github.com/Nexus-Integrated-Technologies/agency/blob/master/docs/foundation-model.md) | The foundation layer models groups, tasks, execution contexts, environments, artifacts, and events as reusable primitives. | Pillar A, Pillar C | Durable agency requires institutional records and artifact trails, not only chat transcripts. |

## Evidence-To-Pillar Summary

### Pillar A: Artificial Humanity

Current evidence supports the AH thesis by showing that AI is becoming
operational agency: persistent systems connected to tools, data, workflows,
approval paths, and institutional tasks. The near-term governance object is not
machine personhood. It is accountable AI service ownership, including security
ownership for tools, data, identities, logs, and incident response.

### Pillar B: Value Capture

Current evidence stresses the original compute-tax framing. Value is captured
through subscriptions, credits, service contracts, cloud spend, workflow
dependency, model routing, and data gravity. Compute and energy levies remain
part of the answer, but public-benefit procurement and service/output capture
must be added. Security also affects value capture because supply-chain risk,
opaque routing, compromised data, and unmanaged tool access can externalize
costs onto public institutions while private providers capture the upside.

### Pillar C: Global Productivity Fund And Automation Dividend

Current evidence supports the public-benefit logic by showing major AI
deployment programs aimed at nonprofits and government. Those programs should
be evaluated not only by adoption numbers, but by what public or institutional
capacity remains after the program ends and whether that capacity can be run
securely. Labor and public-finance sources support the dividend argument as a
policy response to uncertain but potentially uneven productivity gains, while
sovereign-wealth and dividend precedents show that public-asset return sharing
is institutionally possible.

## Claims Not Made

This draft does not claim hidden vendor intent. It does not claim that the named
programs are inherently harmful. It claims that their public shape reveals a
structural transition: AI firms and platforms are moving into the operating
layer of institutions. DSGM Volume 2 argues that institutions should accept AI
support only with governance, portability, local capacity, and public value
preserved.

## Claim Coverage Matrix

| Manuscript claim | Evidence coverage | Status |
| --- | --- | --- |
| AI is moving from standalone tools into institutional operating infrastructure. | Claude Corps, OpenAI People-First AI Fund, ChatGPT Gov, OpenAI for Government, Microsoft Elevate for Changemakers, Google.org AI for Government Innovation, Census BTOS, OMB M-25-21, OMB M-25-22, GSA, NYC, California. | Covered by public institutional sources. |
| The practical precursor to Artificial Humanity is operational agency. | MCP, OpenAI Agents SDK, LangGraph, Microsoft Agent Framework, first-party agency runtime docs. | Covered by public technical sources plus first-party implementation evidence. |
| The harness around the model is now a primary control surface. | LangGraph, Microsoft Agent Framework, OpenAI Agents SDK, agency capability adoption ledger, agency provider routing roadmap. | Covered. |
| Compute-only value capture is insufficient as models become smaller, cheaper, and more distributed. | Volume 1 efficiency-paradox logic, Phi, Gemma, Llama, Alpaca, Ollama, llama.cpp, local tool-calling and OpenAI-compatible serving patterns, agency provider routing roadmap. | Covered as analysis from Volume 1 plus current SLM/local-runtime evidence. |
| Institutional AI adoption should include public-benefit procurement and reinvestment rules. | Public institutional AI programs plus DSGM Pillar B/Pillar C logic. | Covered as normative DSGM analysis, not as a claim that vendors currently require it. |
| Private SLM agency is the recommended steering direction for routine institutional work. | Ollama, llama.cpp, MCP, agency runtime/provider-routing docs, institutional checklist. | Covered as first-party recommendation supported by current local-agent infrastructure. |
| Frontier models remain useful but should be routed intentionally. | Agency provider routing roadmap and public agent framework docs. | Covered as architecture/policy recommendation. |
| AI supply-chain attacks, prompt injection, excessive agency, data leakage, and loss-of-control failures are institutional hazards. | NIST AI RMF/GAI Profile, OWASP LLM Top 10, MITRE ATLAS, CISA AI cybersecurity playbook, CISA/NCSC secure AI guidelines, NSA/CISA/FBI AI data-security guidance, UK NCSC prompt-injection guidance. | Covered by public security sources. |
| "AI takeover" should be translated into operational loss of control for institutional planning. | OWASP excessive agency, NCSC prompt-injection framing, NIST risk-management framing, International AI Safety Report, first-party harness/evidence controls. | Covered as risk analysis, not as a claim of machine intent. |
| Productivity funds and automation dividends are policy proposals grounded in existing public-finance precedents. | IMF fiscal-policy work, CBO uncertainty analysis, ILO/OECD labor exposure work, Alaska Permanent Fund, Norway Government Pension Fund, World Bank UBI guidance. | Covered as DSGM policy architecture, not as a proven AI-era dividend implementation. |
| Named vendor programs are not asserted to be malicious or secretly extractive. | Claims Not Made section and source framing. | Explicitly bounded. |
