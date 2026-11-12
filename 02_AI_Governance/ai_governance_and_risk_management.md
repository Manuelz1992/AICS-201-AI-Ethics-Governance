# TASK 2: AI GOVERNANCE AND RISK MANAGEMENT

## 1. Introduction

In this section, I applied the NIST AI Risk Management Framework (AI RMF 1.0) to develop a governance approach for SecureFinance Africa's proposed AI-powered financial platform.

The platform supports customer identity verification, fraud detection and automated financial risk assessment. Since its recommendations may influence customers' access to financial services, I consider effective governance, accountability and continuous risk monitoring essential before deployment.

I used the four NIST AI RMF functions: GOVERN, MAP, MEASURE and MANAGE to organise my assessment.

## 2. Application of the NIST AI Risk Management Framework

### 2.1 GOVERN – Establishing Accountability

I recommend that SecureFinance Africa establish an AI governance structure before deploying the platform.

The proposed responsibilities are:

- Senior Management: Approve AI governance policies, provide resources and accept or reject significant residual risks.
- AI Governance Committee: Review AI-related risks, approve deployment conditions and monitor compliance.
- Data Protection Officer: Oversee personal data processing, privacy safeguards and data protection obligations.
- AI Development Team: Maintain model documentation, testing records and technical safeguards.
- Compliance and Legal Team: Review applicable legal requirements and regulatory developments.
- Security Team: Protect the platform, monitor threats and coordinate security incident response.
- Human Review Officers: Examine significant or disputed automated recommendations and escalate questionable outcomes.

I recommend that responsibilities be formally documented so that accountability is not transferred entirely to the technology provider or AI model.

### 2.2 MAP – Identifying Context and Risks

I identified the following important characteristics of the proposed system:

- It processes customer identity and financial information.
- It analyses transaction patterns.
- It generates fraud-related alerts.
- It produces financial risk recommendations.
- Its outputs may influence customers' financial opportunities and treatment.

The principal stakeholders include customers, employees, management, technology providers, regulators and business partners.

I consider privacy, discrimination, inaccurate predictions, cybersecurity, lack of transparency and excessive reliance on automated decisions to be important risks requiring assessment.

### 2.3 MEASURE – Evaluating AI Risks

I recommend that the organisation establish measurable indicators to evaluate system performance and potential harm.

The proposed measurements include:

- False positive and false negative rates for fraud detection.
- Selection rates across relevant demographic groups.
- Differences in model performance between customer groups.
- Accuracy and reliability of identity verification.
- Frequency of human overrides.
- Number and severity of privacy or security incidents.
- Customer complaints and disputed decisions.
- Model performance changes over time.

The fairness analysis conducted in Task 4 provides an initial practical example of how demographic differences can be measured using synthetic data.

All measurements should be documented, reviewed periodically and interpreted in the context of the system's intended use.

### 2.4 MANAGE – Risk Treatment and Monitoring

I recommend that SecureFinance Africa use the following risk-management measures:

1. Prioritise risks according to their likelihood and potential impact.
2. Introduce appropriate technical and organisational safeguards.
3. Require human review for significant or disputed decisions.
4. Maintain records of model versions, decisions and corrective actions.
5. Monitor performance and fairness after deployment.
6. Establish procedures for reporting and investigating incidents.
7. Suspend or restrict system functions where serious risks cannot be adequately controlled.
8. Reassess risks whenever the model, data, operating environment or intended use changes.

I recommend that deployment approval be conditional on evidence that significant risks have been adequately addressed.

## 3. AI Risk Assessment Methodology

For this assessment, I used a qualitative five-point scoring approach.

Likelihood:
1 – Rare
2 – Unlikely
3 – Possible
4 – Likely
5 – Almost certain

Impact:
1 – Insignificant
2 – Minor
3 – Moderate
4 – Major
5 – Severe

Risk score = Likelihood × Impact.

Risk classification:

- Low: 1–4
- Medium: 5–9
- High: 10–16
- Critical: 17–25

These scores are my preliminary assessment assumptions based on the fictional system description. They are not measurements from a deployed production system.

## 4. AI Risk Register

