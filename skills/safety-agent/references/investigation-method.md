# Investigation Method Reference

How to classify incidents, choose an analysis method, group causes across many incidents, read reporting data honestly, and write corrective actions that actually reduce risk.

---

## 1. Incident classification

### Actual vs potential severity
- Actual severity: what happened (first aid, medical treatment, lost time, permanent disability, fatality). Drives injury statistics (TRIFR, LTIFR) and regulator notification.
- Potential severity: the worst credible outcome had circumstances been slightly different (a metre to the left, a second later, no hard hat). Drives investigation depth and learning.
- Rate both, on the same consequence scale used in the risk matrix (see risk-method.md). Ask: "What energy was present, and what stood between it and a person?"

### HiPo and SIF
- HiPo (high potential incident): any incident or near miss whose worst credible outcome is a fatality or permanent disabling injury, regardless of actual outcome. HiPos get a formal investigation (for example ICAM) and executive visibility.
- SIF: serious injury or fatality, meaning life-threatening or life-altering outcomes.
- SIF precursor (Campbell Institute, 2020): a high-risk situation in which controls are broken, absent or not complied with. Example: working at height is not a precursor; working at height without fall protection is. Precursors can be found in observations and near misses before anyone is hurt.
- EEI Safety Classification and Learning (SCL) model (Edison Electric Institute, principal author Dr Matthew Hallowell): classify by four questions.
  1. Was high energy present? (above about 500 ft-lbs / 678 J, the threshold the research associates with SIF outcomes; suspended loads, mobile equipment, arc flash usually exceed it)
  2. Did a high-energy incident occur? (release with contact or proximity, generally within about 6 ft / 1.8 m with unrestricted egress, any distance in confined or restricted-egress situations)
  3. Was a serious injury sustained?
  4. Was a direct control present? A direct control targets the high-energy source and works even with unintentional human error (lockout/tagout, machine guarding, hard barriers, fall protection). Training, signs, rules, experience and standard PPE are not direct controls.
- SCL categories: HSIF (high-energy SIF), LSIF (low-energy SIF), PSIF (high-energy release, no direct control, no serious injury: luck), Capacity (high-energy release, direct control worked), Exposure (high energy present without direct control, no release yet), Success (high energy present with direct control, no incident), Low severity.
- EEI's caution: do not turn PSIF counts into a performance target. A rising PSIF rate can mean worse control or a better reporting culture.

### Practical classification fields for every event
1. Actual severity (1 to 5). 2. Potential severity (1 to 5). 3. HiPo yes/no (potential 4 or 5). 4. Energy type (gravity, motion, mechanical, electrical, pressure, temperature, chemical, biological, radiation, sound). 5. High energy yes/no. 6. Direct control present yes/no. 7. Critical risk category linked to the register. 8. Notifiable to regulator yes/no (model WHS Act s35 to s39: death, serious injury or illness, dangerous incident; preserve the site).

Sources:
- https://www.nsc.org/newsroom/new-campbell-institute-research-guides-employers-o
- https://cms.eei.org/-/media/Project/EEI/Documents/Issues-and-Policy/Power-to-Prevent-SIF/eeiSCLmodel.pdf

---

## 2. Analysis methods: ICAM and 5 Whys

### ICAM (Incident Cause Analysis Method)
Based on James Reason's organisational accident ("Swiss cheese") model; developed in the Australian mining sector (associated with BHP Billiton and Safety Wise Solutions, late 1990s). Works backwards from the event through four categories of contributing factors:

| Category | What it captures | Example |
|---|---|---|
| Absent or failed defences | Controls, barriers and recovery measures that were missing or did not work at the time. | Pedestrian barrier removed for a delivery and not replaced; interlock bypassed; no spotter. |
| Individual or team actions | Errors or violations by people at the sharp end immediately before the event. Describe, do not blame. | Operator reversed without looking; worker entered exclusion zone to retrieve a tool. |
| Task or environmental conditions | Conditions present at the time that shaped those actions: workplace, equipment, time pressure, fatigue, lighting, weather, competing tasks. | Night shift, poor lighting, dock congestion at peak, unfamiliar equipment. |
| Organisational factors | Underlying system conditions that created the task conditions or allowed defences to fail: design, resourcing, procedures, training systems, contractor management, MOC, supervision, culture. | No traffic management review after layout change; production targets set without staffing; labour hire induction not required. |

Use ICAM when:
- Actual or potential severity is 4 or 5 (HiPo, SIF, notifiable incident).
- Multiple parties or contractors are involved.
- The event suggests a system failure, a repeat event, or a critical control failure.
- Outputs need to stand up to regulator, legal or board scrutiny.
ICAM is run by a trained lead investigator with a small team, includes interviews, evidence collection and timeline, and normally takes days to weeks.

