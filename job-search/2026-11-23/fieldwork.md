# Choosing your next move and checking it with peers

[Back to the guide](README.md)

## Decide how close to AI you want to work

Pick a primary role family based on the problems you have solved or can demonstrate. Add one adjacent family that uses the same evidence. Use the search examples in [search channels](search.md) to collect a small sample of real roles. Scope can vary even among roles with identical titles.

| Target | Problems to recognize in job descriptions | Evidence to lead with | One way to show how you work with AI |
| --- | --- | --- | --- |
| Software engineer | Maintain an API, modernize a service, ship changes safely, own a feature after launch | A real change, important tests, release strategy and a case where you revised the design | Use an assistant to suggest edge cases for a bounded change. Explain two suggestions you verified and one you rejected. |
| SRE, platform or cloud engineer | Respond to incidents, make deployments safer, improve developer workflows, operate services | A failure investigation, deployment or migration evidence, a runbook, and service telemetry | Use a synthetic alert to evaluate whether a draft incident summary cites the right signals and preserves uncertainty. |
| IT operations or support | Resolve escalations, deploy or maintain systems, automate repetitive work, improve the handover | A troubleshooting tree, before/after workload, diagnostic script and escalation notes | Draft a knowledge-base article from invented tickets. Have a peer reproduce the diagnosis and correct the draft. |
| Data engineer | Reliable ingestion, data quality, orchestration, access and lineage | Data contracts, checks, handling retries/backfills, and decisions on schema evolution | Use synthetic records to test a data-quality assistant against edge cases such as duplicates, invalid dates, and missing fields. |
| Security engineer | Improve detection coverage, harden services, review change risk, investigate alerts | A defensive control, validation procedure, documented limitations and a decision on escalation | Compare summaries of synthetic alerts to their underlying evidence. Assess missed severity and preserve analyst review. |
| Tech lead or engineering manager | Set priorities, coach, manage change and facilitate delivery | A trade-off you led, a team improvement with evidence and an example of developing others | Explain how you would trial an assistant with a small team and measure lead time, review effort and defects before wider adoption. |

Search across three layers. **AI-assisted engineering** means using assistants in ordinary work with testing, access controls and review. **AI infrastructure** involves serving or operating model workloads, with concerns such as capacity, queueing, observability, latency and spend. **Applied AI engineering** adds product evaluation, handling low-confidence results, and decisions about acceptable quality on real tasks. Some teams combine multiple layers. General Kubernetes, distributed systems or data experience can support the transition. Add evidence for the layer you want to work on.

### Learn against job evidence

1. Collect 10–15 distinct postings for your two role families from sources you can revisit. Mark each competency as required, preferred, or inferred. Record the exact line that moved it into a category.
2. Look for recurring requirements across *different employers*. Look separately at adjacent skills you could demonstrate through past work and gaps that need practice.
3. Pick one gap you can address in a weekend-scale exercise or a few focused sessions. Keep the artifact runnable and prepare a three-minute explanation. Let conversations and interview feedback inform whether to continue.
4. State the setting precisely. Mark a personal exercise as a lab. State what real-world constraint it approximates, what remains untested and what you would change in production.

