# Stage 3 – AI Future Conditions Discovery

**Stage status:** `pass_with_cautions`  
**Date completed:** 23 June 2026  
**Lead agent / author:** Codex, acting as Master Coordinator and Documentation Editor  
**Specialist process:** Foundation Models and LLMs; Agents, Coding and Self-Improvement; Generative Software and Interfaces; Robotics and Embodied AI; AI for Science, Medicine and Engineering; Infrastructure, Compute, Open and Edge AI; Safety, Misuse, Ambient AI and Adjacent Technologies  
**Review agents:** Knowledge Integration Architect, Evidence Auditor, Bias and Generalisability Auditor, Adversarial Red Team Agent  
**Evidence base:** Existing Stage 3 ledger rows only, `S3-SRC-001`–`S3-SRC-047`

---

## Executive Summary

Stage 3 was reopened because the earlier technical futures map was useful but too compressed. It had the right ingredients, but not yet the depth of synthesis required for Stage 4. This revised report uses the existing Stage 3 sources only. No new sources were collected. Specialist agents were asked to speak from their assigned source rows, identify mechanisms and bottlenecks, challenge one another indirectly through a chaired synthesis, and allow the final thesis and structure to emerge after discussion rather than before it.

The strongest synthesis is this: AI futures are not governed by a single curve called intelligence. They are shaped by the price of turning capability into verified action. Where reality answers cheaply — code that can be run, outputs that can be tested, candidates that can be scored, environments that can be simulated — AI systems may improve and spread quickly. Where reality is embodied, regulated, expensive, adversarial, socially meaningful or slow to verify, progress may still be real but becomes more uneven, institution-dependent and costly.

This thesis is not a master key. The red team explicitly warned against making it too elegant. Feedback loops matter, but so do capital, energy, chips, data centres, governance, market power, institutional adoption, trust, law, safety, human responsibility and geopolitics. The report therefore treats the future as a set of interacting technical condition bands rather than a single prediction.

The main findings are:

- Foundation-model futures are increasingly model-plus-system futures. Capability depends not only on model weights, but on context, tools, memory-like systems, inference-time compute, scaffolding, evaluation, permissions and deployment environments. [Sources: `S3-SRC-001`–`S3-SRC-010`; Ledger: `S3-TALK-FOUNDATION`, `S3-DISCUSSION-MASTER`]
- AI progress appears strongest where work can be tested, scored, corrected or rolled back cheaply. Coding and some AI R&D tasks are important signals, but benchmark gains do not prove broad autonomy or labour replacement. [Sources: `S3-SRC-004`–`S3-SRC-014`; Ledger: `S3-TALK-AGENTS`, `S3-REDTEAM-001`]
- Generative software and GUI agents may shift some interaction from fixed interfaces toward intent-driven, agent-mediated workflows, but this relocates complexity into verification, permissions, security, maintenance and accountability. [Sources: `S3-SRC-011`, `S3-SRC-012`, `S3-SRC-015`, `S3-SRC-016`; Ledger: `S3-TALK-GUI`]
- Robotics is the point at which AI leaves the browser and discovers gravity. Foundation-model robotics is progressing, but physical deployment remains constrained by dexterity, safety, cost, maintenance, environment variation and liability. [Sources: `S3-SRC-017`–`S3-SRC-024`; Ledger: `S3-TALK-ROBOTICS`]
- AI for science, medicine and engineering may make possibility cheaper by accelerating search, generation and candidate discovery. It does not by itself make validation cheap. Experiments, trials, replication, toxicity, manufacturing, regulation and deployment remain decisive bottlenecks. [Sources: `S3-SRC-025`–`S3-SRC-032`; Ledger: `S3-TALK-SCIENCE`]
- AI infrastructure is not background plumbing. Compute, chips, memory, networking, data centres, electricity, water, capital, inference cost, open-weight models, edge deployment and sovereign AI are first-order future conditions. [Sources: `S3-SRC-033`–`S3-SRC-036`, `S3-SRC-046`, `S3-SRC-047`; Ledger: `S3-TALK-INFRA`]
- Safety is not an appendix to capability. As AI systems act through tools, interfaces, media, companions, devices and institutions, governance, misuse, provenance, trust, companionship, cyber/bio uplift and decentralised deployment become part of the technology’s operating conditions. [Sources: `S3-SRC-037`–`S3-SRC-047`; Ledger: `S3-TALK-SAFETY`]
- Recursive self-improvement remains an unresolved hypothesis and watchlist condition, not an established finding. [Sources: `S3-SRC-004`–`S3-SRC-014`; Ledger: `S3-UNC-001`, `S3-REDTEAM-001`]
- Stage 3 passes forward technical condition bands, signposts, uncertainties and prohibited overextensions. It does not write Stage 4 future worlds and does not authorise curriculum, capability, pedagogy, subject or assessment decisions. [Ledger: `S3-EDITORIAL-001`]

**Claim status:** cross-source synthesis, moderate confidence, `pass_with_cautions`.

---

## Method and Agent Process

This report is the result of a reopened Stage 3 synthesis, not a fresh source collection exercise. The source base remained fixed at the Stage 3 ledger’s accepted rows, `S3-SRC-001`–`S3-SRC-047`. The purpose of the reopened process was to make the existing evidence think harder.

