---
layout: default
title: "AI Agency: Logging, Observability, HITL & Hallucinations | ISACA AAIA Ep. 28"
description: "Explore AI agency and supervision: logging chain of thoughts, the 4 observability categories, human in the loop controls, and how to prevent hallucinations."
keywords: "AI agency, logging and monitoring, chain of thoughts, AI observability, model drift, interpretability, counterfactual explanations, human in the loop, HITL, hallucination, guardrails, nano decisions, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/_vv5zpk0wIg/maxresdefault.jpg"
permalink: /domain-2-ai-operations/ep28-ai-agency.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Agency: Logging, Observability, HITL & Hallucinations",
  "description": "Explore AI agency and supervision: logging chain of thoughts, the 4 observability categories, human in the loop controls, and how to prevent hallucinations.",
  "thumbnailUrl": "https://img.youtube.com/vi/_vv5zpk0wIg/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=_vv5zpk0wIg",
  "embedUrl": "https://www.youtube.com/embed/_vv5zpk0wIg",
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
      "name": "What is AI agency and what risks does it create?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Agency is the ability of a machine to act independently, taking action on its own without waiting for a human to push a button. It creates four practical headaches for auditors: accountability for who is legally responsible when something goes wrong, self-regulation rules the machine follows, conflicting values when an efficient decision ignores human empathy, and the expectation of explainability when even the programmers cannot untangle the math."
      }
    },
    {
      "@type": "Question",
      "name": "What are the four categories of AI observability?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The four categories are data pipelines, which monitor data quality and catch malicious actions like prompt injection; infrastructure and system health, which tracks processing power and storage; model performance, which compares inputs to outputs and user feedback to detect model drift; and interpretability, which uses counterfactual explanations, feature visualization, and influential instance analysis to peek inside the black box."
      }
    },
    {
      "@type": "Question",
      "name": "What is the human in the loop strategy?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Human in the loop is the ultimate safety net for highly critical decisions, where the AI does not act alone. The workflow pauses and a human must give explicit approval before the action is finalized, like an autopilot that flies the plane while a human pilot monitors and can take over. Because it intentionally slows the system, it is reserved for situations where the risk is extremely high."
      }
    },
    {
      "@type": "Question",
      "name": "What causes AI hallucinations and how are they controlled?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A hallucination is when the software confidently presents an answer disconnected from reality. The three main culprits are flawed training data, a lack of real-world grounding, and ambiguity in the data input. To fight them, teams use strict guardrails on what is allowed in and out of the system and templates that force answers into a rigid, consistent structure with less room to wander into fantasy."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Agency: Logging, Observability, Human in the Loop, and Hallucinations

What happens when artificial intelligence systems start making decisions completely on their own — and how do we keep them under control? This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series explores **AI agency and supervision**. For an auditor or corporate leader, this knowledge is crucial: when your organization wants to deploy an automated tool, you need to know exactly how to trace its decisions and where to place human checkpoints to avoid massive financial or reputational damage. It gives you the power to evaluate whether a shiny new AI is actually safe for your specific business workflows.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/_vv5zpk0wIg" title="AI Agency: Logging, Observability, HITL & Hallucinations" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## What Is AI Agency?

**Agency** simply means the ability of a machine to act independently — when an AI does not just give advice but actually takes action on its own without waiting for a human to push a button. A standard thermostat you adjust manually has no agency. A smart climate system that checks the weather forecast, tracks how many people are in the building, and decides to shut down heating in empty rooms to save money has agency. But this independence creates four major practical headaches for auditors:

* **Accountability:** If that smart system freezes the pipes and causes a flood, who is legally responsible for the damage?
* **Self-regulation:** We need to know what internal rules the machine follows to behave safely.
* **Conflicting values:** What if the machine makes a highly efficient decision that completely ignores human empathy or corporate values?
* **Expectation of explainability:** Users expect to know why a decision was made, but if the programmers themselves cannot untangle the math, that is a huge problem.

## Logging and Monitoring the Chain of Thoughts

To solve the explainability problem, we rely on **logging and monitoring**. Deep learning models are incredibly complex because they use massive datasets and perform high-dimensional calculations — looking at millions of factors simultaneously. So we force them to leave a trail of clues called a **chain of thoughts**, an audit log that tracks the data going in, the path the computer took, and the final answer it produced. Think of a student forced to show their math work rather than just writing the final answer.

There is a catch, though. These models make **nano decisions** — millions of tiny, lightning-fast calculations. If we tried to log every one, our hard drives would fill in seconds and no human could read the log. The solution is a middle ground: maintain a modest log of the most critical steps. Specifically, we log the exact **data inputs**, the **model parameters and version numbers**, and the **final outputs**. This gives a practical audit trail to troubleshoot issues without drowning in useless data.

## The 4 Categories of AI Observability

Logging looks at the past, but **observability** looks at the present to ensure the system stays healthy and reliable. There are four main categories to observe:

* **Data pipelines:** The digital plumbing feeding information into the brain of the AI. Monitoring it spots bad data quality before it ruins results and catches malicious actions like a **prompt injection attack**, where a user tries to trick the AI with hidden, harmful instructions.
* **Infrastructure and system health:** The physical computers running the software. We monitor metrics like processing power and storage consumption so we know before the system crashes, helping meet service agreements and manage cloud costs.
* **Model performance:** We constantly compare inputs to outputs and review user feedback. This continuous loop helps detect **model drift** — when an AI gets out of touch with reality and its accuracy slowly degrades, much like an outdated map.
* **Interpretability:** Deep learning models have hidden layers that act like a black box. To peek inside, we use three strategies, described below.

### Three Interpretability Strategies
The first is **counterfactual explanations** — tweaking one tiny detail to see if it flips the outcome. If you are denied a bank loan, a counterfactual test checks whether raising your reported income by one thousand dollars would have changed the denial into an approval. The second is **feature visualization**, which highlights exactly which of the thousands of variables actually mattered most, like using a highlighter pen on the key sentences in a giant book. The third is the **influential instance**, a debugging tool where we purposely delete one specific piece of training data to see if the machine acts differently, helping isolate the exact data that taught the AI a bad habit.

## Human in the Loop: The Ultimate Safety Net

For highly critical decisions, we simply do not let the AI act alone. With the **human in the loop (HITL)** strategy, the workflow pauses and a human must give explicit approval before the action is finalized. Think of an autopilot on a commercial airplane: the computer can fly the plane, but a human pilot always sits there to monitor and take over if something goes wrong. Because doing this intentionally slows down the speed of your automated system, you only want to use it when the risk is extremely high.

## Understanding and Controlling Hallucinations

A **hallucination** happens when the software confidently presents an answer completely disconnected from reality or the input data — the machine making things up. This happens a lot with generative AI. If you are painting a surreal picture, a hallucination is fine; but in a highly regulated industry like healthcare or finance, a hallucination can ruin human lives and destroy trust in your company. There are three main culprits:

* **Flawed training data:** If the machine was fed biased, fictional, or poorly labeled information, it treats those lies as facts.
* **Lack of real-world grounding:** A generative AI only predicts the next logical word from its training; it does not inherently know a human cannot breathe underwater, so it may suggest physically impossible solutions.
* **Ambiguity in data input:** If the prompt is vague, confusing, or harmful, the model gets confused and guesses, often producing inaccurate nonsense.

To fight hallucinations, we implement two strong controls: strict **guardrails** on what is allowed to go into and come out of the system, and **templates** that force the AI to pour its answers into a rigid, consistent structure, leaving less room to wander off into fantasy.

## Testing AI Solutions

Finally, testing an AI is notoriously difficult because the decision-making brain is a black box — you cannot just read the code to see why it made a choice, which creates new challenges traditional testers are not used to. But remember that an AI system is still software: all of your conventional testing practices and tools absolutely still apply to the standard components surrounding the AI, like the databases and the user interface.

<div class="takeaways" markdown="1">

## Key Takeaways

* AI agency means a machine acts independently, raising four issues: accountability, self-regulation, conflicting values, and explainability.
* Logging captures a chain of thoughts, but because models make millions of nano decisions, teams log only critical steps: inputs, model parameters and versions, and outputs.
* Observability spans four categories — data pipelines, infrastructure and system health, model performance, and interpretability — using counterfactual explanations, feature visualization, and influential instances.
* The human in the loop strategy pauses the workflow for explicit human approval on high-stakes decisions, accepting slower speed for greater safety.
* Hallucinations stem from flawed data, lack of real-world grounding, and ambiguous input, and are controlled with guardrails and rigid output templates.

</div>

## Frequently Asked Questions

### What is AI agency and what risks does it create?
Agency is the ability of a machine to act independently, taking action on its own without waiting for a human to push a button. It creates four practical headaches for auditors: accountability for who is legally responsible when something goes wrong, self-regulation rules the machine follows, conflicting values when an efficient decision ignores human empathy, and the expectation of explainability when even the programmers cannot untangle the math.

### What are the four categories of AI observability?
The four categories are data pipelines, which monitor data quality and catch malicious actions like prompt injection; infrastructure and system health, which tracks processing power and storage; model performance, which compares inputs to outputs and user feedback to detect model drift; and interpretability, which uses counterfactual explanations, feature visualization, and influential instance analysis to peek inside the black box.

### What is the human in the loop strategy?
Human in the loop is the ultimate safety net for highly critical decisions, where the AI does not act alone. The workflow pauses and a human must give explicit approval before the action is finalized, like an autopilot that flies the plane while a human pilot monitors and can take over. Because it intentionally slows the system, it is reserved for situations where the risk is extremely high.

### What causes AI hallucinations and how are they controlled?
A hallucination is when the software confidently presents an answer disconnected from reality. The three main culprits are flawed training data, a lack of real-world grounding, and ambiguity in the data input. To fight them, teams use strict guardrails on what is allowed in and out of the system and templates that force answers into a rigid, consistent structure with less room to wander into fantasy.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Agency: Logging, Observability, HITL & Hallucinations](https://www.youtube.com/watch?v=_vv5zpk0wIg).*
