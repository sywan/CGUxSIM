# Production Prompt: CGU-SIM Briefing Package

You are working in the project folder:

`/Users/sywan/My Drive (sxw154@gmail.com)/_Sync/國際事務/MOU/SIM`

Prepare a complete briefing package for Chang Gung University (CGU) academic and administrative leadership regarding the proposed collaboration with the Singapore Institute of Management (SIM). The package must be evidence-based, operational, and task-force oriented. It must help CGU decide what to authorize, who should lead each workstream, what sequence of steps is required, what phase-based approval path is realistic, and what unresolved risks must be conquered before implementation.

This is not a generic partnership pitch. Treat the project as an implementable institutional initiative with intertwined external approvals: SIM Overseas Teaching Centre (OTC) application, Taiwan MOE permission for independent admissions if CGU recruits a distinct parallel cohort, and only then the student pathway / possible CGU-degree return model built on top of those foundations.

## Revision Requirements To Preserve

These requirements supersede any older wording in source drafts:

1. Use neutral report names such as `CGU-SIM Briefing` and `長庚大學與 SIM 合作簡報`.
   - Do not visibly frame the package as a Dean-only briefing.
   - Avoid obvious bureaucratic wording such as `Dean Briefing`, `院長簡報`, `院長裁示`, or `裁示`.
2. The briefing must be maintained as equivalent content across slide decks, React HTML, Word documents, and the public chatbot.
   - If any substantive content changes, synchronize the `.pptx`, one-page HTML, multi-file React build where applicable, `.docx` reports, the chatbot knowledge base, and this prompt.
   - The formats may adapt density and layout to their medium, but they should preserve the same decisions, risks, source posture, phase model, workstreams, and open questions.
   - The persistent public chatbot URL is `https://cgu-sim-chatbot.cguaacsb.chatgpt.site`.
   - Include a visible clickable chatbot link/button in the HTML report, slide decks, and Word reports so readers can move from static briefing formats into the Q&A assistant.
3. The React deliverable must include a self-contained one-page HTML file for convenient distribution.
   - It may also include the normal multi-file Vite build, but the one-page HTML is the primary report artifact.
   - The hero title, language control, and section index buttons must live in a persistent fixed top frame that remains visible and accessible throughout scrolling.
   - In-page navigation links must scroll to the beginning of each section title so the heading remains visible below the fixed frame.
4. The slide decks and Word reports must clearly debrief the five SIM files structurally and pedagogically:
   - how they define the collaboration architecture,
   - how they define the teaching and quality-assurance model,
   - and how those constraints shape future scheme design.
5. The timeline must be phase-based and gate-based, not a rigid week-bound or 30/60/90/180-day schedule.
6. The admissions model must be treated as a Taiwan MOE risk:
   - students would be recruited in parallel with existing `學測` / `分科考試` paths,
   - different tuition and a distinct cohort imply `獨立招生`,
   - independent admissions require Taiwan MOE approval before implementation,
   - and if either SIM OTC approval or Taiwan MOE permission fails, the student-recruitment collaboration cannot proceed as designed.
7. Public-facing slide decks, HTML reports, and Word reports must not reveal internal source-handling practices.
   - Do not mention internal transcript or media file names.
   - Do not state or imply that the June 9, 2026 conversation was recorded.
   - It is acceptable to say that factual points were based on, confirmed by, or discussed in the June 9, 2026 CGU-SIM conversation.

## Required Deliverables

Create the final deliverables as equivalent formats of the same briefing package:

1. English slide deck
   - Format: `.pptx`
   - Audience: CGU academic and administrative leadership.
   - Tone: executive, precise, implementation-oriented.

2. Traditional Chinese slide deck
   - Format: `.pptx`
   - Use Traditional Chinese for Taiwan.
   - Localize the administrative language; do not merely translate the English deck.
   - Use terms such as `推動小組`, `教務處`, `法務審閱`, `學分抵認`, `課程銜接`, `師資盤點`, `招生管道`, `獨立招生`, `教育部核准`, `待釐清事項`, `時程控管`.
   - Avoid obvious Dean-only or bureaucratic wording such as `院長裁示`.

3. React HTML briefing report with i18n, plus one-page distribution file
   - Build a React report/application, preferably under a clear app folder in this project.
   - Support `en` and `zh-TW`.
   - All user-facing strings must come from locale resources or an equivalent i18n dictionary.
   - Include a visible language switcher.
   - The first screen should be an executive dashboard/report, not a marketing landing page.
   - Include structured data for documents, workstreams, risks, decisions, timeline, and open questions.
   - Generate a self-contained one-page HTML report with inline JavaScript and CSS for distribution.
   - Ensure all in-page index links scroll to the section heading, not below the heading, in both English and Traditional Chinese modes.