The process followed the new Agent Cognitive Quality Protocol added to `AGENTS.md`. Each specialist was required to frame scope, identify authorised source IDs, extract mechanisms, separate empirical findings from projections and uncertainties, name likely overclaims, identify surprising or under-discussed patterns, and hand forward only what the Master Coordinator should preserve, weaken or exclude.

Seven source-constrained specialist talks were completed and logged:

- Foundation Models and LLMs: `S3-TALK-FOUNDATION`
- Agents, Coding and Self-Improvement: `S3-TALK-AGENTS`
- Generative Software and Interfaces: `S3-TALK-GUI`
- Robotics and Embodied AI: `S3-TALK-ROBOTICS`
- AI for Science, Medicine and Engineering: `S3-TALK-SCIENCE`
- Infrastructure, Compute, Open and Edge AI: `S3-TALK-INFRA`
- Safety, Misuse, Ambient AI and Adjacent Technologies: `S3-TALK-SAFETY`

Only after these talks were complete did the Knowledge Integration Architect chair a cross-agent synthesis. That discussion identified the strongest recurring mechanisms, tensions, fragile claims and possible report structures. The final thesis and chapter sequence were then adopted as an editorial decision in `S3-EDITORIAL-001`, after the evidence/bias audit and adversarial red-team critique.

The evidence auditor’s recommendation was `revise_before_pass` until the rewrite preserved cautions around benchmark limits, demo-to-deployment gaps, projection status, infrastructure constraints, governance limits, embodiment bottlenecks, high-resource evidence bias and Stage 4 drift. The red team recommended `pass_with_cautions` only if the final report avoided a smooth acceleration story and preserved minority objections. This report implements those weakenings.

The chapter order below is an explanatory route for the reader. It is not a prediction of technological arrival order. Infrastructure and safety are not late because they happen late; they are placed later in the narrative because they reframe what the earlier chapters mean.

---

## Emergent Central Thesis

The tempting story is simple: AI gets smarter, then everything changes.

The evidence does not support a story that simple. The more defensible story is stranger and more useful. AI futures will be shaped by the price of reality-checking: the cost of turning model capability into reliable action in a particular environment.

In software-like worlds, reality can answer quickly. A program runs or fails. A test passes or breaks. A benchmark can score an output. A compiler complains. A log records the result. A generated solution can be searched, mutated, rerun and compared. This does not make software easy, and it certainly does not make software engineering solved. But it does mean that some AI systems can improve through dense feedback loops in ways that are harder elsewhere. [Sources: `S3-SRC-004`–`S3-SRC-014`]

In the physical world, reality answers more slowly and more expensively. A robot that drops a glass cannot simply restore the scene. A warehouse failure may stop a line. A domestic robot must handle pets, clutter, children, dust, stairs, liquids, strangers, fragile objects and law. A medical model can suggest a diagnosis or candidate therapy, but clinical benefit must survive trials, regulation, workflow integration and patient variation. A materials model can generate candidates, but manufacturing and field performance still have to be proved. [Sources: `S3-SRC-017`–`S3-SRC-032`]

In society, reality answers through trust. A synthetic image may not need to persuade everyone to matter; it may need only to raise verification costs, create plausible deniability, or exhaust public attention. An AI companion may not need to be superintelligent to matter; it may need only to be persistent, responsive, intimate and always available. A governance framework may classify risk without ensuring safe behaviour. An open-weight model may broaden access while decentralising misuse and oversight. [Sources: `S3-SRC-037`–`S3-SRC-047`]

So the central question is not, “How intelligent will AI become?” It is: where, and under what constraints, can AI capability be converted into verified, affordable, governable action?

That is the Stage 3 baseline for Stage 4.

---

## Prologue — The Wrong Graph

Much public discussion of AI imagines a graph. The line climbs. The line gets steeper. Somewhere beyond the right edge, the future changes category.

Graphs can be useful, but Stage 3 suggests that this one is dangerously incomplete. It treats intelligence as if it were a substance that accumulates in a model and then spills evenly into society. The sources do not show that. They show technical systems moving along several partly connected tracks: model capability, inference-time reasoning, tool use, software agents, GUI operation, robotics, scientific discovery, compute infrastructure, open and edge deployment, safety evaluation, governance and ambient social use.

The line on the graph also hides the world into which AI must act. A model may become better at writing code, but the relevant question is not only whether it can produce a plausible patch. Can it understand the surrounding system? Can it avoid security regressions? Can it maintain code over time? Can it interact with human review? Can it be trusted with production access? Benchmarks and long-task evaluations are useful signals, but they are not identical to institutional responsibility. [Sources: `S3-SRC-004`, `S3-SRC-005`, `S3-SRC-011`, `S3-SRC-012`]

The same problem appears in science. A model can generate protein structures, candidate materials or engineering designs. That is extraordinary. But a molecule is not a medicine, a material prediction is not a factory, and a design is not a safe bridge or a working battery. The world insists on validation. [Sources: `S3-SRC-025`–`S3-SRC-032`]

The same problem appears in robotics. A robot demo can look like a future arriving early. Yet physical deployment is full of hidden taxes: sensors, actuators, safety standards, maintenance, battery life, uptime, intervention rate, integration cost, insurance, liability and the long tail of ordinary environments. [Sources: `S3-SRC-017`–`S3-SRC-024`]

And the same problem appears in trust. Synthetic media does not need to collapse truth everywhere to matter. It may simply make truth more expensive to establish. Governance does not need to fail everywhere to matter. It may work unevenly, arrive late, or become a ritual of compliance rather than a real control system. [Sources: `S3-SRC-037`–`S3-SRC-042`]

