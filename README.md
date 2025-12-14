# CS305-Journal-Portfolio


**Client and requirements:**

Artemis Financial was the client. The company wanted its software modernized with stronger security because it handled sensitive financial data. The main issue to address was identifying security risks in the application and refactoring it to improve secure communication, data integrity, and overall protection against common vulnerabilities.

**What I did well and why secure coding matters:**

I did well at systematically reviewing the application for weaknesses and using tooling to surface dependency risks. Coding securely is important because security issues can lead to data breaches, financial loss, reputational damage, and compliance problems. Strong software security adds value by reducing risk, improving trust, and helping the company protect customer data and maintain business continuity.

**Most challenging or helpful part of the vulnerability assessment:**

The most challenging part was interpreting vulnerability scan results and determining whether a finding was actionable, a false positive, or required a design-level mitigation. The most helpful part was learning how to use scanning outputs as evidence to guide decisions rather than guessing.

**How I increased layers of security and what I would use in the future:**

I increased security by applying layered defenses such as secure transport (HTTPS/TLS), integrity checks (hashing/checksum), safer configuration practices, and dependency vulnerability scanning. In the future, I would continue using automated tools (static analysis and dependency scanning), threat modeling, and secure design reviews to assess vulnerabilities and then select mitigations based on impact, likelihood, and feasibility.

**How I ensured the application stayed functional and secure after refactoring:**

I verified functionality by running the application and confirming the required features still worked after changes. To ensure security, I re-ran vulnerability scans and reviewed the output to confirm improvements and to check whether any new issues were introduced. I also validated configuration changes (such as HTTPS settings) and confirmed the application ran without errors.

**Resources, tools, and practices used:**

I used secure coding practices, configuration hardening, hashing for integrity, certificate/HTTPS setup, and automated security tools such as OWASP Dependency-Check to identify vulnerable third-party components. These tools and practices will be helpful in future work because they provide repeatable ways to detect and reduce security risks.

**What I would show employers from this assignment:**

I would show the completed security assessment or secure practices report and the evidence of mitigation work (secure refactoring approach, scan results, and documentation). This demonstrates that I can assess risk, use industry tools, implement security improvements, and communicate results clearly in a professional format.