4. English Word briefing report
   - Format: `.docx`
   - Use the same briefing content as the decks and HTML, adapted into a formal report/memo structure.
   - Include executive dashboard, collaboration architecture, document map, phase roadmap, workstreams, DMS modules, scenario comparison, risk register, open questions, decision agenda, and source notes.
   - Insert an upfront hyperlinked table of contents that jumps to the major report sections.

5. Traditional Chinese Word briefing report
   - Format: `.docx`
   - Use Traditional Chinese for Taiwan and localize administrative terms consistently with the Chinese slide deck.
   - Preserve the same content scope and decision posture as the English Word report, Chinese slide deck, and HTML report.
   - Insert an upfront hyperlinked table of contents that jumps to the major report sections.

6. Public shareable chatbot
   - Format: deployable web app/site.
   - Purpose: allow users who know the link to ask questions about the CGU-SIM collaboration in English or Traditional Chinese.
   - Use the same briefing content as the slide decks, HTML, and Word reports, adapted into concise conversational answers.
   - The visible top-left brand should read `CGUxSIM`.
   - i18n must be rationally consistent: when the user selects Traditional Chinese, the surrounding UI should switch to Traditional Chinese; existing English chat messages should remain in English rather than being rewritten retroactively. Future answers should follow the selected language unless the mode is `Auto`.
   - Keep the chatbot grounded in the approved public briefing package. It should state uncertainty and route unresolved items to legal, Academic Affairs, SIM, or Taiwan MOE confirmation rather than inventing answers.
   - Do not expose internal source filenames, media filenames, recording practices, or private evidence-handling notes.
   - Avoid requiring users to install anything. Prefer a public link or a self-contained static deployment when possible.

Save final user-facing deliverables in a clearly named output folder under the project root, unless an existing project convention suggests a better location.

## Primary Source Files

Use the files under `_Internal_Archive_20260711/source_materials/` as the evidence base:

1. Internal June 9, 2026 CGU-SIM conversation source material.
   - Treat this as the primary record of the conversation between Prof. Shu-Yen Wan and Jessy/Jesse Hsieh, SIM's Taiwan representative.
   - Use it internally to verify the conversation-specific facts, but do not expose internal filenames or recording practices in any public-facing slide deck, HTML report, or Word report.

2. Jesse's five follow-up files:
   - `Application Form_10Nov25.docx`
   - `Diploma_Business OTC Application Guide_11Sep2025.docx`
   - `Non-Disclosure Agreement (NDA)_One Way (V. 2023.03.03) Original Template.docx`
   - `Academic Staff Teaching Profile Form- 10162025.xlsx`
   - `Course info_Diploma in Management Studies.pdf`

3. Prior AI-generated reference drafts:
   - `SIM_Partnership_Briefing_v2.docx`
   - `SIM_合作計畫簡報_繁體中文_v2.docx`
   - Use these as reference synthesis only. Cross-check claims against the June 9 conversation source and Jesse's source files before treating them as facts.

4. Optional reference artifacts in `_Internal_Archive_20260711/generated_working_files/Presentation/`
   - Existing slides/images may be useful for visual or storyline reference, but do not let them override the source documents.

## Core Storyline To Preserve

The briefing must separate two linked but different initiatives:

1. Foundation layer: CGU becoming a SIM Overseas Teaching Centre (OTC)
   - CGU would apply to offer SIM diploma modules in Taiwan under SIM quality standards.
   - SIM documents define this as an OTC application process.
   - This is the near-term administrative project and the first gate.

2. Strategic pathway layer: CGU admissions + SIM diploma + overseas partner bachelor's pathway + optional CGU degree
   - CGU may recruit a distinct cohort in parallel with existing `學測` / `分科考試` routes.
   - Because the cohort may have different tuition and a distinct admissions model, CGU should treat this as `獨立招生` requiring Taiwan MOE permission.
   - Students begin as registered CGU freshmen.
   - SIM would issue an additional offer.
   - Students may study an initial portion at CGU, then move to SIM Singapore and onward into SIM partner university bachelor's programmes.
   - The CGU degree is optional and depends on CGU/Taiwan credit and residence requirements.
   - This pathway is strategically valuable for recruitment quality, but it creates credit-recognition, student-status, scheduling, legal, admissions-approval, tuition, and marketing constraints.