The wrong graph tells one story: more intelligence, more transformation. Stage 3 tells a more disciplined story: capability matters, but conversion matters too. AI becomes consequential when capability meets feedback, tools, permissions, infrastructure, cost, adoption and verification. Different domains impose different prices.

---

## Chapter 1 — The Model Is Not the Machine

The first necessary correction is to stop treating the model as the whole technology.

Foundation models remain central. The Stage 3 source base includes current capability reports, safety updates, reasoning-model system cards, open reasoning-model papers, inference-time compute work and long-context evaluation. Together they show that frontier AI is no longer best understood as a text box that predicts the next word. Models are becoming multimodal, tool-connected, reasoning-oriented and increasingly embedded inside systems that search, retrieve, remember, call tools, inspect files, run code, browse interfaces and interact with human workflows. [Sources: `S3-SRC-001`–`S3-SRC-010`]

But the specialist synthesis insisted on a sharper unit of analysis: the deployed AI system. A model’s weights matter, but so do context windows, retrieval, memory-like stores, prompts, post-training, tool access, inference-time compute, external verifiers, user permissions, environment design and monitoring. The future is not merely larger models. It is capability assembled at runtime.

This matters because it changes how progress should be read. A benchmark result may reflect the model. Or it may reflect the scaffold. Or the tool environment. Or the availability of search. Or the evaluation harness. Or leakage from training data. Or a clever way of spending more compute at inference time. Evidence about model ability is therefore evidence about a model-system in a particular measurement context, not a clean measure of general intelligence.

The long-context problem illustrates the point. Longer context windows can be useful. They allow models to hold more documents, code, conversation or state. But long context is not the same as durable memory, deep understanding or reliable synthesis. Evaluation work such as NoLiMa warns that literal matching and retrieval can make systems appear stronger than they are when the task requires non-literal reasoning across noisy or synthetic contexts. [Source: `S3-SRC-010`]

Inference-time compute is another useful but limited signal. Test-time scaling, search and repeated reasoning can improve performance in some settings. Open reasoning-model work and test-time scaling papers show that capability can be increased not only during training but during use. [Sources: `S3-SRC-007`, `S3-SRC-008`, `S3-SRC-009`] Yet inference-time compute is not free. It creates cost, latency, energy demand and reliability questions. A system that can solve a task after many attempts may be impressive in a benchmark and still awkward in a real workflow where time, money, confidence and accountability matter.

The first Stage 3 claim, then, is not that foundation models are becoming universally intelligent. It is that AI capability is becoming system-level. The model is increasingly one component in a larger machine of tools, context, verification, memory, permissions, compute and environment design.

**Claim status:** empirical finding and cross-source synthesis, moderate confidence.  
**Main sources:** `S3-SRC-001`–`S3-SRC-010`; `S3-TALK-FOUNDATION`.  
**Must not be overclaimed:** model scale, long context, tool use or reasoning benchmarks do not prove AGI, understanding, reliable autonomy or smooth social adoption.

---

## Chapter 2 — The World That Answers Back

Once the model is seen as part of a system, a second question appears: what kind of world does the system act inside?

Coding matters because code answers back. It is not the only important AI domain, but it is unusually revealing. A generated patch can be run. A test can fail. A compiler can complain. A repository can expose whether an edit broke something else. A benchmark can at least attempt to compare performance. This makes software a high-feedback environment, and high-feedback environments are where AI systems may improve fastest. [Sources: `S3-SRC-004`–`S3-SRC-014`]

METR-style long-task evaluations, RE-Bench, SWE-style benchmarks, contamination critiques and AI R&D agent work all point in the same broad direction: AI systems are improving in bounded digital tasks, especially where success can be evaluated. [Sources: `S3-SRC-004`, `S3-SRC-005`, `S3-SRC-011`, `S3-SRC-012`] AlphaEvolve and AI Scientist-style systems are important because they gesture toward partial loops in which AI proposes, codes, experiments and evaluates. [Sources: `S3-SRC-013`, `S3-SRC-014`]

That is the real significance of coding agents. It is not the crude claim that software engineers disappear. The stronger and more defensible claim is that software-like environments let AI systems convert generation into correction. They give models something to push against.

The red team insisted on a hard boundary here. Passing tests is not the same as owning a software project. A coding benchmark is not the same as maintaining a production system, understanding ambiguous user needs, protecting security, coordinating across teams, making architectural trade-offs, or carrying legal and organisational responsibility. Benchmark contamination and harness effects are serious concerns. [Sources: `S3-SRC-011`, `S3-SRC-012`; Ledger: `S3-REDTEAM-001`]

This is also where recursive self-improvement enters — and must be restrained. If AI systems become better at coding, AI research, evaluation, kernel optimisation, architecture search or experiment management, then they may help improve AI itself. That is a real watchlist. But the authorised evidence does not establish recursive self-improvement, exponential takeoff or autonomous improvement of model architectures in the strong sense. Current systems still rely on human-built scaffolds, human-defined objectives, bounded evaluators, curated environments and independent validation. [Sources: `S3-SRC-004`–`S3-SRC-014`; Ledger: `S3-UNC-001`]

The most important question is not whether models can write code. It is whether they can reliably participate in closed improvement loops whose outputs are valid, safe and actually better.

