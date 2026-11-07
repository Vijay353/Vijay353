&lt;div align=&quot;center&quot;&gt;

# Vijay Kumar

### PRODUCT & SOLUTIONS &nbsp;|&nbsp; I make enterprise software work for the people who have to use it.

&lt;p align=&quot;center&quot;&gt;
  &lt;em&gt;I connect user needs, what the business decides, and how the systems underneath actually behave.&lt;br/&gt;
  Building agentic systems from promise to proof.&lt;/em&gt;
&lt;/p&gt;

&lt;p align=&quot;center&quot;&gt;
  &lt;a href=&quot;https://www.vijaykumar.live/&quot;&gt;&lt;b&gt;Portfolio ↗&lt;/b&gt;&lt;/a&gt; &amp;nbsp;&amp;nbsp;·&amp;nbsp;&amp;nbsp;
  &lt;a href=&quot;https://www.linkedin.com/in/vk902/&quot;&gt;&lt;b&gt;LinkedIn ↗&lt;/b&gt;&lt;/a&gt; &amp;nbsp;&amp;nbsp;·&amp;nbsp;&amp;nbsp;
  &lt;a href=&quot;https://www.vijaykumar.live/&quot;&gt;&lt;b&gt;Resume ↗&lt;/b&gt;&lt;/a&gt; &amp;nbsp;&amp;nbsp;·&amp;nbsp;&amp;nbsp;
  &lt;a href=&quot;https://www.credly.com/users/vijay-kumar-banoth&quot;&gt;&lt;b&gt;Credly ↗&lt;/b&gt;&lt;/a&gt;
&lt;/p&gt;

&lt;/div&gt;

---

### The Thesis: From Promise to Proof

&lt;blockquote&gt;
  &lt;b&gt;&quot;It reads like three careers, but it&#39;s one skill used at different layers of the same problem.&quot;&lt;/b&gt;
&lt;/blockquote&gt;

I build systems that verify the transaction, not just the conversation. Most enterprise software breaks at the seams between business logic and technical execution—where conversational AI promises an action, but underlying APIs, state machines, or legacy databases fail silently. 

My work sits at the intersection of customer problems, deterministic policy, and enterprise integration—spanning fintech, AP automation, SOC compliance, and CPQ-to-ERP pipelines. Every system is built to fail closed, verify against external source-of-truth state, and maintain an immutable audit trail.

---

### Featured Systems: The Proof Stack

A curated index of 5 production-grade agentic architectures engineered for deterministic enterprise operations.

