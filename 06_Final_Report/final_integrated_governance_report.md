# SECUREFINANCE AFRICA
## Final Integrated AI Ethics, Governance and Regulatory Compliance Report

**Course:** AICS-201 — AI Ethics, Governance and Legal Frameworks  
**Assignment:** Assignment 01 — Final Integrated Governance Report  
**Student:** Emmanuel Iheukwumere  
**Case Study:** SecureFinance Africa  
**Assessment Type:** Individual Case-Based Practical Assessment

---

# 1. Executive Summary

This report assesses the ethical, governance, legal and fairness implications of SecureFinance Africa, a fictional financial technology organisation proposing an AI platform for identity verification, fraud detection and financial risk assessment.

Six major ethical risks are examined: algorithmic bias, privacy violations, unfair automated decisions, inadequate transparency, insufficient human oversight and cybersecurity threats.

The NIST AI Risk Management Framework (AI RMF 1.0) provides the governance structure through its GOVERN, MAP, MEASURE and MANAGE functions. The legal assessment considers the Nigeria Data Protection Act 2023, the EU AI Act where applicable, the UNESCO Recommendation on AI Ethics and the OECD AI Principles.

A practical fairness experiment using 500 synthetic customer records identified an 18.13 percentage-point difference in selection rates between female and male groups. Counterfactual analysis showed that removing a deliberately introduced gender penalty changed 52 female decisions from ineligible to eligible. These findings concern the constructed simulation, not a real financial institution or deployed model.

I recommend conditional deployment approval only after appropriate governance, legal compliance, independent validation, fairness controls, cybersecurity safeguards and meaningful human oversight have been established.

# 2. System Description, Scope and Assumptions

## 2.1 Proposed system

SecureFinance Africa is a fictional financial technology organisation proposing an AI platform with three functions:

1. Customer identity verification.
2. Detection of suspicious financial activities and fraud.
3. Financial risk assessment to support customer decisions.

The platform may process identity and financial information and generate outputs that influence transactions or access to financial products. Incorrect outputs could cause financial losses, unfair rejection or inconvenience to customers.

## 2.2 Assessment scope

This assessment examines ethical risks, data protection, AI governance, fairness, explainability, human oversight, cybersecurity and relevant regulatory requirements. It considers effects on customers, employees, management and regulators.

## 2.3 Assumptions and limitations

The organisation and system are fictional. No real customer or confidential financial information was used.

The fairness experiment uses 500 synthetic records and a deliberately introduced gender-related penalty. The risk scores and residual ratings are preliminary estimates based on the case-study assumptions, not results of an actual organisational audit.

The findings therefore assess a proposed system and do not establish actual misconduct or operational failures.

# 3. Ethical Risk Assessment

## 3.1 Algorithmic bias and discrimination

**Cause:** Biased data, unsuitable variables or discriminatory decision rules.

**Affected stakeholders:** Customers, particularly groups disadvantaged by automated assessments.

**Consequences:** Unequal financial access, reputational damage and possible regulatory consequences.

**Controls:** Test outcomes across demographic groups, review input variables, document limitations and investigate unexplained disparities.

## 3.2 Privacy and excessive data collection

**Cause:** Collecting unnecessary personal information, excessive retention or unauthorised access.

**Affected stakeholders:** Customers and the organisation.

**Consequences:** Identity theft, privacy violations, financial harm and regulatory penalties.

**Controls:** Establish lawful processing, minimise data collection, provide privacy notices, restrict access and apply retention and security controls.

## 3.3 Unfair automated financial decisions

**Cause:** Inaccurate information, unsuitable thresholds or unreliable risk predictions.

**Affected stakeholders:** Customers seeking financial services.

**Consequences:** Incorrect rejection, reduced financial access and loss of customer trust.

**Controls:** Validate decision rules, provide appropriate human review, explain significant decisions and establish appeal procedures.

## 3.4 Lack of transparency and explainability

**Cause:** Unclear decision logic, inadequate documentation or inaccessible explanations.

**Affected stakeholders:** Customers, employees and regulators.

**Consequences:** Customers may be unable to challenge errors, while reviewers may struggle to identify weaknesses.

**Controls:** Maintain model documentation and decision records, provide understandable explanations and enable authorised review.

## 3.5 Inadequate human oversight

