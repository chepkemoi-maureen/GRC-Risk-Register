# GRC Risk Register & Dashboard

## Project Overview
This project provides a **Risk Register template** and a **dashboard to visualize organizational risks**. It is designed to help organizations identify, assess, and manage risks effectively. The dashboard includes a heatmap visualization to highlight high-priority risks, making it easier for leadership to allocate resources and make informed decisions.

---

## Purpose of a Risk Register
A Risk Register is a central tool in **Governance, Risk, and Compliance (GRC)**. Its main purposes include:

1. **Identify all risks in one organized place**  
   Instead of keeping risks in people’s heads, the risk register lists them clearly—technical risks, business risks, cyber risks, operational risks, compliance risks, etc.

2. **Understand what could harm the organization**  
   It helps answer:  
   - “What can go wrong?”  
   - “How serious is it?”  
   - “How likely is it to happen?”  
   This enables informed decision-making.

3. **Measure and prioritize risks**  
   Risks are categorized as:  
   - **High priority** → needs immediate action  
   - **Medium priority** → monitor and apply some controls  
   - **Low priority** → acceptable or minimal action  

4. **Record existing controls**  
   Document what the organization already does to mitigate each risk, e.g., firewalls, antivirus, policies, 2FA, backups.

5. **Plan the treatment (actions)**  
   Define steps to reduce or remove risk, such as:  
   - Implement Multi-Factor Authentication (MFA)  
   - Patch systems  
   - Train employees  
   - Perform vulnerability assessments  

6. **Assign responsibility**  
   Every risk should have an owner (person or department) to ensure accountability.

7. **Track progress and improvements**  
   Update the status of risks: Open, In Progress, Mitigated, Accepted, or Closed.

8. **Ensure compliance**  
   Supports frameworks such as ISO 27001, NIST, SOC2, GDPR. Auditors can see that risks are identified, analyzed, controlled, and tracked.

9. **Communicate risks to management**  
   Provides executives with a clean summary:  
   - Biggest threats  
   - What needs funding  
   - Key decisions  

10. **Support the overall GRC strategy**  
    Helps the organization:  
    - Strengthen security  
    - Reduce incidents  
    - Lower financial loss  
    - Meet regulatory requirements  
    - Improve decision-making

---

## How to Use the Risk Register (Step-by-Step)

1. **List all risks**  
   Fill in each identified risk in the register (technical, operational, compliance, etc.).

2. **Assess each risk**  
   For every risk, assign:  
   - Likelihood (e.g., Low/Medium/High)  
   - Impact (e.g., Low/Medium/High)  

3. **Record existing controls**  
   Document what is already in place to mitigate each risk.

4. **Plan treatment actions**  
   Specify what actions are required to reduce or eliminate the risk.

5. **Assign responsibility**  
   Add the person or department responsible for managing the risk.

6. **Track status**  
   Update risk status as work progresses (Open, In Progress, Mitigated, Accepted, Closed).

7. **Visualize risks using the dashboard**  
   Run the Python script in the `dashboard/` folder to generate a heatmap that highlights high-risk areas.

8. **Review and update regularly**  
   The risk register should be a living document, updated as new risks emerge or mitigation progresses.

---

## How to Run the Dashboard
1. Install Python 3.10+  
2. Install dependencies:  
```bash
pip install -r requirements.txt
