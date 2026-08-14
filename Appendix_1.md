# Results : example of an Eye of Horus output formatted by the Qwen3-30B-A3B model (Using Superprompt1)

Today at 11:48 AM

**NATO – SAS-185-RTG**
**Technical Authority:** Zachary Devereaux, NATO SAS-185-RTG
**Date:** 22-07-2025

## 1. Reference Source

*From Bullets to Bytes: Rethinking NATO’s defence in the Age of Rising Information Warfare – CDA Institute (2023).*
The article analyses the shift from kinetic-focused doctrines to a hybrid stance where **information, cognitive, and cyber domains** are integral to NATO’s collective defence.

**Table 6: Key themes include:**

| Theme                                      | Brief Summary (≤90 char)                                                         |
| ------------------------------------------ | -------------------------------------------------------------------------------- |
| **Strategic Narrative**                    | NATO must own the story of security, not just the battlefield.                   |
| **Cognitive Resilience**                   | Protecting decision-makers from manipulation is as vital as physical protection. |
| **Integrated Information Operations (IO)** | Fuse cyber-defence, PSYOPS, and SIGINT into a single “info-defence” enterprise.  |
| **Data-driven Decision-Making**            | Real-time analytics are required to detect and counter hostile influence.        |
| **Partner-Centric Approach**               | Allies and partners need interoperable tools and shared doctrine.                |

*All excerpts are within fair-use limits.*

## 2. Methodology for COA Generation

| Component                                 | How it is applied                                                                                                                                                                                             |
| ----------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Harold Lasswell’s Communication Model** | “Who-says-what-in-which channel-to-whom-with what effect” is used to map *information-war actors* (adversary, NATO, publics) and identify *critical communication nodes* that must be protected or leveraged. |
| **Kathleen Carley’s BEND Heuristic**      | Each COA is evaluated for its ability to **Boost, Exploit, Neutralize, or Disrupt** adversary influence.                                                                                                      |
| **US Doctrinal Indicators**               | Indicators (pre-launch, early, mid-course, terminal) are *defined* per COA to enable *continuous assessment* and *early warning* of success or failure.                                                       |
| **JASPER AI Attribute Extraction**        | Automated extraction of “attributes → (actors, objectives, means, constraints, environment)” from OSINT sources; results are sanity-checked against the article’s thematic structure.                         |
| **RAG (Retrieval-Augmented Generation)**  | The online LLM queries the CDA article and the open-source repository *RobinBurda/sas185-indicators-and-warnings-for-cognitive-warfare* to enrich indicator lists with *real-time OSINT.*                     |

## 3. Course-of-Action (COA) Generation

Four viable COAs are presented. Each includes **attributes** (purpose, tasks, resources, timeline, risk, BEND focus) and **a set of indicators** aligned to the methodology above.

**Table 7: COA 1 – NATO Integrated Cognitive-Resilience Hub (ICRH)**

| Attribute                 | Detail                                                                                                                                                                                                                                                                                                                                                                                              |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Centralize detection, analysis, and mitigation of adversarial influence targeting NATO decision-makers and allied societies.                                                                                                                                                                                                                                                                        |
| **Key Tasks**             | 1. Establish a *joint hub* at NATO HQ (Brussels) staffed by cyber-defence, intelligence, PSYOPS, and behavioural-science experts.<br>2. Deploy a *real-time analytics platform* ingesting social-media, SIGINT, and open-source feeds.<br>3. Produce *cognitive-risk alerts* for senior leaders and national ministries.<br>4. Conduct *monthly red-team exercises* simulating influence campaigns. |
| **Required Capabilities** | - Multi-domain *data lake* (EU-wide).<br>- AI-driven sentiment / narrative detection (BEND-Boost & Neutralize).<br>- Secure communications (NATO Classified/Unclassified).                                                                                                                                                                                                                          |
| **Timeline**              | Phase 1 (0-6 mo): Concept-validation & staffing.<br>Phase 2 (6-18 mo): Platform build & pilot with 3 Allies.<br>Phase 3 (18-36 mo): Full operational capability (FOC).                                                                                                                                                                                                                              |
| **Risk Assessment**       | *Political:* Perception of “surveillance” – mitigated with transparent governance.<br>*Operational:* Integration of disparate data sources – mitigated by NATO-standard APIs.<br>*Technical:* Model bias – mitigated by continuous human-in-the-loop review.                                                                                                                                        |
| **BEND Focus**            | **Boost** NATO’s narrative coherence; **Neutralize** hostile memes before they reach decision forums.                                                                                                                                                                                                                                                                                               |
| **Indicators**            | • **Pre-launch:** Formal charter signed by 80 % of member states.<br>• **Early:** ≥ 2 successful pilot alerts reducing “influence-score” > 30 % in targeted units.<br>• **Mid-course:** 75 % of national ministries subscribed to hub alerts.<br>• **Terminal:** Post-event analysis shows ≥ 40 % reduction in adversary narrative reach during a simulated crisis.                                 |