3. Regulatory layer: Taiwan MOE admissions approval
   - Taiwan University Act Article 24 requires university admissions rules, including single-school admissions rules, to be drafted by the university and approved by the Ministry of Education before implementation.
   - The CGU-SIM student pathway must be treated as a dual-gate project: SIM OTC approval and Taiwan MOE admissions permission must both clear before recruitment can proceed.

Do not present the collaboration as already finalized. Present it as a feasible but multi-gate project requiring leadership authorization and task-force execution.

## Verified Facts From The June 9 Conversation

Use the following facts explicitly and accurately:

1. Admissions and student status
   - The proposed route would recruit students in parallel with CGU's regular `學測` / `分科考試` paths and should be treated as an independent admissions model unless CGU obtains a different formal interpretation.
   - Because the students may pay different tuition and join a distinct CGU-SIM cohort, CGU must evaluate the Taiwan MOE approval route before any recruitment claim.
   - Students would enter initially as registered CGU students.
   - SIM would need to issue an additional offer.
   - If students later go to Singapore, active CGU student-status handling is unresolved and likely requires leave of absence or withdrawal unless the student returns for a CGU degree.
   - If students do not seek a CGU degree, they may simply continue as SIM students after the CGU phase.

2. CGU degree and dual-degree logic
   - CGU's key constraint is that students must complete at least half of the required credits at CGU/Taiwan to receive a CGU degree.
   - A simple 1+3 model is unlikely to satisfy CGU/Taiwan requirements if the student wants a CGU degree.
   - A possible route discussed: approximately 0.5 year at CGU, approximately 2.5 years at SIM / partner university, then return to CGU for roughly 1.5 years or enough credits to meet the CGU requirement.
   - The unresolved internal question: whether the relevant rule is measured by elapsed study time or by credits completed.
   - CGU leadership needs to understand that the CGU degree should be positioned as optional unless/until CGU confirms the credit/time rule and internal approval pathway.

3. MOU/signature scope
   - Jessy indicated that CGU would need to sign with SIM only, not necessarily with downstream UK/Australian partner universities.
   - This should still be treated as a fact from the conversation and a legal/academic point to verify before formal commitment.

4. Teaching model discussed
   - The SIM diploma has a fixed sequence of 15 modules.
   - CGU may teach the first 6 to 9 modules.
   - For a 42-contact-hour module, the conversation described an approximate 50/50 split: about half taught face-to-face by CGU faculty and about half delivered online/synchronously with SIM.
   - CGU would provide the local teaching faculty.
   - Exams would be held at CGU; exam papers are expected to come from SIM.
   - Whether marked scripts must be returned to Singapore remains unresolved and should be flagged as an operational question for SIM.

5. Scheduling constraints
   - SIM uses a compact cycle: roughly three months per term, with teaching concentrated in the first two months and a break in the third month.
   - The first three modules may be completed in roughly eight weeks.
   - Because online/synchronous portions must align with SIM's schedule, CGU cannot freely compress or reorder all delivery without SIM agreement.
   - A CGU cohort may finish local face-to-face hours before SIM synchronous sessions are available; credit posting may need to wait until the SIM-linked component is complete.

6. CGU credit conversion
   - CGU's baseline discussed in the June 9 conversation: 1 credit equals one contact hour per week over 18 weeks, i.e. 18 hours.
   - CGU currently uses a 16+2 model: 16 weeks of instruction/assessment plus 2 weeks of self-directed learning with no performance evaluation.
   - Prof. Wan proposed mapping SIM contact hours into CGU credit units, possibly using micro-courses around 18 hours each.
   - This needs confirmation from CGU Academic Affairs.

7. Credit recovery for students who stay at CGU
   - If a student starts the SIM pathway but later stays at CGU, the SIM modules taught at CGU should not become wasted learning.
   - Two possible mechanisms were discussed:
     - Build those modules into CGU required-course objectives.
     - Create a course-equivalence / credit-exemption (`抵修`) mapping between SIM modules and CGU courses.
   - Jessy agreed to provide module lists and syllabi for mapping.

8. Strategic recruitment rationale
   - CGU's goal is not merely filling seats; CGU wants to attract stronger students.
   - The pathway may appeal to students/families who want an overseas degree route but prefer a safer first stage in Taiwan.
   - SIM observed demand from families whose students first enter a Taiwan university and then transfer abroad, but often lose the Taiwan first-year credits. The CGU-SIM pathway could reduce that waste if the CGU courses are SIM-recognized modules rather than general education.
   - Student retention and eventual CGU-degree completion matter, but may be a secondary metric in this strategy.

