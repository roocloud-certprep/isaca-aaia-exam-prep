---
layout: default
title: "The AI Life Cycle: All 7 Stages from Plan to Retire | ISACA AAIA Ep. 4"
description: "Explore the 7 stages of the AI life cycle from plan and design to retire, plus latent risk, explainability, Human in the Loop, and the testing types auditors must know."
keywords: "AI life cycle, plan and design, data governance, build models, verification validation, deploy AI, operate and monitor, decommission, latent risk, Human in the Loop, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/tcUsCJ3Q67o/maxresdefault.jpg"
permalink: /domain-1-ai-governance-and-risk/ep04-ai-life-cycle.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "The AI Life Cycle: All 7 Stages from Plan to Retire",
  "description": "Explore the 7 stages of the AI life cycle from plan and design to retire, plus latent risk, explainability, Human in the Loop, and the testing types auditors must know.",
  "thumbnailUrl": "https://img.youtube.com/vi/tcUsCJ3Q67o/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=tcUsCJ3Q67o",
  "embedUrl": "https://www.youtube.com/embed/tcUsCJ3Q67o",
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
      "name": "What are the seven stages of the AI life cycle?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The seven phases are Plan and Design, Collect and Process Data, Build or Adapt Models, Test Evaluate Verify and Validate, Make Available for Use or Deploy, Operate and Monitor, and Retire or Decommission. Risk weaves through every single stage, and different actors may perceive those risks very differently."
      }
    },
    {
      "@type": "Question",
      "name": "What is latent risk in an AI system?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Latent means hidden or dormant. A system might look perfectly safe during early development, but as it encounters new information in the real world it adapts and new dangers can suddenly wake up. This is unique to AI and is why everyone involved shares responsibility for keeping the system trustworthy and fit for purpose."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between verification and validation?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Verification asks whether you built the system correctly according to your engineering blueprints. Validation asks whether you built the right system for your actual business problem. You could perfectly verify a high-speed train engine, but if your business needed an airplane it fails validation."
      }
    },
    {
      "@type": "Question",
      "name": "What are the five types of testing in the AI life cycle?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The five testing types are model testing for performance metrics like accuracy and precision, stress testing with extreme inputs, comparative analysis against older baselines, bias and fairness checks to ensure equitable treatment of all demographics, and scenario analysis using hypothetical real-world situations to predict how the system will react."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# The AI Life Cycle: All 7 Stages from Plan to Retire

Every artificial intelligence system follows a journey from the very first idea to the day it is finally switched off. In this fourth episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series, we go under the hood to explore the seven critical phases of the AI life cycle, examine how risk weaves through every single step, and learn why different people working on the system might see those risks completely differently. Understanding this life cycle is your blueprint for finding hidden vulnerabilities and preventing costly compliance failures before they ever reach the public.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/tcUsCJ3Q67o" title="The AI Life Cycle: All 7 Stages from Plan to Retire" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Understanding the AI Life Cycle and Latent Risk

Similar to traditional software development, the AI life cycle is the journey of a system from creation to implementation, ongoing operation, and eventual retirement. But artificial intelligence introduces a unique challenge called **latent risk**. Latent simply means hidden or dormant: a system might look perfectly safe during its early development, but as it encounters new information in the real world it adapts, and new dangers can suddenly wake up.

Because of this, we must consider the different people involved, often called **actors**. A software engineer creating a foundational language model has a very different viewpoint on risk than the hospital administrator who later uses that exact same model to transcribe patient records. The engineer might only worry about the software crashing; the administrator has to worry about a glitch altering a critical medical diagnosis. This is why everyone shares the responsibility to ensure the system is trustworthy and fit for its specific purpose.

## Phase 1: Plan and Design

This is where you map out the goals, context, and requirements of your proposed technology. Skip risk planning here and you are inviting failure — you might build something that violates ethical standards, introduces unfair bias, or lacks a clear chain of accountability. To prevent this, you start with a **business use case**: a formal justification document explaining exactly what problem you are trying to solve and how this specific technology will solve it.

You must bring **stakeholders** — anyone affected by the system, from the legal team to the end users — together early so leadership decides who is accountable and legal standards are met from day one. During this phase you also conduct an initial risk assessment to spot societal impacts or data biases, establish a **data governance framework** (the rules ensuring information is collected, stored, and used legally and privately), and use **prototyping**. A prototype is a rough early version of the system — just as an architect builds a cardboard scale model before pouring concrete, technologists build a prototype to test assumptions and catch flaws early, saving massive amounts of time and money.

## Phase 2: Collect and Process Data

Artificial intelligence is entirely dependent on the information it consumes; poor inputs directly lead to inaccurate, biased, or legally problematic outputs. The first step is gathering information from places like text documents, images, or environmental sensors. But here is a critical audit point: you must obtain **consent** for the information you collect. If a company secretly records customer phone calls to teach a computer to mimic human voices, it faces massive privacy lawsuits.

Once collected, the information must be **cleaned** — removing duplicates, fixing errors, and deleting irrelevant details — and run through completeness and quality checks. Imagine building an algorithm to predict city traffic but forgetting to include morning rush-hour data; your dataset is incomplete and your predictions will fail. Transparency is key, so you must document the characteristics of your dataset: how it was collected, what tools were used, how many records it contains, and its intended use, so nobody accidentally uses a traffic dataset to predict weather. Finally, keep detailed maintenance logs showing version control, retention plans, and any modifications over time.

## Phase 3: Build or Adapt Models

This is where raw information is transformed into a functioning "brain" for your system. First you choose the right mathematical framework based on problem complexity, then move to **calibration** (gently tweaking internal settings for accuracy, like tuning a guitar before a concert) and **training** (feeding in massive volumes of information so the system recognizes patterns on its own).

A major focus here is **explainability** — being able to look at a computer's final decision and understand exactly why it made that choice. If a bank's automated system denies a small-business loan, the bank must be able to explain which specific financial factors led to that rejection. To support this, systems should be designed with **automated event recording**, essentially an airplane black box for the software that logs every action so auditors can review it later. This logging directly supports **Human in the Loop** oversight, meaning the software does not make the final call on its own — a real person reviews the recommendation before any action is taken, ensuring human judgment and safety always override raw machine efficiency.

## Phase 4: Test, Evaluate, Verify, and Validate

This is where you prove the system actually works safely before letting anyone use it. It is vital to understand the difference between **verification** and **validation**. Verification asks: did we build the system correctly according to our engineering blueprints? Validation asks a different question: did we build the right system for our actual business problem? You could perfectly verify a high-speed train engine, but if your business needed an airplane, it fails validation. All testing must go through official change management processes. There are five specific types of testing you must know:

* **Model testing** — checks basic performance metrics like accuracy and precision against predefined benchmarks.
* **Stress testing** — pushes the system to its absolute limits with bizarre or extreme inputs to see if it breaks.
* **Comparative analysis** — races your new system against older baselines to prove it is actually an improvement.
* **Bias and fairness checks** — ensures the system treats all demographics equally and operates with total equity.
* **Scenario analysis** — feeds the system hypothetical real-world situations to predict how it will react.

Any flaws discovered become **lessons learned** that must be fixed before launch. If a risk cannot be entirely fixed, it goes into a formal risk mitigation plan on the official **project risk register**. Only after passing all these hurdles does management authorize the tool for a production state.

## Phase 5: Make Available for Use or Deploy

This is the transition into live operations. You start with **piloting** — rolling out the tool to a small, controlled group of users to gather feedback and prove the concept before a company-wide launch. You must also ensure compatibility with legacy systems; if your new algorithm cannot communicate with the twenty-year-old inventory database your warehouse relies on, operations will grind to a halt.

If you are handing the technology to third parties or downstream deployers, you must provide exhaustively clear technical documentation detailing how to install, configure, troubleshoot, and maintain the system — documentation that also proves your regulatory compliance to auditors. Deployment is deeply tied to **organizational change management**: you cannot just drop new software on employees and expect success. You must provide training, explain new job responsibilities, secure staff buy-in, and build a solid feedback loop that continuously monitors the user experience.

## Phase 6: Operate and Monitor

Once live, this is not a "set it and forget it" situation. It is a continuous, dynamic process of watching the system work day to day, constantly looking out for both intended and unintended consequences. A system meant to filter spam might unintentionally start deleting legitimate vendor invoices. To catch this, you rely on a **Quality Management System** — a formal, heavily documented framework that proves you are continuously meeting industry regulations. You fuel it using all the technical and risk documents created in earlier phases and validate it through regular ongoing audits.

## Phase 7: Retire or Decommission

All technology eventually reaches the end of its useful life. Usually systems are shut down because they become obsolete or a better alternative hits the market. However, from an audit perspective, a system might be retired *early* if an ongoing risk assessment proves its dangers now exceed management's defined **risk appetite**. You cannot just pull the plug — you need a detailed decommissioning plan routed through change management. You must safely migrate or delete the old data, ensure no other business systems crash when this one disappears, and guarantee operations continue without interruption. Throughout this phase, clear communication with everyone involved is essential to set expectations and minimize disruption.

<div class="takeaways" markdown="1">

## Key Takeaways

* The AI life cycle has seven phases: Plan and Design, Collect and Process Data, Build or Adapt Models, Test/Evaluate/Verify/Validate, Deploy, Operate and Monitor, and Retire.
* Latent risk means hidden dangers can wake up as a system adapts in the real world, and different actors perceive the same risk very differently.
* Build explainable models supported by automated event recording and Human in the Loop oversight so humans keep final control.
* Verification asks "did we build it right?" while validation asks "did we build the right thing?" — backed by five testing types including bias and fairness checks.
* Retirement requires a formal decommissioning plan through change management to migrate or delete data safely without disrupting the business.

</div>

## Frequently Asked Questions

### What are the seven stages of the AI life cycle?
The seven phases are Plan and Design, Collect and Process Data, Build or Adapt Models, Test Evaluate Verify and Validate, Make Available for Use or Deploy, Operate and Monitor, and Retire or Decommission. Risk weaves through every single stage, and different actors may perceive those risks very differently.

### What is latent risk in an AI system?
Latent means hidden or dormant. A system might look perfectly safe during early development, but as it encounters new information in the real world it adapts and new dangers can suddenly wake up. This is unique to AI and is why everyone involved shares responsibility for keeping the system trustworthy and fit for purpose.

### What is the difference between verification and validation?
Verification asks whether you built the system correctly according to your engineering blueprints. Validation asks whether you built the right system for your actual business problem. You could perfectly verify a high-speed train engine, but if your business needed an airplane it fails validation.

### What are the five types of testing in the AI life cycle?
The five testing types are model testing for performance metrics like accuracy and precision, stress testing with extreme inputs, comparative analysis against older baselines, bias and fairness checks to ensure equitable treatment of all demographics, and scenario analysis using hypothetical real-world situations to predict how the system will react.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [The AI Life Cycle: All 7 Stages from Plan to Retire](https://www.youtube.com/watch?v=tcUsCJ3Q67o).*
