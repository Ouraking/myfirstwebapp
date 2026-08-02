# CISM Practice Exam — Advanced Scenario-Based Questions

**Coverage:** All Domains (weighted to the ISACA exam blueprint)
**Difficulty:** Advanced — tests strategic and managerial decision-making
**Question count:** 20

| Domain | Questions |
|---|---|
| Domain 1 — Information Security Governance | 1–4 |
| Domain 2 — Information Security Risk Management | 5–8 |
| Domain 3 — Information Security Program | 9–14 |
| Domain 4 — Incident Management | 15–20 |

---

## Domain 1: Information Security Governance

**Question 1:** A newly hired CISO joins a global financial services firm that recently completed a merger. The two legacy organizations operate under different security frameworks (ISO 27001 and NIST CSF), and executives are pressuring the CISO to quickly consolidate security operations to reduce costs. Which of the following should the CISO do FIRST?

A) Perform a gap analysis between the two security frameworks to identify overlapping controls
B) Gain an understanding of the merged organization's business objectives and strategy
C) Select the more mature of the two frameworks and mandate enterprise-wide adoption
D) Consolidate the two security operations centers to demonstrate immediate cost savings

**Correct Answer:** B
**Explanation:**
- **Why B is correct:** In the ISACA mindset, every governance activity flows from business alignment. Before any framework decision, consolidation, or gap analysis can be meaningful, the CISO must first understand what the merged business is trying to achieve — its objectives, risk appetite, and strategic direction. The security strategy must be derived from, and support, the business strategy.
- **Why other options are incorrect:** Option A is a legitimate activity but is premature — a gap analysis has no baseline for "success" until business objectives define what the target state should be. Option C makes a structural decision without knowing whether either framework fits the merged entity's needs. Option D responds to executive cost pressure with an operational action before governance direction is set; it may lock in a structure that conflicts with the eventual strategy.

---

**Question 2:** An information security manager has been asked to present the state of the security program to the board of directors on a quarterly basis. The board has previously complained that security reporting is "too technical to act on." Which of the following would BEST address the board's concern?

A) A trend report of vulnerabilities detected and patched, sorted by CVSS severity
B) A heat map of the threat landscape compiled from industry threat intelligence feeds
C) Key indicators expressing security performance and risk in terms of impact on business objectives
D) A summary of security tool coverage across the enterprise infrastructure

**Correct Answer:** C
**Explanation:**
- **Why C is correct:** Boards govern; they do not operate. Effective board reporting translates security posture into the language of business impact — progress against risk appetite, exposure of key business services, and return on security investment. Metrics tied to business objectives allow the board to make informed governance decisions (fund, accept, redirect).
- **Why other options are incorrect:** Options A and D are operational/technical metrics; they describe activity, not business outcomes, and are exactly what the board complained about. Option B describes the external environment but does not tell the board what it means for *their* organization or what decision is required of them.

---

**Question 3:** A business unit executive requests an exception to the enterprise password policy because a legacy manufacturing application cannot support the required complexity. The security team confirms the technical limitation is real. What is the BEST course of action for the information security manager?

A) Deny the exception because policy must be applied consistently across the enterprise
B) Grant the exception since the limitation is technically verified and the application is legacy
C) Evaluate compensating controls and present the residual risk to the business owner for a formal risk acceptance decision
D) Require the business unit to fund an immediate replacement of the legacy application

**Correct Answer:** C
**Explanation:**
- **Why C is correct:** Exception management is a risk decision, not a compliance ritual. The security manager's role is to assess the exposure, identify compensating controls (e.g., network segmentation, enhanced monitoring), quantify the residual risk, and route the acceptance decision to the party who owns the risk — the business owner. This preserves both governance discipline and business alignment.
- **Why other options are incorrect:** Option A treats policy as an end in itself; rigid denial without risk analysis is not risk-based management. Option B skips the risk assessment and acceptance step — a verified technical limitation does not eliminate the exposure. Option D is a treatment option the *business owner* may choose after seeing the residual risk; the security manager cannot unilaterally impose funding decisions.

