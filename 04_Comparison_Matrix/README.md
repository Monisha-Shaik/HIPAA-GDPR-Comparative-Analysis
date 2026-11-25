# HIPAA and GDPR Comparison Matrix

Read all 45 comparisons across eight categories below without downloading the workbook.

[Download the Excel matrix](HIPAA_GDPR_Comparison_Matrix.xlsx)

Scope: federal HIPAA and GDPR health-data privacy/security as of October 31, 2026. Earlier law establishes the baseline. Post-cutoff developments are labelled separately. More protective state laws and 42 CFR Part 2 may apply alongside HIPAA; this matrix does not comprehensively compare them. Part 2-related HIPAA notice duties are identified where relevant (45 CFR § 160.203; sources HIPAA-27 and HIPAA-32).

This page reproduces the uploaded workbook. Each topic includes its requirements, provisions, source IDs, legal status, proposed changes, similarities and differences, and practical implications. Source URLs appear in full in the source list.

Historical source basis: Parts 160 and 164 were checked using user-supplied eCFR text captures displaying the version in effect on October 31, 2026. Court-affected provisions are read with the cited judicial and HHS materials. Proposed and post-cutoff developments are identified separately.

## Contents

- [Regulatory Scope](#regulatory-scope)
- [Privacy requirements](#privacy-requirements)
- [Security safeguards](#security-safeguards)
- [Risk management](#risk-management)
- [Third-party responsibilities](#third-party-responsibilities)
- [Breach notification](#breach-notification)
- [Enforcement](#enforcement)
- [Penalties](#penalties)
- [Sources](#sources)

## Regulatory Scope

### Organizations covered

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Covered entities include health plans, health care clearinghouses, and providers that electronically conduct covered transactions. Business associates include persons handling PHI on behalf of a covered entity for covered functions or services, including qualifying subcontractors. |
| GDPR requirement | Within GDPR scope, controllers determine the purposes and means of processing personal data. Processors handle personal data on a controller’s behalf. These roles apply across sectors, subject to material and territorial scope and exclusions. |
| Supporting provisions | HIPAA<br>45 CFR § 160.103. Definitions of covered entity and business associate.<br>GDPR<br>Articles 2, 3, 4(7) and 4(8). |
| Source IDs | HIPAA: HIPAA-01, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC2-Final |
| Legal status | HIPAA cited definitions applicable. GDPR cited definitions and scope provisions applicable as of October 31, 2026. Post-cutoff PC2 finalisation is separately identified in the proposed-change column; it does not replace the October baseline. |
| Relevant proposed change | No replacement of the listed role definitions is identified in selected proposals. After cutoff: the November 2026 HIPAA final rule excludes qualifying telecommunications-relay-service providers from the BA definition (PC2-Final, § IV.H). |
| Similarities and differences | Similarity: Both assign data-protection duties to organizations and service providers.<br><br>Difference: HIPAA uses covered entity and business associate categories. GDPR assigns controller and processor roles across sectors according to processing activities, within its scope. |
| Practical implications | Map each party’s activity before assigning duties. A consumer health app may fall outside HIPAA when it serves individuals independently, while its processing can fall within GDPR if the scope conditions are met. |

### Information protected

| Field | Comparison |
| --- | --- |
| HIPAA requirement | PHI is individually identifiable health information transmitted or maintained in any form, within HIPAA coverage. Exclusions include specified education records, employment records held as employer, and information about persons deceased for more than 50 years. Electronic PHI is the electronic subset. |
| GDPR requirement | Personal data concerns an identified or identifiable natural person. Health data includes information about physical or mental health, including health services, that reveals health status. Article 2 covers automated processing and nonautomated processing in or intended for a filing system. Article 9 gives health data special-category protection. |
| Supporting provisions | HIPAA<br>45 CFR § 160.103. Definitions of individually identifiable health information, PHI and electronic PHI.<br>GDPR<br>Articles 2(1)–(2), 4(1), 4(6), 4(15) and 9(1). |
| Source IDs | HIPAA: HIPAA-01, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA cited PHI definitions applicable. GDPR cited provisions applicable. PC3 scope-related changes remain proposed at the cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3: Council identifiability and pseudonymisation provisions, Article 3(1) and (10), pp. 131 and 140–141. Read against PC3-Base; Council negotiating text is not law. |
| Similarities and differences | Similarity: Both protect identifiable health information within their scope.<br><br>Difference: HIPAA protects PHI in covered relationships. GDPR covers personal data more broadly and treats health data as a special category. |
| Practical implications | Classify the data and the processing context separately. Paper records may qualify under both frameworks, while GDPR’s nonautomated records must meet its filing-system condition. Assess electronic PHI separately when applying the HIPAA Security Rule. |

### Territorial reach

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HIPAA duties follow covered entity and business associate relationships. HHS permits a cloud provider to store electronic PHI outside the United States when the required business associate agreement and applicable HIPAA safeguards are in place. Geographic risks must be considered. |
| GDPR requirement | Article 3 covers processing in the context of an EU establishment, wherever processing occurs. It also covers relevant processing by organizations outside the EU when offering goods or services to people in the EU or monitoring their behaviour there. Article 3(3) addresses places where Member State law applies through public international law. |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.103, 164.308(a)(1)(ii)(A) and 164.502(e). HHS Cloud Computing Guidance, question 9.<br>GDPR<br>Article 3(1)–(3). EDPB Guidelines 3/2018 on territorial scope, final version 2.1. |
| Source IDs | HIPAA: HIPAA-02, HIPAA-27<br>GDPR: GDPR-01, GDPR-02<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Cited HIPAA requirements and GDPR Article 3 applicable at the cutoff. HHS and EDPB documents provide interpretive guidance. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | No direct amendment to GDPR Article 3 or the cited overseas-cloud principle identified in PC1–PC3. |
| Similarities and differences | Similarity: Both can affect health-data processing involving service providers outside their home jurisdiction.<br><br>Difference: HIPAA duties follow covered relationships. GDPR expressly uses establishment and EU targeting or monitoring criteria; citizenship alone does not determine coverage. |
| Practical implications | Assess each workflow and service relationship. A U.S. healthcare organization targeting services to people in the EU may need to meet both frameworks. Document overseas processing locations and assess international transfer requirements separately. |

## Privacy requirements

### Permitted uses and authorization or consent

| Field | Comparison |
| --- | --- |
| HIPAA requirement | A covered entity may use or disclose PHI as the Privacy Rule permits or requires, or under a valid written authorization. Treatment, payment and health care operations generally have permitted pathways without authorization, subject to the applicable conditions and exceptions. Other uses may require authorization. |
| GDPR requirement | Processing personal health data requires an Article 6 lawful basis and an Article 9 condition. Explicit consent is one possible Article 9 condition. Health care and qualifying research may rely on other conditions when their requirements are met. Consent-based processing must satisfy Article 7. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.502(a), 164.506, 164.508 and 164.512(i).<br>GDPR<br>Articles 5(1)(b), 6, 7 and 9(2)–(3). |
| Source IDs | HIPAA: HIPAA-03, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC2-Final, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. Post-cutoff PC2 finalisation is separately identified in the proposed-change column; it does not replace the October baseline. |
| Relevant proposed change | At cutoff: PC2 proposed care-coordination permissions; PC3 addresses research compatibility and incidental sensitive data in AI (Article 3(2)–(3), pp. 132–133). After cutoff: PC2-Final adopts modified care-coordination provisions (§ IV.C, E); the October baseline is unchanged. |
| Similarities and differences | Similarity: Both require a valid legal route for using or sharing health information.<br><br>Difference: HIPAA specifies permitted uses and disclosures and when authorization is required. GDPR requires an Article 6 basis and an Article 9 condition for health data; consent is one possible route. |
| Practical implications | Document the purpose and applicable route for each use. A hospital planning secondary research or vendor reuse must assess that activity separately from the original care purpose. |

### Patient access to records and personal data

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Individuals generally may inspect and obtain PHI in designated record sets, subject to exclusions and permitted denials. At the cutoff, act within 30 days, with one additional 30-day extension on timely written notice. Copy fees must be reasonable and cost-based, limited to permitted copying, supplies, postage and agreed summary costs; inspection is not a chargeable copy service. |
| GDPR requirement | Article 15 provides access, a copy and processing information, respecting others’ rights. Respond without undue delay and normally within one month; up to two further months may be added where necessary, with notice and reasons within the first month. The first copy is generally free; additional copies and manifestly unfounded or excessive requests have specified fee rules. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.501, 164.524(a), (b)(2), (c)(4).<br>GDPR<br>Articles 12(3), 12(5), 15(1)–(4) and 23. |
| Source IDs | HIPAA: HIPAA-04, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC2-Final, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. Post-cutoff PC2 finalisation is separately identified in the proposed-change column; it does not replace the October baseline. |
| Relevant proposed change | At cutoff: PC2 proposed 15 days plus one 15-day extension; PC3 changes request handling (Article 3(4), p. 134). After cutoff: PC2-Final adopts 15 days plus one 30-day extension (§ IV.A.4), effective January 19, 2027; compliance July 19, 2027. |
| Similarities and differences | Similarity: Both give individuals access to information about them and regulate response procedures and fees.<br><br>Difference: HIPAA uses designated record sets, a 30-day baseline and permitted cost-based copy fees. GDPR covers personal data and processing information, uses one month as the usual deadline and generally makes the first copy free. |
| Practical implications | Map where records and personal data are held, including with vendors. A response may require retrieving information beyond the main EHR. Apply the relevant exclusions or restrictions to the particular request. |

### Correction and amendment

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Individuals may request amendment of PHI in designated record sets. Act within 60 days, with one additional 30-day extension on timely written notice. Specified denials are allowed, including accurate and complete records; accepted amendments are appended or linked. A written denial permits a statement of disagreement. |
| GDPR requirement | Article 16 gives individuals a right to rectification of inaccurate personal data without undue delay and completion of incomplete data, taking account of the processing purpose. Article 19 generally requires communicating rectification to recipients unless impossible or disproportionate. Article 12(3) requires information on action without undue delay and within one month, extendable by two months where necessary, with timely reasons. Article 16 separately requires rectification without undue delay. |
| Supporting provisions | HIPAA<br>45 CFR § 164.526(a)–(d), especially (b)(2).<br>GDPR<br>Articles 12(3)–(4), 16 and 19. |
| Source IDs | HIPAA: HIPAA-03, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 request-handling amendment: Article 3(4), p. 134. No replacement of the baseline rectification right is identified; Council mandate, not law. |
| Similarities and differences | Similarity: Both provide a process for addressing inaccurate or incomplete information.<br><br>Difference: HIPAA specifies amendment requests, permitted denials and statements of disagreement. GDPR provides rectification and completion rights, with duties to inform recipients subject to exceptions. |
| Practical implications | Provide a documented correction process and assess which recipients need the update. For a disputed clinical entry, preserve the context and apply the framework’s amendment or rectification rules. |

### Erasure and retention

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HIPAA provides no general individual right to erase medical records and sets no general medical-record retention period. Other laws may require retention. Separately, required HIPAA privacy and security documentation must generally be retained for six years from creation or when last in effect, whichever is later. |
| GDPR requirement | Article 17 requires erasure where a listed ground applies, subject to exceptions including legal retention duties, qualifying health purposes and certain research interests. Article 5(1)(e) limits identifiable storage to the necessary period, with specified exceptions and safeguards. Request-response procedure: Article 12(3)–(4); see the access row. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.316(b)(2)(i), 164.530(j); HHS medical-record retention FAQ.<br>GDPR<br>Articles 5(1)(e), 17(1)–(3) and 19. Article 12(3)–(4). |
| Source IDs | HIPAA: HIPAA-05, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 request-handling amendment: Article 3(4), p. 134. It does not replace the cited erasure grounds or retention exceptions; Council mandate, not law. |
| Similarities and differences | Similarity: Under both frameworks, applicable retention obligations must be considered when deciding how long to keep information.<br><br>Difference: GDPR provides a conditional right to erasure and a storage-limitation principle. HIPAA provides no comparable general erasure right and sets no medical-record retention period in its Privacy Rule. |
| Practical implications | Use a retention schedule and assess erasure requests against the purpose and applicable law. Document the reason when information must be retained. Disconnecting an app does not itself establish that stored copies have been deleted. |

### Minimum necessary and data minimization

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Generally take reasonable steps to limit PHI uses, disclosures and requests to the minimum necessary for the purpose. Exceptions include disclosures to or requests by providers for treatment, disclosures to the individual, authorized uses or disclosures, and specified legally required activities. |
| GDPR requirement | Personal data must be adequate, relevant and limited to what is necessary for the processing purpose. The data minimization principle applies to health data, alongside the lawful basis and special-category requirements. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.502(b) and 164.514(d).<br>GDPR<br>Article 5(1)(c). |
| Source IDs | HIPAA: HIPAA-06, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC2-Final, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. Post-cutoff PC2 finalisation is separately identified in the proposed-change column; it does not replace the October baseline. |
| Relevant proposed change | At cutoff: PC2 proposed a care-coordination minimum-necessary exception. After cutoff: PC2-Final expressly does NOT adopt that exception (§ IV.D). PC3 proposes design/default safeguards for controllers and processors (Article 3(7a), p. 136), not repeal of Article 5(1)(c). |
| Similarities and differences | Similarity: Both seek to limit information use to what the purpose requires.<br><br>Difference: HIPAA has defined exceptions to its minimum necessary standard, including specified treatment disclosures and requests. GDPR applies purpose-linked data minimization to health-data processing. |
| Practical implications | Identify which fields and staff access the task needs. Assess HIPAA exceptions precisely. A treatment-related HIPAA exception does not by itself establish compliance with GDPR minimization. |

### Privacy notices and transparency

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Covered entities generally provide a Notice of Privacy Practices explaining permitted uses and disclosures, individual rights, entity duties and complaint contacts. Distribution duties vary by entity. Direct-treatment providers generally provide notice by first service and seek acknowledgement of receipt, with specified exceptions. |
| GDPR requirement | Controllers provide prescribed information when collecting personal data directly or from other sources, subject to applicable exceptions. Information includes purposes, legal basis, recipients, retention and rights. Communications must be concise, accessible and understandable. |
| Supporting provisions | HIPAA<br>45 CFR § 164.520(a)–(c).<br>GDPR<br>Articles 12–14. |
| Source IDs | HIPAA: HIPAA-07, HIPAA-09, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC2-Final, PC3-Base, PC3, PC3-Status, PC3-Procedure, HIPAA-32, HIPAA-34, HIPAA-35, HIPAA-36 |
| Legal status | HIPAA baseline notice duties apply. The court vacated § 164.520(b)(1)(ii)(F)–(H) on June 18, 2025. Surviving notice amendments required compliance by February 16, 2026. GDPR Articles 12–14 apply. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. Post-cutoff PC2 finalisation is separately identified in the proposed-change column; it does not replace the October baseline. |
| Relevant proposed change | At cutoff: PC2 proposed removing acknowledgement; PC3 proposes narrow information-duty exemptions (Article 3(5)–(6), pp. 134–135), excluding special-category data from its low-intensity exemption. After cutoff: PC2-Final removes acknowledgement (§ IV.I); compliance July 19, 2027. |
| Similarities and differences | Similarity: Both require information about data practices and individual rights.<br><br>Difference: HIPAA uses its Notice of Privacy Practices framework for covered entities. GDPR requires controller disclosures tailored to the processing and whether data come from the individual or another source. |
| Practical implications | Align the notice with actual data flows, recipients and purposes. Treat acknowledgement of a HIPAA notice separately from authorization. Assess consent requirements independently under GDPR. |

### Restrictions and objections

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Individuals may request restrictions on specified uses or disclosures. Covered entities generally need not agree. They must restrict certain payment or operations disclosures to a health plan when the information relates solely to care paid in full by the individual or another person on their behalf and disclosure is not required by law. |
| GDPR requirement | Article 18 gives a right to restrict processing in specified circumstances, including disputed accuracy while it is checked. Article 21 provides objections to processing based on public tasks or legitimate interests, subject to conditions, and to direct marketing. Particular rules govern research objections. Request-response procedure: Article 12(3)–(4); see the access row. |
| Supporting provisions | HIPAA<br>45 CFR § 164.522(a).<br>GDPR<br>Articles 18, 19 and 21. Article 12(3)–(4). |
| Source IDs | HIPAA: HIPAA-08, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 request-handling amendment: Article 3(4), p. 134. It does not replace the cited substantive restriction and objection provisions; Council mandate, not law. |
| Similarities and differences | Similarity: Both provide individuals with mechanisms to seek limits on data use or disclosure.<br><br>Difference: HIPAA generally permits refusal of requested restrictions but mandates a qualifying self-pay health-plan restriction. GDPR provides separate restriction and objection rights with specified conditions and legal bases. |
| Practical implications | Route requests by their purpose and legal grounds. Apply qualifying HIPAA self-pay restrictions to health-plan disclosures. Under GDPR, determine whether a request invokes restriction, objection or another right before deciding its outcome. |

### Electronic copies and data portability

| Field | Comparison |
| --- | --- |
| HIPAA requirement | The access right includes a copy of PHI in a designated record set. For electronically maintained PHI, provide the requested electronic form and format if readily producible, or an agreed readable electronic form and format. Access rights and exclusions remain applicable. |
| GDPR requirement | Article 20 allows individuals to receive personal data they provided in a structured, commonly used, machine-readable format and transmit it to another controller when processing is automated and based on consent or contract. Direct transmission applies where technically feasible and must respect others’ rights. Request-response procedure: Article 12(3)–(4); see the access row. |
| Supporting provisions | HIPAA<br>45 CFR § 164.524(a), (c)(2)(ii).<br>GDPR<br>Articles 15 and 20(1)–(4). Article 12(3)–(4). |
| Source IDs | HIPAA: HIPAA-04, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC2, PC2-Status, PC2-Final, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA and GDPR baseline provisions in this row applicable as of October 31, 2026. PC2 and PC3 changes remain proposed at that cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. Post-cutoff PC2 finalisation is separately identified in the proposed-change column; it does not replace the October baseline. |
| Relevant proposed change | At cutoff: PC2 proposed app access and electronic transfers. After cutoff: PC2-Final adopts specified app-access and EHR-directed-transfer rights (§ IV.A.5–6). PC3 has no direct Article 20 change identified in the Council mandate. |
| Similarities and differences | Similarity: Both support individuals obtaining information in electronic form.<br><br>Difference: HIPAA’s electronic-copy right follows designated-record-set access rules. GDPR portability concerns data provided by the individual and requires automated processing based on consent or contract. |
| Practical implications | Separate access requests from requests for GDPR portability. A hospital’s legal basis may support access without triggering Article 20 portability. Check the requested data, format and applicable conditions before arranging transfer. |

### De-identification, anonymisation and pseudonymisation

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HIPAA permits expert determination or Safe Harbor de-identification. A limited data set remains PHI, with a data-use agreement for specified research, public-health or operations uses. |
| GDPR requirement | Genuinely anonymous information falls outside GDPR; pseudonymised information remains personal data where identification remains reasonably possible. Separating identifiers is not automatically anonymisation. |
| Supporting provisions | HIPAA<br>45 CFR § 164.514(a)–(b), (e).<br>GDPR<br>Recital 26; Articles 4(5) and 11. |
| Source IDs | HIPAA: HIPAA-27, HIPAA-31, HIPAA-26<br>GDPR: GDPR-01<br>Related: PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Applicable baseline at October 31, 2026; proposal statements are conditional and separate from applicable duties. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 proposes identifiability and pseudonymisation provisions: Council Article 3(1), (10), pp. 131, 140–141; compare PC3-Base. Negotiating text, not baseline law. |
| Similarities and differences | Similarity: Both distinguish identifiable information from information meeting a de-identification or anonymity standard.<br><br>Difference: HIPAA has specified de-identification methods and a limited-data-set pathway. GDPR anonymity depends on identifiability in context; pseudonymisation ordinarily reduces risk without removing GDPR duties. |
| Practical implications | Assess re-identification risk and recipient context before research sharing. Do not equate a HIPAA limited data set or identifier removal with GDPR anonymity. |

### Automated decision-making

| Field | Comparison |
| --- | --- |
| HIPAA requirement | The cited HIPAA provisions regulate PHI uses, disclosures, authorization and access. They do not establish a direct counterpart to the specific GDPR Article 22 restriction. Security safeguards are addressed separately in this matrix. |
| GDPR requirement | Article 22 concerns solely automated decisions producing legal or similarly significant effects. Exceptions and safeguards apply; qualifying contract/consent cases require human-intervention and contest rights. Special-category decisions face further conditions; related transparency duties apply. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.502(a), 164.508, 164.524.<br>GDPR<br>Articles 13(2)(f), 14(2)(g), 15(1)(h), 22(1)–(4). |
| Source IDs | HIPAA: HIPAA-27, HIPAA-26<br>GDPR: GDPR-01<br>Related: PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Applicable baseline at October 31, 2026; proposal statements are conditional and separate from applicable duties. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 proposes Article 22 changes and related guidance (Council Article 3(7), pp. 135–136; (12a), p. 142). It is not enacted at cutoff. |
| Similarities and differences | Similarity: Both frameworks continue to govern covered information used in automated systems.<br><br>Difference: GDPR adds a specific restriction and safeguards for qualifying solely automated decisions. HIPAA privacy permissions alone do not satisfy that separate GDPR test. |
| Practical implications | Identify whether the decision is solely automated and significantly affects a person. Check exceptions, meaningful human oversight and health-data conditions; assess other relevant laws separately. |

### Accounting of disclosures and recipient information

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Individuals may request an accounting of specified disclosures during the previous six years. Exclusions include treatment/payment/operations, authorized disclosures and limited data sets. Act within 60 days, with one permitted 30-day extension; the first accounting in 12 months is free. |
| GDPR requirement | Article 15(1)(c), interpreted in C-154/21, generally requires actual recipient identities where data have been or will be disclosed. Categories suffice where identification is impossible or the controller demonstrates a manifestly unfounded or excessive access request. This remains an access right, not an identical six-year HIPAA disclosure-accounting regime. |
| Supporting provisions | HIPAA<br>45 CFR § 164.528(a)–(c).<br>GDPR<br>Articles 12 and 15(1)(c); C-154/21, RW v Österreichische Post AG (January 12, 2023), paragraph 51 and operative ruling. |
| Source IDs | HIPAA: HIPAA-27, HIPAA-26<br>GDPR: GDPR-01, GDPR-12<br>Related: PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Applicable baseline at October 31, 2026; proposal statements are conditional and separate from applicable duties. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 Article 3(4), p. 134, proposes request-handling changes; it does not create HIPAA-style disclosure accounting under GDPR. |
| Similarities and differences | Similarity: Both support transparency about recipients of personal health information.<br><br>Difference: HIPAA provides a defined accounting right with exclusions, timing and lookback rules. GDPR recipient information follows its access framework and has no matching six-year accounting formula. |
| Practical implications | Distinguish disclosure accounting from access to the underlying chart or GDPR recipient information. Preserve the records needed to answer the relevant request. |

### Marketing and sale of health information

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Marketing and sale of PHI generally require authorization under § 164.508(a)(3)–(4), subject to defined exceptions and required remuneration disclosures. |
| GDPR requirement | Direct marketing remains subject to lawful-basis and health-data conditions. Individuals may object to direct marketing at any time, after which that processing must stop; other communications laws may also apply. |
| Supporting provisions | HIPAA<br>45 CFR § 164.508(a)(3)–(4).<br>GDPR<br>Articles 6, 9 and 21(2)–(4). |
| Source IDs | HIPAA: HIPAA-27, HIPAA-26<br>GDPR: GDPR-01 |
| Legal status | Applicable baseline at October 31, 2026; proposal statements are conditional and separate from applicable duties. |
| Relevant proposed change | No direct replacement of the cited marketing/sale provisions is identified in selected PC1–PC3 materials. |
| Similarities and differences | Similarity: Both impose conditions on using health information for marketing.<br><br>Difference: HIPAA has specific authorization rules for marketing and PHI sales. GDPR adds an unconditional objection to direct marketing; that objection is distinct from withdrawal of consent. |
| Practical implications | Identify purpose, remuneration and exceptions before using or selling PHI. For GDPR, establish the Article 6/9 route and honour direct-marketing objections. |

## Security safeguards

### Access controls and authentication

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Implement technical controls allowing access to electronic PHI only to authorized persons or programs. Unique user identification and emergency access procedures are required. Automatic logoff is addressable. Verify that a person or entity seeking access is the one claimed. |
| GDPR requirement | Controllers and processors implement measures appropriate to risk. Article 32(4) requires steps so people acting under their authority process data only on instructions unless law requires otherwise. |
| Supporting provisions | HIPAA<br>45 CFR § 164.312(a)(1), (a)(2)(i)–(iii) and (d).<br>GDPR<br>Article 32(1)–(2), (4). |
| Source IDs | HIPAA: HIPAA-10, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC1 proposes multi-factor authentication with limited exceptions. Proposed at the cutoff. No direct replacement of Article 32 identified in PC3. |
| Similarities and differences | Similarity: Both require measures to protect information against unauthorized access.<br><br>Difference: HIPAA specifies access-control and identity-verification requirements, including required and addressable items. GDPR applies a risk-based security standard and controls processing by people acting under authority. |
| Practical implications | Assign individual accounts and appropriate access permissions. Verify identities and review changes when staff or vendor access ends. |

### Encryption at rest and in transit

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Encryption is addressable under the baseline Security Rule: assess reasonableness and appropriateness, implement it where appropriate, or document the decision and any reasonable equivalent alternative. Transmission security is a required standard; its encryption and integrity-control implementation specifications are addressable. |
| GDPR requirement | Article 32 includes encryption and pseudonymisation among measures to consider as appropriate to risk, technology and processing context. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.306(d)(3), 164.312(a)(2)(iv), 164.312(e)(1)–(2).<br>GDPR<br>Article 32(1)(a), (2). |
| Source IDs | HIPAA: HIPAA-11, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, HIPAA-28 |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. |
| Relevant proposed change | PC1 proposes encryption of electronic PHI at rest and in transit with limited exceptions. Proposed at the cutoff. |
| Similarities and differences | Similarity: Both make encryption decisions part of protecting information in light of security risks.<br><br>Difference: Under the baseline HIPAA rule, encryption is addressable and requires a justified assessment. GDPR lists encryption among measures to apply as appropriate to risk and processing context. |
| Practical implications | Document encryption and key management. HIPAA notification is not required for PHI secured according to HHS guidance, including an uncompromised decryption key. GDPR Article 34(3)(a) can remove individual communication when affected data are unintelligible; assess Article 33 authority notification separately. |

### Audit controls and activity review

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Implement mechanisms to record and examine activity in systems containing or using electronic PHI. Regularly review records of system activity, including audit logs, access reports and security incident tracking. |
| GDPR requirement | Security measures must fit the risk. Article 32(1)(d) requires a process for regularly testing, assessing and evaluating their effectiveness. Article 5(2) requires demonstrated accountability. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.312(b), 164.308(a)(1)(ii)(D).<br>GDPR<br>Articles 5(2) and 32(1)(d). |
| Source IDs | HIPAA: HIPAA-10, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. |
| Relevant proposed change | PC1 proposes an annual compliance audit and more specific safeguard effectiveness review. A compliance audit has a different purpose from event-log review. |
| Similarities and differences | Similarity: Both require assessment of whether security measures are working effectively.<br><br>Difference: HIPAA expressly requires audit controls and review of system activity. GDPR’s cited provisions require accountability and security-effectiveness testing without prescribing the same universal audit-log specification. |
| Practical implications | Define which system events to record, who reviews them and how findings are addressed. Distinguish event-log review from a broader compliance audit. |

### Physical safeguards and device handling

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Implement physical safeguards for facilities, workstations, devices and media used for electronic PHI. Address access controls, workstation use and security, media disposal and reuse, and required or addressable implementation items. |
| GDPR requirement | Article 32 requires appropriate organizational and technical measures, considering risks including unauthorized access, loss and destruction. |
| Supporting provisions | HIPAA<br>45 CFR § 164.310(a)–(d).<br>GDPR<br>Article 32(1)–(2). |
| Source IDs | HIPAA: HIPAA-10, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. |
| Relevant proposed change | PC1 proposes stronger documentation and system-configuration controls. Proposed at the cutoff. |
| Similarities and differences | Similarity: Both require protection against risks such as unauthorized access, loss and destruction.<br><br>Difference: HIPAA explicitly lists facility, workstation, device and media safeguards. GDPR addresses these risks through its broader requirement for appropriate technical and organizational measures. |
| Practical implications | Control access to workstations and storage locations and document secure handling, reuse and disposal of equipment holding patient data. |

### Backups and recovery

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Establish contingency procedures for emergencies affecting electronic PHI systems. Required implementation items include a data backup plan, disaster recovery plan and emergency-mode operation plan. Testing and revision procedures and application/data criticality analysis are addressable. |
| GDPR requirement | Article 32 addresses ongoing availability and resilience, timely restoration after incidents, and regular effectiveness testing. |
| Supporting provisions | HIPAA<br>45 CFR § 164.308(a)(7).<br>GDPR<br>Article 32(1)(b)–(d). |
| Source IDs | HIPAA: HIPAA-10, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. |
| Relevant proposed change | PC1 proposes procedures to restore specified systems and data within 72 hours and separate backup/recovery controls. These are proposed requirements at the cutoff. |
| Similarities and differences | Similarity: Both address availability, resilience and recovery of protected information.<br><br>Difference: HIPAA specifies contingency-plan components and distinguishes required from addressable items. GDPR states risk-appropriate restoration and regular security-testing outcomes. |
| Practical implications | Document backup and restoration arrangements, test recovery and prioritize essential care systems. Coordinate responsibilities with service providers. |

### Workforce training and sanctions

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Security awareness/training and appropriate sanctions are required for Security Rule regulated entities. Covered entities also train their workforce on relevant privacy policies and apply sanctions for violations. |
| GDPR requirement | Article 32(4) controls processing under authority. Where a DPO is designated, Article 39(1)(b) includes monitoring awareness, training and related audits. GDPR does not prescribe HIPAA’s exact internal-sanctions scheme. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.308(a)(1)(ii)(C), (a)(5), 164.530(b), (e).<br>GDPR<br>Articles 32(4), 39(1)(b). |
| Source IDs | HIPAA: HIPAA-27, HIPAA-24<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | Applicable baseline at October 31, 2026; proposal statements are conditional and separate from applicable duties. |
| Relevant proposed change | PC1 proposes more detailed documented security duties and specified reviews; it does not replace the baseline distinction between internal sanctions and regulatory penalties. |
| Similarities and differences | Similarity: Both link workforce conduct and awareness to information protection.<br><br>Difference: HIPAA explicitly specifies training and workforce sanctions. GDPR addresses authorized processing and DPO compliance-monitoring tasks without the same named sanction specification. |
| Practical implications | Provide role-appropriate training, keep evidence and apply documented workforce policies consistently. Distinguish internal staff sanctions from regulator penalties. |

## Risk management

### Risk assessment

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Covered entities and business associates must assess threats and vulnerabilities to the confidentiality, integrity and availability of all electronic PHI they hold. The analysis must be accurate and thorough. |
| GDPR requirement | Controllers assess risks to individuals when selecting compliance measures. Controllers and processors assess security risks, considering likelihood, severity and processing context. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.308(a)(1)(ii)(A), 164.306(b).<br>GDPR<br>Articles 24(1) and 32(1)–(2). |
| Source IDs | HIPAA: HIPAA-12, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. |
| Relevant proposed change | PC1 proposes a more detailed written risk analysis covering asset inventories, network maps, threats, vulnerabilities and risk levels. Proposed at the cutoff. |
| Similarities and differences | Similarity: Both use risk assessment to guide the selection of safeguards.<br><br>Difference: HIPAA focuses its Security Rule analysis on electronic PHI confidentiality, integrity and availability. GDPR also considers broader risks to individuals’ rights and freedoms. |
| Practical implications | Map health-data flows and systems, identify threats and affected people, and record likelihood, impact and existing controls. |

### Risk reduction

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Implement security measures that reduce identified risks and vulnerabilities to a reasonable and appropriate level. Selection considers organizational capabilities, infrastructure, cost and risk. |
| GDPR requirement | Controllers must integrate safeguards into processing design and operation. Controllers and processors implement security measures appropriate to the assessed risk. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.308(a)(1)(ii)(B), 164.306(b).<br>GDPR<br>Articles 25(1) and 32(1). |
| Source IDs | HIPAA: HIPAA-10, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC1 proposes more prescriptive safeguards. PC3 proposes extending design/default obligations expressly to processors (Article 3(7a), p. 136). Both are proposals at cutoff. |
| Similarities and differences | Similarity: Both require measures that respond to identified risks.<br><br>Difference: HIPAA specifies a required risk-management implementation item. GDPR additionally expresses data protection by design and embeds safeguards into processing choices and operation. |
| Practical implications | Assign responsibility for corrective actions, choose proportionate controls and document implementation and remaining risks. An assessment alone does not implement safeguards. |

### Impact assessments

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Security risk analysis is required for regulated entities. The cited Security Rule does not establish a separate GDPR-style DPIA or its prior-consultation process. |
| GDPR requirement | Before processing likely to create high risk, the controller must conduct a DPIA; large-scale health-data processing is a specified trigger. Assess necessity, proportionality, risks and safeguards. Consult the authority if high residual risk remains. |
| Supporting provisions | HIPAA<br>45 CFR § 164.308(a)(1)(ii)(A).<br>GDPR<br>Articles 35(1)–(3), (7) and 36(1). |
| Source IDs | HIPAA: HIPAA-12, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC1 proposes more detailed risk analysis. PC3 proposes common DPIA lists, template and methodology (Article 3(9), pp. 138–139); this does not replace the baseline Article 35 trigger at cutoff. |
| Similarities and differences | Similarity: Both require structured consideration of risks and safeguards.<br><br>Difference: HIPAA security risk analysis applies generally to regulated entities. GDPR requires a DPIA before processing likely to create high risk and adds prior consultation where high residual risk remains. |
| Practical implications | Before a new health-data project, perform HIPAA risk analysis and separately screen for a GDPR DPIA. Obtain DPO advice where designated and resolve the consultation requirement before processing. |

### Ongoing review

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Periodically evaluate technical and nontechnical safeguards, including after relevant environmental or operational changes. Review and update security measures and documentation as needed; the baseline does not set a universal annual risk-analysis deadline. |
| GDPR requirement | Controllers review compliance measures when necessary. Security effectiveness is tested regularly. Review the DPIA where necessary, at least when the processing risk changes. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.308(a)(8), 164.306(e), 164.316(b)(2)(iii).<br>GDPR<br>Articles 24(1), 32(1)(d) and 35(11). |
| Source IDs | HIPAA: HIPAA-10, HIPAA-12, HIPAA-24, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | HIPAA baseline Security Rule and cited GDPR provisions applicable at October 31, 2026. PC1 remains proposed. The regulatory agenda forecasts final action in July 2027. |
| Relevant proposed change | PC1 proposes compliance audits and reviews of specified security measures at least every 12 months, plus ongoing asset-inventory and network-map updates. Proposed intervals must be distinguished from baseline duties. |
| Similarities and differences | Similarity: Both require continuing review and updates when relevant circumstances change.<br><br>Difference: HIPAA specifies periodic evaluations and updates to safeguards and documentation. GDPR combines necessary compliance updates, regular security testing and DPIA review when processing risk changes; neither cited baseline creates a universal annual full-assessment deadline. |
| Practical implications | Set review triggers for new systems, vendors, incidents and changed data uses. Record reassessments and follow through on corrective actions. |

### Governance roles

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Covered entities designate a privacy official and complaint contact; Security Rule regulated entities identify a responsible security official. These are distinct functions, even where one person performs multiple roles. |
| GDPR requirement | DPO designation is required under Article 37 triggers, including core large-scale special-category processing, and must satisfy independence/task rules. Article 27 separately requires an EU representative for qualifying Article 3(2) organizations, subject to exceptions. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.530(a), 164.308(a)(2).<br>GDPR<br>Articles 27, 37–39. |
| Source IDs | HIPAA: HIPAA-27, HIPAA-24<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Applicable baseline at October 31, 2026; proposal statements are conditional and separate from applicable duties. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | No direct replacement of the cited role-designation duties is identified in selected PC1–PC3 materials. |
| Similarities and differences | Similarity: Both assign responsibility for privacy or security governance.<br><br>Difference: HIPAA specifies privacy/security officials. GDPR’s DPO role has conditional designation, independence and task requirements; the EU representative is a separate role. |
| Practical implications | Assign accountable officials and check DPO and EU-representative triggers separately rather than relabelling a HIPAA official as a GDPR DPO. |

### Documentation and records of processing

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Required privacy/security policies, actions and decisions must be documented. Retain required documentation for six years from creation or last effective date, whichever is later, and update/access it as required. |
| GDPR requirement | Article 30 requires controller and processor records of processing with different specified contents. The under-250-person exception is conditional and does not apply merely because an organization is small when processing includes health data. GDPR sets no matching universal six-year RoPA period. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.316, 164.530(j).<br>GDPR<br>Articles 5(2), 24 and 30(1)–(5). |
| Source IDs | HIPAA: HIPAA-27, HIPAA-24<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, GDPR-07, GDPR-08, GDPR-09 |
| Legal status | Article 30 baseline remains applicable at October 31, 2026. Separate Omnibus IV procedure 2025/0130(COD): June compromise endorsed in committee July 2; not enacted at cutoff. It was not absorbed into Digital Omnibus procedure 2025/0360(COD). |
| Relevant proposed change | PC1: proposed written documentation and asset inventories/network maps. Separately, Omnibus IV Article 1(2): May 2025 proposal used fewer than 750 persons; June 2026 compromise uses fewer than 1,000. RoPA remains required for high-risk processing and core activities requiring a DPO under Article 37(1)(b)/(c). Special-category processing alone would no longer automatically exclude the exemption. This is proposed, not the applicable Article 30(5) rule. After cutoff: Parliament adopted its first-reading text on November 24, 2026, P10_TA(2026)0382. OEIL records the procedure as awaiting the Council’s first-reading position. Council formal adoption, Official Journal publication and entry-into-force dates have not been verified. |
| Similarities and differences | Similarity: Both require evidence of compliance and information about data-handling activities.<br><br>Difference: HIPAA specifies documentation retention periods. GDPR specifies records of processing activities and conditional exemptions; the documentation sets are not interchangeable. |
| Practical implications | Maintain policies and decision evidence alongside a processing inventory. Use appropriate retention schedules rather than applying HIPAA’s documentation period automatically to all medical records or GDPR data. |

## Third-party responsibilities

### Roles and responsibility allocation

| Field | Comparison |
| --- | --- |
| HIPAA requirement | A business associate performs specified functions or services involving PHI for a covered entity, outside its workforce. Business associates also have direct HIPAA duties. Exceptions apply, including certain treatment disclosures. |
| GDPR requirement | A controller determines processing purposes and means; a processor acts on its behalf. Joint controllers share that determination. Roles follow actual activities, not contract labels. |
| Supporting provisions | HIPAA<br>45 CFR § 160.103; § 164.502(e)(1).<br>GDPR<br>Articles 4(7)–(8), 26 and 28(10). |
| Source IDs | HIPAA: HIPAA-01, HIPAA-13, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Cited HIPAA and GDPR provisions applicable at October 31, 2026. PC1 business-associate security changes remain proposed at the cutoff. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | No direct replacement of the cited role definitions identified in the selected PC1–PC3 materials. PC1 would strengthen security duties for business associates. |
| Similarities and differences | Similarity: Both allocate duties according to the organization’s role in handling information.<br><br>Difference: HIPAA uses covered entity and business associate relationships. GDPR distinguishes controllers, processors and joint controllers; a business associate is not automatically a processor. |
| Practical implications | Document each vendor’s activities, data access and independent uses before assigning roles under either framework. |

### Business associate and processing agreements

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Generally obtain a written BAA or permitted arrangement before sharing PHI with a business associate. Specify permitted uses, safeguards, reporting and assistance with individual rights. Regulatory exceptions apply. |
| GDPR requirement | Processor arrangements require a binding written contract or qualifying legal act covering instructions, confidentiality, security, rights assistance, compliance evidence and end-of-service data handling. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.502(e)(2), 164.504(e)(2)–(3), 164.308(b), 164.314(a).<br>GDPR<br>Article 28(3), (9). |
| Source IDs | HIPAA: HIPAA-14, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | Cited HIPAA and GDPR provisions applicable at October 31, 2026. PC1 business-associate security changes remain proposed at the cutoff. |
| Relevant proposed change | PC1 proposes additional business-associate security assurances and contingency-plan activation reporting. These are proposed at the cutoff; existing contract duties remain the baseline. |
| Similarities and differences | Similarity: Both require defined, enforceable safeguards when information is handled on behalf of another organization.<br><br>Difference: HIPAA generally requires a BAA or permitted arrangement, subject to exceptions. GDPR requires an Article 28 contract or qualifying legal act for processor relationships, with its own mandatory terms. |
| Practical implications | Match the agreement to the services and data flows. Include each applicable framework’s terms before starting the service. |

### Subcontractors and subprocessors

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Business associates must obtain required assurances from PHI-handling subcontractors. Downstream agreements impose the applicable restrictions and safeguards; subcontractors can themselves be business associates. |
| GDPR requirement | Processors need prior specific or general written controller authorisation for subprocessors. General authorisation requires notice and an opportunity to object. Equivalent obligations flow down; the initial processor remains liable to the controller. |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.103, 164.502(e)(1)(ii), 164.504(e)(5), 164.308(b)(2).<br>GDPR<br>Article 28(2), (4). |
| Source IDs | HIPAA: HIPAA-13, HIPAA-14, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | Cited HIPAA and GDPR provisions applicable at October 31, 2026. PC1 business-associate security changes remain proposed at the cutoff. |
| Relevant proposed change | PC1 proposes annual technical-safeguard verification through business-associate and subcontractor relationships. Proposed at the cutoff; existing downstream agreements remain required. |
| Similarities and differences | Similarity: Both extend contractual protection through downstream service-provider relationships.<br><br>Difference: GDPR expressly requires controller authorization of subprocessors and keeps the initial processor liable to the controller for their performance. HIPAA requires applicable downstream assurances and restrictions for PHI-handling subcontractors. |
| Practical implications | Maintain the vendor chain and downstream contracts. Under GDPR, record authorisations and manage change notices and objections. |

### Vendor oversight and termination

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Address known material BAA violations through reasonable corrective steps and, if unsuccessful, termination where feasible. Contracts require return or destruction of PHI at termination if feasible; otherwise protections and use limits continue. |
| GDPR requirement | Controllers select processors offering sufficient guarantees. Processors provide compliance evidence and permit audits. After services end, return or delete data at the controller’s choice, including copies, unless EU or Member State law requires storage. |
| Supporting provisions | HIPAA<br>45 CFR § 164.504(e)(1)(ii)–(iii), (e)(2)(ii)(J), (iii).<br>GDPR<br>Article 28(1), (3)(g)–(h). |
| Source IDs | HIPAA: HIPAA-14, HIPAA-26, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status |
| Legal status | Cited HIPAA and GDPR provisions applicable at October 31, 2026. PC1 business-associate security changes remain proposed at the cutoff. |
| Relevant proposed change | PC1 proposes technical-safeguard verification at least every 12 months, supported by expert analysis and written certification. This is distinct from the baseline exit and return/destruction duties. |
| Similarities and differences | Similarity: Both address vendor assurances and handling of information when services end.<br><br>Difference: GDPR expressly requires audit cooperation and return or deletion at the controller’s choice, unless law requires storage. HIPAA requires action on known material violations and qualifies return or destruction by feasibility. |
| Practical implications | Define evidence, escalation and exit procedures. Confirm how retained copies and backups are handled; ending access alone does not establish deletion. |

### International transfers

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HIPAA does not impose a GDPR-style adequacy regime or general US-only storage requirement. Overseas BA services require applicable agreements, safeguards and risk analysis. |
| GDPR requirement | Chapter V requires a valid transfer route: adequacy, appropriate safeguards such as SCCs/BCRs, or a qualifying derogation. The EU–US Data Privacy Framework adequacy decision concerns qualifying certified US organizations, not all US recipients. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.308(a)(1), 164.502(e), 164.504(e); HHS cloud guidance, question 9.<br>GDPR<br>Articles 44–49; Decisions (EU) 2021/914 and 2023/1795. |
| Source IDs | HIPAA: HIPAA-02, HIPAA-27, HIPAA-26<br>GDPR: GDPR-01, GDPR-04, GDPR-05, GDPR-06<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure, GDPR-10, GDPR-11, GDPR-13 |
| Legal status | DPF Decision 2023/1795 remained operative at October 31, 2026: General Court dismissed Latombe (T-553/23) on September 3, 2025; appeal C-703/25 P, lodged October 31, 2025, remained pending. The June 4, 2026 order concerns intervention, not the merits. |
| Relevant proposed change | No direct replacement of the cited Chapter V routes is identified in selected PC1–PC3 materials. |
| Similarities and differences | Similarity: Both require safeguards when health data are handled through overseas service arrangements.<br><br>Difference: GDPR adds a distinct international-transfer regime. A HIPAA BAA does not itself provide a GDPR Chapter V transfer mechanism. |
| Practical implications | Identify recipient, location and onward transfers; document the GDPR route and any needed assessment or supplementary measures, alongside HIPAA vendor safeguards. |

## Breach notification

### Breach definition and notification thresholds

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Impermissible PHI use or disclosure is presumed a breach unless an exception applies or assessment shows low compromise probability. Consider data, recipient, actual access and mitigation. Notification duties concern unsecured PHI. |
| GDPR requirement | A personal-data breach includes security failures causing destruction, loss, alteration, unauthorised disclosure or access. Authority notification is required unless risk to individuals is unlikely; individual communication uses a high-risk threshold. |
| Supporting provisions | HIPAA<br>45 CFR § 164.402.<br>GDPR<br>Articles 4(12), 33(1) and 34(1). |
| Source IDs | HIPAA: HIPAA-15, HIPAA-25, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure, HIPAA-28 |
| Legal status | Cited HIPAA Breach Notification Rule and GDPR Articles 33–34 applicable at October 31, 2026. Relevant PC1 and PC3 changes remain proposed; proposed deadlines are not the baseline. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 proposes raising the Article 33 authority-notification threshold to high risk. This does not replace the existing breach definition or baseline risk test at the cutoff (Council mandate, Article 3(8), pp. 137–138). |
| Similarities and differences | Similarity: Both require assessment of a security or privacy incident to determine notification duties.<br><br>Difference: HIPAA uses a compromise-probability assessment and unsecured-PHI rules. GDPR includes confidentiality, integrity and availability breaches and applies separate risk thresholds for authority and individual notices. |
| Practical implications | Apply each notification test separately. HHS-standard encryption with an uncompromised key can place PHI outside HIPAA unsecured-PHI notice duties. GDPR Article 34(3)(a) can remove individual communication for unintelligible data, but does not automatically remove Article 33 authority reporting. |

### Notification to regulators

| Field | Comparison |
| --- | --- |
| HIPAA requirement | For 500 or more affected individuals, notify HHS without unreasonable delay, within 60 days of discovery. For fewer than 500, report within 60 days after the discovery year ends. |
| GDPR requirement | The controller notifies the competent authority without undue delay and, where feasible, within 72 hours of awareness unless risk is unlikely. Explain any delay; incomplete information may follow in phases without undue further delay. |
| Supporting provisions | HIPAA<br>45 CFR § 164.408.<br>GDPR<br>Article 33(1), (4). |
| Source IDs | HIPAA: HIPAA-15, HIPAA-25, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Cited HIPAA Breach Notification Rule and GDPR Articles 33–34 applicable at October 31, 2026. Relevant PC1 and PC3 changes remain proposed; proposed deadlines are not the baseline. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 proposes 96 hours in place of 72 and reporting with support of a national entry point, with transitional arrangements. The 72-hour baseline remains applicable at the cutoff (Council mandate, Article 3(8)). |
| Similarities and differences | Similarity: Both require regulator notification when their respective reporting conditions are met.<br><br>Difference: HIPAA timing depends on the affected-person count, including annual reporting for breaches affecting fewer than 500 people. GDPR generally requires reporting within 72 hours of awareness where feasible, unless risk is unlikely. |
| Practical implications | Record discovery or awareness, risk decisions and affected-person counts. Track the applicable reporting clock; a maximum deadline does not justify unnecessary delay. |

### Notification to individuals and public communication

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Notify affected people without unreasonable delay, within 60 days of discovery. Notify prominent media when more than 500 residents of one State or jurisdiction are affected. Substitute-notice rules also apply. |
| GDPR requirement | Communicate high-risk breaches to affected people without undue delay. Article 34(3) permits exceptions for effective protection or subsequent risk removal; disproportionate effort requires equally effective public communication instead. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.404, 164.406 and 164.412.<br>GDPR<br>Articles 23 and 34(1)–(4). |
| Source IDs | HIPAA: HIPAA-15, HIPAA-25, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Cited HIPAA Breach Notification Rule and GDPR Articles 33–34 applicable at October 31, 2026. Relevant PC1 and PC3 changes remain proposed; proposed deadlines are not the baseline. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | The selected PC3 Article 33 changes concern authority reporting. They do not turn the proposed 96-hour deadline into an individual-notice deadline. Baseline Article 34 and HIPAA individual-notice duties apply. |
| Similarities and differences | Similarity: Both require communication to affected individuals when the applicable conditions are met.<br><br>Difference: HIPAA specifies a 60-day outer limit and additional media notice in defined cases. GDPR requires high-risk individual communication without undue delay, with specified exceptions and a public-communication alternative for disproportionate effort. |
| Practical implications | Prepare accessible notices and assess individual and public communication separately. HIPAA law-enforcement delay must meet § 164.412. GDPR Article 34 remains applicable; any legislative restriction must satisfy Article 23 and the relevant applicable law. |

### Business associate and processor reporting

| Field | Comparison |
| --- | --- |
| HIPAA requirement | A business associate notifies its covered entity without unreasonable delay, within 60 days of discovery, identifying affected people and providing available notice information. |
| GDPR requirement | A processor notifies its controller without undue delay after awareness. Article 33(2) sets no separate numerical hour limit for that report. |
| Supporting provisions | HIPAA<br>45 CFR § 164.410.<br>GDPR<br>Articles 28(3)(f) and 33(2). |
| Source IDs | HIPAA: HIPAA-15, HIPAA-25, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Cited HIPAA Breach Notification Rule and GDPR Articles 33–34 applicable at October 31, 2026. Relevant PC1 and PC3 changes remain proposed; proposed deadlines are not the baseline. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC1 proposes business-associate reporting of contingency-plan activation within 24 hours. This is a separate proposed security duty, not a replacement for the cited breach-notice deadline. |
| Similarities and differences | Similarity: Both require vendors to promptly inform the organization on whose behalf they handle data about relevant breaches.<br><br>Difference: HIPAA business-associate notice has a 60-day outer limit and must avoid unreasonable delay. GDPR processor notice must occur without undue delay; its rule has no separate numerical hour limit. |
| Practical implications | Agree on rapid vendor escalation, evidence sharing and named contacts so the responsible organization can meet its own notification duties. |

### Notification content and documentation

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Individual notices describe events, affected data, protective steps, the response and contacts. Document notices or the basis for non-notification. Required breach-notification documentation is retained for six years under the incorporated HIPAA documentation rules. |
| GDPR requirement | Authority reports describe the incident, approximate affected numbers, contacts, consequences and response. Document all personal-data breaches, including effects and remedial action, even when authority notification is unnecessary. |
| Supporting provisions | HIPAA<br>45 CFR §§ 164.404(c), 164.414(a)–(b), 164.530(j).<br>GDPR<br>Articles 33(3)–(5) and 34(2). |
| Source IDs | HIPAA: HIPAA-15, HIPAA-25, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure |
| Legal status | Cited HIPAA Breach Notification Rule and GDPR Articles 33–34 applicable at October 31, 2026. Relevant PC1 and PC3 changes remain proposed; proposed deadlines are not the baseline. PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | PC3 proposes common notification arrangements and high-risk lists (Article 3(8), pp. 137–138; Article 3(14), p. 142). Baseline breach documentation remains applicable. |
| Similarities and differences | Similarity: Both require incident information and evidence supporting notification decisions.<br><br>Difference: GDPR expressly requires documentation of all personal-data breaches. HIPAA requires evidence of required notices or why notification was unnecessary; the prescribed notice contents also differ. |
| Practical implications | Maintain an incident record with the decision rationale, recipients, timestamps, communications and corrective actions. Distinguish confirmed facts from estimates and update reports when necessary. |

## Enforcement

### Enforcement authorities and jurisdiction

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HHS OCR leads federal civil HIPAA enforcement through complaints and compliance reviews; possible criminal violations may be referred to DOJ. State attorneys general may also bring civil actions on behalf of residents under 42 USC § 1320d-5(d). |
| GDPR requirement | Independent Member State supervisory authorities enforce GDPR. Eligible cross-border cases use lead-authority cooperation; the EDPB resolves specified disputes. Article 55 exceptions apply. |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.306–160.312; 42 USC §§ 1320d-5(d), 1320d-6.<br>GDPR<br>Articles 51, 55–56, 60 and 65. |
| Source IDs | HIPAA: HIPAA-16, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC3-Base, PC3, PC3-Status, PC3-Procedure, GDPR-03, HIPAA-29 |
| Legal status | Cited baseline HIPAA and GDPR enforcement provisions applicable at October 31, 2026. Regulation (EU) 2025/2518 is adopted and in force but generally applies from April 2, 2027.  PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | Regulation (EU) 2025/2518 is adopted law supplementing cross-border GDPR enforcement procedures, generally applicable from April 2, 2027. It is not a pending proposal or an applicable October 2026 procedure (Article 37). |
| Similarities and differences | Similarity: Both use public authorities to investigate noncompliance and pursue remedies.<br><br>Difference: HIPAA combines federal OCR enforcement, DOJ criminal proceedings and state-attorney-general civil actions. GDPR uses Member State supervisory authorities with lead-authority cooperation and EDPB dispute resolution in relevant cases. |
| Practical implications | Identify the competent authority and legal regime for the organization and activity. Cross-border GDPR coordination is not a single EU regulator replacing national authorities. |

### Complaints and individual remedies

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Any person may complain to HHS about alleged HIPAA noncompliance, generally within 180 days of knowing or reasonably knowing of it, extendable for good cause. Retaliation is prohibited. HIPAA creates no private right of action; separate claims under other laws are outside this comparison. |
| GDPR requirement | Individuals may complain to supervisory authorities and seek judicial remedies. Article 80 permits qualifying nonprofit representation, subject to its conditions and national options. Article 82 provides compensation for material or non-material damage caused by infringement, subject to controller/processor responsibility and liability conditions. |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.306, 160.316; 42 USC § 1320d-5; Acara v. Banks, 470 F.3d 569, 571–72 (5th Cir. 2006); Brown, No. 23-11896 (11th Cir., July 18, 2024), pp. 7–8 (unpublished).<br>GDPR<br>Articles 57(1)(f), 77–80 and 82. |
| Source IDs | HIPAA: HIPAA-18, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC3-Base, PC3, PC3-Status, PC3-Procedure, GDPR-03, HIPAA-33, HIPAA-30 |
| Legal status | Cited baseline HIPAA and GDPR enforcement provisions applicable at October 31, 2026. Regulation (EU) 2025/2518 is adopted and in force but generally applies from April 2, 2027.  PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | Adopted Regulation 2025/2518 generally applies April 2, 2027. Separately, PC3 addresses authority handling of manifestly unfounded/excessive requests (Article 3(11), p. 141). These do not replace baseline remedies at cutoff. |
| Similarities and differences | Similarity: Both provide regulatory complaint routes.<br><br>Difference: HIPAA has no private right of action to enforce it. GDPR expressly provides judicial remedies, qualifying nonprofit representation and a right to compensation for damage caused by infringement; compensation is distinct from regulatory fines. |
| Practical implications | Provide clear complaint contacts, preserve the chronology and supporting records, and respond without retaliation. Separate internal complaints from regulator proceedings. |

### Investigations and cooperation

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HHS may investigate complaints and conduct compliance reviews. Covered entities and business associates must cooperate and provide relevant records and access under the Enforcement Rule. |
| GDPR requirement | Supervisory authorities may require information, audit processing, and access data and premises subject to procedural law. Controllers and processors must cooperate. Authorities coordinate relevant cross-border investigations. |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.306(c), 160.308 and 160.310.<br>GDPR<br>Articles 31, 57(1)(h), 58(1) and 60–62. |
| Source IDs | HIPAA: HIPAA-17, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure, GDPR-03 |
| Legal status | Cited baseline HIPAA and GDPR enforcement provisions applicable at October 31, 2026. Regulation (EU) 2025/2518 is adopted and in force but generally applies from April 2, 2027.  PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | Regulation (EU) 2025/2518 adds cross-border investigation and cooperation procedures from April 2, 2027, subject to Article 36 transitional rules. PC1 proposed annual compliance audits are organizational duties, not replacement OCR investigation powers. |
| Similarities and differences | Similarity: Both allow authorities to obtain compliance evidence and require cooperation from regulated organizations.<br><br>Difference: GDPR expressly provides audit and premises-access powers and cooperation between national authorities. HIPAA uses OCR complaint investigations and compliance reviews under its Enforcement Rule. |
| Practical implications | Assign an investigation contact and retain policies, assessments, contracts and relevant system records. Track requested evidence and response dates. |

### Corrective actions and enforcement outcomes

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HHS seeks voluntary compliance and may resolve findings through corrective action or resolution agreements. Unresolved matters may lead to civil money penalties with administrative hearing rights. |
| GDPR requirement | Authorities can warn, reprimand, order compliance, require rectification or erasure, restrict or ban processing, and suspend international data flows. Administrative fines may accompany other measures; decisions are subject to judicial remedy. |
| Supporting provisions | HIPAA<br>45 CFR § 160.312; Part 160, Subparts D and E.<br>GDPR<br>Articles 58(2), 58(4) and 78. |
| Source IDs | HIPAA: HIPAA-17, HIPAA-27<br>GDPR: GDPR-01<br>Related: PC1, PC1-Guidance, PC1-Status, PC3-Base, PC3, PC3-Status, PC3-Procedure, GDPR-03 |
| Legal status | Cited baseline HIPAA and GDPR enforcement provisions applicable at October 31, 2026. Regulation (EU) 2025/2518 is adopted and in force but generally applies from April 2, 2027.  PC3: Council mandate; Parliament position pending; not law at October 31, 2026. |
| Relevant proposed change | No direct replacement of the listed core corrective powers identified in selected PC1–PC3 materials. The adopted 2025/2518 procedural regulation has a future application date; it does not change this row’s October 2026 baseline. |
| Similarities and differences | Similarity: Both support corrective action and financial sanctions for noncompliance.<br><br>Difference: GDPR expressly authorizes processing restrictions, bans and suspension of international data flows. HIPAA resolution can involve voluntary compliance, corrective action or resolution agreements, followed where appropriate by civil money penalties. |
| Practical implications | Track remedial obligations, evidence and deadlines. Evaluate service changes needed to comply with an order; financial penalty amounts belong in the Penalties category. |

## Penalties

### Civil penalty structure

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Civil money penalties use four culpability tiers: lack of knowledge despite reasonable diligence; reasonable cause without willful neglect; willful neglect corrected within the specified period; and willful neglect not corrected within that period. Covered entities and business associates can be liable. |
| GDPR requirement | Administrative-fine ceilings depend on the infringed provisions. Article 83(4) covers specified organizational obligations; Article 83(5)–(6) covers more serious infringements and noncompliance with authority orders. Public-body fines depend on Member State rules. |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.401–160.404.<br>GDPR<br>Article 83(2), (4)–(7). |
| Source IDs | HIPAA: HIPAA-19, HIPAA-27<br>GDPR: GDPR-01 |
| Legal status | Cited penalty framework applicable at October 31, 2026. HHS retained 2025-adjusted civil amounts for 2026. The 2019 lower-tier annual-cap policy is enforcement discretion, distinct from the regulatory table. Proposed PC1–PC3 duties are not enacted penalty amounts. |
| Relevant proposed change | No direct replacement of the listed penalty-tier or GDPR Article 83 framework identified in the selected PC1–PC3 materials. Proposed substantive duties could change what conduct constitutes noncompliance if enacted. |
| Similarities and differences | Similarity: Both assess culpability and case circumstances when determining financial sanctions.<br><br>Difference: HIPAA organizes civil penalties into four culpability-and-correction tiers. GDPR sets ceilings by infringement category and considers culpability when deciding the actual fine. |
| Practical implications | Identify the breached provision, responsible parties and correction history before comparing potential sanctions. Maximum figures alone do not predict the outcome. |

### Civil monetary limits at the research cutoff

| Field | Comparison |
| --- | --- |
| HIPAA requirement | Published per-violation ranges (USD): Tier 1, $145–$73,011; Tier 2, $1,461–$73,011; Tier 3, $14,602–$73,011; Tier 4, $73,011–$2,190,294. The regulatory calendar-year cap is $2,190,294 for identical violations; HHS’s 2019 discretion policy applies lower annual caps to Tiers 1–3. The January 28, 2026 table supplies the 2025 adjustment, retained for 2026. Applicability depends on violation and assessment dates. |
| GDPR requirement | Article 83(4): up to EUR 10 million or, for an undertaking, 2% of preceding-year worldwide annual turnover, whichever is higher. Article 83(5)–(6): up to EUR 20 million or 4%, whichever is higher. |
| Supporting provisions | HIPAA<br>45 CFR §§ 102.3, 160.404; 91 FR 3665; 91 FR 66566; 84 FR 18151.<br>GDPR<br>Article 83(4)–(6). |
| Source IDs | HIPAA: HIPAA-20, HIPAA-21, HIPAA-22, HIPAA-19, HIPAA-27<br>GDPR: GDPR-01 |
| Legal status | Cited penalty framework applicable at October 31, 2026. HHS retained 2025-adjusted civil amounts for 2026. The 2019 lower-tier annual-cap policy is enforcement discretion, distinct from the regulatory table. Proposed PC1–PC3 duties are not enacted penalty amounts. |
| Relevant proposed change | The January 2026 adjustment table and October 2026 no-adjustment notice are adopted administrative updates, not PC1–PC3 proposals. The listed baseline amounts and GDPR ceilings are kept separate from proposed obligations. |
| Similarities and differences | Similarity: Both establish limits on administrative financial sanctions; the maximum is not automatically the amount imposed.<br><br>Difference: HIPAA uses USD ranges and identical-violation annual caps, with separate enforcement discretion. GDPR uses EUR ceilings and, for undertakings, worldwide-turnover alternatives, whichever is higher. |
| Practical implications | Use HIPAA-20 for the published dollar table and HIPAA-21 for the 2026 freeze. HIPAA-22 separately sets lower-tier discretionary annual caps; its original unadjusted amounts are $25,000 / $100,000 / $250,000 for Tiers 1–3 and $1.5 million for Tier 4, subject to inflation. These are not current inflation-adjusted cap quotations or settlement amounts. |

### Penalty factors and correction

| Field | Comparison |
| --- | --- |
| HIPAA requirement | HHS considers the violation’s extent and duration, harm, compliance history, financial condition and justice-related factors. Timely correction of violations not due to willful neglect can support a statutory defense; reduction or waiver provisions also apply. |
| GDPR requirement | Authorities consider seriousness, duration, intent or negligence, mitigation, safeguards, prior infringements, cooperation and affected-data categories. Fines must be effective, proportionate and dissuasive; linked infringements are subject to Article 83(3). |
| Supporting provisions | HIPAA<br>45 CFR §§ 160.408, 160.410 and 160.412.<br>GDPR<br>Article 83(1)–(3). |
| Source IDs | HIPAA: HIPAA-19, HIPAA-27<br>GDPR: GDPR-01 |
| Legal status | Cited penalty framework applicable at October 31, 2026. HHS retained 2025-adjusted civil amounts for 2026. The 2019 lower-tier annual-cap policy is enforcement discretion, distinct from the regulatory table. Proposed PC1–PC3 duties are not enacted penalty amounts. |
| Relevant proposed change | No direct amendment to the listed penalty factors or correction defenses identified in selected PC1–PC3 materials. Risk assessment or remediation requirements proposed in PC1 do not themselves waive penalties. |
| Similarities and differences | Similarity: Both consider the seriousness of noncompliance, harm, history and remedial circumstances.<br><br>Difference: HIPAA includes specific correction defenses and reduction or waiver provisions. GDPR weighs mitigation and cooperation within its proportionality-based fine decision; correction does not automatically remove liability. |
| Practical implications | Document discovery, corrective action, patient harm, prevention measures and regulator cooperation. Remediation does not automatically remove liability. |

### Criminal sanctions and other national penalties

| Field | Comparison |
| --- | --- |
| HIPAA requirement | 42 USC § 1320d-6 covers specified knowing misconduct, including qualifying unauthorized obtaining or disclosure by employees or other individuals. Penalties: up to $50,000 and/or one year; false pretenses, $100,000 and/or five years; intent to sell, transfer or use information for commercial advantage, personal gain or malicious harm, $250,000 and/or ten years. |
| GDPR requirement | GDPR does not establish a single EU-wide imprisonment tariff. Article 84 leaves other penalties to Member States; Recital 149 recognises national criminal sanctions, subject to applicable safeguards. |
| Supporting provisions | HIPAA<br>42 USC § 1320d-6(a)–(b).<br>GDPR<br>Article 84 and Recital 149. |
| Source IDs | HIPAA: HIPAA-23, HIPAA-19, HIPAA-27<br>GDPR: GDPR-01 |
| Legal status | 42 USC § 1320d-6 is the cited federal criminal provision at the cutoff. GDPR Article 84 leaves other penalties to Member State law; no single EU-wide imprisonment tariff is established. Civil-money inflation adjustments and discretionary civil caps do not set these criminal penalties. |
| Relevant proposed change | No direct change to the cited federal criminal penalty levels or Article 84 identified in selected PC1–PC3 materials. National criminal laws require a separate jurisdiction-specific analysis. |
| Similarities and differences | Similarity: Both legal systems allow criminal or other national penalties in addition to administrative sanctions.<br><br>Difference: HIPAA specifies federal criminal fine and imprisonment levels for defined misconduct. GDPR leaves other penalties to Member State law and does not establish one EU-wide imprisonment tariff. |
| Practical implications | Separate organizational civil exposure from criminal allegations against responsible persons. For GDPR, identify the relevant Member State law before stating criminal consequences. |

## Sources

| Source ID | Official document | Publisher | URL | Version or status |
| --- | --- | --- | --- | --- |
| HIPAA-01 | 45 CFR § 160.103 Definitions, in effect October 31, 2026 | eCFR, Office of the Federal Register and Government Publishing Office | https://www.ecfr.gov/on/2026-10-31/title-45/subtitle-A/subchapter-C/part-160/section-160.103 | October 31, 2026 point-in-time text checked using the user-supplied Part 160 eCFR capture, including the dated banner and § 160.103 definitions. |
| GDPR-01 | Regulation (EU) 2016/679, consolidated version dated May 4, 2016 (CELEX 02016R0679-20160504) | EUR-Lex, Publications Office of the European Union | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A02016R0679-20160504 | CELEX 02016R0679-20160504; consolidated baseline dated May 4, 2016 |
| HIPAA-02 | Guidance on HIPAA and Cloud Computing, question 9 | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/special-topics/health-information-technology/cloud-computing/index.html | Guidance, question 9 |
| GDPR-02 | Guidelines 3/2018 on the territorial scope of the GDPR, version 2.1 | European Data Protection Board | https://www.edpb.europa.eu/system/files/documents/files/file1/edpb_guidelines_3_2018_territorial_scope_after_public_consultation_en_1.pdf | Final version 2.1 |
| HIPAA-03 | Summary of the HIPAA Privacy Rule | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/privacy/laws-regulations/index.html | Official summary, used for baseline provisions |
| HIPAA-04 | Individuals’ Right under HIPAA to Access their Health Information | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/access/index.html | Official access guidance, baseline provisions |
| HIPAA-05 | HIPAA FAQ on medical-record retention | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/faq/does-hipaa-require-covered-entities-to-keep-medical-records-for-any-period/index.html | Official retention FAQ |
| HIPAA-06 | Minimum Necessary Requirement | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/minimum-necessary-requirement/index.html | Official minimum necessary guidance |
| HIPAA-07 | Notice of Privacy Practices for Protected Health Information | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/privacy-practices-for-protected-health-information/index.html | Baseline notice guidance, read with HIPAA-09 |
| HIPAA-08 | Right to request restrictions under HIPAA | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/faq/under-hipaa-may-an-individual-request-that-a-covered-entity-restrict-how-it-uses-or-discloses-that-individuals-protect-health-information/index.html | Official restriction FAQ |
| PC2 | 2021 HIPAA Privacy Rule proposal, 86 FR 6446 | HHS Office for Civil Rights, Federal Register | https://www.govinfo.gov/content/pkg/FR-2021-01-21/pdf/2020-27157.pdf | January 21, 2021 NPRM, proposed at cutoff |
| PC2-Status | 2026 Privacy Final Rule issued November 16, 2026, after the research cutoff | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/privacy/2026-privacy-final-rule/index.html | After-cutoff HHS announcement: final rule issued November 16, 2026. Use PC2-Final for operative dates and text. |
| PC3 | Council Digital Omnibus negotiating mandate ST 14756/26 | Council of the European Union | https://data.consilium.europa.eu/doc/document/ST-14756-2026-INIT/en/pdf | October 2026 negotiating text |
| PC3-Status | Council negotiating position agreed October 21, 2026 | Council of the European Union | https://www.consilium.europa.eu/en/press/press-releases/2026/10/21/digital-rulebook-council-agrees-position-to-simplify-data-protection-privacy-and-cyber-reporting-rules/ | October 21 press release, updated October 22 |
| HIPAA-09 | Status of the 2024 Privacy Rule following the June 18, 2025 court order | U.S. Department of Health and Human Services, Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/regulatory-initiatives/index.html | HHS explanation of the June 18, 2025 order and surviving notice requirements. Supplement with court-authored HIPAA-34 and HIPAA-35; broad initiatives page is not the judgment itself. |
| HIPAA-10 | Summary of the HIPAA Security Rule | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/security/laws-regulations/index.html | Official baseline Security Rule summary |
| HIPAA-11 | Is the use of encryption mandatory in the Security Rule? | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/faq/is-the-use-of-encryption-mandatory-in-the-security-rule/index.html | Official guidance on addressable encryption |
| PC1 | HIPAA Security Rule proposed update, 90 FR 898 | HHS, Federal Register | https://www.govinfo.gov/content/pkg/FR-2025-01-06/pdf/2024-30983.pdf | January 6, 2025 proposal; proposed at cutoff |
| PC1-Guidance | Security Rule NPRM fact sheet | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/security/hipaa-security-rule-nprm/factsheet/index.html | Explanation of proposed requirements |
| PC1-Status | Regulatory agenda, RIN 0945-AA22 | Office of Information and Regulatory Affairs | https://www.reginfo.gov/public/do/eAgendaViewRule?RIN=0945-AA22&amp;operation=OPERATION_PRINT_RULE&amp;pubId=202510 | Agenda forecast is planning information, not a final rule or guaranteed date |
| HIPAA-12 | Guidance on Risk Analysis | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/security/guidance/guidance-risk-analysis/index.html | Interpretive guidance on baseline risk analysis and ongoing updates |
| HIPAA-13 | Business Associates | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/privacy/guidance/business-associates/index.html | Official guidance; role definitions and exceptions |
| HIPAA-14 | Business Associate Contracts and sample provisions | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/covered-entities/sample-business-associate-agreement-provisions/index.html | Official guidance and illustrative clauses; sample wording itself is not mandatory |
| HIPAA-15 | Breach Notification Rule | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/breach-notification/index.html | Official summary of 45 CFR §§ 164.400–414; baseline definitions, notices and records |
| HIPAA-16 | Enforcement Process | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/enforcement-process/index.html | Official explanation of enforcement routes and DOJ referral |
| HIPAA-17 | How OCR Enforces the HIPAA Privacy and Security Rules | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/examples/how-ocr-enforces-the-hipaa-privacy-and-security-rules/index.html | Official guidance on investigation and resolution; reviewed November 20, 2023 |
| HIPAA-18 | What OCR Considers During Intake and Review | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/examples/what-ocr-considers-during-intake-and-review/index.html | Official intake guidance including 180-day filing rule; reviewed November 20, 2023 |
| GDPR-03 | Regulation (EU) 2025/2518: additional procedural rules for GDPR enforcement | European Parliament and Council; EUR-Lex | https://eur-lex.europa.eu/eli/reg/2025/2518/oj/eng | Adopted November 26, 2025; in force at cutoff; applies April 2, 2027, subject to Article 36 transitions |
| HIPAA-19 | 45 CFR Part 160, Subpart D: civil money penalties | Government Publishing Office, annual CFR edition | https://www.govinfo.gov/content/pkg/CFR-2025-title45-vol2/xhtml/CFR-2025-title45-vol2-chapA-subchapC.html | Penalty-specific reference to 45 CFR Part 160, Subpart D, in the October 1, 2025 annual edition. HIPAA-27 is the general Parts 160/164 reference. Use HIPAA-20 and HIPAA-21 for updated dollar amounts. |
| HIPAA-20 | Annual Civil Monetary Penalties Inflation Adjustment, 91 FR 3665 | HHS; Federal Register, Government Publishing Office | https://www.govinfo.gov/content/pkg/FR-2026-01-28/html/2026-01688.htm | Final rule effective January 28, 2026; 2025 inflation adjustment; applies to assessments on/after publication for violations on/after November 2, 2015 |
| HIPAA-21 | No Adjustment to HHS Civil Monetary Penalty Amounts for 2026, 91 FR 66566 | HHS; Federal Register, Government Publishing Office | https://www.govinfo.gov/content/pkg/FR-2026-10-21/html/2026-21524.htm | October 21, 2026 notice retains 2025-adjusted amounts for 2026 |
| HIPAA-22 | Notification of Enforcement Discretion Regarding HIPAA Civil Money Penalties, 84 FR 18151 | HHS; Federal Register, Government Publishing Office | https://www.govinfo.gov/content/pkg/FR-2019-04-30/html/2019-08530.htm | April 30, 2019 policy states indefinite effect pending further rulemaking; lower tier-specific annual caps are separate from regulation |
| HIPAA-23 | 42 USC § 1320d-6: wrongful disclosure and criminal penalties | U.S. Congress; Government Publishing Office | https://www.govinfo.gov/content/pkg/USCODE-2024-title42/html/USCODE-2024-title42-chap7-subchapXI-partC-sec1320d-6.htm | Primary U.S. Code, 2024 edition; includes the 2009 clarification concerning employees and other individuals. |
| HIPAA-24 | 45 CFR Part 164, Subpart C: Security standards, dated link | eCFR, OFR/GPO | https://www.ecfr.gov/on/2026-10-31/title-45/subtitle-A/subchapter-C/part-164/subpart-C | October 31, 2026 Subpart C text checked using the user-supplied Part 164 eCFR capture. Read with the annual text in HIPAA-27; PC1 remains a separate proposal. |
| HIPAA-25 | 45 CFR Part 164, Subpart D: Breach notification, dated link | eCFR, OFR/GPO | https://www.ecfr.gov/on/2026-10-31/title-45/subtitle-A/subchapter-C/part-164/subpart-D | October 31, 2026 Subpart D text checked using the user-supplied Part 164 eCFR capture, including notification timing and law-enforcement delay. |
| HIPAA-26 | 45 CFR Part 164, Subpart E: Privacy standards, dated link | eCFR, OFR/GPO | https://www.ecfr.gov/on/2026-10-31/title-45/subtitle-A/subchapter-C/part-164/subpart-E | October 31, 2026 Subpart E text checked using the user-supplied Part 164 eCFR capture. Court-affected provisions must be read with HIPAA-09 and HIPAA-34/35; presence in eCFR does not establish enforceability. |
| HIPAA-27 | 45 CFR Parts 160 and 164: primary regulatory text | Government Publishing Office | https://www.govinfo.gov/content/pkg/CFR-2025-title45-vol2/xhtml/CFR-2025-title45-vol2-chapA-subchapC.html | October 1, 2025 annual edition, supplemented by user-supplied October 31, 2026 eCFR captures of Parts 160 and 164. Read court-affected provisions with HIPAA-09/34/35 and dollar amounts with HIPAA-20/21. |
| HIPAA-28 | Guidance rendering unsecured PHI unusable, unreadable or indecipherable | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/breach-notification/guidance/index.html | Encryption safe harbour includes the requirement that the confidential process or key has not been breached. |
| HIPAA-29 | State Attorneys General enforcement authority | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/compliance-enforcement/state-attorneys-general/index.html | Explains HITECH § 13410(e), codified at 42 USC § 1320d-5(d). |
| HIPAA-30 | Brown v. Columbus Police Department et al., No. 23-11896 | U.S. Court of Appeals for the Eleventh Circuit; GPO | https://www.govinfo.gov/content/pkg/USCOURTS-ca11-23-11896/pdf/USCOURTS-ca11-23-11896-0.pdf | July 18, 2024 unpublished, nonprecedential Eleventh Circuit opinion, pp. 7–8. Supporting authority; HIPAA-33 supplies the published Fifth Circuit decision. Neither is cited for an exhaustive list of current enforcement actors. |
| HIPAA-31 | Methods for de-identification of PHI | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/special-topics/de-identification/index.html | Official guidance on Expert Determination and Safe Harbor; read limited-data-set requirements in § 164.514(e), HIPAA-27. |
| HIPAA-32 | 42 CFR Part 2 Final Rule fact sheet | HHS Office for Civil Rights | https://www.hhs.gov/hipaa/for-professionals/regulatory-initiatives/fact-sheet-42-cfr-part-2-final-rule/index.html | Part 2 remains a separate confidentiality regime; February 16, 2026 compliance date. Included for scope context, not a complete Part 2 comparison. |
| PC2-Final | 2026 HIPAA Privacy Final Rule, 91 FR 74848 | HHS; Federal Register, GPO | https://www.govinfo.gov/content/pkg/FR-2026-11-19/html/2026-23429.htm | AFTER CUTOFF: issued November 16 and published November 19, 2026; effective January 19, 2027; compliance July 19, 2027. § IV.A.4–6, C–E, H–I distinguish adopted, modified and non-adopted proposals. |
| PC3-Base | Digital Omnibus Commission proposal, COM(2025) 837 final | European Commission; EUR-Lex | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A52025PC0837 | November 19, 2025; procedure 2025/0360(COD). Commission proposal is distinct from the later Council mandate. |
| PC3-Procedure | Digital Omnibus legislative procedure 2025/0360(COD) | European Parliament Legislative Observatory | https://oeil.europarl.europa.eu/oeil/en/procedure-file?reference=2025%2F0360%28COD%29 | Parliament position pending at research cutoff; Council mandate is a negotiating position, not enacted law. |
| GDPR-04 | Rules on international data transfers | European Commission | https://commission.europa.eu/law/law-topic/data-protection/international-dimension-data-protection/rules-international-data-transfers_en | Official explanation of Chapter V transfer tools. Assess destination, recipient and transfer context. |
| GDPR-05 | EU–US Data Privacy Framework adequacy decision, (EU) 2023/1795 | European Commission; EUR-Lex | https://eur-lex.europa.eu/eli/dec_impl/2023/1795/oj/eng | July 10, 2023 decision; Article 1 concerns qualifying organizations on the US Data Privacy Framework List. Not a blanket adequacy finding for all US recipients. |
| GDPR-06 | Standard contractual clauses for third-country transfers, (EU) 2021/914 | European Commission; EUR-Lex | https://eur-lex.europa.eu/eli/dec_impl/2021/914/oj/eng | June 4, 2021 decision; applicable module, transfer assessment and supplementary safeguards require contextual analysis. |
| HIPAA-33 | Acara v. Banks, 470 F.3d 569 (5th Cir. 2006) | U.S. Court of Appeals for the Fifth Circuit | https://www.ca5.uscourts.gov/opinions/pub/06/06-30356-CV0.wpd.pdf | Published November 13, 2006. Pinpoint: 571–72; official slip opinion pp. 2–4. Holds that HIPAA creates no private cause of action. Published circuit authority; binding force depends on jurisdiction. |
| GDPR-07 | Omnibus IV, COM(2025) 501 final/3, Article 1(2) | European Commission; EUR-Lex | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A52025PC0501R%2801%29 | May 21, 2025 initiative; corrected English text. Original proposal: fewer than 750 persons; high-risk processing exception. Separate from Digital Omnibus COM(2025) 837. |
| GDPR-08 | Omnibus IV final compromise, ST 10482/26 ADD 3, Article 1(2), p. 15 | Council of the European Union | https://data.consilium.europa.eu/doc/document/ST-10482-2026-ADD-3/en/pdf | June 19, 2026 negotiating text: fewer than 1,000 persons; RoPA remains for high-risk activities and core activities requiring a DPO under Article 37(1)(b)/(c). Recitals 8–10a explain scope. Not enacted at research cutoff. |
| GDPR-09 | Omnibus IV legislative procedure 2025/0130(COD) | European Parliament Legislative Observatory | https://oeil.europarl.europa.eu/oeil/en/procedure-file?reference=2025%2F0130%28COD%29 | Separate Omnibus IV procedure. At October 31, 2026: negotiated text endorsed in committee, not enacted. AFTER CUTOFF: Parliament adopted first-reading text November 24, 2026, P10_TA(2026)0382; OEIL awaits Council first-reading position. Publication and entry-into-force dates not verified. |
| GDPR-10 | Latombe v Commission, T-553/23: Official Journal judgment notice | General Court of the European Union; Official Journal | https://eur-lex.europa.eu/eli/C/2025/5446/oj/eng | Notice of September 3, 2025 judgment, ECLI:EU:T:2025:831. Use GDPR-13 for the full reasoned judgment. Appeal C-703/25 P is separately identified in GDPR-11. |
| GDPR-11 | Latombe appeal C-703/25 P, case record and June 4, 2026 intervention order | Court of Justice of the European Union; InfoCuria | https://infocuria.curia.europa.eu/tabs/redirect/juris/documents.jsf?num=C-703%2F25 | Appeal lodged October 31, 2025; pending at cutoff. ECLI:EU:C:2026:465 admits intervention, not a merits ruling. Order: https://juris.curia.europa.eu/juris/document/document.jsf?docid=312430&amp;doclang=FR |
| GDPR-12 | RW v Österreichische Post AG, C-154/21, judgment January 12, 2023 | Court of Justice of the European Union; EUR-Lex | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A62021CJ0154 | ECLI:EU:C:2023:3. Paragraph 51 and operative ruling interpret Article 15(1)(c): actual recipient identities, subject to impossibility and manifestly unfounded/excessive-request exceptions. |
| GDPR-13 | Latombe v Commission, T-553/23: full judgment September 3, 2025 | General Court of the European Union; EUR-Lex | https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A62023TJ0553 | ECLI:EU:T:2025:831; CELEX 62023TJ0553. Full judgment, distinct from the GDPR-10 Official Journal notice. Paragraph 22 concerns facts/law at adoption; operative ruling dismisses the action. Appeal material remains separately identified in GDPR-11. |
| HIPAA-34 | Purl v HHS, No. 2:24-cv-00228-Z: judgment, docket document 111 | U.S. District Court, Northern District of Texas; copy hosted by Georgetown Health Care Litigation Tracker | https://litigationtracker.law.georgetown.edu/wp-content/uploads/2024/10/Purl_2025.06.18_JUDGMENT.pdf | June 18, 2025 judgment, page 1, reproduced by Georgetown. Read with the July 3 amended judgment (HIPAA-35), HHS explanation (HIPAA-09), and September 10 appeal-dismissal order (HIPAA-36). This is a hosted court-document copy, not a direct court-docket retrieval. |
| HIPAA-35 | Purl v HHS, No. 2:24-cv-00228-Z: amended judgment, docket document 114 | U.S. District Court, Northern District of Texas; copy hosted by Georgetown Health Care Litigation Tracker | https://litigationtracker.law.georgetown.edu/wp-content/uploads/2024/10/Purl-M.D.-et-al_2205.07.03._AMENDED-JUDGMENT.pdf | July 3, 2025 amended judgment, page 1, reproduced by Georgetown. Retains vacatur and specified notice exceptions. Source filename has a year typo; the filed document identifies July 3, 2025. Appeal dismissal is documented in HIPAA-36. |
| HIPAA-36 | Purl v HHS, No. 25-10743: dismissal order and judgment issued as mandate | U.S. Court of Appeals for the Fifth Circuit; copy hosted by Georgetown Health Care Litigation Tracker | https://litigationtracker.law.georgetown.edu/wp-content/uploads/2025/09/Purl_2025.09.10_ORDER-ON-MOTION-TO-DISMISS.pdf | September 10, 2025, document 51-2, pp. 1–2. Appeal dismissed under FRAP 42(b) on appellants’ motion; clerk’s transmittal identifies judgment issued as mandate. Hosted court-document copy. The September 2 government letter states it did not notice an appeal: https://litigationtracker.law.georgetown.edu/wp-content/uploads/2025/09/Purl_2025.09.02_DEFENDANTS-LETTER.pdf |