| ID | Risk | Likelihood | Impact | Score | Owner | Proposed control | Residual risk |
|---|---|---:|---:|---:|---|---|---|
| R01 | Algorithmic bias and discrimination | 4 | 5 | 20 | AI Governance Committee | Demographic fairness testing, representative data and independent review | Medium |
| R02 | Privacy violations and excessive data collection | 4 | 5 | 20 | Data Protection Officer | Data minimisation, lawful processing, access controls and retention policies | Medium |
| R03 | Inaccurate fraud detection | 4 | 4 | 16 | Fraud Operations Manager | Model validation, threshold reviews and human investigation | Medium |
| R04 | Inaccurate financial risk recommendations | 3 | 5 | 15 | Credit Risk Manager | Independent validation, decision review and appeal procedures | Medium |
| R05 | Lack of transparency and explainability | 4 | 4 | 16 | AI Product Manager | Explainability testing, decision records and customer-facing explanations | Medium |
| R06 | Inadequate human oversight | 3 | 5 | 15 | Operations Manager | Mandatory review procedures, staff training and escalation authority | Low |
| R07 | Cybersecurity breach or unauthorised access | 3 | 5 | 15 | Information Security Manager | Encryption, strong authentication, monitoring and security testing | Medium |
| R08 | Model drift and declining performance | 3 | 4 | 12 | AI Development Lead | Continuous monitoring, periodic validation and controlled model updates | Medium |

The residual-risk ratings represent my estimated risk levels after implementing the proposed controls. They are not evidence that these controls have already been implemented or tested.

## 5. Human Oversight and Accountability

I recommend that automated recommendations should not be treated as unquestionable decisions, particularly where they could significantly affect customers.

Human reviewers should be able to:

- Examine the information supporting an AI recommendation.
- Identify inaccurate or incomplete input data.
- Challenge recommendations that appear unfair or unreliable.
- Request additional verification where necessary.
- Override inappropriate recommendations with documented reasons.
- Escalate serious or recurring problems to the appropriate management team.

The organisation should also maintain audit records showing who reviewed or changed significant decisions and why.

## 6. Continuous Monitoring and Incident Escalation

I recommend that SecureFinance Africa introduce a formal monitoring and escalation process.

The process should include:

1. Detection: Identify unusual model behaviour, security events, unfair outcomes or customer complaints.
2. Reporting: Record the incident and notify the responsible team.
3. Assessment: Determine the affected system components, customers and potential consequences.
4. Containment: Restrict or suspend affected functionality where necessary.
5. Investigation: Establish the cause and preserve relevant records.
6. Remediation: Correct the underlying problem and validate the corrective action.
7. Review: Update the risk register and report significant findings to management.

Serious privacy and security incidents should also be assessed for applicable legal notification obligations.

## 7. Deployment Governance Recommendation

Based on my assessment, I do not recommend immediate unrestricted deployment of the proposed platform.

I recommend a controlled deployment approach, subject to the following conditions:

- Completion of independent model validation.
- Evidence of acceptable fairness performance.
- Implementation of privacy and cybersecurity safeguards.
- Documented human oversight procedures.
- Approved incident response and escalation arrangements.
- Defined monitoring indicators and review intervals.
- Formal approval of remaining risks by authorised management.

If significant risks remain uncontrolled, deployment should be delayed until appropriate corrective measures have been completed.

## 8. Conclusion

My application of the NIST AI Risk Management Framework shows that effective AI governance requires more than technical accuracy. It requires clear accountability, proper risk identification, measurable performance indicators and continuous risk management.

I identified eight significant risks and proposed controls to reduce their likelihood or impact. I consider algorithmic discrimination, privacy violations and inaccurate financial recommendations particularly important because of their potential consequences for customers.

I therefore recommend that SecureFinance Africa adopt the proposed governance structure and risk-management controls before allowing the system to influence consequential customer decisions.

## 9. Reference

National Institute of Standards and Technology (NIST) (2023). Artificial Intelligence Risk Management Framework (AI RMF 1.0). NIST AI 100-1.

https://doi.org/10.6028/NIST.AI.100-1