&lt;table width=&quot;100%&quot;&gt;
  &lt;tr&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;small&gt;&lt;code&gt;AGENTIC AI · SERVICE OPERATIONS&lt;/code&gt;&lt;/small&gt;
      &lt;br/&gt;
      &lt;h3&gt;Refund Assurance&lt;/h3&gt;
      &lt;p&gt;When an AI service session closes with &lt;em&gt;&quot;your refund has been processed,&quot;&lt;/em&gt; this agent monitors the processing window, probes Order Management, and reopens the case strictly upon confirmed gateway failure.&lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Proof Stack:&lt;/b&gt;&lt;br/&gt;
      • &lt;code&gt;73/73&lt;/code&gt; unit &amp; integration tests passing&lt;br/&gt;
      • &lt;code&gt;1&lt;/code&gt; idempotent state recovery write&lt;br/&gt;
      • &lt;code&gt;100%&lt;/code&gt; silent gateway failure catch rate (v7 → v8)
      &lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Architecture Flow:&lt;/b&gt;&lt;br/&gt;
      &lt;code&gt;Async Webhook&lt;/code&gt; → &lt;code&gt;Order Mgmt Probe&lt;/code&gt; → &lt;code&gt;Deterministic Policy&lt;/code&gt; → &lt;code&gt;Case Reopen (v7→v8)&lt;/code&gt; → &lt;code&gt;Audit Trail&lt;/code&gt;
      &lt;/p&gt;
      &lt;p&gt;&lt;sub&gt;&lt;em&gt;Note: Salesforce Service Cloud-style async gateway flows simulated and labeled.&lt;/em&gt;&lt;/sub&gt;&lt;/p&gt;
      &lt;p&gt;&lt;a href=&quot;https://www.vijaykumar.live/#work&quot;&gt;&lt;b&gt;View Case Study ↗&lt;/b&gt;&lt;/a&gt;&lt;/p&gt;
    &lt;/td&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;small&gt;&lt;code&gt;AGENTIC AI · FINANCE OPERATIONS&lt;/code&gt;&lt;/small&gt;
      &lt;br/&gt;
      &lt;h3&gt;MatchPoint (Three-Way Match Controller)&lt;/h3&gt;
      &lt;p&gt;Autonomous accounts payable reconciliation controller that aligns Purchase Orders, Goods Receipts, and Invoices—escalating only mathematically proven discrepancies while eliminating false positive alert fatigue.&lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Proof Stack:&lt;/b&gt;&lt;br/&gt;
      • &lt;code&gt;60%&lt;/code&gt; reduction in matching exceptions (~12K → ~4.8K)&lt;br/&gt;
      • &lt;code&gt;1&lt;/code&gt; idempotent exception write per true anomaly&lt;br/&gt;
      • &lt;code&gt;0&lt;/code&gt; false escalations on valid variance tolerances
      &lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Architecture Flow:&lt;/b&gt;&lt;br/&gt;
      &lt;code&gt;Intake (PO/GR/Inv)&lt;/code&gt; → &lt;code&gt;Match Extractor&lt;/code&gt; → &lt;code&gt;Discrepancy Policy&lt;/code&gt; → &lt;code&gt;Idempotent Write&lt;/code&gt; → &lt;code&gt;Reconciliation Verifier&lt;/code&gt;
      &lt;/p&gt;
      &lt;p&gt;&lt;sub&gt;&lt;em&gt;Note: SAP ERP enterprise transaction backend simulated and labeled.&lt;/em&gt;&lt;/sub&gt;&lt;/p&gt;
      &lt;p&gt;&lt;a href=&quot;https://matchpoint.hiddenpoint06.de/&quot;&gt;&lt;b&gt;Live Demo ↗&lt;/b&gt;&lt;/a&gt; &amp;nbsp;·&amp;nbsp; &lt;a href=&quot;https://www.vijaykumar.live/#work&quot;&gt;&lt;b&gt;View Case Study ↗&lt;/b&gt;&lt;/a&gt;&lt;/p&gt;
    &lt;/td&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;small&gt;&lt;code&gt;AGENTIC AI · SECURITY &amp; COMPLIANCE&lt;/code&gt;&lt;/small&gt;
      &lt;br/&gt;
      &lt;h3&gt;Business Impact Gate (SOC Issue Solver)&lt;/h3&gt;
      &lt;p&gt;Pre-flight verification gate before high-impact infrastructure containment actions. Joins real-time Defender incidents with CMDB dependency graphs, change freezes, and SLA policies before staging dual-approval packets.&lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Proof Stack:&lt;/b&gt;&lt;br/&gt;
      • &lt;code&gt;70%&lt;/code&gt; reduction in review &amp; triage latency&lt;br/&gt;
      • &lt;code&gt;1,420&lt;/code&gt; synthetic incident sessions verified&lt;br/&gt;
      • &lt;code&gt;Dual-approval&lt;/code&gt; staging with zero unverified mutations
      &lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Architecture Flow:&lt;/b&gt;&lt;br/&gt;
      &lt;code&gt;Defender Alert&lt;/code&gt; → &lt;code&gt;CMDB &amp; Freeze Join&lt;/code&gt; → &lt;code&gt;Constraint Extractor&lt;/code&gt; → &lt;code&gt;Policy CAP-1.0 (Fail-Closed)&lt;/code&gt; → &lt;code&gt;Dual Approval&lt;/code&gt;
      &lt;/p&gt;
      &lt;p&gt;&lt;sub&gt;&lt;em&gt;Note: Microsoft Graph &amp; ServiceNow verified API contracts behind fail-closed adapters; scenario data synthetic.&lt;/em&gt;&lt;/sub&gt;&lt;/p&gt;
      &lt;p&gt;&lt;a href=&quot;https://www.vijaykumar.live/#work&quot;&gt;&lt;b&gt;View Case Study ↗&lt;/b&gt;&lt;/a&gt;&lt;/p&gt;
    &lt;/td&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;small&gt;&lt;code&gt;AGENTIC AI · MARKETPLACE OPERATIONS&lt;/code&gt;&lt;/small&gt;
      &lt;br/&gt;
      &lt;h3&gt;MarginPulse&lt;/h3&gt;
      &lt;p&gt;Real-time margin defense agent connecting physical kitchen capacity to digital ad spend. Evaluates POS/KDS ticket spikes against margin thresholds to pause sponsored listings, verified by live read-back—never blind HTTP 200s.&lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Proof Stack:&lt;/b&gt;&lt;br/&gt;
      • &lt;code&gt;81&lt;/code&gt; Vitest unit/integration + &lt;code&gt;6&lt;/code&gt; Playwright E2E tests&lt;br/&gt;
      • Exactly &lt;code&gt;1&lt;/code&gt; verified PATCH mutation per surge trigger&lt;br/&gt;
      • &lt;code&gt;Independent read-back&lt;/code&gt; verification before confirmation
      &lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Architecture Flow:&lt;/b&gt;&lt;br/&gt;
      &lt;code&gt;POS/KDS Webhook&lt;/code&gt; → &lt;code&gt;Evidence Gatherer&lt;/code&gt; → &lt;code&gt;18-Check Deterministic Policy&lt;/code&gt; → &lt;code&gt;Manager Staging&lt;/code&gt; → &lt;code&gt;Verified PATCH&lt;/code&gt;
      &lt;/p&gt;
      &lt;p&gt;&lt;sub&gt;&lt;em&gt;Note: Multi-tenant marketplace ad server &amp; POS webhooks simulated and labeled.&lt;/em&gt;&lt;/sub&gt;&lt;/p&gt;
      &lt;p&gt;&lt;a href=&quot;https://www.vijaykumar.live/#work&quot;&gt;&lt;b&gt;View Case Study ↗&lt;/b&gt;&lt;/a&gt;&lt;/p&gt;
    &lt;/td&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td colspan=&quot;2&quot; width=&quot;100%&quot; valign=&quot;top&quot;&gt;
      &lt;small&gt;&lt;code&gt;AGENTIC AI · DATA &amp; ENTERPRISE AI&lt;/code&gt;&lt;/small&gt;
      &lt;br/&gt;
      &lt;h3&gt;GenAI Agentic RAG System&lt;/h3&gt;
      &lt;p&gt;Production document intelligence and reasoning pipeline answering complex queries over heterogeneous unstructured repositories using verified citation grounding and autonomous ReAct tool-calling loops.&lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Proof Stack:&lt;/b&gt;&lt;br/&gt;
      • &lt;code&gt;&lt; 2s&lt;/code&gt; end-to-end response latency on multi-document corpora&lt;br/&gt;
      • &lt;code&gt;90%+&lt;/code&gt; factual extraction accuracy across benchmark evaluations&lt;br/&gt;
      • &lt;code&gt;Zero hallucinated citations&lt;/code&gt; via strict claim-to-chunk sentence attribution
      &lt;/p&gt;
      &lt;p&gt;&lt;b&gt;Architecture Flow:&lt;/b&gt;&lt;br/&gt;
      &lt;code&gt;Enterprise Query&lt;/code&gt; → &lt;code&gt;Hybrid Dense/Sparse Retrieval&lt;/code&gt; → &lt;code&gt;ReAct Agent Reasoning&lt;/code&gt; → &lt;code&gt;Claim Attributor&lt;/code&gt; → &lt;code&gt;Grounded Output&lt;/code&gt;
      &lt;/p&gt;
      &lt;p&gt;&lt;sub&gt;&lt;em&gt;Note: Evaluated against multi-document enterprise corpora using LLaMA 3, ReAct tool execution, and Streamlit telemetry.&lt;/em&gt;&lt;/sub&gt;&lt;/p&gt;
      &lt;p&gt;&lt;a href=&quot;https://www.vijaykumar.live/#work&quot;&gt;&lt;b&gt;View Case Study ↗&lt;/b&gt;&lt;/a&gt;&lt;/p&gt;
    &lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;