---

**Question 4:** Which of the following is the BEST indication that information security governance has been successfully integrated into an organization?

A) The CISO reports administratively to the chief information officer
B) Annual security awareness training completion rates exceed 95 percent
C) The organization has achieved ISO 27001 certification for its data centers
D) Security requirements are considered as part of every major business initiative and investment decision

**Correct Answer:** D
**Explanation:**
- **Why D is correct:** Governance is successful when security ceases to be a bolt-on function and becomes embedded in business decision-making. When security requirements are weighed in every major initiative — new products, M&A, outsourcing, technology investments — security is aligned with and inseparable from the business, which is the ultimate goal of governance.
- **Why other options are incorrect:** Option A describes a reporting line, which by itself proves nothing about integration (and reporting to the CIO can actually create independence concerns). Option B is a compliance/activity metric that measures participation, not behavioral or organizational integration. Option C is a point-in-time certification with a limited scope; certification can coexist with poor integration.

---

## Domain 2: Information Security Risk Management

**Question 5:** A vulnerability scan identifies a critical flaw in a customer-facing payment application. The vendor will not release a patch for 60 days, and taking the application offline would halt order processing. What should the information security manager do FIRST?

A) Assess the likelihood of exploitation and the potential business impact of the vulnerability
B) Implement a web application firewall rule to block the known exploit pattern
C) Notify the audit committee of a material weakness in the control environment
D) Invoke the incident response plan to prepare for a potential breach

**Correct Answer:** A
**Explanation:**
- **Why A is correct:** ISACA's sequencing discipline: before selecting any treatment, the manager must understand the risk — how exposed the application actually is, whether exploitation is occurring in the wild, and what a compromise would mean to the business. The assessment determines whether compensating controls, accelerated escalation, or even accepted risk is the appropriate response.
- **Why other options are incorrect:** Option B is a plausible compensating control, but selecting it *before* assessing the risk assumes the treatment; it may be insufficient or unnecessary. This is the classic "technically correct but out of sequence" distractor. Option C is premature — there is no assessed risk to report yet, and a vulnerability is not automatically a material weakness. Option D confuses a vulnerability with an incident; no compromise has been identified.

---

**Question 6:** Following an enterprise risk assessment, the information security manager determines that the residual risk of a revenue-generating cloud service exceeds the organization's stated risk appetite. The service owner insists the service must continue operating without additional controls due to contractual commitments. What is the BEST next step for the information security manager?

A) Escalate the risk to senior management for a decision on treatment or formal acceptance
B) Disable the service until residual risk is brought within the risk appetite
C) Document the service owner's verbal acceptance and continue monitoring the risk
D) Purchase cyber insurance to transfer the excess residual risk

**Correct Answer:** A
**Explanation:**
- **Why A is correct:** When residual risk exceeds appetite and the risk owner declines further treatment, the decision no longer belongs at the operating level. The security manager's obligation is to escalate to the management level with authority to either accept risk above appetite (a deliberate governance decision) or mandate treatment. The manager advises; management decides.
- **Why other options are incorrect:** Option B exceeds the security manager's authority and would inflict the very business damage risk management exists to prevent. Option C is defective governance — risk acceptance above appetite must be formal, documented, and made by someone with the authority to bind the organization, not captured as a verbal note. Option D is a treatment option that only management can select after the escalation; insurance also cannot transfer reputational or regulatory consequences.

---

**Question 7:** An organization is finalizing a contract with a SaaS provider that will process regulated customer data. The provider's SOC 2 Type II report is clean, but the provider refuses to include a right-to-audit clause and will not commit to breach notification timelines. Which of the following should be the information security manager's GREATEST concern?

A) The provider's infrastructure may not be compliant with the organization's internal hardening standards
B) The provider's data centers are located in a different geographic region
C) The SOC 2 report was issued by an audit firm the organization has not worked with before
D) The organization will be unable to verify the provider's ongoing control effectiveness or meet its own regulatory notification obligations