### 5 Whys
Ask "why" repeatedly (about five times) from the event to reach a cause the organisation can act on.
Use 5 Whys when:
- Actual and potential severity are low (1 to 3) and the cause chain is simple and linear.
- A supervisor needs a quick, structured look within 24 to 48 hours.
- As a sub-tool inside ICAM to drill into one contributing factor.
Limits: single causal chain, stops at the first plausible answer, tends to end at "worker did not follow procedure". If the answer is a person, ask one more why: why did the system make that the easy choice? Escalate to ICAM if a fatal-potential factor emerges.

### Rules for both
- Separate facts from opinions; build a timeline first.
- Look at what was normal, not just what went wrong (work as done vs work as imagined).
- Every finding should map to at least one control or system fix; "human error" is a starting point, not a root cause.

Sources:
- https://sitemate.com/resources/articles/safety/icam-investigation/
- https://www.compliancecouncil.com.au/capabilities/icam-investigations/

---

## 3. Root cause theme taxonomy (for grouping free-text incident descriptions)

Use to tag incidents and near misses so trends surface across sites. An incident can carry more than one theme; choose a primary theme. Keyword cues are starting points for text classification; always confirm with the context of the description.

| Theme | Definition | Keyword cues |
|---|---|---|
| Housekeeping | Untidy, obstructed or contaminated work areas. | spill, wet floor, oil, clutter, debris, rubbish, cord across, left on floor, obstructed walkway, slipped on, tripped over, stored in aisle |
| Manual handling | Lifting, carrying, pushing, pulling, repetitive or awkward postures. | lifting, lifted, carrying, twisting, bending, pushing trolley, pulling, strain, sprain, back pain, shoulder, repetitive, overreach, heavy box |
| Plant-pedestrian interaction | People and mobile plant or vehicles in the same space. | forklift, reach truck, pallet jack, reversing, telehandler, excavator, truck, loader, struck by vehicle, near miss with forklift, walkway, blind spot, spotter |
| Procedure not followed | A defined procedure, permit or rule existed but was not applied. | did not follow, bypassed, short cut, no permit, without isolation, did not lock out, skipped, ignored sign, not as per SWMS, override |
| Inadequate training or competency | Person lacked skill, licence, induction or familiarity. | new starter, first day, not trained, unfamiliar, no licence, not inducted, labour hire, agency, apprentice, did not know how |
| Fatigue | Tiredness, long hours, shift effects, inadequate rest. | tired, fatigue, long shift, double shift, overtime, night shift, fell asleep, microsleep, 12 hour, no break |
| Supervision | Absent, inadequate or conflicting supervision or direction. | no supervisor, unsupervised, left alone, supervisor not present, told to hurry, instructed to, lack of oversight, leading hand away |
| Design | Plant, workplace or task design created the hazard. | design, layout, no guard fitted, too high, awkward access, poor visibility, blind corner, no handrail, unsuitable tool, ergonomics |
| Maintenance | Equipment condition, defects, overdue servicing. | faulty, broken, defect, worn, leaking, failed, not serviced, overdue service, brakes, damaged racking, tag out of date |
| Contractor management | Gaps in selecting, inducting, coordinating or overseeing contractors. | contractor, subcontractor, sub, third party, external crew, not inducted, did not sign in, SWMS not reviewed, coordination |
| Communication | Information not passed on or misunderstood. | handover, not told, miscommunication, radio, language barrier, misunderstood, no sign, not informed, conflicting instructions, shift change |

Practitioner notes:
- "Procedure not followed" should rarely be a root cause on its own. Pair it with why (training, design, supervision, production pressure).
- Track themes against potential severity, not just counts. Ten housekeeping slips matter less than one plant-pedestrian HiPo.
- Psychosocial events (aggression, harassment, overload) need their own themes mapped to the 14 Code hazards (see risk-method.md).

Source: practitioner taxonomy; categories align with ICAM task, environmental and organisational factors.

---

## 4. Signals of under-reporting and how to read near miss ratios

### Signals a site is under-reporting
- Total reporting rate (all reports per 200,000 hours or per worker) drops while hours, headcount or activity stay flat or rise.
- Near miss to injury ratio falling: injuries steady or rising, near misses falling.
- Reports dominated by minor first aid with few or no near misses, observations or hazards.
- High ratio of medical treatment or lost time injuries to first aid injuries (minor events not being reported).
- Delayed reporting: rising share of events reported more than 24 hours after occurrence; injuries first appearing as workers' compensation claims or via payroll leave.
- Clusters of reports at month-end or after audits (catch-up reporting).
- Large variation between similar sites or shifts (for example, night shift reports far fewer).
- Contractor and labour hire reporting near zero while employees report normally.
- Injury rates tied to bonuses, prizes or league tables; "zero harm" boards counting days without injury.
- Survey or interview signals: workers say reporting leads to blame, extra paperwork or no feedback.

