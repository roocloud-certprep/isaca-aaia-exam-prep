---
layout: default
title: "Sample AI Audit Process: Plan, Execute & Report | ISACA AAIA Ep. 46"
description: "Walk through the full AI audit lifecycle: scoping, data collection, model assessment, bias, explainability, compliance, performance, reporting, and remediation. AAIA Ep. 46."
keywords: "sample AI audit process, AI audit lifecycle, audit scoping, data collection, model assessment, bias and fairness, transparency, compliance assessment, performance outcome, audit reporting, remediation monitoring, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/PMje9soXezo/maxresdefault.jpg"
permalink: /domain-3-auditing-ai/ep46-sample-audit-process.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "Sample AI Audit Process: Plan, Execute & Report",
  "description": "Walk through the full AI audit lifecycle: scoping, data collection, model assessment, bias, explainability, compliance, performance, reporting, and remediation. AAIA Ep. 46.",
  "thumbnailUrl": "https://img.youtube.com/vi/PMje9soXezo/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=PMje9soXezo",
  "embedUrl": "https://www.youtube.com/embed/PMje9soXezo",
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
      "name": "What happens during the scoping phase of an AI audit?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Scoping means defining exactly what you will evaluate and what you will ignore, like drawing property lines before building a fence. For a hospital claims-approval system you identify the specific algorithms making the decisions, pinpoint every data source such as medical histories and physician notes, map the exact logic the system uses over time, and define the regulatory boundaries including civil rights guidelines and emerging AI laws."
      }
    },
    {
      "@type": "Question",
      "name": "What are the phases of the AI audit lifecycle?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The lifecycle phases are scoping, data collection, model assessment, bias and fairness assessment, transparency and explainability, compliance assessment, performance and outcome assessment, reporting, and remediation and monitoring. Together they establish boundaries, verify inputs, inspect internal mechanics, check equality, demand clear logic, ensure legal adherence, monitor long-term outcomes, document findings, and track corrective actions to completion."
      }
    },
    {
      "@type": "Question",
      "name": "How does an AI audit detect bias and unfairness?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "During the bias and fairness assessment, you ensure the system treats all groups equally and does not illegally discriminate, like spotting a toll booth that charges red cars double for no reason. You ask how the team embedded ethics into workflows and scrutinize outputs for disparities tied to protected characteristics. For example, if patients over sixty are denied seventy percent of the time but are only thirty percent of applicants, that is a massive red flag of a biased system."
      }
    },
    {
      "@type": "Question",
      "name": "What happens after the AI audit report is written?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "After reporting comes remediation and monitoring, because identifying problems is useless if no one fixes them. The recommendations become mandatory tasks assigned to management, a dedicated tracking application oversees the actions, and the process should be controlled by an independent group like risk management or internal audit. They track progress until every issue is resolved and report the final status to key stakeholders."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# Sample AI Audit Process: Plan, Execute, and Report

What does a complete artificial intelligence audit actually look like from start to finish? This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series provides a comprehensive breakdown of the **AI audit lifecycle**, walking through every phase an auditor must navigate when evaluating a high-risk automated system. Understanding this full pipeline is essential: if your enterprise implements an automated tool for high-stakes decisions, you will know exactly how to structure the investigation to ensure it is legally compliant and ethically sound, and you can use this blueprint to evaluate any vendor software before your company signs a contract or puts customer data at risk. Throughout, we use the running example of a hospital system that automatically approves or denies patient treatment claims.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/PMje9soXezo" title="Sample AI Audit Process: Plan, Execute & Report" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Phase 1: Scoping

Scoping means defining exactly what you will evaluate and, just as importantly, what you will ignore — like drawing the property lines before building a fence so you know where your jurisdiction ends. For our hospital claims system, scoping identifies the specific algorithms making the screening decisions, pinpoints every single data source (medical histories, intake forms, physician notes), maps out the exact logic the system uses to evaluate a case over time, and defines the regulatory boundaries by listing all the civil rights guidelines and emerging AI laws the system must obey.

## Phase 2: Data Collection

Before testing the software, you must scrutinize the information it was taught with. If you teach a child using a textbook full of lies, the child will fail the test — and the exact same logic applies to software. You gather the historical datasets used for training, such as past hospital approvals, patient demographics, and protected categories like race or age. You verify this information is complete, diverse, and error-free by comparing a sample against actual medical records. You inquire about the results of any previous data management assessments, and crucially you investigate privacy controls to confirm the original patients gave legal consent for their personal information to be used for machine learning.

## Phase 3: Model Assessment

This is where you open up the hood and evaluate how the mathematical engine was built and trained. You ask developers to explain their design process and how data flows through the system. You look at the **architecture** — the structural design of the software — which might use decision trees (essentially massive automated flowcharts) or neural networks (complex webs designed to mimic human brain cells). You evaluate the documentation for **hyperparameters**, which are dials or settings adjusted by a human programmer before the machine starts learning, similar to setting an oven temperature before baking. You review performance metrics like accuracy rates, including the **F1 score**, a calculation used to balance precision and recall so the system does not just blindly deny every patient to minimize risk. Importantly, you must ask developers why these exact targets were chosen to represent success.

## Phase 4: Bias and Fairness Assessment

You must ensure the system treats all groups of people equally and does not illegally discriminate. Imagine a toll booth that charges red cars double the price of blue cars for no logical reason — you are looking for that exact kind of unfairness in the software logic. You ask the engineering team how they embedded ethical considerations into their daily workflows, then scrutinize the output to detect disparities tied to protected characteristics. For example, if treatment claims from patients over the age of sixty are denied seventy percent of the time while they make up only thirty percent of the applicant pool, you have identified a massive red flag indicating a biased system.

## Phase 5: Transparency and Explainability

You must be able to understand and communicate exactly how the software arrived at a specific conclusion — like a math teacher demanding that students show their work rather than just writing down the final answer. You review the documentation to ensure it provides clear insights into the decision-making process. If a patient was recommended for immediate surgery because of a specific risk score or vital-sign history, you must verify those specific deciding criteria are plainly communicated to the human doctors using the tool.

## Phase 6: Compliance Assessment

This is your strict legal verification to ensure the system breaks no laws or mandated obligations. You verify all personal data is processed lawfully, transparently, and only for the exact purpose the user agreed to. You investigate where the software physically resides: is it running locally on an isolated workstation in the hospital basement, or is it hosted globally and accessible via the open internet? If it is global, you must ensure it complies with extra-jurisdictional mandates — the regulations of other countries that apply when data crosses international borders.

## Phase 7: Performance and Outcome Assessment

You need to see whether the system actually works well in the real world over a long period. You cannot judge a car's reliability by driving it once around the block; you have to see how it performs over thousands of miles. You verify the model consistently produces acceptable outcomes and compare its real-world success against the old manual way of doing things — for example, measuring whether patients approved by the automated system have better recovery rates after one year compared to those evaluated strictly by human administrators. If the software is built for internal use, this step may be blended into the model assessment phase; but if the company plans to sell or license the software commercially, this long-term outcome tracking becomes an entirely separate and mandatory phase.

## Phase 8: Reporting

This is where you formally document absolutely everything discovered during the investigation. The final audit report details the initial scope, the objectives, and the legal requirements. It explicitly lists every identified bias, compliance gap, ethical defect, accountability concern, and performance issue. Crucially, it must include actionable recommendations — like instructing the team to retrain the software with a more diverse dataset to eliminate a bias you found. Finally, you must obtain formal agreement and ownership from senior management regarding these findings.

## Phase 9: Remediation and Monitoring

Identifying the problems is useless if no one actually fixes them. The recommendations from your report become mandatory tasks assigned to management. A dedicated tracking application or mechanism must be used to oversee these actions, and the tracking process should be controlled by an appropriate and independent group, like the risk management department or the internal audit team. They will track progress until every single issue is resolved and report the final status to key stakeholders.

<div class="takeaways" markdown="1">

## Key Takeaways

* The AI audit lifecycle runs from scoping and data collection through model, bias, explainability, compliance, and performance assessments, ending in reporting and remediation.
* Scoping draws clear jurisdiction lines, while data collection verifies training data is complete, diverse, error-free, and lawfully consented.
* Model assessment inspects architecture, hyperparameters, and metrics like the F1 score, demanding developers justify why their success targets were chosen.
* Bias assessment scrutinizes outputs against protected characteristics, and explainability requires the system to "show its work" to human decision-makers.
* Reporting documents every finding with actionable recommendations and management sign-off, and an independent group tracks remediation until every issue is resolved.

</div>

## Frequently Asked Questions

### What happens during the scoping phase of an AI audit?
Scoping means defining exactly what you will evaluate and what you will ignore, like drawing property lines before building a fence. For a hospital claims-approval system you identify the specific algorithms making the decisions, pinpoint every data source such as medical histories and physician notes, map the exact logic the system uses over time, and define the regulatory boundaries including civil rights guidelines and emerging AI laws.

### What are the phases of the AI audit lifecycle?
The lifecycle phases are scoping, data collection, model assessment, bias and fairness assessment, transparency and explainability, compliance assessment, performance and outcome assessment, reporting, and remediation and monitoring. Together they establish boundaries, verify inputs, inspect internal mechanics, check equality, demand clear logic, ensure legal adherence, monitor long-term outcomes, document findings, and track corrective actions to completion.

### How does an AI audit detect bias and unfairness?
During the bias and fairness assessment, you ensure the system treats all groups equally and does not illegally discriminate, like spotting a toll booth that charges red cars double for no reason. You ask how the team embedded ethics into workflows and scrutinize outputs for disparities tied to protected characteristics. For example, if patients over sixty are denied seventy percent of the time but are only thirty percent of applicants, that is a massive red flag of a biased system.

### What happens after the AI audit report is written?
After reporting comes remediation and monitoring, because identifying problems is useless if no one fixes them. The recommendations become mandatory tasks assigned to management, a dedicated tracking application oversees the actions, and the process should be controlled by an independent group like risk management or internal audit. They track progress until every issue is resolved and report the final status to key stakeholders.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [Sample AI Audit Process: Plan, Execute & Report](https://www.youtube.com/watch?v=PMje9soXezo).*