**Correct Answer:** D
**Explanation:**
- **Why D is correct:** Accountability for regulated data cannot be outsourced. Without audit rights, the organization loses the ability to verify controls between attestation periods; without contractual notification timelines, it may be unable to meet its own legal breach-notification deadlines. Both gaps strike at the organization's ability to discharge obligations it retains regardless of the outsourcing arrangement — a governance-level exposure.
- **Why other options are incorrect:** Option A misapplies internal standards to a SaaS model — the concern is outcome assurance, not mirroring internal configurations. Option B may raise data-residency questions but is manageable and is only a concern if specific regulations prohibit it — it is not the *greatest* concern presented. Option C is a minor due-diligence item; SOC 2 reports from reputable independent firms are standard.

---

**Question 8:** An information security manager is designing key risk indicators (KRIs) for the security program. What is the PRIMARY purpose of KRIs?

A) To demonstrate the return on investment of security controls to executive management
B) To provide an early warning that risk exposure is approaching or exceeding acceptable thresholds
C) To benchmark the organization's security posture against industry peers
D) To measure the operational efficiency of the security team's processes

**Correct Answer:** B
**Explanation:**
- **Why B is correct:** KRIs are forward-looking trip wires. Their primary value is signaling that risk levels are trending toward or past defined thresholds *before* losses materialize, enabling management to act proactively — reprioritizing treatment, tightening controls, or revisiting acceptance decisions.
- **Why other options are incorrect:** Option A describes value/ROI metrics, which justify investment rather than warn of exposure. Option C describes benchmarking, which provides context but no early warning. Option D describes key performance indicators (KPIs) — a classic ISACA distractor that swaps performance measurement for risk measurement.

---

## Domain 3: Information Security Program

**Question 9:** An organization has hired an information security manager to establish a security program where none formally existed. Senior management has allocated an initial budget. Which of the following should the manager do FIRST?

A) Procure and deploy foundational security technologies such as endpoint detection and SIEM
B) Conduct a gap analysis against a recognized security framework
C) Define a security strategy based on the organization's business objectives and risk profile
D) Hire security staff to build out the core operational functions

**Correct Answer:** C
**Explanation:**
- **Why C is correct:** A program without a strategy is a collection of activities. The strategy — derived from business objectives, the organization's risk profile, and its risk appetite — defines the target state that every subsequent decision (framework selection, gap analysis, staffing, technology) must serve. Strategy first; everything else follows from it.
- **Why other options are incorrect:** Option A spends budget on technology before knowing what risks the program must address — a common real-world failure ISACA loves to punish. Option B is the classic "right activity, wrong time" distractor: a gap analysis requires a defined target state, which the strategy provides. Option D commits structure and payroll before the strategy defines what capabilities are actually needed.

---

**Question 10:** After two years of mandatory annual security awareness training with completion rates above 98%, an organization continues to experience successful phishing compromises. Which of the following would BEST enable the information security manager to evaluate the awareness program's effectiveness?

A) Increase the frequency of training from annually to quarterly
B) Require a passing score on a knowledge assessment at the end of each training module
C) Track the trend of employee behavior through simulated phishing campaign results over time
D) Compare training completion rates across departments to identify lagging business units

**Correct Answer:** C
**Explanation:**
- **Why C is correct:** The objective of awareness training is behavioral change, and effectiveness must be measured against that objective. Trending simulated phishing results (click rates, credential submission rates, reporting rates) over time directly measures whether behavior is improving — which completion rates demonstrably have not captured.
- **Why other options are incorrect:** Option A is a program change, not an evaluation method — and changing the program before measuring it is out of sequence. Option B measures knowledge retention at a point in time, not behavior under realistic conditions; people who pass quizzes still click links. Option D compares an activity metric (completion) already shown to be disconnected from outcomes.

