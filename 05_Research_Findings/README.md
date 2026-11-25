# Research Findings

## Regulatory Scope

The comparison identified four dimensions along which coverage differs: organizations covered, information protected, territorial applicability and the boundary between identifiable and de-identified or anonymous information. Both frameworks assign responsibilities for protecting identifiable health information, but their coverage boundaries are not interchangeable. These findings reflect the October 31, 2026 baseline.

### Organizations Covered

HIPAA coverage centers on defined covered entities and business associates. Covered entities include health plans, health care clearinghouses and healthcare providers conducting specified electronic transactions. Business associates perform qualifying functions or services involving protected health information on behalf of covered entities, including through subcontracting relationships. GDPR assigns controller and processor roles across sectors, subject to its material and territorial scope. Handling health information alone therefore does not establish HIPAA coverage, while operating outside healthcare does not exclude GDPR coverage (45 CFR §§ 160.102–160.103; Regulation (EU) 2016/679, Articles 2–4).

### Information Protected

HIPAA protects individually identifiable health information within its coverage boundaries, subject to specified exclusions. Its Privacy Rule covers protected health information in different forms; its Security Rule addresses electronic protected health information. GDPR protects personal data within its material scope and treats health data as a special category. Article 2(1) covers wholly or partly automated processing and nonautomated processing of personal data that form part of, or are intended to form part of, a filing system. Coverage therefore depends on the information and processing context, rather than sensitivity alone (45 CFR § 160.103; Regulation (EU) 2016/679, Articles 2, 4 and 9).

### Territorial Applicability and International Transfers

The comparison distinguishes whether a framework applies from the conditions governing overseas processing. HIPAA coverage follows covered-entity and business-associate relationships rather than an establishment or targeting test equivalent to GDPR Article 3. GDPR applicability depends on its territorial criteria, including EU establishment and specified offering-of-goods-or-services or monitoring activities involving people in the EU. Separately, GDPR Chapter V regulates transfers of personal data to third countries or international organizations. HHS guidance permits overseas cloud storage when applicable HIPAA requirements are satisfied, including business-associate arrangements and assessment of geographic risks. Overseas-storage permission therefore should not be compared directly with GDPR's applicability test (45 CFR §§ 160.102–160.103; Regulation (EU) 2016/679, Article 3 and Chapter V; U.S. Department of Health and Human Services [HHS], n.d.-b).

### De-identification and the Boundary of Protection

Whether information remains identifiable creates another important coverage distinction. Information meeting HIPAA's de-identification requirements through Expert Determination or Safe Harbor is no longer protected health information. Under GDPR, pseudonymisation does not itself remove information from protection: data attributable to an individual using additional information remain personal data. Anonymous information falls outside GDPR where individuals are no longer identifiable under the assessment described in Recital 26. Consequently, satisfying HIPAA de-identification requirements does not automatically establish GDPR anonymity (45 CFR § 164.514(a)–(b); Regulation (EU) 2016/679, Recital 26 and Article 4(5); HHS, n.d.-a).

### Implications for Health-data Processing and AI Training

Healthcare organizations and other entities processing health data must assess applicability separately under each framework. Shared safeguards can support governance, but cannot replace identification of the relevant organizational roles, information, activities and territorial conditions.

This distinction also matters when treatment data are reused for AI training. HIPAA-de-identified information may remain personal data under GDPR. Where identifiable health data remain within GDPR, reuse requires an appropriate Article 6 basis and Article 9 condition, alongside assessment of purpose limitation and other applicable duties. Permission to process information for treatment does not automatically establish permission for a vendor's separate model-training purpose (Regulation (EU) 2016/679, Articles 5, 6 and 9). These findings identify differences in coverage and reuse conditions rather than a general permission or prohibition on AI training. They concern regulatory responsibilities, not measured improvements in privacy, security or patient outcomes.

## References

45 CFR §§ 160.102–160.103. (2026). General administrative requirements, October 31 historical version.

https://www.ecfr.gov/on/2026-10-31/title-45/subtitle-A/subchapter-C/part-160

45 CFR § 164.514. (2026). Other requirements relating to uses and disclosures of protected health information, October 31 historical version.

https://www.ecfr.gov/on/2026-10-31/title-45/subtitle-A/subchapter-C/part-164/section-164.514

Regulation (EU) 2016/679 of the European Parliament and of the Council of 27 April 2016. (2016). *Official Journal of the European Union, L 119*, 4 May 2016, 1–88.

https://eur-lex.europa.eu/eli/reg/2016/679/oj/eng

U.S. Department of Health and Human Services. (n.d.-a). *Guidance regarding methods for de-identification of protected health information in accordance with the Health Insurance Portability and Accountability Act (HIPAA) Privacy Rule.*

https://www.hhs.gov/hipaa/for-professionals/special-topics/de-identification/index.html

U.S. Department of Health and Human Services. (n.d.-b). *Guidance on HIPAA & cloud computing.* See “Do the HIPAA Rules allow a covered entity or business associate to use a CSP that stores ePHI on servers outside of the United States?”

https://www.hhs.gov/hipaa/for-professionals/special-topics/health-information-technology/cloud-computing/index.html

## Supporting Comparison Matrix

These findings synthesize the matrix's regulatory-scope comparisons and its de-identification, anonymisation and pseudonymisation comparison. The AI-training example illustrates an implication of those distinctions; it is not a separate empirical study.

[Read the comparison matrix](../04_Comparison_Matrix/README.md)