**COA 2 – Alliance-Wide Integrated Information-Operations (IO) Training Programme**

| Attribute                 | Detail                                                                                                                                                                                                                                                                                                                                     |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Purpose**               | Embed *information-operations* competence across all NATO forces, ensuring every commander can plan and execute defensive and offensive IO.                                                                                                                                                                                                |
| **Key Tasks**             | 1. Design a *curriculum* (strategic communication, cognitive security, cyber-effects).<br>2. Certify *IO instructors* from each nation.<br>3. Deliver *annual joint exercises* (e.g., *Operation Narrative Shield*).                                                                                                                       |
| **Required Capabilities** | - NATO Defence College augmentation.<br>- Simulation environments (virtual-reality influence battlefields).                                                                                                                                                                                                                                |
| **Timeline**              | 0-12 mo: Curriculum development.<br>12-24 mo: Instructor certification.<br>24-36 mo: First joint exercise.                                                                                                                                                                                                                                 |
| **Risk Assessment**       | *Political:* Nations may view IO training as “propaganda”. Countered by emphasizing defensive posture and NATO’s Article 5 mandates.<br>*Operational:* Curriculum overload – mitigated by modular design (1-day blocks).                                                                                                                   |
| **BEND Focus**            | **Exploit** NATO’s own capabilities to *counter-narrate*; **Disrupt** adversary planning cycles.                                                                                                                                                                                                                                           |
| **Indicators**            | • **Pre-launch:** NATO STANAG on IO approved.<br>• **Early:** 10 instructors certified, pilot course delivered to two commands.<br>• **Mid-course:** ≥ 70 % of NATO units report inclusion of IO in after-action reviews.<br>• **Terminal:** After a live crisis, NATO’s coordinated messaging pre-empts adversary narrative by ≥ 2 hours. |

**Table 8: COA 3 – Joint Cognitive-Security Liaison Cells (JCSLC) in NATO’s Strategic Commands**

| Attribute                 | Detail                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| ------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Embed *cognitive-security specialists* directly within Allied Joint Force Commands (JFC-Brunssum, JFC-Southeast, etc.) to provide *on-the-ground* advice during operations.                                                                                                                                                                                                                                                                                                      |
| **Key Tasks**             | 1. Recruit *cognitive scientists*, psychologists, and IO specialists.<br>2. Create *cell SOPs* linking to the ICRH (COA 1) and to national intelligence.<br>3. Conduct *real-time briefings* during crises.                                                                                                                                                                                                                                                                      |
| **Required Capabilities** | - Secure liaison channels (NATO NIPRNet).<br>- Rapid-response analytical kits (portable AI inference).                                                                                                                                                                                                                                                                                                                                                                           |
| **Timeline**              | 0-9 mo: Staffing plan.<br>9-18 mo: Cell activation at two JFCs.<br>18-30 mo: Full rollout to all NATO strategic commands.                                                                                                                                                                                                                                                                                                                                                        |
| **Risk Assessment**       | *Technical:* Data-sharing constraints – mitigated via NATO-approved classification markings.<br>*Operational:* Overlap with existing intelligence cells – mitigated by clear charter delineating “cognitive” focus.                                                                                                                                                                                                                                                              |
| **BEND Focus**            | **Neutralize** influence attempts at the operational level; **Disrupt** adversary planning through *early warning*.                                                                                                                                                                                                                                                                                                                                                              |
| **Indicators**            | • **Pre-launch:** Cell charter ratified by Supreme Allied Commander Europe (SACEUR).<br>• **Early:** First cell provides actionable brief during a NATO exercise, reducing “information-gap” incidents by 50 %.<br>• **Mid-course:** All JFCs host at least one JCSLC.<br>• **Terminal:** During a real crisis, JCSLCs deliver *cognitive-risk assessments* that inform NATO’s strategic communications strategy, leading to measurable decline in adversary “persuasion index”. |