9. Potential Taiwan MOE co-teaching angle
   - The synchronous online component may align with Taiwan MOE's `共授` concept, especially if students and faculty on both sides participate.
   - The current policy framing may focus on foreign universities rather than SIM-like institutions, so this is a possible strategic argument, not a confirmed benefit.

10. Taiwan MOE independent-admissions gate
   - Taiwan University Act Article 24 states that university admissions should be handled under fair, just, and public principles, either independently or jointly with other universities.
   - It also states that admissions rules, including admissions method, quotas, applicant-status recognition, grade review, appeals, and other required matters, are drafted by the university and implemented only after MOE approval.
   - This confirms the user's concern: if CGU recruits a distinct cohort in parallel with regular admissions paths and different tuition, the `獨立招生` route is a high-risk external approval gate.
   - The SIM OTC application process and Taiwan MOE admissions-permission process are intertwined; failure of either gate blocks the student-recruitment collaboration as designed.

## Verified Facts From Jesse's Documents

Use these facts and cite the source file in internal notes and, where appropriate, deck appendices.

### `Diploma_Business OTC Application Guide_11Sep2025.docx`

1. SIM's DMS, DIB, DBF, and DAC programmes may be offered through Overseas Teaching Centres.
2. Programmes offered through OTCs are described as identical to those at SIM Singapore, with the same entry/exit requirements and the same qualification rights upon completion.
3. Interested OTCs must submit a completed Application Form with required supporting documents.
4. SIM evaluates the OTC's suitability, including quality standards and compliance with relevant legislative requirements.
5. The OTC must provide academic delivery in its home country plus logistical and administrative support for students.
6. The OTC must document that its teaching site meets regulatory and legislative requirements.
7. Application procedure:
   - OTC submits application.
   - SIM reviews completeness and may request clarifications.
   - SIM-appointed staff conduct an onsite audit visit; fees, if any, are borne by the applicant OTC.
   - Teaching staff review is conducted online using the Academic Teaching Staff Profile Information Form.
   - SIM assesses findings and makes the final decision.
8. If approved, a formal agreement must be signed by all required parties within 180 days from the date of SIM approval.
9. After one cohort completes, the OTC provides documentation and facilitates onsite accreditation, subject to operational requirements and minimum cohort size. SIM may use remote or desk-based verification if onsite accreditation is not feasible.
10. SIM conducts an annual progress/development review after programme commencement, coordinated with the appointed Administrative Staff and Academic Head.
11. Annexes 1 to 3 are available only after signing the NDA:
   - Annex 1: Details on Programme Delivery
   - Annex 2: Teaching Centre's Deliverables
   - Annex 3: SIM's Roles & Responsibilities

### `Application Form_10Nov25.docx`

The Application Form is the formal OTC application and requires CGU to prepare evidence in six major areas:

1. Section 1: Overseas Teaching Centre Information
   - English and Chinese registered names.
   - Registered address and teaching-site address.
   - License/registration type, number, validity, and supporting certificate.
   - Programme(s) applied for.
   - For Diploma in Management Studies (DMS), Diploma in Accounting (DAC), Diploma in Banking and Finance (DBF), and Diploma in International Business (DIB), the form includes 6-module and 9-module options.
   - Applicant, agreement/contract signatory, and SIM-notice liaison details.
   - Proof of signatory authority is required.

2. Section 2: Current Programmes Offered
   - Existing local and international programmes.
   - Progression pathways and destination institutions/countries.
   - Annual enrolment size.
   - Website links or marketing materials.

3. Section 3: Delivery of SIM Programmes
   - Rationale for offering SIM programmes.
   - Student profile and target groups.
   - Expected proportion progressing to SIM Singapore.
   - Counselling and support for progression decisions.
   - Academic-year structure.
   - How face-to-face and online components will be scheduled.
   - How written assessments will be conducted at the OTC.
   - Contingency plan for programme disruption/default.
   - Teaching pedagogy, additional academic support, attendance monitoring, and intervention for underperforming students.
   - Marketing/recruitment strategy.
   - April and October intake projections, three-year intake projections, and first-intake commencement date.

4. Section 4: Staffing
   - Academic staff assigned to SIM programme delivery.
   - Academic Director and academic liaison with SIM.
   - CVs and justifications for appointments.
   - Academic Staff Teaching Profile Forms.
   - Administrative support staff responsible for student registration, class scheduling, and onsite accreditation coordination.

