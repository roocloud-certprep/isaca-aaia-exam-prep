---
layout: default
title: "AI Threats: Data Poisoning, Prompt Injection & Model Theft | ISACA AAIA Ep. 31"
description: "Explore AI threats across three attack surfaces: data leakage, data and model poisoning, model theft, prompt injection, evasion, inversion, and disruption."
keywords: "AI threats, attack surface, training data leakage, data exfiltration, data poisoning, model poisoning, model theft, prompt injection, model evasion, model inversion, denial of service, retrieval augmented generation, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/kh95HOcRPkk/maxresdefault.jpg"
permalink: /domain-2-ai-operations/ep31-ai-threats.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "AI Threats: Data Poisoning, Prompt Injection & Model Theft",
  "description": "Explore AI threats across three attack surfaces: data leakage, data and model poisoning, model theft, prompt injection, evasion, inversion, and disruption.",
  "thumbnailUrl": "https://img.youtube.com/vi/kh95HOcRPkk/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=kh95HOcRPkk",
  "embedUrl": "https://www.youtube.com/embed/kh95HOcRPkk",
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
      "name": "What are the three attack surfaces of an AI system?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "An attack surface is any digital location where an unauthorized person might try to break in or cause damage. The three surfaces are development-time threats that occur while the system is being built, runtime security threats that target the conventional servers and infrastructure hosting the model, and threats through use that happen during routine daily operations involving what users type in and what the system answers back."
      }
    },
    {
      "@type": "Question",
      "name": "What is the difference between data poisoning and model poisoning?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Data poisoning means deliberately injecting malicious or corrupted information into the training dataset to manipulate how the system behaves, which can also affect retrieval augmented generation when an attacker sneaks false information into documents the AI reads. Model poisoning is different because the attacker directly tampers with the mathematical parameters, core architecture, or software libraries of the model itself, which can also happen if you buy a pre-trained system that was tampered with before delivery."
      }
    },
    {
      "@type": "Question",
      "name": "How can an AI model be stolen without breaking into the server?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Beyond directly downloading the model files, an attacker can send thousands of carefully designed questions to the system and analyze the exact answers it gives to reverse engineer the mathematical logic and build an exact digital clone. It is like a rival chef tasting your signature dish every day until they figure out your secret recipe without ever stepping into your kitchen."
      }
    },
    {
      "@type": "Question",
      "name": "What is a prompt injection attack?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A prompt injection targets generative systems with specifically crafted text commands that manipulate the system into ignoring its original safety rules, like hypnotizing a loyal guard into opening a vault. An indirect prompt injection happens when the system reads a seemingly normal file containing hidden malicious instructions. Developers defend with structural templates that sanitize inputs and filters that monitor and block inappropriate outputs."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# AI Threats: Data Poisoning, Prompt Injection, and Model Theft

Artificial intelligence systems are vulnerable at every stage — when we build them, when we run them, and when end users interact with them. This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series breaks down the major threats facing AI systems. Mastering these threat profiles has immense practical value: you will be equipped to advise your organization on whether a new automated tool is actually safe to deploy for office workflows, and you will know exactly what security questions to ask external vendors before signing a contract.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/kh95HOcRPkk" title="AI Threats: Data Poisoning, Prompt Injection & Model Theft" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## The Three AI Attack Surfaces

The industry-standard framework divides AI vulnerabilities into three primary **attack surfaces** — an attack surface being any digital location where an unauthorized person might try to break in or cause damage:

* **Development-time threats** occur while the system is actively being built — the construction phase. Vulnerabilities here involve the engineer workspaces and the supply chain where raw information is gathered.
* **Runtime security threats** target the conventional computer systems hosting the model. AI requires standard web servers, software wrappers, and network infrastructure, so if a hacker exploits a traditional software flaw to access the server, the AI is compromised no matter how well it was designed.
* **Threats through use** happen during routine daily operations, focusing on the information people type into the system and the answers it provides back.

## Training Data Leakage

The first major development threat is **training data leakage**. Training AI requires massive datasets, and data leakage happens when this highly sensitive information is stolen or copied out of the secure workspace, usually because of weak access controls along the digital supply chain. The leak might happen at the original collection source, during data cleaning, or directly from programmer workstations. Picture a high-security kitchen testing a secret recipe: if the doors are left unlocked and an assistant walks out with a bag of secret ingredients, that is data leakage.

In the tech world, data scientists use highly flexible testing environments that prioritize convenience, so a simple command can accidentally or intentionally transfer thousands of private records to an external cloud drive. This unauthorized outward transfer is called **data exfiltration**, and organizations must build strict network barriers to prevent it.

## Poisoning Attacks: Data and Model

Poisoning attacks are divided into data poisoning and model poisoning. **Data poisoning** means deliberately injecting malicious or corrupted information into the training dataset to manipulate how the final system behaves. Finding these bad records is incredibly difficult because datasets are enormous, and attackers can introduce poison at the data source, through a compromised data broker, by intercepting network traffic, or during the data cleaning phase.

There is also a huge risk with **in-context training**, where the AI reads external documents to find answers — often called **Retrieval Augmented Generation (RAG)**. Imagine giving a student an open-book test: if an attacker sneaks false information into that textbook, the student confidently gives the wrong answer. The ultimate impact of data poisoning is either a secret **backdoor** that triggers bad behavior on command, or general sabotage that ruins the reliability of the entire system.

**Model poisoning** is a completely different approach. Instead of corrupting the raw information, the attacker directly tampers with the mathematical parameters, the core architecture, or the software libraries of the model itself. This can also happen if you purchase a pre-trained system from a vendor that was tampered with before delivery. Preventing direct model poisoning requires exceptionally strict access controls to the core programming environments.

## Model Theft

Creating an AI is a massive financial investment, so stolen models are highly valuable intellectual property — and they help hackers plan future adversarial attacks. An AI is essentially a highly complex mathematical formula represented by software code and configuration files. The most obvious form of **model theft** is a hacker breaking into a server and illegally downloading those exact files. However, an attacker can also steal a model without ever breaking in: by sending thousands of carefully designed questions and analyzing the exact answers, the attacker can reverse engineer the mathematical logic and build an exact digital clone — like a rival chef visiting your restaurant every day, tasting your signature dish, and eventually figuring out your secret recipe without ever stepping into your kitchen.

## Threats Through Use: Injection, Evasion, and Inversion

The most common threat through use is the **prompt injection** — an attack targeting generative systems with specifically crafted text commands that manipulate the system into ignoring its original safety rules, similar to hypnotizing a loyal guard into opening a vault by convincing them you are their new boss. These attacks are incredibly popular because anyone can attempt them through the normal user interface. An **indirect prompt injection** happens when the system reads a seemingly normal file that contains hidden malicious instructions. To defend, developers build structural templates that sanitize user inputs and install filters that monitor and block inappropriate outputs.

Next is **model evasion**, where an attacker intentionally alters their input to slip past the detection capabilities of the AI. For instance, if a filter blocks certain keywords, an attacker might slightly misspell those words to bypass it while still conveying the malicious message — the goal being to force a misclassification.

**Model inversion** tries to extract highly confidential information from the system. The attacker feeds in slightly modified inputs, observes the responses, and works backwards to deduce the hidden inner workings. Through this interrogation, the attacker can achieve **attribute inference** (figuring out sensitive details about people in the training data), **membership inference** (mathematically confirming if a specific person's record was used), and in extreme cases reconstruct near-perfect copies of the private training data.

## Vendor Risk and Solution Disruption

Many companies do not build their own systems from scratch; they purchase vendor-supplied AI out of the box. When you buy a pre-built system, the vendor handles the security of the training phase — but if that vendor suffered a data poisoning attack before you bought the software, your organization still suffers the negative impacts of that compromised system.

Finally, **AI solution disruption** can cause massive operational damage. Attackers flood the system with a huge volume of requests or send incredibly complex math problems, consuming all the computing power and creating a **denial of service**. The system becomes so overwhelmed that it crashes and denies access to legitimate users entirely.

<div class="takeaways" markdown="1">

## Key Takeaways

* AI vulnerabilities span three attack surfaces: development-time, runtime security, and threats through use.
* Training data leakage and exfiltration exploit weak access controls along the supply chain, demanding strict network barriers.
* Data poisoning corrupts training data (including RAG documents) while model poisoning tampers directly with parameters, architecture, or libraries — including in pre-trained vendor models.
* Models can be stolen by downloading files or by reverse engineering answers through thousands of crafted queries to build a clone.
* Threats through use include prompt injection, model evasion (forcing misclassification), and model inversion (attribute and membership inference), while vendor risk and denial-of-service disruption round out the threat picture.

</div>

## Frequently Asked Questions

### What are the three attack surfaces of an AI system?
An attack surface is any digital location where an unauthorized person might try to break in or cause damage. The three surfaces are development-time threats that occur while the system is being built, runtime security threats that target the conventional servers and infrastructure hosting the model, and threats through use that happen during routine daily operations involving what users type in and what the system answers back.

### What is the difference between data poisoning and model poisoning?
Data poisoning means deliberately injecting malicious or corrupted information into the training dataset to manipulate how the system behaves, which can also affect retrieval augmented generation when an attacker sneaks false information into documents the AI reads. Model poisoning is different because the attacker directly tampers with the mathematical parameters, core architecture, or software libraries of the model itself, which can also happen if you buy a pre-trained system that was tampered with before delivery.

### How can an AI model be stolen without breaking into the server?
Beyond directly downloading the model files, an attacker can send thousands of carefully designed questions to the system and analyze the exact answers it gives to reverse engineer the mathematical logic and build an exact digital clone. It is like a rival chef tasting your signature dish every day until they figure out your secret recipe without ever stepping into your kitchen.

### What is a prompt injection attack?
A prompt injection targets generative systems with specifically crafted text commands that manipulate the system into ignoring its original safety rules, like hypnotizing a loyal guard into opening a vault. An indirect prompt injection happens when the system reads a seemingly normal file containing hidden malicious instructions. Developers defend with structural templates that sanitize inputs and filters that monitor and block inappropriate outputs.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [AI Threats: Data Poisoning, Prompt Injection & Model Theft](https://www.youtube.com/watch?v=kh95HOcRPkk).*