---

**Question 11:** An organization is outsourcing its 24/7 security monitoring to a managed security service provider (MSSP). From the information security manager's perspective, which of the following is MOST important to include in the contract?

A) Clearly defined service levels, escalation procedures, and the right to audit the provider's controls
B) The specific SIEM technology stack and correlation rules the MSSP will operate
C) A requirement that all MSSP analysts hold industry security certifications
D) A provision allowing the organization to terminate the contract without penalty

**Correct Answer:** A
**Explanation:**
- **Why A is correct:** When a security function is outsourced, accountability remains with the organization; the contract is the primary governance instrument over the provider. Defined service levels make performance measurable and enforceable, escalation procedures ensure incidents reach the organization in time to act, and audit rights preserve the ability to verify that contracted controls actually operate.
- **Why other options are incorrect:** Option B over-specifies the "how" — the organization should contract for outcomes and service levels, not dictate the provider's toolset. Option C addresses one input to quality but guarantees nothing about service delivery. Option D is a useful commercial safeguard but is an exit mechanism, not a means of governing ongoing service performance.

---

**Question 12:** During the design of a new enterprise application, the project team asks the information security manager which controls must be implemented. What should PRIMARILY drive the selection of controls?

A) The controls catalog of the security framework the organization has adopted
B) The results of a risk assessment of the application and the data it will process
C) Controls implemented by industry peers for similar applications
D) The security features natively available in the chosen technology platform

**Correct Answer:** B
**Explanation:**
- **Why B is correct:** Controls exist to modify risk. The nature and sensitivity of the data, the threats to the application, and the potential business impact of compromise — established through risk assessment — determine which controls are warranted and to what strength. This ensures control investment is proportionate to actual exposure, satisfying cost-benefit discipline.
- **Why other options are incorrect:** Option A provides a menu, not a selection method — frameworks themselves direct that controls be chosen based on risk. Option C (benchmarking) reflects other organizations' risk profiles, not this one's. Option D lets available features drive requirements — inverting the proper sequence in which requirements drive technology decisions.

---

**Question 13:** An information security manager wants to reduce the number of vulnerabilities discovered in applications after deployment. Which of the following approaches would be MOST effective?

A) Increase the frequency of penetration testing on production applications
B) Require developers to remediate all critical findings before each release
C) Deploy a runtime application self-protection (RASP) solution across the production estate
D) Integrate security requirements and checkpoints throughout the development life cycle, beginning at the requirements phase

**Correct Answer:** D
**Explanation:**
- **Why D is correct:** Vulnerabilities are cheapest and most effectively addressed at the point of introduction. Embedding security from the requirements phase onward — security requirements, threat modeling in design, secure coding standards, testing gates — prevents defects from being created rather than detecting them after the fact. This is the management-level, process-oriented answer.
- **Why other options are incorrect:** Option A detects vulnerabilities *after* deployment — the very outcome the manager wants to reduce. Option B is a detective/corrective gate late in the cycle; it addresses findings but does not prevent them, and creates release pressure rather than process improvement. Option C is a technical mitigation that shields flaws at runtime without reducing their introduction.

---

**Question 14:** An information security manager is establishing a metrics program for the security program. Which attribute of a proposed metric is MOST important?

A) The metric supports decisions by being linked to the objectives it is intended to measure
B) The metric can be collected automatically from existing security tools
C) The metric aligns with those published in industry benchmarking studies
D) The metric can be expressed quantitatively rather than qualitatively

**Correct Answer:** A
**Explanation:**
- **Why A is correct:** A metric is only valuable if it informs a decision. Metrics must trace to the objectives of the security program (and ultimately business objectives) so that movement in the metric tells management whether objectives are being met and what action to take. Everything else — automation, comparability, precision — is secondary to decision relevance.
- **Why other options are incorrect:** Option B is about collection efficiency; an easily collected but irrelevant metric is noise (the "measure what's easy" trap). Option C provides comparability but says nothing about relevance to this organization's objectives. Option D is desirable, but a relevant qualitative indicator beats an irrelevant precise number.