**Cause:** Excessive reliance on automated recommendations and weak escalation procedures.

**Affected stakeholders:** Customers, operational employees and management.

**Consequences:** Errors or unfair decisions may pass without appropriate examination.

**Controls:** Define mandatory review cases, train reviewers, provide override authority and establish escalation procedures.

## 3.6 Cybersecurity and confidentiality

**Cause:** Unauthorised access, data theft, system manipulation or security weaknesses.

**Affected stakeholders:** Customers and the organisation.

**Consequences:** Financial loss, compromised information and operational disruption.

**Controls:** Apply authentication, access restrictions, encryption, security monitoring, vulnerability management and incident response.

# 4. AI Governance and Risk Management

## 4.1 Application of the NIST AI Risk Management Framework

I selected the NIST AI Risk Management Framework (AI RMF 1.0) to structure the proposed governance approach for SecureFinance Africa. The framework has four functions:

- **GOVERN:** Establish accountability, policies, responsibilities and management oversight.
- **MAP:** Identify the system's purpose, operating environment, stakeholders and potential risks.
- **MEASURE:** Evaluate accuracy, fairness, privacy, security, reliability and explainability.
- **MANAGE:** Prioritise risks, implement controls, monitor outcomes and respond to incidents.

These functions should operate throughout the AI system lifecycle.

## 4.2 Governance responsibilities

SecureFinance Africa should assign responsibilities as follows:

| Role | Responsibility |
|---|---|
| Senior management | Approve strategy, resources and deployment decisions. |
| AI Governance Committee | Oversee AI policies, risks and system performance. |
| Data Protection Officer | Advise on privacy, data protection and DPIAs. |
| AI Development Team | Document, test and validate the system. |
| Compliance and Legal Team | Review applicable legal requirements. |
| Information Security Team | Manage cybersecurity controls and incidents. |
| Human Review Officers | Examine disputed decisions and escalate errors. |

These are proposed roles for the fictional organisation.

## 4.3 Risk scoring methodology

I used a qualitative risk matrix. Likelihood and impact are each scored from 1 to 5.

**Risk score = Likelihood × Impact**

| Score | Classification |
|---|---|
| 1–4 | Low |
| 5–9 | Medium |
| 10–16 | High |
| 17–25 | Critical |

Residual risk represents the estimated risk remaining after proposed controls. These estimates have not been validated through an operational audit.

## 4.4 AI risk register

| ID | Risk | Likelihood | Impact | Score | Owner | Proposed control | Residual risk |
|---|---|---:|---:|---:|---|---|---|
| R01 | Algorithmic bias | 4 | 5 | 20 | AI Governance Committee | Fairness testing and independent validation | Medium |
| R02 | Privacy violations | 4 | 5 | 20 | Data Protection Officer | Lawful processing, minimisation, access and retention controls | Medium |
| R03 | Inaccurate fraud detection | 4 | 4 | 16 | Fraud Operations Manager | Threshold testing and human investigation | Medium |
| R04 | Incorrect financial risk assessments | 3 | 5 | 15 | Credit Risk Manager | Validation, explanations and appeals | Medium |
| R05 | Insufficient transparency | 4 | 4 | 16 | AI Product Manager | Decision records and model documentation | Medium |
| R06 | Inadequate human oversight | 3 | 5 | 15 | Operations Manager | Review procedures, training and override authority | Low |
| R07 | Cybersecurity breach | 3 | 5 | 15 | Information Security Manager | Encryption, authentication and security monitoring | Medium |
| R08 | Model drift | 3 | 4 | 12 | AI Development Lead | Performance monitoring and periodic validation | Medium |

The initial scores reflect the fictional system's assumed risk exposure. Residual ratings are estimates based on proposed controls, not verified operational results.

## 4.5 Monitoring and incident management

The organisation should monitor fairness metrics, fraud detection errors, model performance, data protection complaints, security alerts and customer appeals.

Serious incidents should be reported to the relevant risk owner and escalated to the AI Governance Committee and senior management. Where necessary, the affected system function should be suspended while the incident is investigated.

Human reviewers should have adequate training, access to relevant decision information and authority to challenge automated recommendations.

## 4.6 Accountability and review

The AI Governance Committee should periodically review risk assessments, testing evidence, complaints, incidents and corrective actions. Significant changes to system purpose, data sources or decision rules should trigger reassessment and documented approval.