5. Section 5: Facilities and Resources
   - Classrooms, learning resources, support services, and planned resources.

6. Section 6: Additional Information
   - OTC strengths, achievements, and strategic plans relevant to SIM programmes.

Appendix A includes SIM's blended learning model:

- Diploma (DAC / DBF / DIB / DMS): 630 total contact hours, 42 standard contact hours per module.
- For Diploma (DAC / DBF / DIB / DMS), Appendix A states:
  - SIM delivery per module: Non-exam 18 hours / Exam 24 hours.
  - OTC delivery per module: Non-exam 24 hours / Exam 18 hours.
- This differs slightly from the June 9 conversation's approximate 21/21 description. The briefing should flag the need to reconcile the exact delivery split with SIM after the NDA annexes are released.

### `Course info_Diploma in Management Studies.pdf`

Use this as the official course-information source for DMS:

1. DMS is a 15-month full-time programme.
2. DMS includes 15 modules/subjects.
3. Total contact hours: 630.
4. Standard contact hours: 42 per module.
5. Programme aims:
   - Broad-based training in management, finance, accountancy, marketing, economics, statistics, mathematics, law, and information technology.
   - Effective verbal and written communication.
   - Teamwork.
   - Use of computer tools in decision-making/problem-solving.
6. Module list from the PDF:
   - English For Business
   - Business Communications
   - Business Mathematics
   - Microeconomics
   - Macroeconomics
   - Business Law
   - Business Statistics
   - Operations Management
   - Managerial Accounting
   - Information Systems for Business
   - Financial Accounting
   - Principles of Marketing
   - Managing Human Resources
   - Managing People and Organisations
   - Business Finance
7. Course relevance to CGU:
   - `Information Systems for Business` and `Business Statistics` are directly relevant to Information Management strengths.
   - Accounting, finance, marketing, HR, and operations modules require broader Management College faculty mapping, not only Information Management.

Important discrepancy to resolve:

- The DMS module sequence in the PDF differs from the DMS module order shown in the `Data` sheet of `Academic Staff Teaching Profile Form- 10162025.xlsx`, where DMS modules are listed as:
  - Business Statistics
  - English for Business
  - Financial Accounting
  - Business Communications
  - Business Mathematics
  - Microeconomics
  - Business Finance
  - Managerial Accounting
  - Managing Human Resources
- The briefing should not assume a final CGU teaching sequence until SIM confirms which sequence and which 6 or 9 modules apply to CGU.

### `Academic Staff Teaching Profile Form- 10162025.xlsx`

Use this as the staffing-readiness source:

1. The workbook contains a Summary sheet and Profile sheets for up to five academic teaching staff.
2. Each teacher profile requests:
   - Personal details.
   - Citizenship/nationality.
   - SIM modules to be taught.
   - Work experience and current teaching institution.
   - Academic qualifications.
   - English language proficiency.
3. The form states each teacher is strictly limited to a maximum of two modules.
4. The Summary sheet asks for module assignments, years of experience, highest qualification, awarding institution, and current teaching institute.
5. Supporting documents are compulsory:
   - Academic qualification certificates.
   - Transcripts.
6. The Application Form warns incomplete submissions will prevent the interview/review from proceeding.
7. Staffing implication:
   - If CGU teaches 6 modules, at least 3 qualified teachers are needed.
   - If CGU teaches 9 modules, at least 5 qualified teachers are needed, assuming no teacher exceeds two modules.
   - This is likely a critical bottleneck because English-medium teaching capability must be confirmed.

### `Non-Disclosure Agreement (NDA)_One Way (V. 2023.03.03) Original Template.docx`

Use this as the legal-gate source:

1. The NDA is one-way: CGU, as receiving party, protects SIM confidential information.
2. The NDA must be signed before SIM releases Annexes 1 to 3.
3. It covers confidential information relating to SIM, partner organizations, students, teaching staff, employees, customers, suppliers, products, policies, financial/accounting information, and other business affairs.
4. Confidential information may be used only for preparing/evaluating the proposal.
5. Access must be limited to need-to-know representatives.
6. The receiving party is responsible for representative breaches.
7. Copying/reproduction is limited to what is necessary.
8. SIM may request return or destruction of confidential information and written certification.
9. No news release, publicity, marketing material, reference, statement, announcement, confirmation, or denial about the proposal or NDA may be made without SIM's express written permission.
10. PDPA compliance is required when handling personal data.
11. Governing law: Singapore law.
12. Jurisdiction: exclusive jurisdiction of Singapore courts.
13. Confidentiality obligations continue for seven years after completion of the final deliverable and after confidential information is returned/destroyed.
14. The NDA states that no joint venture or partnership is created and neither party is obligated to proceed.
15. Fields to fill include date, project description, receiving party legal name, signatory name/designation/place/date/company stamp.
16. Briefing implication:
   - Legal review is an immediate gate.
   - Marketing/recruitment plans cannot publicly name SIM until written permission is secured.
   - CGU must designate an authorized signatory and internal confidentiality controls.