Stage 3 therefore treats agentic software acceleration as plausible and important, but bounded. It passes forward a condition band in which coding agents and AI R&D tools accelerate some software-like workflows, especially where goals are clear and feedback is dense. It does not pass forward the claim that AI agents replace software engineers, own open-ended projects, or recursively self-improve.

**Claim status:** empirical finding for bounded coding-agent progress; speculative projection for broader agentic acceleration; unresolved uncertainty for recursive self-improvement.  
**Main sources:** `S3-SRC-004`–`S3-SRC-014`; `S3-TALK-AGENTS`; `S3-REDTEAM-001`.  
**Must not be overclaimed:** benchmarks do not prove labour replacement, broad autonomy or recursive self-improvement.

---

## Chapter 3 — When Software Becomes Negotiation

If coding agents show AI acting on software from the inside, GUI agents show AI acting on software from the outside.

For most of the personal-computing era, software has been an arrangement of fixed surfaces: windows, menus, buttons, forms, dashboards, icons, files. Humans learn the interface and operate it directly. Generative software and GUI agents suggest a different pattern. A person states an intention; an AI system interprets the task, reads the interface, plans actions, clicks, types, calls tools, assembles code, generates a dashboard, fills a form, or creates a temporary workflow around the user’s goal. [Sources: `S3-SRC-015`, `S3-SRC-016`]

The generative-software specialist described this as software becoming a conversation between intent, model, interface, tools and verification. That is a useful image, provided it is not made magical. The future here is not “anyone can instantly make any app.” It is that some software interaction may shift from fixed interface operation to agent-mediated execution.

This matters because interfaces are not decorative. They are how institutions encode permissions, workflows, defaults, evidence, roles and accountability. A GUI agent that clicks a button is not merely producing text. It is changing state. It may send a message, delete a file, submit a form, purchase an item, alter a record, transfer information, or expose data. Once AI crosses from advice into interface operation, safety questions become operational questions.

This domain also inherits the coding-agent cautions. Generated applications and adaptive interfaces still need requirements, security, accessibility, testing, versioning, maintainability, integration, support and accountability. A temporary generated UI can be elegant and still be dangerous if no one can audit what it did. A GUI agent can succeed in a benchmark and fail when a platform changes a button, when hidden state matters, when a prompt injection appears inside a webpage, or when a real account holds money, health information or legal records. [Sources: `S3-SRC-011`, `S3-SRC-012`, `S3-SRC-015`, `S3-SRC-016`]

The most interesting possibility is not the disappearance of software engineering. It is the relocation of software complexity. Some visible friction may disappear from the user’s screen. New friction will appear in verification, permissions, sandboxes, audit trails, provenance, reversibility, platform rules and liability.

This chapter also changes the meaning of access. If software becomes more adaptive, some users may gain new power: they can ask for tools without knowing the old interface rituals. But dynamic interfaces may also make shared instruction harder. If every user sees a different workflow generated on demand, what counts as a reliable process? Who can inspect it? How is accessibility guaranteed? How does an institution teach, audit or certify something that changes shape around each person?

The evidence is not strong enough to predict a general end of fixed interfaces. It is strong enough to pass forward a generative-interface transition band: AI may increasingly mediate some digital actions through natural language, generated interfaces and GUI operation. The bottlenecks are security, verification, accountability, platform control, user intent and failure recovery.

**Claim status:** empirical finding for active GUI-agent research; speculative projection for broad generative-interface transition, low-to-moderate confidence.  
**Main sources:** `S3-SRC-011`, `S3-SRC-012`, `S3-SRC-015`, `S3-SRC-016`; `S3-TALK-GUI`.  
**Must not be overclaimed:** instant UI or app generation does not eliminate software complexity; it moves complexity into verification and control.

---

## Chapter 4 — Gravity, Hands and the Price of Bodies

Robotics is where the acceleration story meets the floor.

Industrial robotics is already real. The International Federation of Robotics reports large-scale industrial deployment, and automation is deeply established in structured manufacturing and logistics contexts. [Source: `S3-SRC-017`] What is changing is the attempt to bring foundation-model methods into robotics: cross-embodiment datasets, robot foundation models, vision-language-action systems and generalist policies such as Open X-Embodiment/RT-X, RT-2, OpenVLA, π0 and Octo. [Sources: `S3-SRC-018`–`S3-SRC-023`]

This is important. It suggests that robots may become less brittle, less hand-scripted and more able to generalise across tasks, objects and instructions. Language can help specify goals. Vision can help interpret scenes. Large datasets can help transfer behaviour across embodiments. Simulation can help generate practice. On-device models may reduce dependence on cloud latency for some tasks.

But robotics is not simply AI plus a body. It is AI plus bodies, surfaces, tools, humans, dust, liquids, pets, stairs, weather, kitchens, hospitals, warehouses, maintenance schedules, insurance policies and safety standards. It is where action becomes expensive.

The robotics specialist’s most memorable line deserves to survive into the final report: AI leaves the browser and discovers gravity. In software, a failed action can often be retried. In robotics, a failed action can damage a product, injure a person, halt a workflow, or destroy trust in the deployment. Physical systems must deal with perception, force, friction, sensor fusion, battery life, gripper design, deformable objects, long-tail environments, human unpredictability and repair. [Sources: `S3-SRC-017`, `S3-SRC-023`, `S3-SRC-024`]