# 5. Legal and Regulatory Compliance

## 5.1 Nigeria Data Protection Act 2023

The Nigeria Data Protection Act (NDPA) 2023 is directly relevant because SecureFinance Africa would process customers' identity and financial information.

The organisation should establish a lawful basis for processing, provide transparent privacy information, collect only necessary data and implement appropriate security and retention controls.

Section 28 provides for a Data Protection Impact Assessment (DPIA) where processing is likely to create high risks to individuals' rights and freedoms. Given the proposed profiling and financial assessments, SecureFinance Africa should assess the need for a DPIA before deployment and address identified risks.

Section 37 addresses decisions based solely on automated processing, including profiling, where they produce legal or similarly significant effects. The Act provides specified exceptions subject to safeguards. Relevant safeguards include the ability to obtain human intervention, express a point of view and contest a decision.

Accordingly, the organisation should establish appropriate human review and challenge procedures for significant financial decisions. It should also maintain suitable technical and organisational security measures and procedures for managing personal data breaches.

## 5.2 European Union Artificial Intelligence Act

Regulation (EU) 2024/1689 establishes a risk-based framework for AI systems. It may apply to organisations outside the EU where the conditions in Article 2 are met, including certain systems placed on the EU market or outputs used within the EU.

Annex III, point 5(b), generally classifies AI systems used to evaluate the creditworthiness of natural persons or establish their credit scores as high-risk. However, it excludes systems used solely to detect financial fraud from this particular classification.

This distinction matters because SecureFinance Africa proposes both fraud detection and financial risk assessment. Its fraud detection function should not automatically be treated as high-risk under this provision. Its creditworthiness assessment function may qualify as high-risk where the Act applies.

Where the high-risk requirements apply, the organisation should consider obligations concerning risk management, data governance, technical documentation, record-keeping, transparency, human oversight, accuracy, robustness and cybersecurity.

The organisation should assess each function separately and obtain appropriate legal advice before operating in the EU.

## 5.3 UNESCO Recommendation on the Ethics of Artificial Intelligence

UNESCO adopted its Recommendation on the Ethics of Artificial Intelligence in 2021. It promotes human rights, dignity, fairness, non-discrimination, transparency, privacy, accountability and human oversight.

These principles are relevant because the proposed platform may influence access to financial services and process personal information. SecureFinance Africa should use them to guide responsible system design and operation.

The Recommendation is a non-binding international instrument. It provides ethical and policy guidance rather than imposing the same direct legal obligations as national legislation.

## 5.4 OECD AI Principles

The OECD AI Principles promote trustworthy AI through inclusive growth, human-centred values, fairness, transparency, robustness, security, safety and accountability.

They provide useful guidance for documenting system limitations, monitoring outcomes and maintaining responsibility for automated decisions. They are policy principles, not a directly binding statute.

## 5.5 Comparison of frameworks

| Framework | Nature | Relevance |
|---|---|---|
| Nigeria Data Protection Act 2023 | Binding Nigerian legislation | Governs applicable personal-data processing and automated decision safeguards. |
| EU AI Act 2024 | Binding EU regulation within its scope | May regulate qualifying creditworthiness assessment systems. |
| UNESCO AI Recommendation 2021 | Non-binding international recommendation | Guides human rights, fairness, privacy and oversight. |
| OECD AI Principles | Non-binding policy principles | Supports transparency, accountability and trustworthy AI. |

## 5.6 Compliance recommendations

SecureFinance Africa should:

1. Document a lawful basis and purpose for each personal-data processing activity.
2. Conduct a DPIA where required and address identified high risks.
3. Provide clear privacy notices and appropriate ways to exercise data rights.
4. Establish human intervention and challenge procedures for significant automated decisions.
5. Apply suitable access controls, security measures and retention limits.
6. Assess EU AI Act territorial scope and system classification before entering the EU market.
7. Use UNESCO and OECD principles to strengthen internal ethical governance.

## 5.7 Compliance conclusion

The NDPA 2023 is central to the proposed Nigerian deployment. The EU AI Act requires a separate assessment where its territorial scope is met. UNESCO and OECD instruments provide complementary ethical guidance but are not equivalent to binding legislation.

Compliance should be reviewed throughout the system lifecycle, with documented assessments, controls and accountability.

# 6. Fairness and Explainability Evaluation