---

## Domain 4: Incident Management

**Question 15:** A security analyst detects active ransomware encryption in progress on a server supporting a critical business process. The organization has a documented and tested incident response plan. What should be done FIRST?

A) Restore the affected server from the most recent clean backup
B) Initiate the incident response plan and contain the affected system in accordance with it
C) Conduct a forensic analysis to identify the initial infection vector
D) Notify law enforcement and the organization's cyber insurance carrier

**Correct Answer:** B
**Explanation:**
- **Why B is correct:** With active encryption spreading, the priority is limiting damage through the organization's predefined, tested process. Invoking the incident response plan activates the response team with defined roles and triggers containment actions that were designed and rehearsed in advance — preventing the improvised, ad hoc decisions that worsen major incidents.
- **Why other options are incorrect:** Option A is a recovery step; restoring before containment and eradication risks immediate reinfection and may destroy evidence. Option C is an investigation activity that follows containment — analyzing the vector while encryption continues sacrifices the business to satisfy curiosity. Option D is a notification step that the plan itself will sequence; it does nothing to stop the ongoing damage.

---

**Question 16:** Following the resolution of a major security incident, the information security manager schedules a post-incident review. What is the PRIMARY objective of this review?

A) To determine which employees' actions contributed to the incident and apply sanctions
B) To calculate the total financial loss attributable to the incident for insurance recovery
C) To produce the final incident documentation required by the organization's regulators
D) To identify lessons learned and improve the incident response capability and control environment

**Correct Answer:** D
**Explanation:**
- **Why D is correct:** The post-incident review closes the improvement loop: what happened, how well did detection and response perform, which controls failed or were missing, and what must change in plans, controls, or training. Its output feeds corrective actions that reduce both the likelihood and the impact of future incidents — continuous improvement is the review's reason for existing.
- **Why other options are incorrect:** Option A turns the review into a blame exercise, which suppresses the candor needed to surface root causes. Options B and C are legitimate by-products — loss quantification and regulatory documentation may draw on the review — but they are administrative outcomes, not the primary objective.

---

**Question 17:** During a prolonged outage caused by a destructive cyberattack, the incident commander is unsure whether to invoke the organization's disaster recovery plan or continue attempting recovery in place. Which of the following would BEST support this decision?

A) The judgment of the most senior technical engineer on the response team
B) Predefined invocation criteria based on maximum tolerable outage and impact thresholds
C) The estimated cost of operating from the disaster recovery site
D) The preference of the affected business unit's leadership at the time of the incident

**Correct Answer:** B
**Explanation:**
- **Why B is correct:** Invocation decisions made under pressure are unreliable unless anchored to criteria established in calm conditions. Predefined thresholds — derived from the business impact analysis (maximum tolerable outage, recovery time objectives, impact severity) — convert an emotional wartime judgment into a governed, repeatable decision: when projected downtime exceeds tolerance, invoke.
- **Why other options are incorrect:** Option A substitutes individual technical optimism ("we can fix it in one more hour") for business-based criteria — a leading cause of blown recovery windows. Option C is already factored into DR strategy design; re-litigating cost mid-incident delays the decision. Option D injects ad hoc stakeholder preference at the worst possible time; business tolerance should already be encoded in the invocation criteria.

---

**Question 18:** An insider is suspected of exfiltrating confidential data, and the organization anticipates both termination proceedings and possible criminal prosecution. When collecting evidence from the suspect's workstation, which of the following is MOST important?

A) Maintaining a documented chain of custody using forensically sound acquisition methods
B) Completing the evidence collection before the suspect's next scheduled workday
C) Using the same disk imaging software as the local law enforcement agency
D) Encrypting all collected evidence with the organization's enterprise key management system

