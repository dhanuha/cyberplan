# Cybersecurity Plan for our Website

## About the Project

**HerSafeHome** is a final semester project developed by our team of four students at Monash University, bringing together expertise from diverse fields:

- **Cybersecurity**: My role, focused entirely on securing the application and its data.
- **MBIS** 
- **Data Science**
- **IT**

The platform addresses gender inequality in urban safety by helping women find safer walking routes using data on streetlights and emergency services. By leveraging our unique strengths, we created a solution that empowers users to navigate their environments confidently, particularly at night.

## Technologies Used

- **Frontend**: Built using React with AWS Amplify for seamless user interactions.
- **Backend**: Node.js running on AWS Lambda for scalable and efficient processing.
- **Database**: PostgreSQL hosted on AWS RDS, with automated data encryption.
- **DNS**: Managed by AWS Route 53 for reliable domain resolution.

The project integrates security, usability, and data insights to deliver a robust and impactful solution.

---

## My Contribution as the Cybersecurity Lead

As the sole cybersecurity lead for this project, I was fully responsible for all security-related aspects, including:

1. **Vulnerability Assessment**: 
   - Conducted penetration testing using OWASP ZAP and Nmap.
   - Performed STRIDE-based vulnerability analysis with associated CVEs.

2. **Mitigation Strategies**: 
   - Implemented SSL/TLS for secure communication.
   - Configured headers (HSTS, CSP, X-Frame-Options) to mitigate clickjacking, XSS, and related risks.

3. **Incident Management**:
   - Developed an Incident Response Plan outlining detection, containment, and recovery steps.
   - Used AWS monitoring tools to ensure continuous system integrity.

4. **Documentation**: 
   - Prepared the comprehensive cybersecurity plan, detailing risk assessments, mitigation strategies, and incident management protocols.

5. **Security Education**:
   - Explained and demonstrated implemented security measures to the team, helping them understand the importance of secure application design.

---

## Security Features Implemented

### Addressing OWASP Top 10 Risks

- **Sensitive Data Exposure**: 
   - SSL encryption for data in transit.
   - AWS RDS encryption for data at rest.
- **Security Misconfiguration**: 
   - Regular updates and security audits.
- **Cross-Site Scripting (XSS)**:
   - Input validation and CSP headers.
- **SQL Injection**:
   - Parameterized queries and secure database interactions.



### STRIDE Analysis

I conducted a STRIDE-based analysis to identify potential vulnerabilities across six categories (Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege). Mitigation strategies were developed for each identified threat, with examples linked to relevant CVEs.

---

## Risk Management

The Risk Register tracks the likelihood, impact, and current status of identified vulnerabilities. Key mitigations include:

- Restricting CORS policies to specific domains.
- Enforcing HTTPS with HSTS headers.
- Validating all user inputs to prevent malicious actions.

---

## Incident Management Plan

A robust plan ensures the project is prepared for any security incidents:

1. **Detection**: Continuous monitoring using automated tools.
2. **Containment**: Isolating affected components to prevent escalation.
3. **Eradication**: Addressing root causes and verifying system integrity.
4. **Recovery**: Gradual restoration of services and monitoring for recurrence.

---

## Lessons Learned

This project was an incredible opportunity for me to apply my cybersecurity knowledge to a real-world problem. By collaborating with a multidisciplinary team, I honed my technical and communication skills, ensuring that security was seamlessly integrated into every aspect of the project.

Additionally, I learned how to use **LeanKit** for project tracking and **Miro** retrospectives at the end of every iteration. These tools were invaluable for maintaining organization, reflecting on progress, and planning actionable improvements for each phase of the project.

---

## Repository Contents

- **Cybersecurity Plan**: Detailed documentation of all security efforts.
- **Incident Response Plan**: Steps for managing potential security incidents.
- **Risk Register**: Comprehensive list of vulnerabilities, impacts, and mitigation efforts.

## Document
- access the detailed [cybersecurity plan](./CyberSecurityPlan.pdf).