## Required Analytical Outputs Inside The Briefing

The decks and React report must include these analytical artifacts:

1. Decision agenda for CGU leadership
   - Approve creation of a CGU-SIM task force.
   - Decide whether to proceed with NDA legal review and signature.
   - Assign an authorized signatory and proof-of-authority owner.
   - Decide the initial programme scope: likely DMS first, with 6-module vs 9-module scenario comparison.
   - Authorize Academic Affairs consultation on credit/time rules, course mapping, and student-status handling.
   - Authorize admissions / MOE compliance assessment for `獨立招生`, tuition, quota, student-status disclosure, and application route.
   - Authorize staffing inventory and English-medium teaching readiness review.
   - Authorize SIM follow-up questions after NDA annexes are available.
   - Decide whether/how to explore the optional CGU-degree pathway.

2. Workstream model
   - Executive sponsor: project sponsor or designated lead.
   - Academic lead: department/college academic owner for DMS mapping and faculty assignment.
   - Academic Affairs lead: credit conversion, `抵修`, CGU degree eligibility, student status, 16+2 / micro-course handling.
   - Admissions / MOE compliance lead: independent admissions rationale, tuition/quota framing, MOE consultation and submission path.
   - Legal lead: NDA, Singapore jurisdiction, PDPA, no-publicity clause, formal agreement.
   - International affairs / SIM liaison: communication with Jessy/SIM, MOU/agreement coordination.
   - Staffing lead: teaching-profile forms, CVs, certificates/transcripts, English proficiency.
   - Operations lead: scheduling, classroom/facility evidence, assessment logistics, accreditation visit preparation.
   - Recruitment/advising lead: `學測` track, student/family messaging, progression counselling, no-publicity compliance.
   - Finance/business-case lead: fees, revenue share, onsite audit costs, student pricing, sustainability.

3. Timeline
   - Phase 0: Internal alignment.
   - Phase 1: Legal and policy framing before external commitments.
   - Phase 2: SIM clarification and MOE admissions design after initial authorization.
   - Phase 3: Evidence pack and staffing build.
   - Phase 4: Parallel external review by SIM and Taiwan MOE.
   - Phase 5: Formal agreement and launch permission after both approvals.
   - Phase 6: Pre-launch recruitment/advising/operations after internal, SIM, and MOE approvals.
   - Phase 7: First-cohort delivery, post-cohort accreditation, and annual review.

4. Scenario comparison
   - Scenario A: OTC-only pilot / DMS modules at CGU.
   - Scenario B: OTC + SIM Singapore progression after 6 modules.
   - Scenario C: OTC + SIM Singapore progression after 9 modules.
   - Scenario D: Optional CGU degree return path after overseas partner degree.
   - Compare each on student value, CGU value, approvals, staffing load, credit complexity, timeline, and risk.

5. Risk register
   Include at least these risks:
   - Taiwan MOE may reject the independent admissions proposal; without MOE permission, the student-recruitment collaboration cannot proceed as designed.
   - CGU/Taiwan credit/time requirement may prevent an easy dual-degree story.
   - Student status during overseas phase may require leave/withdrawal and careful advising.
   - NDA no-publicity clause may constrain recruitment communications.
   - Singapore governing law / jurisdiction may require legal escalation.
   - Exact blended delivery split remains locked behind NDA annexes and must be reconciled with the June 9 conversation notes.
   - Module sequence discrepancy between DMS PDF and xlsx Data sheet.
   - Faculty bottleneck: max two modules per teacher; 6-9 modules require 3-5 qualified English-capable faculty.
   - Synchronous online schedule may not align cleanly with CGU semesters.
   - Exam marking/script-return logistics remain unresolved.
   - Fees/revenue-share/business model remains unavailable until annexes are released.
   - Onsite audit fees and accreditation requirements may create cost and timing uncertainty.
   - Minimum cohort size for post-cohort accreditation is unspecified.
   - Public claims about SIM/partner universities require written permission and careful verification.

