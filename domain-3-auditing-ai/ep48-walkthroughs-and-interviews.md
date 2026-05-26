---
layout: default
title: "AI Audit Walkthroughs & Interviews: Design & Evidence Capture | ISACA AAIA Ep. 48"
description: "Master AI audit walkthroughs and interviews: document review, live demonstrations, business risk, data sourcing, bias testing, performance metrics, and compliance."
keywords: "AI audit walkthroughs, audit interviews, document review, risk register, data register, model assessment, bias and fairness, adversarial testing, F1 score, model drift, EU AI Act, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/qVASk58mKTo/maxresdefault.jpg"
permalink: /domain-3-auditing-ai/ep48-walkthroughs-and-interviews.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Audit Walkthroughs & Interviews: Design & Evidence Capture",
  "description": "Master AI audit walkthroughs and interviews: document review, live demonstrations, business risk, data sourcing, bias testing, performance metrics, and compliance.",
  "thumbnailUrl": "https://img.youtube.com/vi/qVASk58mKTo/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=qVASk58mKTo",
  "embedUrl": "https://www.youtube.com/embed/qVASk58mKTo",
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
      "name": "What is the phased approach for AI audit walkthroughs and interviews?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Auditors do not rely only on written reports. They use a phased approach: first review the official documents, then request a live demonstration of the system in action, and finally ask targeted questions to the personnel responsible for the technology. Demonstrations are conducted multiple times throughout the evaluation to confirm the internal safety checks are actually working."
      }
    },
    {
      "@type": "Question",
      "name": "What is a risk register and a data register in an AI audit?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A risk register is a master list of all potential problems that could go wrong with a project, used to assess technical, ethical, regulatory, and societal risks. A data register is a detailed inventory cataloging all the information used to teach the model, including how the raw material was acquired and the methods used to evaluate its quality."
      }
    },
    {
      "@type": "Question",
      "name": "What is adversarial testing and why does it matter?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Adversarial testing is a security drill where friendly experts deliberately try to trick or break the system to find its hidden vulnerabilities. Auditors investigate security testing for data leakage, malicious injections, and adversarial prompts, and check whether automated testing frameworks were used and what the results were."
      }
    },
    {
      "@type": "Question",
      "name": "What questions do auditors ask about bias and fairness?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Auditors verify whether the system aligns with the organization's ethical values, whether it processes protected class data like race, religion, or gender, and whether it makes high-stakes decisions in areas like law enforcement or hiring. They check what steps detected prejudice, how bias was remediated, whether the system was tested on a diverse group of users, and how edge cases were handled."
      }
    },
    {
      "@type": "Question",
      "name": "What consumer rights must auditors verify in an AI compliance assessment?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Auditors verify that citizens are clearly informed of their rights when a machine makes a decision about their life, that there are mechanisms to contest the outcome with a human being, and that users can completely opt out of the automated process. They also confirm procedures for reporting major security incidents or data breaches to the proper authorities, including any notification required under laws like the EU AI Act."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Audit Walkthroughs and Interviews: Design and Evidence Capture

Evaluating an artificial intelligence system means more than reading written reports — it means sitting down with the people who design, build, and maintain the algorithms. This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series explores the exact methodology for guided conversations and interactive demonstrations used to extract critical information directly from stakeholders. Mastering these interviewing techniques lets you step into any high-stakes corporate environment, cut through dense technical jargon, and identify massive operational or legal risks before a new technology is ever deployed to the public — potentially saving your organization from severe financial and reputational damage.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/qVASk58mKTo" title="AI Audit Walkthroughs & Interviews: Design & Evidence Capture" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## The Phased Walkthrough Methodology

When evaluating a system, auditors do not just rely on written reports. They use a phased approach: review the paperwork, request a live demonstration, and then ask targeted questions to the personnel responsible for the technology. These demonstrations are conducted multiple times throughout the evaluation to confirm that the internal safety checks are actually working.

Think of this process like buying a large commercial bakery. You start by reading the financial statements and recipes — the document review. Then you walk through the kitchen while the bakers are working to see if they actually wash their hands and measure the flour correctly. Finally, you interview the head chef to understand their daily routine and uncover any hidden problems with the ovens.

## Business Context and Project Risk

The first major category focuses on business context and overall project risk. Auditors must identify the exact purpose of the technology and the specific problem it solves, ask whether a formal business case justified the financial investment, and determine who the intended users are and whether those groups were consulted during design. They investigate the underlying market assumptions, what regulations apply, and who is ultimately accountable if the system makes a disastrous decision.

A central artifact here is the **risk register** — a master list of all potential problems that could go wrong. Auditors ask about the methodology used to assess technical, ethical, regulatory, and societal risks, and whether the system could create positive social impacts or harm individuals, communities, the environment, or violate human rights. They check how risks are fixed, how the project ties into the broader company risk management plan, what continuous reporting is required, and how risks are reassessed throughout the system's life cycle. Consider building a hydroelectric dam: before pouring concrete, you must ask who needs the electricity, whether local townspeople were consulted, how it impacts the fish population, and who takes the legal blame if the dam overflows.

## Data Collection and Model Assessment

Data is the fuel that makes these systems work. Auditors look for a **data register** — a detailed inventory cataloging all information used to teach the computer — and ask how the raw material was acquired and what methods evaluated its quality. Crucially, they investigate whether the organization obtained proper legal consent and strictly followed internal policies and external privacy regulations during collection. Like running a high-end restaurant, you cannot just buy meat from an unknown supplier; you need an inventory log, freshness verification, and certificates proving the farm followed all agricultural and health laws.

In the model assessment phase, data first goes through **preprocessing** — cleaning the raw information and removing sensitive personal details to make it anonymous. Auditors ask how anonymization is validated so nobody can be secretly re-identified, whether the dataset is large and diverse enough to represent reality, and how the team identified extreme data points known as **outliers**. They then examine the **algorithms** — the mathematical rulebooks the computer follows — asking why specific ones were chosen, whether they were built internally or bought, and whether central algorithm and model registers exist. They must understand how the system reaches outcomes and whether decisions can be explained to non-technical people through formal transparency documentation, and whether users are warned they are talking to a machine.

## Testing, Security, and Code Management

This part of the evaluation dives deeply into testing, security, and code governance. Auditors ask exactly how the final outcomes were tested and what checks were used, examining security testing for **data leakage, malicious injections, and adversarial prompts**. **Adversarial testing** is a security drill where friendly experts deliberately try to trick or break the system to find hidden vulnerabilities. Auditors check whether automated testing frameworks were used and what the results were — you may hear jargon like pytest, PyTorch Lightning, TensorFlow Extended, or GitHub Actions, but these are simply brand names for digital toolboxes and automated assembly lines programmers use to test and organize software.

Everyday governance matters too. Auditors ask how the software code is protected, who can validate it, and who is allowed to release it into production. They check **version management controls** — a systematic way of saving and tracking software drafts over time — and how routine maintenance and updates are handled. Most importantly, they ask whether a human being is in the decision loop with power to step in and change the machine's decision, and about iterative testing to detect **model drift**, which happens when a system slowly becomes less accurate because the real world has changed around it. Like maintaining a fleet of delivery trucks, you hire mechanics to test the locks, monitor the engines with diagnostics, keep a logbook of who can drive, and regularly check wheel alignment because over thousands of miles the steering naturally drifts.

## Bias, Fairness, and Edge Cases

Auditors begin by verifying that the system aligns with the organization's core ethical values. They determine whether it processes **protected class data** — sensitive attributes like race, religion, or gender — and whether it makes high-stakes decisions in areas like law enforcement, biometric tracking, immigration, critical infrastructure, transportation, education, justice and democratic processes, or employment hiring. They ask what steps detected prejudice in the data, what defines a sensitive attribute, and how any discovered bias was remediated.

They also check whether the system was tested on a diverse group of users, whether re-evaluation succeeded, and whether diverse stakeholders were engaged in training and testing. They verify how the system handles anomalies, whether a formal reporting mechanism exists for unusual outcomes, and how **edge cases** — extreme, unusual, or rare situations outside normal operations — were tested. Consider a voice-activated emergency elevator: if you only test it with tall men who share a local accent, the system is biased. You must test it with children, elderly passengers, and people with heavy accents, and test edge cases like someone whispering during an emergency or a fire alarm blaring in the background.

## Performance, Outcomes, and Compliance

Auditors need the specific mathematical measures used to define success, why those metrics were chosen, and where the target values came from. You might encounter terms like **F1 score, Recall, or a Confusion Matrix** — specialized grading rubrics engineers use to measure how often the system guesses correctly versus how often it makes a mistake or triggers a false alarm. They ask how results were evaluated, whether the team ran real-world tests simulating a live production environment, and about **stress testing** that pushes the system to its limits with heavy load, extreme edge cases, and bizarre anomalies. Like testing a suspension bridge, you do not just drive one car across it; you park heavy cargo trucks bumper-to-bumper during a simulated hurricane to see how much stress the steel cables can take before snapping.

The final area is the **compliance assessment**. Auditors ask how the team identified which global laws apply and whether they maintain a central compliance register. Depending on the jurisdiction — such as under the **European Union Artificial Intelligence Act** — organizations may need to formally notify a market surveillance body when a system is deployed and complete mandatory conformity assessments. Beyond corporate rules, auditors fiercely protect consumer rights: they verify that citizens are informed of their rights when a machine decides their fate, that there are mechanisms to contest the outcome with a human, that users can opt out of the automated process entirely, and that procedures exist for reporting major security incidents or data breaches to the proper authorities.

<div class="takeaways" markdown="1">

## Key Takeaways

* AI evaluation uses a phased walkthrough: review documents, request live demonstrations, and interview the personnel responsible — repeated to confirm safety checks work.
* Business context, the risk register, data sourcing with legal consent, and a data register form the foundation of the assessment.
* Model assessment covers preprocessing, anonymization, outliers, algorithm choice, explainability, and version management to catch model drift.
* Bias and fairness testing examines protected class data, high-stakes decisions, diverse user testing, and edge cases that fall outside normal operations.
* Performance metrics like the F1 score and stress testing, plus a compliance assessment protecting consumer rights and reporting obligations, complete the evaluation.

</div>

## Frequently Asked Questions

### What is the phased approach for AI audit walkthroughs and interviews?
Auditors do not rely only on written reports. They use a phased approach: first review the official documents, then request a live demonstration of the system in action, and finally ask targeted questions to the personnel responsible for the technology. Demonstrations are conducted multiple times throughout the evaluation to confirm the internal safety checks are actually working.

### What is a risk register and a data register in an AI audit?
A risk register is a master list of all potential problems that could go wrong with a project, used to assess technical, ethical, regulatory, and societal risks. A data register is a detailed inventory cataloging all the information used to teach the model, including how the raw material was acquired and the methods used to evaluate its quality.

### What is adversarial testing and why does it matter?
Adversarial testing is a security drill where friendly experts deliberately try to trick or break the system to find its hidden vulnerabilities. Auditors investigate security testing for data leakage, malicious injections, and adversarial prompts, and check whether automated testing frameworks were used and what the results were.

### What questions do auditors ask about bias and fairness?
Auditors verify whether the system aligns with the organization's ethical values, whether it processes protected class data like race, religion, or gender, and whether it makes high-stakes decisions in areas like law enforcement or hiring. They check what steps detected prejudice, how bias was remediated, whether the system was tested on a diverse group of users, and how edge cases were handled.

### What consumer rights must auditors verify in an AI compliance assessment?
Auditors verify that citizens are clearly informed of their rights when a machine makes a decision about their life, that there are mechanisms to contest the outcome with a human being, and that users can completely opt out of the automated process. They also confirm procedures for reporting major security incidents or data breaches to the proper authorities, including any notification required under laws like the EU AI Act.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Audit Walkthroughs & Interviews: Design & Evidence Capture](https://www.youtube.com/watch?v=qVASk58mKTo).*
