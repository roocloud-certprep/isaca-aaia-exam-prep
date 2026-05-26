---
layout: default
title: "Types of AI Controls: Governance, Technical, Legal & Ethical | ISACA AAIA Ep. 39"
description: "Explore the six categories of AI controls auditors validate: governance, technical and privacy, operations, SDLC, legal compliance, and ethical human values. AAIA Ep. 39."
keywords: "types of AI controls, AI control environment, AI governance controls, technical privacy controls, SDLC controls, legal compliance controls, ethical AI controls, RACI chart, model drift, FRIA, DPIA, LIME, SHAP, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/tE_x6Vlwpjo/maxresdefault.jpg"
permalink: /domain-3-auditing-ai/ep39-types-of-ai-controls.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "Types of AI Controls: Governance, Technical, Legal & Ethical",
  "description": "Explore the six categories of AI controls auditors validate: governance, technical and privacy, operations, SDLC, legal compliance, and ethical human values. AAIA Ep. 39.",
  "thumbnailUrl": "https://img.youtube.com/vi/tE_x6Vlwpjo/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=tE_x6Vlwpjo",
  "embedUrl": "https://www.youtube.com/embed/tE_x6Vlwpjo",
  "publisher": {
    "@type": "Organization",
    "name": "RooCloud",
    "logo": {
      "@type": "ImageObject",
      "url": "https://roocloud.com/assets/logo.png"
    }
  }
}
</script>
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What are the six categories of AI controls?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The six categories are governance and organizational controls, technical security and privacy controls, operation and life cycle management, system development life cycle (SDLC) controls, legal risk compliance and regulatory controls, and ethical and human values controls. Together they form an interconnected web that protects an AI system from the boardroom to the technical firewalls to human ethics."
      }
    },
    {
      "@type": "Question",
      "name": "What is the role of an auditor in the AI control environment?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The golden rule is that an auditor validates controls but does not execute them. Like a theme park safety inspector who reviews maintenance logs rather than tightening bolts personally, the auditor gathers evidence proving the engineering team ran the tools, correctly interpreted the results, and met company requirements. Many existing cybersecurity and privacy protocols simply need to be expanded to cover AI."
      }
    },
    {
      "@type": "Question",
      "name": "What is model drift and why does it matter?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Model drift happens when a system loses its accuracy over time because the real-world environment it operates in has changed. A system trained to predict fashion trends on data from the 1990s would produce entirely wrong predictions today because society drifted away from those styles. Continuous monitoring must stay active after deployment specifically to detect this drift."
      }
    },
    {
      "@type": "Question",
      "name": "What are LIME and SHAP in AI explainability?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "LIME stands for Local Interpretable Model-Agnostic Explanations and isolates why one single specific prediction was made, like a teacher explaining why you lost points on one essay question. SHAP stands for SHapley Additive exPlanations and provides a broader view, showing the overall importance and weight of different features across all predictions, like reading the syllabus rubric for the entire semester."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# Types of AI Controls: Governance, Technical, Legal, and Ethical Safeguards

Building, using, and eventually retiring intelligent technologies safely requires a massive ecosystem of safeguards. This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series unpacks the six major categories of **AI controls** — ranging from executive boardrooms and strict technical firewalls to legal compliance and human ethics. Understanding this interconnected web is a real-world advantage: you can use it to build a unified risk checklist the next time your company wants to buy an automated resume screener or a predictive sales tool, verifying that the vendor protects your data, adheres to privacy laws, and produces fair, unbiased results before you ever sign a contract.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/tE_x6Vlwpjo" title="Types of AI Controls: Governance, Technical, Legal & Ethical" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## The Auditor's Role: Validate, Don't Execute

The golden rule is that an auditor validates controls but does not execute them. Think of a safety inspector at a theme park. The inspector does not personally climb the roller coaster to tighten the bolts; instead, they review the maintenance logs to prove the mechanics tightened those bolts according to official safety standards. Similarly, you will not personally run the software scripts that detect unfair bias in an algorithm. You will gather evidence proving the engineering team ran those tools, correctly interpreted the results, and met your company's requirements. You also do not need to reinvent the wheel — many existing cybersecurity and privacy protocols simply need to be expanded to cover these new concerns, combining policies, technical tweaks, and continuous monitoring.

## 1. Governance and Organizational Controls

This is the foundation that dictates how a company manages its technological assets from the very top. It starts with absolute accountability: a company must document exactly who is responsible for what, often by creating a **RACI chart** (Responsible, Accountable, Consulted, and Informed) that maps who does the work, who holds ultimate ownership, who provides input, and who is merely kept in the loop. Organizations should appoint a high-level executive such as a Chief Data Officer or Chief AI Officer as the ultimate point of authority.

The enterprise also needs a dedicated internal policy that establishes core principles, incorporates legal regulations and risk management, and aligns the technology with the business mission. Established industry frameworks provide a structured baseline. Asset management requires an exhaustive registry of every automated model — like a logistics company tracking every delivery truck — detailing purpose, stakeholders, version, and life cycle stage. A dedicated risk committee tracks key risk indicators (an early-warning metric, like a check-engine light), reviews independent assessments, and monitors third-party vendor risk. Finally, governance includes tight control over legal contracts, such as contractual language guaranteeing a vendor secured explicit consent to use customer data for training.

## 2. Technical, Security, and Privacy Controls

These are the concrete safeguards built directly into the digital infrastructure. **Data quality** is arguably the most important technical control because models learn exclusively from the information they consume — like a water treatment plant straining to purify contaminated river water. Organizations must document thresholds for acceptable information, rules for resolving poor inputs, and methods for continuous monitoring.

Access controls for privileged administrators, regular users, applications, and third parties must be calibrated by data sensitivity, with multifactor authentication mandatory and periodic **recertification** to ensure people retain only the access they currently need. Configuration management keeps systems in a secure state through automation, patching, and proactive vulnerability detection tied to incident management. Rigorous testing frameworks demand end-to-end testing, scenario analysis, and aggressive bias testing. Privacy requires encryption, **hashing** (scrambling data into unreadable characters), **anonymization**, cryptographic key management, regular privacy impact assessments, and **data minimization** — collecting only what is necessary, like packing only a weekend bag. Finally, incident management ensures the response plan explicitly covers automated products with clear steps to identify, contain, mitigate, and restore.

## 3. Operation and Life Cycle Management

This focuses on the day-to-day running and maintenance of the system over its lifespan. It relies on extensive documentation: dataflow diagrams capturing logical, physical, and context views, and process flows breaking down how data is collected, enriched, and outputted — like the plumbing blueprints of a skyscraper. Decision-making documentation drives **explainability**, the capacity to understand the exact techniques and mathematical scores a system uses to turn an input into an output. Traceability logs record where information was sourced, how consent was obtained, and how data was transformed.

Life cycle management involves strict change management and version control, with documented approvals, impact assessments, and records retained in a ticketing system. Modern environments use automated tools and **containerization** (packaging software with all its files into a single digital box so it runs anywhere). Even after deployment, continuous monitoring watches for **model drift** — when a system loses accuracy because the real-world environment changed, like a fashion-trend predictor trained on 1990s data.

## 4. System Development Life Cycle (SDLC) Controls

These govern the actual creation and building phases. The exact controls depend on the project management approach: a rapid, continuous delivery approach like DevSecOps handles controls very differently than a structured, sequential waterfall approach. Notably, many ambitious development projects never reach deployment — and the failure rate is rarely due to methodology, but rather poor leadership or unclear business requirements. During ideation, teams document the problem, align objectives with strategic goals, and preemptively brainstorm potential harm. In the design phase, the focus shifts to architecture and data fitness: was the data purchased legally, is it complete, and does it represent the diverse population to avoid unfair outcomes? During deployment management, organizations often automate releases, so auditors must verify operations teams monitor automated pathways for unexpected errors.

## 5. Legal, Risk, Compliance, and Regulatory Controls

This is how an organization plays by society's rules. Risk and impact assessments categorize systems by danger level so high-risk platforms are managed under laws like the European Union AI Act or New York City Local Law 144, which regulates automated employment decisions. These assessments must be iterative, not one-time events. The highest-risk systems require a **Fundamental Rights Impact Assessment (FRIA)** — like an environmental impact study before building a dam, but protecting human civil liberties instead of wildlife — for technologies like biometric identification, critical infrastructure, essential public services, law enforcement, and border control. A **Data Protection Impact Assessment (DPIA)** evaluates privacy threats. Compliance means adhering to all global, national, and local laws, while contract management binds external vendors. A crucial control is the **whistleblower process**, a safe, protected mechanism encouraging people to self-report unethical or illegal behavior without fear of retaliation. Regulatory reporting integrates specialized mandates into daily operations.

## 6. Ethical and Human Values Controls

These ensure the technology treats people with dignity, fairness, and respect. An ethical impact assessment can leverage free, open-source guidelines or corporate frameworks. **Consent management** validates the right to opt out of automated processing, respects the consent status of training data, enforces retention limits, and confirms the **right to be forgotten** — permanently erasing a person from digital records on request. Bias management tests for bias introduced by human developers and against protected characteristics; validating representative sampling helps detect failures, as with a medical algorithm trained only on high-altitude data that fails in tropical climates. Transparency requires disclosing when people interact with an automated agent and uses tools like **LIME** (Local Interpretable Model-Agnostic Explanations, explaining one prediction) and **SHAP** (SHapley Additive exPlanations, showing feature importance across all predictions). Human oversight is non-negotiable: humans stay in the loop, conduct independent ethical reviews, and anyone impacted must have a functional appeal process reviewed by a real person.

<div class="takeaways" markdown="1">

## Key Takeaways

* Auditors validate AI controls but never execute them — they gather evidence that the engineering team ran the tools and met requirements.
* The six control categories are governance, technical/security/privacy, operations and life cycle, SDLC, legal/compliance/regulatory, and ethical human values.
* Governance hinges on accountability tools like RACI charts, executive ownership, model registries, and risk committees tracking key risk indicators.
* Continuous monitoring after deployment is essential to catch model drift, while explainability tools like LIME and SHAP make decisions transparent.
* High-risk systems require iterative risk assessments, a FRIA and DPIA, whistleblower channels, and human oversight with a functional appeal process.

</div>

## Frequently Asked Questions

### What are the six categories of AI controls?
The six categories are governance and organizational controls, technical security and privacy controls, operation and life cycle management, system development life cycle (SDLC) controls, legal risk compliance and regulatory controls, and ethical and human values controls. Together they form an interconnected web that protects an AI system from the boardroom to the technical firewalls to human ethics.

### What is the role of an auditor in the AI control environment?
The golden rule is that an auditor validates controls but does not execute them. Like a theme park safety inspector who reviews maintenance logs rather than tightening bolts personally, the auditor gathers evidence proving the engineering team ran the tools, correctly interpreted the results, and met company requirements. Many existing cybersecurity and privacy protocols simply need to be expanded to cover AI.

### What is model drift and why does it matter?
Model drift happens when a system loses its accuracy over time because the real-world environment it operates in has changed. A system trained to predict fashion trends on data from the 1990s would produce entirely wrong predictions today because society drifted away from those styles. Continuous monitoring must stay active after deployment specifically to detect this drift.

### What are LIME and SHAP in AI explainability?
LIME stands for Local Interpretable Model-Agnostic Explanations and isolates why one single specific prediction was made, like a teacher explaining why you lost points on one essay question. SHAP stands for SHapley Additive exPlanations and provides a broader view, showing the overall importance and weight of different features across all predictions, like reading the syllabus rubric for the entire semester.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [Types of AI Controls: Governance, Technical, Legal & Ethical](https://www.youtube.com/watch?v=tE_x6Vlwpjo).*
