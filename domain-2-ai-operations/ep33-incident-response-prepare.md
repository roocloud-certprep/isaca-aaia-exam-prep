---
layout: default
title: "AI Incident Response — Prepare: Policies, IR Team & Tabletops | ISACA AAIA Ep. 33"
description: "Phase 1 of AI incident response: adapt ISO 27035-1, build AI-ready policies, model cards, an upgraded IR team, and run tabletop exercises before a crisis hits."
keywords: "AI incident response, ISO 27035-1, incident response preparation, model card, tabletop exercise, data poisoning, AI ethicist, data steward, escalation protocol, incident response team, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/HHa-8nQMlEc/maxresdefault.jpg"
permalink: /domain-2-ai-operations/ep33-incident-response-prepare.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Incident Response — Prepare: Policies, IR Team & Tabletops",
  "description": "Phase 1 of AI incident response: adapt ISO 27035-1, build AI-ready policies, model cards, an upgraded IR team, and run tabletop exercises before a crisis hits.",
  "thumbnailUrl": "https://img.youtube.com/vi/HHa-8nQMlEc/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=HHa-8nQMlEc",
  "embedUrl": "https://www.youtube.com/embed/HHa-8nQMlEc",
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
      "name": "What are the five phases of the ISO 27035-1 incident response framework?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The five phases are prepare, identify and report, assess, respond, and post-incident review. You prepare by building policies and assembling your team, identify and report by detecting the problem and sounding the alarm, assess by determining severity and impact, respond by containing, eliminating and recovering, and finally conduct a post-incident review to learn lessons and improve future defenses. The same five steps can be adapted to handle AI crises."
      }
    },
    {
      "@type": "Question",
      "name": "What three types of AI incidents must an organization prepare for?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The three types are abuse of the system's output to cause harm to society, such as mass-producing fake threatening letters to manipulate an election; disclosure of confidential or personal data the algorithm absorbed during training; and the system generating predictions that are biased, incorrect, or hallucinated, where the computer confidently makes things up."
      }
    },
    {
      "@type": "Question",
      "name": "What is a model card and why is it important during an incident?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A model card is essentially a nutritional label for software. Instead of listing calories it documents the exact data ingredients and logic the system uses, including its internal architecture and the raw information it studied. During an emergency, flawless model documentation lets investigators interpret exactly how the system makes decisions so they are never flying blind."
      }
    },
    {
      "@type": "Question",
      "name": "Who should be on an AI incident response team?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Alongside normal technology and security staff, an AI incident response team must include data stewards or owners who understand the training datasets, data engineers and scientists who built the model and can interpret anomalous behavior, privacy experts who keep the cleanup within global privacy and data sovereignty laws, and an AI ethicist who serves as the moral compass to keep technical fixes safe and ethical for society."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Incident Response — Prepare: Policies, IR Team, and Tabletop Exercises

When intelligent algorithms fail, you need a plan that was written long before the crisis began. This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series opens a five-part series on AI incident response, and it covers **Phase 1 — Prepare**, the very first step in the incident-response lifecycle that runs through identify and report, assess, respond, and post-incident review. Mastering preparation lets you assess whether your organization is genuinely ready for a crisis, ensure your corporate emergency playbooks include the right experts and procedures, and prevent a simple software mistake from turning into a catastrophic legal or reputational disaster.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/HHa-8nQMlEc" title="AI Incident Response — Prepare: Policies, IR Team & Tabletops" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Adapting the ISO 27035-1 Five-Phase Framework

In conventional environments, disasters usually look like a network outage, a malicious hacker seizing control, or severe data corruption. These events are highly destructive, but they are completely understood by technical professionals. To handle them, the industry relies on a global standard known as the **ISO 27035-1** framework, which lays out a reliable five-phase pathway for managing security emergencies:

1. **Prepare** — build your policies, define your processes, and assemble your emergency team before anything goes wrong.
2. **Identify and report** — detect the problem and sound the alarm.
3. **Assess** — figure out the severity and impact of the damage.
4. **Respond** — contain the threat, eliminate it, and recover normal operations.
5. **Post-incident review** — analyze the root cause to learn lessons and improve future defenses.

Think of this like managing a house fire: you install smoke alarms to prepare, the alarm rings to identify the fire, you check how big it is to assess, you spray water to respond, and you figure out why the stove caught fire during the post-incident phase. Emergencies caused by intelligent algorithms are a relatively new global phenomenon, but we do not need to throw away this rulebook — we can adapt these exact same five steps to handle algorithmic crises.

## Why Preparation Is the Most Critical Phase

The most critical step for an organization's survival and long-term resilience is the very first phase, preparation. Most corporations already have an incident response program, but the vast majority have failed to adapt their policies, procedures, and staff to handle issues specific to artificial intelligence.

### The Three Major Types of Algorithmic Incidents

* **Abuse of the system's output to cause harm to society.** Imagine someone using a text-generating algorithm to instantly mass-produce thousands of fake, threatening letters to manipulate a local election.
* **Disclosure of confidential or personal data** that the algorithm absorbed during its educational training phase. This is like a corporate receptionist accidentally broadcasting a client's private medical history over the public intercom.
* **Predictions that are biased, entirely incorrect, or hallucinated.** Hallucination means the computer is confidently making things up — think of a digital map that enthusiastically tells a driver to turn onto a bridge that simply does not exist.

An updated, automated-ready response program must explicitly address these unique risks and their potential impact on human welfare.

## Updating Policies, Ethics, and Documentation

To prepare properly, an organization must update its emergency policies to tackle these specific threats, outline precise detection techniques, and establish ethical guidelines. A crucial rule of crisis management is that **debates over the ethics of using an algorithm must happen far away from active incident response efforts**. You do not debate the philosophy of breaking a window when the building is actively burning — those decisions must be made when heads are cool.

A massive part of preparation involves maintaining flawless **model documentation**. When an emergency happens, investigators need to interpret exactly how the system makes decisions, its internal architecture, and the raw information it studied. This is typically done using a **model card** — essentially a nutritional label for software. Instead of listing calories, it lists the exact data ingredients and logic the system uses. This documentation must also include a clear communication plan and escalation protocols so you know exactly who to call, whether that involves internal business leaders, external public relations firms, or law enforcement agencies.

## Upgrading the Incident Response Team

You cannot fight a new type of digital fire with the exact same fire department. Alongside your normal technology and security guards, your team must include specialized subject matter experts and risk management professionals:

* **Data stewards or owners** — experts who intimately understand the specific datasets used to teach the algorithm. They are like librarians who know every single book in the library.
* **Data engineers and scientists** — the mechanics who handled the preprocessing and training of the model. Because they built the engine, they are perfectly positioned to interpret bizarre, anomalous behavior.
* **Privacy experts** — they guide cleanup efforts to ensure that investigating the incident does not accidentally violate global privacy laws, data sovereignty regulations, or individual human rights.
* **An AI ethicist** — a brand new type of stakeholder who serves as the moral compass of the team, specifically trained to ensure all technical fixes remain safe and ethical for society.

## Training the Team with Tabletop Exercises

Once you have your team and your rules, the organization must train them using standard operating procedures, typically through **tabletop exercises**. A tabletop exercise is a simulated role-play: the team gathers around a table, pretends a massive disaster is happening right now, and tests their reflexes and tools. These practice runs must be uniquely tailored to intelligent systems.

The forensic tools you use to evaluate a normal network breach are completely different from the tools you need to investigate **data poisoning** — a covert attack where someone secretly sneaks malicious information into the system's educational materials, forcing it to learn the wrong lessons. Imagine someone sneaking into a bakery at night and swapping the labels on the sugar and the salt: the doors were not broken, but every cake produced the next day is ruined. To catch a poisoning attack, the response team cannot just look at network security logs — they need deep access to the **data lake**, the massive central storage pool where all raw organizational information lives. By collaborating with data scientists to analyze what goes into the machine versus what comes out, the team gains the experience needed to act swiftly during a real crisis.

<div class="takeaways" markdown="1">

## Key Takeaways

* The ISO 27035-1 five-phase framework — prepare, identify and report, assess, respond, and post-incident review — can be adapted from traditional disasters to algorithmic crises.
* Preparation is the most critical phase for survival; most organizations have an IR program but have not adapted it for AI-specific risks.
* The three AI incident types are output abuse harming society, disclosure of confidential training data, and biased, incorrect, or hallucinated predictions.
* Settle ethical debates and maintain crystal-clear model cards during preparation so investigators are never flying blind in a real crisis.
* An AI-ready response team adds data owners, scientists, privacy experts, and an AI ethicist, all of whom rehearse with AI-tailored tabletop exercises.

</div>

## Frequently Asked Questions

### What are the five phases of the ISO 27035-1 incident response framework?
The five phases are prepare, identify and report, assess, respond, and post-incident review. You prepare by building policies and assembling your team, identify and report by detecting the problem and sounding the alarm, assess by determining severity and impact, respond by containing, eliminating and recovering, and finally conduct a post-incident review to learn lessons. The same five steps can be adapted to handle AI crises.

### What three types of AI incidents must an organization prepare for?
The three types are abuse of the system's output to cause harm to society, such as mass-producing fake threatening letters to manipulate an election; disclosure of confidential or personal data the algorithm absorbed during training; and the system generating predictions that are biased, incorrect, or hallucinated, where the computer confidently makes things up.

### What is a model card and why is it important during an incident?
A model card is essentially a nutritional label for software. Instead of listing calories it documents the exact data ingredients and logic the system uses, including its internal architecture and the raw information it studied. During an emergency, flawless model documentation lets investigators interpret exactly how the system makes decisions so they are never flying blind.

### Who should be on an AI incident response team?
Alongside normal technology and security staff, an AI incident response team must include data stewards or owners who understand the training datasets, data engineers and scientists who built the model and can interpret anomalous behavior, privacy experts who keep the cleanup within global privacy and data sovereignty laws, and an AI ethicist who serves as the moral compass to keep technical fixes safe and ethical for society.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Incident Response — Prepare: Policies, IR Team & Tabletops](https://www.youtube.com/watch?v=HHa-8nQMlEc).*