## 6.1 Assessment objective and methodology

I conducted a fairness assessment to examine how a simulated financial eligibility decision rule could produce unequal outcomes across demographic groups. The experiment used Python, Pandas, Fairlearn, Matplotlib and JupyterLab.

The assessment included group selection rates, true positive rates (TPR), false positive rates (FPR), false negative rates (FNR), individual decision reviews and counterfactual analysis.

## 6.2 Synthetic dataset and data quality

I generated 500 fictional customer records: 256 female and 244 male. No real customer or financial information was used.

The dataset contained zero missing values and zero duplicate records. A gender-related penalty was deliberately introduced into the simulated decision rule to demonstrate how an inappropriate variable can influence eligibility outcomes.

This was a constructed decision mechanism, not a trained or deployed machine learning model.

## 6.3 Fairness metrics and results

I used the following metrics:

- **Selection rate:** Proportion of each group classified as eligible.
- **True positive rate:** Proportion of actually eligible records correctly classified as eligible.
- **False positive rate:** Proportion of actually ineligible records incorrectly classified as eligible.
- **False negative rate:** Proportion of actually eligible records incorrectly classified as ineligible.

The Fairlearn analysis produced these results:

| Metric | Female | Male | Absolute difference |
|---|---:|---:|---:|
| Selection rate | 26.95% | 45.08% | 18.13 percentage points |
| True positive rate | 57.02% | 93.58% | 36.55 percentage points |
| False positive rate | 0.00% | 5.93% | 5.93 percentage points |
| False negative rate | 42.98% | 6.42% | 36.55 percentage points |

The female-to-male selection-rate ratio was approximately 0.598. This means the female selection rate was about 59.8% of the male rate.

The false negative rate was also substantially higher for female records. Approximately 42.98% of actually eligible female records were classified as ineligible, compared with 6.42% of male records.

These results demonstrate unequal outcomes within the constructed dataset. They do not establish discrimination in a real organisation or production AI system.

## 6.4 Counterfactual analysis

I compared the original simulated decisions with decisions generated after removing the deliberately introduced gender penalty while preserving the other relevant scoring components.

The analysis produced the following results:

- Total records: 500.
- Female records: 256.
- Male records: 244.
- Female decisions changed: 52.
- Male decisions changed: 0.
- Total decisions changed: 52, representing 10.40% of all records.
- Percentage of female decisions changed: 20.31%.

All 52 changed decisions moved from ineligible to eligible after removal of the penalty.

This demonstrates the effect of the deliberately introduced penalty within the simulation. It is not evidence of a causal effect in a real-world financial system.

## 6.5 Individual decision review and explainability

I reviewed individual records using their financial scores, gender-related adjustments, prediction scores and eligibility classifications. This helped illustrate how decision components can be examined to identify potentially unfair rules.

A production system should maintain documented decision logic, provide explanations appropriate to the decision and allow authorised staff to investigate disputed outcomes.

## 6.6 Evidence and reproducibility

The project repository contains the Jupyter notebook and synthetic dataset, together with the following evidence:

**Visualisations**
- `visualisations/fairness_metrics.png`
- `visualisations/counterfactual_analysis.png`

**CSV results**
- `analysis_results/fairness_metrics_by_gender.csv`
- `analysis_results/fairness_group_differences.csv`
- `analysis_results/fairness_group_ratios.csv`
- `analysis_results/counterfactual_results.csv`
- `analysis_results/individual_decision_review.csv`

These files support examination and reproduction of the documented experiment.

## 6.7 Recommendations and conclusion

SecureFinance Africa should remove unjustified demographic penalties, investigate differences in selection and error rates, validate data quality, conduct group-level fairness testing and introduce human review for disputed or significant decisions.

Fairness monitoring should continue after deployment, with documented thresholds, corrective actions and reassessment after material model or data changes.

The experiment demonstrates why fairness, explainability and human oversight are necessary safeguards for automated financial decisions.

# 7. Prioritised Recommendations

## 7.1 Immediate actions

1. Establish an AI Governance Committee with documented accountability.
2. Investigate and remove unjustified demographic penalties.
3. Complete applicable data protection assessments and document lawful processing.
4. Introduce human review and customer challenge procedures for significant decisions.

## 7.2 Medium-term actions

