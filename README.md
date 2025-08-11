# Gophish-Campaign-Simulation
Incident Response Planning and Execution

## Objective:
To demonstrate proficiency in threat simulation by creating and executing a realistic phishing campaign.

### Skills Learned
1. ???

### Tools Used
- <a href="https://getgophish.com/">Gophish</a>


## Steps:
| Steps  | Descrition | Reference Photo |
|--------|------------|-----------------|
| Step 1 |  | *Ref 1:  |
| Step 2 |  | *Ref 2:  |
| Step 3 |  | *Ref 3:  |
| Step 4 |  | *Ref 4:  |
| Step 5 |  | *Ref 5:  |


*Ref 1:*


**Ref 2:**


*Ref 3:*


*Ref 4:*


*Ref 5:*





## Notes:

### Phishing Simulation:

### Phase 1: Planning the Simulation
- This is the most important part, as it shows you think strategically, not maliciously. Your goal is to simulate a realistic scenario in a controlled, isolated environment (like a home lab or virtual machine).
- Define Your Objective: Start with a clear statement of purpose. For your portfolio, this could be:
    - "To demonstrate proficiency in threat simulation by creating and executing a realistic phishing campaign."
    - "To analyze user susceptibility and provide actionable metrics and remediation plans."
- Choose a Scenario: The email needs to be believable. Pick a common, real-world threat vector. Great examples include:
    - A fake password reset notification from a major service (e.g., Google, Microsoft).
    - A fake HR policy update or a mandatory training email.
    - A package delivery notification from a shipping company.
- Phishing Tool: GoPhish is a popular and free open-source tool designed specifically for ethical phishing simulations. You can run it on a virtual machine.
    - Landing Page: Use the phishing tool to create a fake landing page that mirrors the legitimate site. Crucially, this page should be configured only to collect data for your simulation and not to send it anywhere or         cause any harm.

### Phase 2: Execution in an Isolated Lab Environment
- Configure a safe, controlled environment. This is a non-negotiable point for your portfolio.
- Set Up Your Lab: Explain that you configured a virtual network with a test client (e.g., a Windows or Linux VM) to act as the "victim." This shows you understand network isolation and ethical boundaries.
- Launch the Campaign: Use your chosen tool to send the simulated email to the test client.
- Record the Behavior: Document the outcome of the simulation. Did the "user" click the link? Did they enter fake credentials on the landing page? This data is what you will analyze.

### Phase 3: Analysis and Reporting
- Collect the Metrics: The phishing tool will provide metrics. Create a simple report or dashboard with the following data:
    - Email Send Rate: How many emails were sent? (In your case, this would be a small number, e.g., 1-5).
    - Open Rate: How many emails were opened?
    - Click Rate: How many times was the link clicked?
    - Credential Submission Rate: How many times were credentials entered?
- Formulate a Post-Campaign Report: This report is your main deliverable. Structure it like a real-world document with the following sections:
- Executive Summary: A high-level overview of the simulation's purpose, scope, and key findings.
- Campaign Overview: Detail the email scenario, the tools used, and the environment.
- Findings: Present your metrics with clear charts or graphs.
- Analysis: Explain what the data means. Why was the campaign successful? What made the email so convincing?
- Recommendations/Remediation: This is crucial. Propose a follow-up training plan, suggest technical controls (like a DMARC policy or email filtering), or advocate for a specific security awareness program.