Safety standards such as ISO 10218 matter because robotics cannot be evaluated only as model capability. It must be evaluated as equipment operating near people and property. [Source: `S3-SRC-024`] A humanoid robot demo may be a useful research signal, but it is not deployment evidence. Adoption depends on uptime, intervention rates, total cost of ownership, site integration, maintenance, liability, worker acceptance and the availability of tasks structured enough for reliable performance.

The most defensible near-term claim is therefore narrower than the public imagination often wants. AI-enabled robotics may advance first in structured and semi-structured environments where tasks are economically valuable, variation is limited, and failure can be bounded: factories, warehouses, inspection, logistics, selected health or service contexts, perhaps some constrained domestic support. Broad domestic general-purpose robotics remains much less supported by the current evidence.

Robotics plays a crucial role in Stage 3 because it disciplines software-determinism. It reminds the project that “AI can do the task in a browser” and “AI can do the task in a room” are different claims. It also gives Stage 4 a vital technical condition band: embodied automation under physical constraints.

**Claim status:** empirical finding for robotics progress under bounded conditions; speculative projection for broader embodied acceleration, low-to-moderate confidence.  
**Main sources:** `S3-SRC-017`–`S3-SRC-024`; `S3-TALK-ROBOTICS`.  
**Must not be overclaimed:** robotics will not necessarily follow software timelines; demos do not prove general-purpose labour replacement.

---

## Chapter 5 — The Candidate Engine and the Wall of Proof

AI for science can look like the most dazzling part of the future. It may also be the easiest place to confuse possibility with proof.

The evidence base includes major examples: AlphaFold 3 for biomolecular interaction modelling, RFdiffusion for protein design, GNoME-style materials discovery, automated-laboratory work, data-centric critiques of AI drug discovery, FDA AI-enabled medical device listings, WHO guidance on large multimodal models for health, and reviews of generative models in engineering design. [Sources: `S3-SRC-025`–`S3-SRC-032`]

The specialist synthesis offered a useful frame: AI is becoming a candidate engine. It can generate possibilities, search large spaces, propose structures, suggest molecules, design proteins, screen materials, optimise shapes, organise literature, propose experiments and help automate parts of laboratory work. This can matter enormously. If the cost of producing plausible candidates falls, the front end of discovery changes.

But the candidate engine is not the same as validated impact.

In biology, a predicted structure or designed protein is not a therapy. In medicine, an AI-enabled device listing is not proof of patient benefit across populations. In materials science, a candidate compound is not a deployed product. In engineering, a generated design is not automatically manufacturable, safe, durable or desirable. In automated labs, a closed loop of prediction, synthesis and characterisation may be powerful in a narrow domain while still requiring correction, replication and human interpretation. [Sources: `S3-SRC-028`–`S3-SRC-032`]

This distinction is not pessimism. It is the central truth of the domain. AI may make possibility cheap while making validation the bottleneck. The bottleneck may even become more visible because AI generates more plausible candidates than existing validation systems can absorb. Laboratories, trials, toxicology, manufacturing, field testing, regulation, replication and institutional uptake may become the scarce resources.

This matters for technical futures because the social effect of AI-for-science depends on where acceleration occurs. If AI speeds up only literature search or candidate generation, the world changes differently than if it reduces full R&D cycle time, improves clinical outcomes, or shortens manufacturing translation. The difference between a promising molecule and a safe medicine can be years, capital, regulation, patient heterogeneity and failure.

The evidence is strong enough to say AI is materially useful in selected scientific domains. It is not strong enough to say AI has solved science, medicine, drug discovery, engineering or climate technology. It supports a technical condition band of discovery acceleration with validation bottlenecks.

The signposts are unusually important here. Stage 4 should watch for AI-designed therapies reaching Phase II/III with positive evidence, automated-lab results reproducing independently, AI-generated materials surviving manufacturing tests, and prospective evidence that medical AI improves patient outcomes rather than only benchmark scores or device counts.

**Claim status:** empirical finding for selected AI-for-science utility; speculative projection for broader discovery acceleration; moderate confidence with major validation cautions.  
**Main sources:** `S3-SRC-025`–`S3-SRC-032`; `S3-TALK-SCIENCE`.  
**Must not be overclaimed:** generated candidates are not validated scientific, clinical or industrial outcomes.

---

## Chapter 6 — The Cloud Has a Body

AI often appears weightless. A prompt goes in. An answer appears. The interface is clean enough to hide the machinery.

But the cloud has a body.

That body is made of chips, high-bandwidth memory, networking, data centres, cooling systems, land, water, electricity, grid interconnections, capital, supply chains, export controls, procurement rules, engineering labour and geopolitical strategy. Infrastructure is not a footnote to AI futures. It is one of their determining conditions. [Sources: `S3-SRC-033`–`S3-SRC-036`]

The infrastructure specialist’s point changes the interpretation of every previous chapter. Inference-time compute may improve reasoning, but it costs money and energy. Long-context agent loops may be useful, but they create latency and infrastructure demand. Robotics fleets require hardware, maintenance and local deployment. AI-for-science requires compute, data, instruments and laboratories. Open models require distribution, hardware and governance. Edge AI requires devices capable of running useful models locally.

Energy and data-centre sources show that AI is becoming visible in electricity planning and infrastructure debates. [Sources: `S3-SRC-033`, `S3-SRC-034`] AI supercomputer trend work points to concentration in high-capital organisations and regions. [Source: `S3-SRC-035`] Algorithmic efficiency and falling inference costs can broaden access, but they do not make infrastructure irrelevant. If costs fall, demand may rebound because more uses become economically possible. [Source: `S3-SRC-036`]