5. Improve decision transparency and maintain model documentation.
6. Strengthen cybersecurity through access controls, encryption and security monitoring.
7. Monitor fairness, accuracy, false-positive rates, false-negative rates and model drift.

## 7.3 Long-term actions

8. Arrange independent assurance of fairness, security and governance controls.
9. Review regulatory obligations before entering additional markets.
10. Conduct periodic governance reviews and document corrective actions.

# 8. Deployment Recommendation

## 8.1 Overall decision

I recommend that SecureFinance Africa should not proceed with unrestricted deployment at this stage.

The synthetic fairness experiment demonstrated substantial differences in eligibility outcomes. The wider assessment also identified privacy, cybersecurity, transparency and oversight risks that require effective controls.

## 8.2 Conditions for deployment

Deployment should be considered only after the organisation has:

- Established accountable AI governance.
- Completed applicable legal and data protection assessments.
- Removed unjustified discriminatory decision rules.
- Conducted independent fairness and system validation.
- Implemented human review and customer appeal procedures.
- Established cybersecurity, monitoring and incident response controls.

Any initial deployment should be limited and closely monitored, with clear suspension criteria. Important decisions should not rely solely on unverified automated outputs.

**Decision: Conditional approval only after remediation and independent validation.** This is not approval for immediate production deployment.

# 9. Conclusion

This assessment examined the ethical, governance, legal and fairness implications of the proposed SecureFinance Africa platform.

It identified six ethical risks, developed an eight-item risk register using NIST AI RMF functions and reviewed relevant Nigerian and international frameworks.

The synthetic fairness experiment identified an 18.13 percentage-point selection-rate difference and showed that removing the simulated gender penalty changed 52 female decisions. These results demonstrate the importance of fairness testing but do not establish discrimination in a real system.

Responsible deployment requires lawful data processing, accountability, fairness, transparency, cybersecurity and meaningful human oversight. I therefore recommend conditional deployment approval only after the identified risks have been addressed and independently validated.

# 10. References

1. National Institute of Standards and Technology (NIST). (2023). *Artificial Intelligence Risk Management Framework (AI RMF 1.0).* https://doi.org/10.6028/NIST.AI.100-1

2. Federal Republic of Nigeria. (2023). *Nigeria Data Protection Act 2023.* Nigeria Data Protection Commission. https://ndpc.gov.ng/

3. European Parliament and Council of the European Union. (2024). *Regulation (EU) 2024/1689 laying down harmonised rules on artificial intelligence (Artificial Intelligence Act).* https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng

4. European Commission. *AI Act Service Desk: Annex III — High-risk AI systems.* https://ai-act-service-desk.ec.europa.eu/en/ai-act/annex-3

5. United Nations Educational, Scientific and Cultural Organization (UNESCO). (2021). *Recommendation on the Ethics of Artificial Intelligence.* https://www.unesco.org/en/legal-affairs/recommendation-ethics-artificial-intelligence

6. Organisation for Economic Co-operation and Development (OECD). *OECD AI Principles.* https://oecd.ai/en/ai-principles

7. Fairlearn. *Fairlearn documentation.* https://fairlearn.org/

8. McKinney, W. (2010). Data Structures for Statistical Computing in Python. *Proceedings of the 9th Python in Science Conference.* https://doi.org/10.25080/Majora-92bf1922-00a

9. Hunter, J. D. (2007). Matplotlib: A 2D Graphics Environment. *Computing in Science & Engineering, 9*(3), 90–95. https://doi.org/10.1109/MCSE.2007.55

---

# Appendix A: Project Repository

**GitHub repository:**  
https://github.com/Manuelz1992/AICS-201-AI-Ethics-Governance

The repository contains the project documentation, ethical risk assessment, AI governance analysis, legal compliance review, synthetic dataset, fairness analysis notebook, exported results and visual evidence.

# Appendix B: Academic Integrity and Use of Tools

This assessment was developed using a combination of independent analysis, practical experimentation and technical documentation.

Python, Pandas, Fairlearn, Matplotlib and JupyterLab were used to create and analyse the synthetic dataset. Git and GitHub were used for version control and project documentation.

AI-assisted support was used for guidance on report organisation, technical explanations and document refinement. The practical dataset, analysis outputs and reported experimental findings are based on the documented synthetic-data exercise. No real customer records or confidential organisational information were used.