6. Open-question log
   Separate questions by owner:
   - CGU Academic Affairs:
     - Is the CGU degree requirement measured by credits, elapsed time, residency, or a combination?
     - Can SIM contact hours be mapped into CGU credits or micro-courses?
     - Can SIM modules be embedded into required-course objectives or handled via `抵修`?
     - What student status applies when a student leaves for SIM?
   - CGU Legal:
     - Is Singapore governing law and exclusive jurisdiction acceptable?
     - Who can sign the NDA and later formal agreement?
     - What internal confidentiality controls are needed?
   - Admissions / MOE compliance:
     - Does the different tuition and parallel recruitment model require an independent admissions application?
     - What MOE approval route is viable for a programme-specific CGU-SIM cohort?
     - How should quotas, tuition, student status, SIM offer, and overseas progression be disclosed?
     - What happens to the SIM application work if MOE declines the admissions proposal?
   - SIM/Jessy:
     - Which DMS module sequence should CGU use?
     - Which 6 or 9 modules are eligible for CGU delivery?
     - What is the exact split of SIM vs OTC hours for exam and non-exam modules?
     - How flexible are synchronous online sessions for a Taiwan cohort?
     - Who marks exams, and must scripts be returned to Singapore?
     - What are fee/revenue-share terms?
     - What is the minimum cohort size for accreditation?
     - What written permission is needed for recruitment materials?
   - College leadership:
     - Is DMS the initial target, or should DAC/DBF/DIB/DIT/GDBA be considered later?
     - Which departments can provide qualified English-medium faculty?
     - What level of recruitment/retention tradeoff is acceptable?

7. Document checklist
   Include a table with source document, required CGU action, owner, dependencies, and deadline.

8. Faculty-readiness matrix
   Include columns:
   - SIM module.
   - Possible CGU equivalent course.
   - Potential CGU faculty.
   - English-medium readiness.
   - Qualification evidence needed.
   - Academic transcript/certificate status.
   - Risk level.

9. Leadership-ready recommendation
   The recommendation should be sober and concrete:
   - Proceed with a structured feasibility/application phase, not public launch.
   - Start with DMS and compare 6-module vs 9-module models.
   - Treat the optional CGU-degree path as a second-stage design pending Academic Affairs confirmation.
   - Sign/review NDA only after legal review and internal signatory approval.
   - Run SIM review and Taiwan MOE admissions-permission work as intertwined applications.

## Recommended Slide Deck Structure

Suggested length: 14-18 main slides, with appendices as needed.

English deck:

1. Title: CGU-SIM Collaboration Briefing: OTC Application And Student Pathway Design
2. Executive Decision Summary
3. What Is Actually On The Table: OTC Foundation Plus Regulated Admissions Path
4. Why This Matters To CGU: Recruitment Quality And Internationalization
5. Two External Approvals: SIM OTC And Taiwan MOE Admissions Permission
6. Five SIM Documents Define The Collaboration Structure
7. The SIM Documents Also Define The Pedagogical Model CGU Must Test
8. Proposed Student Journey And Where It Is Confirmed vs Unresolved
9. SIM OTC Application Process And Gates
10. DMS Programme Facts: 15 Months, 15 Modules, 630 Contact Hours
11. 6-Module vs 9-Module CGU Delivery Scenarios
12. Credit, Student-Status, And CGU-Degree Constraints
13. Required Documents And Evidence CGU Must Prepare
14. Staffing Requirements And Faculty Bottlenecks
15. Implementation Workstreams And Owners
16. Phase-Based Roadmap And Approval Gates
17. Risk Register And Mitigation Plan
18. Open Questions For CGU And SIM
19. Decisions Requested From CGU Leadership
20. Immediate Next Actions By Phase
21. Appendix: Source Notes, Module List, Document Checklist

Traditional Chinese deck:

1. 標題：長庚大學與 SIM 合作簡報：海外教學中心申請與學生銜接路徑
2. 決策摘要
3. 本案實質內容：OTC 基礎加上受規範的招生路徑
4. 對長庚的策略意義：招生品質與國際化
5. 兩個外部核准：SIM OTC 與台灣教育部招生核准
6. SIM 五份文件共同定義合作結構
7. 五份文件也定義需要測試的教學模式
8. 學生路徑構想：已確認事項與待釐清事項
9. SIM 海外教學中心申請流程與關卡
10. DMS 課程事實：15 個月、15 門課、630 接觸學時
11. 長庚開授 6 門與 9 門課之情境比較
12. 學分、學籍與長庚學位限制
13. 長庚需備齊之文件與佐證
14. 師資需求與可能瓶頸
15. 推動小組工作分工
16. 階段式推動路線與核准關卡
17. 風險登錄與因應策略
18. 長庚與 SIM 待釐清問題
19. 需決策事項
20. 立即行動項目
21. 附錄：資料來源、課程清單、文件清單