This creates two futures that may happen at once. Frontier AI may become more centralised, because the largest systems require huge capital, specialised chips, power contracts and data-centre buildouts. At the same time, open-weight models, edge AI and sovereign AI may decentralise some capability into local devices, national systems, institutional stacks and smaller providers. [Sources: `S3-SRC-046`, `S3-SRC-047`]

Neither side is simply good or bad. Centralised frontier AI may allow stronger monitoring, coordinated safety practices and high performance, but it may also concentrate power and access. Open and edge AI may improve resilience, local control, privacy and innovation, but it may also complicate monitoring, misuse control, standardisation and accountability. Sovereign AI may support local languages and strategic autonomy while fragmenting technical ecosystems and governance norms.

The infrastructure chapter therefore prevents two opposite errors. The first is thinking that energy or chips will simply stop AI. The second is thinking that software efficiency will make the physical substrate disappear. Both are too simple. Infrastructure is a moving constraint: sometimes a bottleneck, sometimes an accelerator, sometimes a source of inequality, sometimes a source of geopolitical divergence.

For Stage 4, this passes forward two major condition bands: infrastructure-constrained frontier AI and open/edge/sovereign divergence. Any plausible future world will need to ask not only what AI can do, but where capability lives, who can afford it, who controls it, and how visible it is to governance.

**Claim status:** empirical finding for infrastructure as first-order condition; speculative projection for open/edge/sovereign divergence; moderate confidence.  
**Main sources:** `S3-SRC-033`–`S3-SRC-036`, `S3-SRC-046`, `S3-SRC-047`; `S3-TALK-INFRA`.  
**Must not be overclaimed:** compute growth does not guarantee AGI; energy constraints are neither fatal nor irrelevant; open AI is neither simply democratic nor simply dangerous.

---

## Chapter 7 — Trust Becomes More Expensive

A technical futures report can be tempted to end with capability: better models, better agents, better robots, better science. But the safety specialist forced a different ending. AI enters society not as raw intelligence, but as permissions, interfaces, media, companions, devices, standards, laws, audits and attack surfaces.

The central movement is from AI as output generator to AI as environmental condition. A chatbot gives an answer. A deployed AI system may act on a device, operate an account, impersonate a person, generate a synthetic image, assist cyber reconnaissance, answer a biological query, classify a user, keep a lonely person company, monitor a workplace, or satisfy a compliance checklist. The risk is not only that AI becomes “smarter.” It is that AI becomes ambient: present in the background conditions of trust, identity, intimacy, security and governance. [Sources: `S3-SRC-037`–`S3-SRC-047`]

Governance is already becoming more concrete. NIST’s Generative AI Profile offers a practical risk taxonomy, and the EU AI Act creates a risk-based legal framework with obligations around general-purpose and high-risk systems. [Sources: `S3-SRC-037`, `S3-SRC-038`] But governance documents are not proof of safety. They create categories, duties and pressure. Actual safety depends on evaluation, monitoring, enforcement, incentives, institutional capacity and real deployment behaviour.

Misuse evidence must also be held carefully. Cyber misuse sources support productivity and scaling uplift more strongly than clear, widespread novel autonomous cyber capability. Biosecurity risk depends on operational uplift, not merely whether a model can produce concerning text. Tacit knowledge, materials, procurement, lab access, concealment and intent still matter. [Sources: `S3-SRC-039`, `S3-SRC-040`]

Synthetic media is another domain where the disciplined claim is subtler than the theatrical one. Deepfakes and synthetic content can matter in politics, scams, harassment and reputation. Detection remains fragile in real-world conditions. But the evidence does not support a universal claim that deepfakes end democracy or make truth impossible. The better claim is that synthetic media raises verification costs and creates context-specific trust vulnerabilities. Trust may not be destroyed; it may become more expensive. [Sources: `S3-SRC-041`, `S3-SRC-042`]

AI companions and social agents deserve separate treatment because they do not need frontier-level reasoning to matter. Repeated relational interaction is different from a one-off assistant query. A companion system may be always available, emotionally responsive, memory-like, personalised and disclosure-inviting. That creates possible benefits and distinctive risks: dependency, crisis interaction, privacy leakage, manipulation, attachment, sexualisation, developmental vulnerability and the difficulty of designing systems that are responsive without pretending to be human in exploitative ways. [Sources: `S3-SRC-043`, `S3-SRC-044`]

Neurotechnology belongs only as a watchlist item. Neural data and mental privacy are important, and medical or accessibility applications may matter. The authorised evidence does not support claims of near-term population-scale mind reading or cognitive control. [Source: `S3-SRC-045`]

The safety chapter therefore changes the whole report. It shows that technical futures are also trust futures. Agentic systems raise the stakes of permissioning. GUI agents raise the stakes of state-changing actions. Open and edge AI raise the stakes of decentralised governance. Synthetic media raises the stakes of provenance. Companions raise the stakes of relational safety. Laws and standards raise the stakes of enforcement.

The right conclusion is not panic. It is precision. Safety is about action, environment and relationship, not only bad outputs. AI may not produce one dramatic rupture; it may change the weather.