For an infrastructure-focused AI project, keep the scope to serving one small model or using a local mock workload when hardware is unavailable. Capture normal and overloaded behavior, define a user-visible measure, and document what happens when capacity or concurrency changes. A short report could explain end-to-end latency versus time to first token, request errors, queue depth, and a decision about admission control or degraded service. Label mock measurements as synthetic. [Google SRE monitoring guidance](https://sre.google/sre-book/monitoring-distributed-systems/) · [vLLM production metrics](https://docs.vllm.ai/en/stable/usage/metrics/)

For a productivity example, pick a specific task such as adding a regression test. Try a comparable task with and without AI help. Track time including validation, failed tests, and changes you needed to make after review. Describe the setup and give the actual observations as experience from a small trial. [What developer productivity experiments measured](market.md#the-evidence-on-entry-level-hiring-and-software-productivity)

### Adjust for career stage

- **Early career or changing fields.** Look for work-study apprenticeships, graduate roles, entry-level titles, support and operations work, and internal teams with defined onboarding where appropriate. Pair a demo with something another person reviewed. In an interview, walk through learning a system, isolating a fault, asking for help and verifying the fix. Confirm supervision and expectations for the first month.
- **Experienced individual contributor.** Show the path from a problem to a measured result, with examples of changes under pressure, collaborative decisions and handover. For an adjacent role, lead with problems you already own, name the actual gap, and bring evidence of how you started closing it.
- **Staff, lead or manager.** Show what changed across teams, the decisions you influenced, and the measures you used. Clarify how much of the advertised job is delivery, system design, people management and escalation. For an AI adoption role, discuss how you would manage data access, review load, reliability and what would cause you to pause the rollout.

## Run a 30-minute onCallTogether session

The session can be for company, an application second opinion, a mock interview or a shared search block. Begin by asking what each person wants from the call. Use one short artifact they choose to share, such as an anonymized vacancy, a public portfolio page, a few CV bullets or an interview question.

| Time | Activity |
| --- | --- |
| 0–5 minutes | Check in. Agree on the kind of help, whether to take notes and what may be shared later. |
| 5–12 minutes | The first person brings one problem. Read a vacancy, test a CV bullet, or listen to a 90-second incident story. Ask what the person wants a recruiter or engineer to understand. |
| 12–19 minutes | Switch roles. Ask one specific follow-up and offer one concrete observation. |
| 19–25 minutes | Work quietly on one action each. Clarify a location question, rewrite a bullet, or find the employer’s official posting. |
| 25–30 minutes | Name the next step and when to check in. Ask first before introducing someone, forwarding their CV or sharing their notes. |

Feedback that helps sounds like *“I understood the outage, but I couldn’t tell which decision you owned. What would you say in one sentence?”* A peer can also point out assumptions about the posting, time zone, stack or hiring process. Offer to look up the source together. Treat recruiter conversations and shared materials as private by default, and get everyone’s agreement before recording or using an AI note-taker.

Large randomized experiments on LinkedIn found a causal link between some newly formed weak ties and job mobility on that platform. Participants should feel free to reconnect with a former teammate, conference acquaintance or contributor for a real question or conversation. The study concerned connections formed through recommendations on a specific network and gives no estimate of an individual’s chances of getting a referral. [Rajkumar et al., *Science*](https://doi.org/10.1126/science.abl4476)

## Verify the recruiter and the assignment

- **Look for an independent path to the employer.** Open its careers site yourself, find the requisition or ask an official contact to confirm it, and check the recruiting firm’s identity when it is an agency assignment. Even a real company name or establishment registration number can be copied. If an agency is unable to name the client yet, ask it to confirm the recruiter’s identity, what it can share about the role, and when it will request consent to send your CV. [French government company directory](https://annuaire-entreprises.data.gouv.fr/) · [Cybermalveillance.gouv.fr on false job ads](https://www.cybermalveillance.gouv.fr/tous-nos-contenus/fiches-reflexes/fausses-offres-demploi-creees-par-des-fraudeurs)
- **Verify test delivery before opening or running anything.** Ask the company to confirm unfamiliar links, packages or tooling through its established channel. A request to install an unsigned app, enable macros, grant remote desktop access, enter credentials or run a downloaded project with personal or employer credentials available deserves independent verification. Ask for a browser-based or read-only exercise if the delivery channel or software cannot be verified.
- **Keep payment and sensitive records out of early contact.** An upfront training fee, payment to release earnings, equipment cheque, request to install financial software or demand for early bank or ID documents warrants a pause. Verify the legal employer and the requested step independently before sharing sensitive information. [Cybermalveillance.gouv.fr on unsolicited job offers](https://www.cybermalveillance.gouv.fr/tous-nos-contenus/fiches-reflexes/propositions-d-emploi-non-sollicitees)
- **Respond when something went wrong.** Stop contact and retain messages, sender details, URLs and payment records without re-opening suspicious files. If money or bank details are involved, contact your bank promptly. If an account or work device may be affected, contact the relevant security team. French official resources explain reporting and complaint options. [Cybermalveillance.gouv.fr](https://www.cybermalveillance.gouv.fr/tous-nos-contenus/fiches-reflexes/fausses-offres-demploi-creees-par-des-fraudeurs) · [Justice.fr on fraud and complaints](https://www.justice.fr/je-suis-victime/atteintes-biens/arnaque-fraude-escroquerie)

## Maintain the guide

When proposing an update, state the geography, population, time period and metric for each statistic. Link to the original data or study. When reporting a hiring-policy change, include the role, the date checked and the employer’s exact terminology. Share examples with personal details removed. Confirmation from the employer is useful for disputed or incomplete postings. [Market refresh checklist](market.md#refresh-this-picture-while-searching)