**Correct Answer:** A
**Explanation:**
- **Why A is correct:** Evidence that cannot be shown to be authentic and unaltered is inadmissible. A documented chain of custody — who collected what, when, how, and every transfer thereafter — combined with forensically sound methods (write blockers, verified images, hash values) preserves evidentiary integrity for both the employment action and criminal proceedings. Without it, everything else is wasted effort.
- **Why other options are incorrect:** Option B addresses timing; speed matters but is worthless if the evidence is legally unusable. Option C is unnecessary — admissibility depends on validated, forensically sound methodology, not on matching a specific agency's toolset. Option D protects confidentiality of the evidence but does not establish its integrity or provenance, which are what courts require.

---

**Question 19:** An information security manager is developing the incident classification scheme for the organization's incident response plan. Severity levels should PRIMARILY be based on which of the following?

A) The number of systems and endpoints affected by the incident
B) The potential impact on business operations, data, and stakeholders
C) The sophistication and attribution of the threat actor involved
D) The estimated effort and time required for technical remediation

**Correct Answer:** B
**Explanation:**
- **Why B is correct:** Classification drives escalation, resource allocation, and executive notification — all of which should be proportionate to what the incident means for the business. An incident affecting one system that processes regulated data or supports a critical revenue process can vastly outweigh a hundred compromised kiosks. Business impact, informed by the business impact analysis, is the anchoring criterion.
- **Why other options are incorrect:** Option A is a volume proxy that correlates poorly with consequence — the classic trap of counting systems instead of weighing impact. Option C is threat intelligence context; a sophisticated actor causing negligible impact is not automatically a severe incident. Option D measures response cost, not harm to the organization, and is often unknowable at classification time.

---

**Question 20:** A breach involving customers' personal data has been confirmed and is likely to attract media attention and regulatory scrutiny across multiple jurisdictions. Which of the following BEST ensures that external communications about the incident are handled appropriately?

A) Instructing all employees to refrain from discussing the incident until the investigation concludes
B) Delaying all external notifications until the full forensic root cause analysis is complete
C) Having the CISO personally brief journalists to demonstrate technical transparency and competence
D) Executing the predefined incident communication plan, with designated spokespersons and legal review of all external statements

**Correct Answer:** D
**Explanation:**
- **Why D is correct:** Multi-jurisdiction breach communications must satisfy conflicting pressures — statutory notification deadlines, litigation exposure, and reputational stewardship — simultaneously. A predefined communication plan resolves these in advance: designated, trained spokespersons ensure consistency; legal review protects privilege and accuracy; and mapped regulatory timelines ensure obligations are met even before the investigation concludes.
- **Why other options are incorrect:** Option A is one element of message control but is purely suppressive — it makes no affirmative communication and cannot satisfy notification obligations. Option B is dangerous — many regulations impose fixed notification windows (e.g., 72 hours) that expire long before forensics conclude; waiting converts a breach into a compliance violation. Option C bypasses the communication structure; the CISO's role is to inform the messaging, not to freelance with the press.

---

## Answer Key

| Q | Answer | Domain | Trigger |
|---|--------|--------|---------|
| 1 | B | Governance | FIRST |
| 2 | C | Governance | BEST |
| 3 | C | Governance | BEST |
| 4 | D | Governance | BEST |
| 5 | A | Risk Management | FIRST |
| 6 | A | Risk Management | BEST |
| 7 | D | Risk Management | GREATEST |
| 8 | B | Risk Management | PRIMARY |
| 9 | C | Program | FIRST |
| 10 | C | Program | BEST |
| 11 | A | Program | MOST important |
| 12 | B | Program | PRIMARILY |
| 13 | D | Program | MOST effective |
| 14 | A | Program | MOST important |
| 15 | B | Incident Management | FIRST |
| 16 | D | Incident Management | PRIMARY |
| 17 | B | Incident Management | BEST |
| 18 | A | Incident Management | MOST important |
| 19 | B | Incident Management | PRIMARILY |
| 20 | D | Incident Management | BEST |