## React HTML Report Requirements

Build an executive dashboard/report with the following sections:

1. Executive dashboard
   - Current project stage.
   - Recommended next decision.
   - Top five risks.
   - Near-term actions by phase.

2. Collaboration architecture
   - Visual or structured explanation of OTC layer, admissions/MOE regulatory layer, and pathway layer.
   - Confirmed vs unresolved markers.

3. Document map
   - Guide, Application Form, DMS course info, Teaching Profile Form, NDA, prior drafts.
   - Show role, owner, required action, status, dependency.

4. Timeline
   - Phase-based roadmap from internal alignment to post-cohort accreditation.
   - Do not use rigid week-bound or 30/60/90 labels in visible timeline copy.

5. Workstreams
   - Owner matrix with expected deliverables and decision rights.

6. DMS modules
   - Module list and contact-hour facts.
   - Include warning that module sequence must be confirmed because the PDF and xlsx list differ.

7. Scenario comparison
   - 6 modules vs 9 modules vs optional CGU-degree return path.

8. Risk register
   - Severity, likelihood, mitigation, owner, next action.

9. Open questions
   - Group by CGU Academic Affairs, Admissions / MOE compliance, Legal, SIM/Jessy, and College leadership.

10. Decision agenda
   - What CGU leadership should approve now, defer, or ask the task force to verify.

Technical expectations:

- Use structured data files such as `src/data/*.ts` or `src/data/*.json`.
- Use locale files such as `src/locales/en.ts` and `src/locales/zh-TW.ts`.
- No hardcoded visible strings inside components.
- Include responsive layout for desktop and mobile.
- Use clear professional UI: tables, timelines, status tags, tabs/segmented controls.
- Avoid a marketing-style hero page or decorative filler.
- Generate a one-page HTML output by inlining the built JavaScript and CSS.
- Make in-page navigation anchors land at the top of the section heading with the title visible below sticky navigation.
- Run build/lint checks if available.
- Verify both language modes render correctly.

## Content Quality Rules

1. Be candid about uncertainty.
   - Mark items as `Confirmed by June 9 conversation`, `Confirmed by SIM document`, `Prior draft only`, `Assumption`, `Pending SIM`, or `Pending CGU`.

2. Do not overclaim partner university details.
   - If mentioning University of London, LSE, UK/Australian partners, grade requirements, or articulation guarantees, verify from source materials or clearly mark as requiring confirmation.

3. Do not write as if the project is approved.
   - The correct posture is: "feasible pathway requiring staged approvals."

4. Make the leadership decision role explicit without using Dean-only framing.
   - CGU leadership should see which decisions need authority, which tasks can be delegated, and which issues require external confirmation.

5. Make implementation concrete.
   - Every workstream should have an owner, first deliverable, dependency, and deadline.

6. Use bilingual administrative precision.
   - English should be executive and direct.
   - Traditional Chinese should sound like a Taiwan university internal briefing.

7. Avoid superficial partnership language.
   - No generic claims such as "enhance global competitiveness" unless tied to a concrete action, risk, or metric.

8. Cite source files in appendices or source notes.
   - The audience does not need dense footnotes on every slide, but major claims must be traceable.

## Suggested Workflow

1. Inventory source files in `_Internal_Archive_20260711/source_materials/`.
2. Extract source notes into a structured table:
   - claim
   - source file
   - evidence excerpt or paraphrase
   - status
   - briefing implication
3. Build the decision agenda, risk register, workstream matrix, and timeline before writing slides.
4. Draft the English storyline.
5. Draft the Traditional Chinese storyline using localized university-administration wording.
6. Generate English `.pptx`.
7. Generate Traditional Chinese `.pptx`.
8. Build React i18n report.
9. Visually verify slides.
10. Run and inspect React report in both languages.
11. Final response should list generated files, source gaps, assumptions, checks performed, and recommended next human action.

## Final Response Format

When the work is complete, provide:

1. Links/paths to the English slide deck, Traditional Chinese slide deck, and React report.
2. Brief summary of the briefing package.
3. Assumptions and unresolved questions.
4. Checks performed.
5. Recommended next human action for CGU.
