# CVs, portfolios and IT interviews when both sides use AI

[Back to the guide](README.md)

*Sources checked 23 November 2026. Employer examples describe published processes and policies. Confirm the rules for your specific stage.*

A usable application has three properties. The form captures the right facts, a recruiter can quickly see why the candidate fits, and a technical interviewer can probe the same evidence in depth. AI can help edit and rehearse that evidence. The underlying decisions, results and limitations still have to come from the candidate.

## What employers have reported

In Apec’s May 2026 study, **8% of employers in the sample said they used AI to recruit managerial and professional staff in 2025**, up from 4% reported for 2024. For mid-sized and large businesses, 13% reported use and 27% reported use or plans for use. The leading use was writing job adverts. Apec surveyed 1,150 private-sector employers with at least ten employees that had hired at least one person in that employment category in 2025. These are employer-level, self-reported figures across occupations. They give no percentage of IT applications ranked or rejected by AI. [Apec, 2026 recruitment practices for managerial and professional staff](https://corporate.apec.fr/home/nos-etudes/toutes-nos-etudes/pratiques-de-recrutement-de-cadres-2026.html)

On the candidate side, Apec found that **31% of managerial and professional staff who had taken a job-search step in the previous three months** had tried generative AI for the search in March 2026, up from 15% in December 2024. Among that group of AI users, 77% had used it for a cover letter and 70% for a CV. The question counted activity such as updating a profile or reading vacancies, so the denominator extends beyond people who submitted applications. The survey measures usage, with no estimate of its effect on interview chances. [Apec, Managerial and Professional Staff and AI, 2026, p. 28](https://corporate.apec.fr/files/live/sites/corporate/files/Nos%20etudes/PDF/Les%20cadres%20et%20l%27IA%202026.pdf#page=28)

In Apec’s employer survey on 2025 recruitment, 71% of employers reported using a pre-screening phone interview and 41% reported formal evaluation of behavioural skills through tests or role-play. Prepare the recruiter conversation alongside the technical exercise. Speak clearly about your scope, results, next role, availability and working arrangements. [Apec, 2026 recruitment practices for managerial and professional staff](https://corporate.apec.fr/home/nos-etudes/toutes-nos-etudes/pratiques-de-recrutement-de-cadres-2026.html)

## Make the CV readable and easy to verify

An applicant tracking system (ATS) can collect applications, store documents and manage the workflow. Resume parsing extracts fields such as name, contact details and work history. Other configured features may search, filter, suggest matches or help with assessment. For instance, Lever documents field extraction, Greenhouse documents partial and failed parses, and Thales describes an AI-enabled matching tool that supports recruiter review in its talent community. A short rejection turnaround gives too little information to identify the mechanism. [Lever resume parsing](https://help.lever.co/s/article/Understanding-Resume-Parsing), [Greenhouse parse troubleshooting](https://support.greenhouse.io/hc/en-us/articles/200989175-Unsuccessful-resume-parse), [Thales recruitment privacy notice](https://careers.thalesgroup.com/global/en/privacynotice)

1. Maintain an evidence bank with dates, scope, your contribution, stack, results, how results were measured, and what you may discuss publicly. Reuse it to prepare a base CV for each role family. Start with the CV language requested by the employer. If the posting leaves it open and the team recruits in English, send your English CV. If you are unsure, ask what the first reviewer accepts. List actual working proficiency, for example *English (fluent) · French (A2, self-assessed)*, if those descriptions are accurate. Translate an unfamiliar job title or qualification in plain English and preserve its level and scope.
2. Use the posting or portal’s requested file format. Where it accepts both, keep an editable Word file and a selectable-text PDF ready. Prefer one column and ordinary headings such as *Work Experience*, *Skills* and *Education*. Put contact details in the body. Use text for dates, links and essential skills, and use simple formatting in place of tables, icons or graphics. [Apec on CV imports](https://www.apec.fr/faq.html?question=je-n-arrive-pas-a-importer-mon-cv-que-faire), [Greenhouse parse troubleshooting](https://support.greenhouse.io/hc/en-us/articles/200989175-Unsuccessful-resume-parse)
3. Copy the exported PDF’s text into a plain-text editor. Check reading order, titles, dates, bullets, accents, and contact details. Correct imported fields in the portal before submitting. This checks basic extractability. The receiving employer’s parser and workflow can still behave differently. [Lever resume parsing](https://help.lever.co/s/article/Understanding-Resume-Parsing)
4. Pull three to five important requirements from the posting. Match them to real examples and move the strongest evidence up. Include terms from the posting when they accurately describe your work, such as *incident management* or *Terraform*. If experience comes from a side project or lab, say so. Leave unsupported keywords and unverifiable impact figures out of the application. [Apec on tailoring a CV](https://www.apec.fr/candidat/etre-accompagne-dans-votre-recherche-demploi/1er-emploi/fiche-conseils/adapter-son-cv-par-rapport-a-une-offre-demploi-pour-le-rendre-plus-attractif.html)
5. Lead with action, system or users affected, scale if shareable, and the verified outcome. For an operations role, replace the variables in this example with facts from your own records. *Automated [process] across [systems or teams], reducing [metric] from [A] to [B] over [period], as measured by [source].* If you lack an approved metric, name the concrete change and verification, such as adding a documented recovery procedure and running it in staging.
6. Write a short cover note around one team-specific reason and one or two pieces of evidence. If the form asks why this team, tie a public fact about its work to a credible problem you want to solve. Read it aloud and keep wording you would use in a conversation.

A generic AI “ATS score” can serve as a self-review checklist. It has no access to the employer’s hidden settings or reviewer criteria. Pay attention to observable faults such as a scrambled work history or an important requirement with no supporting evidence. Track recruiter screens by role family over several weeks before changing your CV strategy.

## Use AI to edit and rehearse

Pick a task with a clear input and a result you can independently check. Provide a public vacancy and an anonymised set of verified work examples. Remove identifiers you do not need for the task and keep former-employer systems, source code, tickets, operational notes, client details, credentials and private assessment material outside external tools. Review the provider’s data terms before using personal material. Save your final copy and a record of the exact role and version sent.

| Stage | Useful AI task | What to check yourself |
| --- | --- | --- |
| Vacancy review | Extract stated responsibilities and distinguish explicit requirements, preferences and unknowns. | Reopen the employer’s listing and verify location, employment country, attendance, language and opening status. |
| CV tailoring | Map each requirement to a verified evidence item and suggest changes in order or phrasing. | Verify every tool, metric, title, date and ownership claim against your records. |
| Language and copy editing | Suggest natural phrasing, translation or shorter versions. | Keep exact qualifications, official names, technical meaning and your own voice. |
| Interview prep | Ask questions one at a time and probe missing details or trade-offs. | Answer out loud before reading feedback and confirm disputed facts independently. |
| Technical practice | Suggest test cases, counterexamples or a simplified practice environment from public material. | Run the checks, inspect the results and explain what the exercise left untested. |
| Follow-up | Condense your actual notes into a short draft you can send yourself. | Check names, promises, deadlines and what the interviewer said. |

**Prompt for mapping a posting to your evidence**

> I’ll give you a public job posting and anonymised examples from my own work. Quote each explicit requirement. Match it to evidence I supplied or mark it “to confirm.” Identify what the employer requires, what it prefers, and what the posting leaves open. Suggest up to three changes to my CV. Keep my dates, responsibilities and results as supplied.

**Prompt for interview practice**

> Act as the technical hiring manager for this role. Ask one question at a time and wait for my answer. Follow up on my own contribution, the trade-off I made, how I verified the result, and what I would change. At the end, point out specific answers I could improve. Use the facts I gave you and leave the wording of my answers to me.

## Check the assessment rules for each stage

| Published example | What the candidate guidance says |
| --- | --- |
| L’Oréal | Its AI charter encourages preparation and says to disclose AI use on case studies or technical tests, show prompts and explain choices. It bars real-time AI assistance in interviews. [L’Oréal’s AI charter](https://careers.loreal.com/en/ai-charter) |
| Zscaler | Its candidate guide welcomes tools for preparation and says evaluations assess the candidate’s own unaided ability. [Zscaler candidate resources](https://www.zscaler.com/candidate-resource-hub) |
| Anthropic | It welcomes preparatory help, asks candidates to complete take-homes without Claude unless explicitly allowed, and says live interviews should be completed without AI assistance unless interviewers indicate otherwise. [Anthropic candidate guidance](https://www.anthropic.com/candidate-ai-guidance) |
| HackerRank | Its October 2026 release notes describe built-in coding agents and employer-configured AI model selection in some interviews. Read the session instructions to learn which built-in tools you can use. The presence of a feature in the platform gives no permission to use an external tool. [HackerRank October 2026 release notes](https://support.hackerrank.com/articles/9093711123-october-2026-release-notes) |

Read the invitation, assessment brief and linked policies. Ask before starting if allowed documentation, autocomplete, code generation, external services, copying exercise content, disclosure or accessibility support are unclear. Proceed without AI while permission is unclear, including real-time answer overlays or meeting assistants. Where use is authorised, be ready to describe your own contribution and the checks you ran. If instructions differ, ask the recruiter to confirm which rule applies to that stage.

> Hi, thanks for sending the instructions. Which resources can I use for this stage, such as documentation, autocomplete, or a built-in or external AI assistant? If AI is allowed, would you like a prompt log or a short note explaining how I used it and what I checked? I’m also happy to complete the exercise without AI.

When allowed and accurate, say *I used [approved tool] to suggest [test cases or approaches]. I made [decision], verified it with [check], and rejected [suggestion] because [reason].* Ask before providing transcript excerpts if the employer expects a specific format or the material includes sensitive information.

## Build interview evidence for the work you want

Prepare a 60-second introduction and five stories in the confirmed interview language. If stages use different languages, ask what to expect in each and practise in the languages you can use comfortably. Useful story types include delivery, debugging or an incident, a trade-off, a collaboration challenge, and learning from a setback. Practise a two-minute first answer and a deeper technical follow-up. Explain the problem, your responsibility, alternatives considered, criteria you used, and how you know the outcome. Distinguish personal decisions from team results. Provide an honest account of an unsuccessful hypothesis or an unresolved limitation.

Alan’s published guide is one French tech employer example. Its software engineering process can include feature design and discussion of a past project. The company also describes role-based case or situational questions. Use the recruiter’s current instructions to prepare for the required format. [Alan hiring process](https://alan.com/en/careers/a/hiring-process-step-by-step)

| Role family | Practice task | Questions to rehearse |
| --- | --- | --- |
| Support, infrastructure or systems | Triage a fictional service degradation using sample alerts, tickets and a change timeline. | Which check comes first? What would justify rollback or escalation? How do you update affected users? |
| DevOps, platform or SRE | Review a small deployment design, add failure checks and propose a recovery path. | Who owns the service? How do you confirm reliability and recover from a failed deployment? What signals would you page on? |
| Software engineering | Add a bounded feature with tests to an unfamiliar small codebase. | Why this interface? What could regress? How would you deploy and observe the change? |
| Data engineering or analytics | Diagnose missing or duplicate records in a synthetic data pipeline. | What data quality test catches recurrence? How do you backfill safely and validate downstream results? |
| Applied AI, if relevant | Evaluate a small AI-assisted workflow on approved or synthetic inputs. | What’s the baseline? Which failures matter most? What happens when the model is slow, wrong or unavailable? |

Run one solo exercise and an AI-assisted rehearsal using public or synthetic material before a technical round. In the solo version, drive the diagnosis and explain as you go. In the AI-assisted version, state a small task and its constraints, inspect the patch, verify assumptions against the repository or documentation, and run checks yourself. Compare the **total time through verification**, quality of the result, and failure modes. During a real interview, follow the rules for that session.

Practise answering both *“How do you use AI in your work?”* and *“When do you decide to work without it?”* A grounded answer names a task, safe inputs, the tool’s limited contribution, a rejected suggestion or check, and the observed outcome. Distinguish personal experiments from employer-approved practice. Avoid extrapolating a local experiment into a universal speed claim. [Compare the underlying productivity studies](market.md#the-evidence-on-entry-level-hiring-and-software-productivity).

Ask the employer how AI is used on the actual team. Start with “Where do you allow AI in production work, and which tools and data can people use?” and “How do you check an AI-generated suggestion before shipping it?” Follow up on review responsibility, test or evaluation criteria, access to tools and how the team knows whether its workflow improves.

## Publish work a reviewer can inspect

Pick one or two relevant artifacts that take little time to understand. A portfolio can show structured troubleshooting, recovery, integration, maintainability, accessibility, quality or collaboration. Use code or infrastructure you can share, synthetic data, an authorised open-source contribution, or an anonymised case study. GitHub’s own portfolio guide recommends showcasing a small set of projects with a concise overview, a demo, setup instructions, and tests or examples. [GitHub portfolio guide](https://docs.github.com/en/account-and-profile/tutorials/using-your-github-profile-to-enhance-your-resume)

Give each project a short README or case-study page with these details.

- The user problem, your role, constraints and the project’s real status.
- One quick demonstration and instructions to run it with safe example data.
- A link to a specific change, test, design decision, runbook or issue that shows your involvement.
- A checkable result, its measurement conditions, and a known limitation.
- A short description of any material AI contribution, what you verified, and whom a reviewer should credit.

For a support or platform role, a small service with health checks, a staged recovery drill, and a clear incident write-up can show how you operate it. For applied AI, show a limited use case, an ordinary baseline, a small labelled test set, example failures, and a fallback. For AI-assisted engineering, show a small change you reviewed and verified. A conventional IT project can be strong evidence on its own.

Before sharing, open the link while signed out, run the documented happy path, and check that private material, client information and credentials are absent from screenshots, logs and repository history. Prepare to point directly at two artifacts and explain each in under a minute.

## Handle candidate data and screening in France

French Labour Code articles L1221-6, L1221-8 and L1221-9 tie requested information to professional abilities or the role, require advance information about recruitment methods, and require advance notice of devices that collect personal information. Assessment results are confidential. CNIL’s recruitment guide explains what a recruiter should tell candidates about processing, how candidates can exercise data rights, and the safeguards that apply to software for sorting and evaluating applications. [French Labour Code, recruitment section](https://www.legifrance.gouv.fr/codes/section_lc/LEGITEXT000006072050/LEGISCTA000006189415/2025-07-02), [CNIL recruitment guide, sheets 7, 8 and 13](https://www.cnil.fr/fr/le-guide-du-recrutement)

GDPR Article 22 generally restricts decisions based exclusively on automated processing that have legal or similarly significant effects, subject to exceptions and safeguards. The question is whether automated processing alone produced the decision. A process with meaningful human review can also include automated administrative assistance or recommendations. When a process appears to rely on solely automated decision-making, read the privacy notice and use the recruiter’s or data protection contact. Ask how the tool affects the decision and, where applicable, how to request human intervention or contest a decision. Keep the posting reference and relevant correspondence. [GDPR, Articles 13–15 and 22](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A32016R0679), [CNIL recruitment guide](https://www.cnil.fr/fr/le-guide-du-recrutement)

Under the amended EU AI Act timetable, the requirements of Chapter III, Sections 1–3, for systems classified as high-risk under Annex III, including qualifying employment and recruitment systems, are scheduled to apply from **2 December 2027**, with the Article 6(5) exception specified in Article 113. The existing data protection and French recruitment rules above apply independently of that future date. [European Commission AI Act timetable](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai), [Regulation (EU) 2026/1744 amending the AI Act](https://eur-lex.europa.eu/eli/reg/2026/1744/oj/eng/pdf)

For a recorded or automated interview, check which data are captured, the purpose, retention and recipient, and who makes the hiring decision. Ask the recruiter about an alternative format if you need one. [CNIL recruitment guide](https://www.cnil.fr/fr/le-guide-du-recrutement)

If the contact or test itself seems suspicious, use the [recruiter and assignment verification steps](fieldwork.md#verify-the-recruiter-and-the-assignment).