### How to interpret near miss ratios
- Heinrich (1931) proposed 300 no-injury events : 29 minor injuries : 1 major injury. His data and definitions cannot be reviewed.
- Bird (1969), drawing on about 1.7 million incident reports from nearly 300 companies, proposed 600 near misses : 30 property damage : 10 minor injuries : 1 serious or disabling injury.
- Caveats:
  - Ratios are population averages; they vary widely by industry and hazard and do not predict any one site's numbers.
  - Reducing minor injuries does not reliably reduce serious and fatal ones. Since the 1990s injury rates have fallen faster than fatality rates in the US, and SIFs often have different causes (high energy, failed critical controls) from minor injuries (Manuele; ASSP Professional Safety review).
  - Ratios depend on reporting culture. A rising near miss ratio usually reflects better reporting, not more danger.
- Modern SIF view: stop treating the pyramid as one triangle. Separate the subset of events with SIF potential (high energy, missing direct control) and track them on their own. Measure critical control verification and HiPo learning, not total near miss counts. Use near miss volume as a culture health signal, and SIF-potential near misses as a risk signal.

Practical bands to start with (calibrate per organisation):
- Near miss + hazard reports per recordable injury: under 5 suggests under-reporting; 10 to 30 is typical of an engaged site; much higher means check quality (trivial reports).
- Share of reports classified HiPo: track trend and look for sites reporting zero HiPos with high-energy work.

Sources:
- https://aeasseincludes.assp.org/professionalsafety/pastissues/059/09/F1Reb_0914Z.pdf
- https://www.fabrico.io/blog/safety-triangle-heinrich-vs-bird/
- https://cms.eei.org/-/media/Project/EEI/Documents/Issues-and-Policy/Power-to-Prevent-SIF/eeiSCLmodel.pdf

---

## 5. What a good corrective action looks like

A corrective action is good when it changes the conditions that allowed the event, at the highest practicable level of the hierarchy, and someone proves it worked.

Test every action against:
- SMART: Specific (what, where, which plant), Measurable (how will we know it is done), Assigned (one named owner with authority), Realistic (resourced), Time-bound (due date matched to risk: critical within days, high within 30 days).
- Hierarchy level: tag each action (elimination, substitution, isolation, engineering, administrative, PPE). For HiPo and SIF events, at least one action should be at isolation or higher unless documented as not reasonably practicable.
- Linked to a cause: each action traces to an ICAM factor or why-chain finding, especially organisational factors.
- Interim controls: if the permanent fix takes time, specify what protects people until then.
- Verified effectiveness: closure requires evidence the action was done (photo, record) and, separately, a check after 30 to 90 days that it works in practice (field observation, test, data trend). Close on effectiveness, not completion.
- Shared: lessons sent to sites with the same hazard; risk register and critical control performance standards updated.

Weak vs strong examples:

| Weak | Strong |
|---|---|
| "Retrain operator." | "Install fixed barrier and gated pedestrian crossing at Dock 3 forklift aisle (engineering/isolation). Owner: DC Ops Manager. Due 15 Nov. Verify: HSE field check 30 days after install and telematics near-miss review at 90 days." |
| "Remind staff to be careful on stairs." | "Replace worn stair nosings with slip-resistant nosings on mezzanine stairs A and B (engineering). Owner: Facilities Lead. Due 30 days. Verify: slip test result and no slip incidents in 3 months." |
| "Toolbox talk on lockout." | "Fit lockable isolators and machine-specific isolation procedure on palletiser 2 (engineering plus admin). Owner: Maintenance Manager. Due 21 days. Verify: two isolation field audits per month for 3 months, 100% compliant." |

Red flags in action registers:
- Over half of actions are retrain, remind, toolbox talk, or update procedure.
- Actions closed the same day as the investigation.
- Owners are the injured worker or a role without authority or budget.
- Repeat events with the same cause after the action was "closed".

Sources:
- https://worksafe.qld.gov.au/__data/assets/pdf_file/0022/72634/how-to-manage-work-health-and-safety-risks-cop-2021.pdf (hierarchy; admin and PPE least effective)
- https://cms.eei.org/-/media/Project/EEI/Documents/Issues-and-Policy/Power-to-Prevent-SIF/eeiSCLmodel.pdf (direct controls)