**Table 9: COA 4 – Allied “Info-Defence” Data-Lake & AI-Analytics Consortium (ADIC)**

| Attribute                 | Detail                                                                                                                                                                                                                                                                                                                                                                                                                      |
| ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Purpose**               | Create a *shared, NATO-wide data-lake* of information-warfare artefacts (malicious memes, deep-fakes, bot-net signatures) and an *AI consortium* to develop predictive models.                                                                                                                                                                                                                                              |
| **Key Tasks**             | 1. Draft legal framework for *cross-border data sharing* (GDPR-compatible).<br>2. Build *cloud-native repository* with tiered access (classified-unclassified).<br>3. Sponsor *AI research contracts* (e.g., for BEND-Boost/Exploit algorithms).                                                                                                                                                                            |
| **Required Capabilities** | - NATO Cloud Services (NCS) integration.<br>- Partnership with EU’s *ENISA & JRC* for data standards.                                                                                                                                                                                                                                                                                                                       |
| **Timeline**              | 0-6 mo: Legal & policy work.<br>6-18 mo: Infrastructure deployment.<br>18-30 mo: First AI model (BEND-Disrupt) operational.                                                                                                                                                                                                                                                                                                 |
| **Risk Assessment**       | *Political:* Sovereignty concerns – mitigated by data-minimisation and opt-out clauses.<br>*Technical:* Model poisoning – mitigated by multi-layer validation and adversarial-training.                                                                                                                                                                                                                                     |
| **BEND Focus**            | **Exploit** open-source data for *predictive analytics*; **Disrupt** adversary campaigns via *early-warning alerts*.                                                                                                                                                                                                                                                                                                        |
| **Indicators**            | • **Pre-launch:** Formal data-sharing agreement signed by ≥ 18 nation-states.<br>• **Early:** Data-lake ingests > 10 TB of OSINT within 3 months.<br>• **Mid-course:** AI model flags ≥ 90 % of test-campaigns (precision > 0.85).<br>• **Terminal:** During a live geopolitical event, ADIC provides *pre-emptive counter-narrative recommendations* that are incorporated into NATO’s strategic messaging within 4 hours. |

**Table 10: Summary of Extracted Attributes**

| Attribute                   | Value (derived from article)                                                                                                      |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| **Strategic Intent**        | Preserve alliance cohesion by defending the *cognitive domain*.                                                                   |
| **Operational Environment** | Multi-domain (cyber, information, kinetic), contested narratives, high-speed OSINT flow.                                          |
| **Key Actors**              | NATO HQ, Joint Forces, National Ministries, adversary state/non-state influence actors, public spheres.                           |
| **Desired Effects**         | *Boost* NATO’s narrative; *Exploit* own data for rapid response; *Neutralize* adversary messaging; *Disrupt* influence pipelines. |
| **Constraints**             | Legal (EU data-privacy), political (sovereignty), technical (interoperability).                                                   |
| **Metrics**                 | Narrative reach reduction (%), alert latency (hrs), training completion rates (%), model precision/recall.                        |

## 5. Recommendations

1. **Adopt COA 1 (ICRH) as the foundational pillar** – it delivers the real-time situational awareness required for the other COAs to be effective.
2. **Phase-in COA 2 and COA 3 concurrently** (12-24 months) to embed capability and expertise across the alliance.
3. **Launch COA 4 (ADIC) as a parallel, longer-term R&D effort**—its outputs will enhance the ICRH analytics and the liaison cells.

Implementing this tiered approach aligns with *NATO’s Strategic Concept (2022)* and leverages the “bullets-to-bytes” paradigm identified in the CDA Institute analysis.

**Prepared by:**
Zachary Devereaux, Technical Authority – NATO SAS-185-RTG
Open-AI Playground – COA Assistant (JASPER AI integration)

*End of Section*