---

### Operating Principles

How I approach product architecture, system design, and technical governance:

1. **01. Start with the person, not the ticket.**  
   A feature request or support ticket is usually the visible symptom of a broken workflow. I start with the operator's actual context and observe the lived friction before writing a line of code or drafting an integration spec.

2. **02. Trace it to the system.**  
   Follow what someone experiences down to the raw database transactions, integration schemas, and asynchronous event streams underneath. Fix the structural failure at the system layer rather than patching symptoms with UI cosmetic fixes.

3. **03. Own it past the handoff.**  
   Requirements specifications are never the finish line. True product ownership extends through solution architecture, API contracts, UAT, production go-live, and monitoring edge cases under real-world operational stress.

4. **04. Let evidence set the priority.**  
   Telemetry, behavioral event data, and deterministic test proofs dictate priorities—never the loudest voice in the room. If a claim cannot be verified against telemetry or audited logs, it remains a hypothesis.

---

### Background & Credibility

&lt;table&gt;
  &lt;tr&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;b&gt;Experience&lt;/b&gt;&lt;br/&gt;
      • &lt;b&gt;Third Estate Ventures&lt;/b&gt; · BI &amp; UX Designer, Fellow &lt;em&gt;(Current)&lt;/em&gt;&lt;br/&gt;
      • &lt;b&gt;Configit&lt;/b&gt; · Senior Solutions Consultant → Solutions Consultant&lt;br/&gt;
      • &lt;b&gt;FactSet&lt;/b&gt; · Client Solutions Consultant → Associate
    &lt;/td&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;b&gt;Education&lt;/b&gt;&lt;br/&gt;
      • &lt;b&gt;University at Buffalo&lt;/b&gt; · M.S., Management Information Systems&lt;br/&gt;
      • &lt;b&gt;MNIT Jaipur&lt;/b&gt; · B.Tech., Computer Science &amp; Engineering
    &lt;/td&gt;
  &lt;/tr&gt;
  &lt;tr&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;b&gt;Credentials &amp; Certifications&lt;/b&gt;&lt;br/&gt;
      • &lt;b&gt;CSPO&lt;/b&gt; · Certified Scrum Product Owner&lt;br/&gt;
      • &lt;b&gt;Lean Six Sigma&lt;/b&gt; · Green Belt&lt;br/&gt;
      • &lt;b&gt;ITIL 4&lt;/b&gt; · IT Service Management
    &lt;/td&gt;
    &lt;td width=&quot;50%&quot; valign=&quot;top&quot;&gt;
      &lt;b&gt;Core Technical Stack&lt;/b&gt;&lt;br/&gt;
      • &lt;b&gt;Languages:&lt;/b&gt; TypeScript · Python · SQL · Node.js&lt;br/&gt;
      • &lt;b&gt;Frontend &amp; Testing:&lt;/b&gt; React · Playwright · Vitest · Tailwind&lt;br/&gt;
      • &lt;b&gt;Data &amp; Cloud:&lt;/b&gt; SQLite · PostgreSQL · Azure · REST / GraphQL
    &lt;/td&gt;
  &lt;/tr&gt;
