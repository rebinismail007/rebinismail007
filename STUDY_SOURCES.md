# Study source review and reconstruction scope

Reviewed on 21 October 2026. Twenty supplied PDFs were checked for requirements, data models, commands, code excerpts and relevant screenshots. Complete original project directories were unavailable. The repositories were implemented and committed now, with current dates.

## What each source contributed

| Supplied document | Material found | Public portfolio use |
| --- | --- | --- |
| Machinelearning Mandatory assignment | Startup-regression brief; a pandas CSV-loading fragment on page 13; many incomplete code sections | `python-startup-regression`: new pipeline, synthetic data, validation, evaluation and plots |
| BASIC NETWORK CONCEPTS | SQL query and injection examples | `csharp-green-home`: local defensive parameterization and literal-search tests |
| Domain Model: Green Home | Broker/property/buyer/seller concepts; property price, area, energy label and postcode | `csharp-green-home`: new property/domain implementation |
| Frisør Virksomhed – Business Models | Business analysis, user stories, acceptance criteria and interface screenshots; no complete app source | Existing `csharp-rodeo-booking`: smaller new implementation of booking and confirmation ideas |
| Metode afsnit | Z-Park discussion of Scrum, XP, TDD, reviews and shared code | Parking simulator requirements/test mapping; no historical process metrics are claimed for the new code |
| Noter Normalformer og spørgsmål | Property/city table descriptions, normalization notes and design questions | `csharp-green-home`: normalized postcode/city relation and exact price storage |
| Obligatorisk Opgave Talepapir | Scrum, waterfall and XP comparison | Context for explaining method choices; no artificial executable project created from theory alone |
| OpenVPN Theory and Practical | CA/certificate theory, setup commands and configuration screenshots | `python-tls-lab`: local certificate/trust concepts, not a reconstructed VPN deployment |
| Opgave 5–6 Prøve | HTTP/REST explanation and Postman screenshots for a wood-pellet API | HTTP/CRUD study context; screenshots do not contain a full C# implementation |
| Opgave 6 Kryptering | Symmetric/asymmetric encryption and frontend/backend filtering discussion | TLS learning context; no unsupported claim that encryption alone provides all security properties |
| Opgavesæt systemudvikling | Weather, sales and parking briefs naming C#, Vue, REST and Raspberry Pi | `vue-parking-simulator`: selected display and sensor-state requirements |
| PLT internship notes | Angular/TypeScript, C#, SQL and CSS fragments mixed with diary notes and explanations | Context for the standalone synthetic survey example; internal application code, credentials and personal data are not published |
| Parkeringssensor 3. semester | Display colours, total availability, manual handling of sensor failures and a C#/Vue outline | `vue-parking-simulator`: display behaviour, typed events and manual override |
| Persona | Business/user personas for a vehicle-sales case | Product-analysis context; no recovered executable code |
| Rebin HomeWork 1–4 | Security concepts and discussion of attack categories | Defensive database and certificate exercises; no external attack automation |
| Rebin. Systemudvikling 5.8 | Discussion of multi-tenant and multi-instance database choices | Architecture context; the new local database examples do not claim a deployed multi-tenant system |
| Risikovurdering Parkeringssensor 3. semester | Hardware/software failure risks and a risk matrix | Parking unknown/stale states and tests. Private team reflections are excluded |
| SSL exercise 1: Create certificates | OpenSSL private key → CSR → certificate commands | `python-tls-lab`: automated CA/leaf generation, SAN hostname verification and real TLS tests |
| Quantum Key Distribution (QKD) | Qiskit/Aer one-qubit code visible on page 17, plus BB84/sifting notes | `python-bb84-lab`: recovered circuit flow, fixed small-sample handling, reference backend and intercept/resend experiment |
| normalfordeling opgave | Normal-distribution exercises and graph screenshots, with some inconsistent written answers | `javascript-probability-lab`: new calculator and presets, using recalculated probabilities |

## How to read the repositories

- **Reconstructed** means new runnable code based on a documented idea or visible snippet.
- **Extended** means functionality added now, such as tests, validation, error handling or a simulator control.
- **Fictional data** is labelled; generated model scores are results on the included synthetic demonstration data.
- No backdated commits, original-team contribution claims, employer credentials or raw personal records are included.

The goal is a portfolio that can be run, inspected and discussed. The source PDFs remain reference material rather than public repository attachments.
