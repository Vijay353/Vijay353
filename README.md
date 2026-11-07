<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img src="assets/header-light.svg" width="100%" alt="Vijay Kumar. Solutions and Product. I take the failures people still fix by hand and turn them into systems that are safe to automate.">
</picture>

[Portfolio](https://www.vijaykumar.live/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/vk902/) &nbsp;·&nbsp; [Email](mailto:banothvijaykumar01@gmail.com)

Looking for **Solution Engineer and Product** roles that sit between policy, systems, and the people who run them. I'm strongest at taking a vague, recurring operational failure and turning it into a system that behaves the same way every time and can be audited afterwards.

<br>

### MatchPoint &nbsp;<sub><sup>ACCOUNTS PAYABLE</sup></sub>

Clearing three-way-match exceptions inside CFO authority, and stopping where a person has to decide.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/matchpoint-story-dark.svg">
  <img src="assets/matchpoint-story-light.svg" width="100%" alt="Problem: invoice mismatches are fixed by hand. Constraint: post only inside the approval limit, never twice, and prove it. Decision: check rules first, post once, read it back. Result: 60% fewer exceptions in simulated runs, about 12K down to 4.8K; the rest reach a person with the reasoning.">
</picture>

<br><br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/matchpoint-flow-dark.svg">
  <img src="assets/matchpoint-flow-light.svg" width="100%" alt="Flow: Match, Policy, Authorize, Post, Verify. Anything outside the approval limit goes to a person. Guarantees: rules before every write, one post per invoice, read-back check, tamper-evident log.">
</picture>

**Why it matters** &nbsp; AP stops deciding exceptions by whoever has been around longest. Every posting is decided by written policy, approved per record, and can be proven to an auditor later — without a single duplicate payment.

**How it was proven** &nbsp; Built and tested against stateful ERP, supplier, and carrier simulators over real HTTP, failure cases included: 201 automated tests, 22 of them end-to-end in a real browser. Sandbox and live adapters are already in place and fail closed until they are verified against a real system.

[Case study and live demo →](https://www.vijaykumar.live/work#matchpoint)

<br>

### Same approach, other high-stakes failures

<table>
  <tr>
    <td width="50%" valign="top">
      <br>
      <b><a href="https://www.vijaykumar.live/work#refund-assurance">Refund Assurance</a></b> &nbsp;<sub>SERVICE OPS</sub>
      <p>A promised refund fails quietly and the case gets closed anyway. This reopens it as an owned recovery case, only when the failure is confirmed.</p>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/refund-flow-dark.svg">
        <img src="assets/refund-flow-light.svg" width="100%" alt="Event, Extract, Policy, Reopen, Verify">
      </picture>
      <p><sub><b>Guarantee</b> &nbsp;One permission-checked write, proven by an independent read-back.</sub></p>
    </td>
    <td width="50%" valign="top">
      <br>
      <b><a href="https://www.vijaykumar.live/work#business-impact-gate">Business Impact Gate</a></b> &nbsp;<sub>SECURITY OPS</sub>
      <p>An analyst is about to isolate a device without knowing what the business loses. This adds that context and stages a dual-approval request instead.</p>
      <picture>
        <source media="(prefers-color-scheme: dark)" srcset="assets/gate-flow-dark.svg">
        <img src="assets/gate-flow-light.svg" width="100%" alt="Snapshot, Extract, Policy, Stage, Verify">
      </picture>
      <p><sub><b>Guarantee</b> &nbsp;Zero device changes on its own, and an expired request never counts as approved.</sub></p>
    </td>
  </tr>
</table>

<br>

### How I work

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/how-i-work-dark.svg">
  <img src="assets/how-i-work-light.svg" width="100%" alt="How I work, as seen in MatchPoint: 1. Start with what breaks: price variances, partial receipts, duplicate invoices. 2. Policy decides inside CFO authority before any ERP write. 3. Each write is idempotent and logged in a tamper-evident log. 4. A post counts only once it is read back from the ERP.">
</picture>

<br>

### Where I fit

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/where-i-fit-dark.svg">
  <img src="assets/where-i-fit-light.svg" width="100%" alt="Product Management, proof: Third Estate data rebuild with 60% fewer duplicate records. Solution Engineering, proof: Configit delivery across Salesforce, SAP and Configit CPQ. Solution Consulting, proof: FactSet, helped cut client onboarding time by 40%.">
</picture>

<br><br>

### Background

| | |
|:--|:--|
| **Third Estate Ventures** <br><sub>Sep 2025 – Jun 2026</sub> | BI & UX Designer, Multi-Project Fellow. Took analysts from discovery to a rebuilt property dataset and the Power BI views they use — 60% fewer duplicate records. |
| **Configit** <br><sub>Feb 2021 – May 2024</sub> | Solutions Consultant → Senior Solutions Consultant. Turned manufacturers' quote-to-order problems into requirements and owned delivery across Salesforce, SAP, and Configit CPQ. |
| **FactSet** <br><sub>Dec 2018 – Feb 2021</sub> | Associate → Client Solutions Consultant. Traced institutional clients' data and analytics issues to the platform underneath; helped cut onboarding time by 40%. |
| **Education** | M.S. Management Information Systems, University at Buffalo · B.Tech Computer Science, MNIT Jaipur |
| **Credentials** | CSPO · Lean Six Sigma Green Belt · ITIL 4 |

<br>

---

**Open to Solution Engineer, Product, and Solutions Consultant conversations.**<br>
I'm the best fit where the job needs real system design and someone who can explain it to both the people running the process and the people approving it.

[Email](mailto:banothvijaykumar01@gmail.com) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/vk902/) &nbsp;·&nbsp; [Portfolio](https://www.vijaykumar.live/)

<sub>Every system here is tested against stateful simulations of the real platforms, including how they fail, so the guarantees hold before anything touches production.</sub>