&lt;/table&gt;

---

&lt;div align=&quot;center&quot;&gt;

### Let's work together.

&lt;p&gt;
  Open to &lt;b&gt;Product Management&lt;/b&gt;, &lt;b&gt;Technology Consulting&lt;/b&gt;, and &lt;b&gt;Enterprise Solutions&lt;/b&gt; roles.&lt;br/&gt;
  Let&#39;s connect to discuss building reliable, agentic systems that scale.
&lt;/p&gt;

&lt;p&gt;
  &lt;a href=&quot;mailto:banothvijaykumar01@gmail.com&quot;&gt;&lt;b&gt;Email me ↗&lt;/b&gt;&lt;/a&gt; &amp;nbsp;&amp;nbsp;·&amp;nbsp;&amp;nbsp;
  &lt;a href=&quot;https://www.linkedin.com/in/vk902/&quot;&gt;&lt;b&gt;LinkedIn ↗&lt;/b&gt;&lt;/a&gt; &amp;nbsp;&amp;nbsp;·&amp;nbsp;&amp;nbsp;
  &lt;a href=&quot;https://www.vijaykumar.live/&quot;&gt;&lt;b&gt;Portfolio ↗&lt;/b&gt;&lt;/a&gt;
&lt;/p&gt;

<br/>

&lt;sub&gt;© 2026 Vijay Kumar. Built with clean, editorial Markdown.&lt;/sub&gt;

&lt;/div&gt;