**Claim status:** empirical finding for active governance, misuse, synthetic-media and companion concerns; speculative projection for ambient trust-pressure environment; low-to-moderate confidence for long-run effects.  
**Main sources:** `S3-SRC-037`–`S3-SRC-047`; `S3-TALK-SAFETY`.  
**Must not be overclaimed:** governance is not proof of control; cyber/bio risk is not demonstrated catastrophe; deepfakes do not automatically collapse truth; companions are not inherently harmful; neurotechnology is not near-term mass mind reading.

---

## Cross-Domain Synthesis — The Price of Reality-Checking

The specialist talks converged around one recurring question: how does AI output become reliable action?

The answer changes by domain.

In foundation models, reliability depends on system design: context, tools, inference-time compute, memory-like retrieval, evaluation and supervision. In coding, reliability depends on tests, compilers, benchmarks, review and deployment evidence. In generative software, reliability depends on permissions, audit trails, sandboxes, platform stability and reversibility. In robotics, reliability depends on bodies, sensors, actuators, safety standards and real environments. In science, reliability depends on experiments, trials, replication, manufacturing and regulation. In infrastructure, reliability depends on compute, energy, chips, data centres, supply chains and cost. In safety, reliability depends on governance, monitoring, provenance, incident reporting, misuse controls and trust.

This is why a single high-AI/low-AI axis is too blunt. AI could accelerate dramatically in software while moving slowly in robotics. It could produce abundant scientific candidates while clinical validation remains slow. It could become cheap at the edge while frontier models remain concentrated. It could become safer in regulated enterprise systems while more dangerous in decentralised misuse contexts. It could improve productivity without delivering broad autonomy. It could become ambient and socially consequential without becoming superintelligent.

The strongest Stage 3 synthesis is therefore plural. It identifies interacting condition bands rather than a forecast.

The red team’s caution remains important: the price of reality-checking is not the only causal factor. Markets, power, institutions, culture, regulation, labour, trust, capital and geopolitical strategy can all accelerate or block deployment. But reality-checking is the technical mechanism that appeared most consistently across the specialist evidence. It is the hinge between capability and consequence.

---

## Technical Condition Bands for Stage 4

These bands are not lived-world scenarios. They are technical conditions Stage 4 may combine with Stage 1R and Stage 2 when it later models human life inside plausible futures.

| Band ID | Technical condition band | Claim type | Confidence | Stage 4 use | Key cautions |
|---|---|---|---|---|---|
| TFB-01 | Feedback-rich software acceleration | Speculative Projection | Moderate | Model futures where coding, software maintenance, testable digital work and AI R&D tooling accelerate. | Do not infer full software-engineer replacement or reliable broad autonomy. |
| TFB-02 | Agentic tool-use expansion with reliability ceilings | Speculative Projection | Low to moderate | Model futures where AI acts through tools and workflows but remains bounded by permissions, auditability, liability and error recovery. | Do not treat tool use as safe autonomy. |
| TFB-03 | Generative interface transition | Speculative Projection | Low to moderate | Model futures where some interaction shifts from fixed interfaces to intent-driven, generated or agent-operated workflows. | Do not claim software complexity disappears. |
| TFB-04 | Embodied automation under physical constraints | Speculative Projection | Low to moderate | Model futures where robotics expands in structured/semi-structured environments but remains constrained in open physical settings. | Do not transfer software timelines to robotics. |
| TFB-05 | Discovery acceleration with validation bottlenecks | Speculative Projection | Moderate | Model futures where AI accelerates candidate generation in science, medicine and engineering while validation remains scarce. | Do not treat candidates as validated discoveries. |
| TFB-06 | Infrastructure-constrained frontier AI | Speculative Projection | Moderate | Model futures where compute, energy, chips, data centres, capital, water, supply chains or geopolitics shape deployment. | Do not treat compute as either destiny or fatal barrier. |
| TFB-07 | Open, edge and sovereign AI divergence | Speculative Projection | Moderate | Model futures where capability diffuses into open-weight models, local devices and national/institutional stacks. | Pair access gains with governance and misuse trade-offs. |
| TFB-08 | Governance-thickened AI deployment | Speculative Projection | Moderate | Model futures where audits, risk classification, procurement rules, provenance and law shape deployment. | Governance frameworks do not prove safety. |
| TFB-09 | Ambient trust-pressure environment | Speculative Projection | Low to moderate | Model futures where synthetic media, companions, impersonation, surveillance and automated judgement raise trust costs. | Avoid truth-collapse or companion-harm universal claims. |
| TFB-10 | Self-improvement watch band | Uncertainty / Speculative Projection | Open | Monitor whether AI-assisted AI R&D and coding loops become genuinely compounding. | Recursive self-improvement is not established. |

---

## Signpost Register

Stage 3 should be reopened or Stage 4 should adjust its assumptions if strong evidence appears in any of these areas:

- Independent long-task evaluations show reliable day-scale or week-scale agent performance on novel, post-training-cutoff tasks. [Sources: `S3-SRC-004`, `S3-SRC-005`]
- Production coding-agent deployments show low defect rates, manageable review burden, security performance and maintenance outcomes across real repositories. [Sources: `S3-SRC-011`, `S3-SRC-012`]
- AI systems produce independently verified improvements to AI training, inference, compilers, kernels, evaluation suites or research infrastructure. [Sources: `S3-SRC-013`, `S3-SRC-014`]
- Generated software or GUI-agent workflows become routinely verified, sandboxed, audited and rolled back in enterprise settings. [Sources: `S3-SRC-015`, `S3-SRC-016`]
- Robotics deployments report autonomy rate, intervention rate, uptime, safety incidents and total cost of ownership across real sites. [Sources: `S3-SRC-017`–`S3-SRC-024`]
- AI-designed drugs, proteins, materials or engineering systems survive independent replication, clinical trials, manufacturing or field deployment. [Sources: `S3-SRC-025`–`S3-SRC-032`]
- Data-centre power, chips, memory, water, grid connections or export controls materially delay or redirect AI deployment. [Sources: `S3-SRC-033`–`S3-SRC-036`]
- Inference costs fall sharply enough to enable widespread reasoning, multimodal or agentic use, or rebound demand overwhelms efficiency gains. [Source: `S3-SRC-036`]
- Open-weight, edge or sovereign AI ecosystems materially change access, safety, monitoring or geopolitical control. [Sources: `S3-SRC-046`, `S3-SRC-047`]
- Cyber or bio evidence shows operational uplift beyond productivity and friction reduction. [Sources: `S3-SRC-039`, `S3-SRC-040`]
- Synthetic-media provenance systems become widely adopted, fail visibly, or are bypassed at scale. [Sources: `S3-SRC-041`, `S3-SRC-042`]
- Companion-system incidents, regulation or longitudinal evidence materially changes the assessment of relational AI risk. [Sources: `S3-SRC-043`, `S3-SRC-044`]
- Neurotechnology evidence moves beyond ethics/watchlist status into materially deployed neural-data or interface systems with broad social relevance. [Source: `S3-SRC-045`]

---

## What This Stage Does Not Establish

This stage does not establish:

- AGI timelines;
- recursive self-improvement;
- exponential intelligence growth;
- that coding agents will replace software engineers;
- that agentic systems are reliable autonomous workers;
- that instant UI or app generation eliminates software complexity;
- that robotics will follow software timelines;
- that humanoid demos prove broad labour replacement;
- that AI has solved science, medicine, engineering or climate technology;
- that FDA device listings prove clinical benefit;
- that governance frameworks prove safe deployment;
- that deepfakes collapse shared reality;
- that AI companions are inherently harmful or inherently beneficial;
- that open or edge AI is simply democratic, safe, dangerous or uncontrollable;
- that compute and energy constraints are either fatal or irrelevant;
- Stage 4 lived-world scenarios;
- curriculum design, capabilities, subjects, pedagogy, assessment or learner AI-use policy.

---

## Draft Pass-Forward Candidates

The following survived specialist discussion and review and are authorised for filtered inclusion in `PASS_FORWARD.md`:

1. AI futures should be analysed as model-plus-system futures, not model-only trajectories. [Sources: `S3-SRC-001`–`S3-SRC-010`; Ledger: `S3-EDITORIAL-001`]
2. AI appears likely to accelerate fastest where outputs can be cheaply tested, scored, corrected or rolled back; this is strongest in software-like domains and weaker where validation is slow or expensive. [Sources: `S3-SRC-004`–`S3-SRC-014`, `S3-SRC-025`–`S3-SRC-032`; Ledger: `S3-DISCUSSION-MASTER`]
3. Coding agents and AI R&D tools may accelerate bounded, evaluable work, but recursive self-improvement remains unresolved. [Sources: `S3-SRC-004`–`S3-SRC-014`; Ledger: `S3-UNC-001`, `S3-REDTEAM-001`]
4. Generative interfaces and GUI agents may change some software interaction, but verification, permissioning, security and accountability remain central constraints. [Sources: `S3-SRC-011`, `S3-SRC-012`, `S3-SRC-015`, `S3-SRC-016`]
5. Robotics progress is real but physically bottlenecked, especially outside structured settings. [Sources: `S3-SRC-017`–`S3-SRC-024`]
6. AI for science may accelerate search and candidate generation in selected domains, but validation remains the decisive constraint. [Sources: `S3-SRC-025`–`S3-SRC-032`]
7. Infrastructure is a first-order AI future condition. [Sources: `S3-SRC-033`–`S3-SRC-036`, `S3-SRC-046`, `S3-SRC-047`]
8. Open, edge and sovereign AI may broaden access while decentralising risk, governance and control. [Sources: `S3-SRC-046`, `S3-SRC-047`]
9. Governance, safety, misuse, synthetic media, companions and ambient AI are technical future conditions, not external side issues. [Sources: `S3-SRC-037`–`S3-SRC-047`]
10. Stage 4 should use technical condition bands rather than a single AI future forecast. [Ledger: `S3-EDITORIAL-001`]

---

## Conclusion

The most useful way to leave Stage 3 is not with a prediction, but with a discipline.

Do not ask only how powerful AI becomes. Ask where that power can be tested. Ask where it can act. Ask who grants permission. Ask what it costs. Ask what breaks when it fails. Ask whether the world answers cheaply or expensively. Ask who owns the infrastructure. Ask who can see the system. Ask who bears responsibility. Ask how trust is maintained when generation becomes effortless.

Stage 3 passes with cautions because the evidence supports a strong technical futures map, but not a single future. AI may accelerate dramatically where reality can be made into feedback. It may slow where reality is physical, regulated, expensive, adversarial, socially meaningful or hard to verify. It may centralise and decentralise at once. It may become more capable and harder to govern at the same time. It may transform some domains by making possibilities cheap while leaving proof painfully expensive.

Stage 4 can now take this technical map and, using Stage 1R and Stage 2, model what human life might look like inside different combinations of these conditions. Stage 3 itself stops here.
