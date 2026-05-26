---
layout: default
title: "Identifying AI Assets: Inventory, Data Gathering & Documentation | ISACA AAIA Ep. 38"
description: "Learn how to identify AI assets, build a non-punitive inventory, gather data through surveys and discovery tools, and combat shadow AI. ISACA AAIA Ep. 38."
keywords: "identifying AI assets, AI inventory, AI asset inventory, shadow AI, AI discovery tools, data gathering, AI documentation, model catalog, AI audit, dataflow diagrams, surveys and interviews, ISACA AAIA"
author: "RooCloud"
image: "https://img.youtube.com/vi/ay0IQCHK9Z8/maxresdefault.jpg"
permalink: /domain-3-auditing-ai/ep38-identifying-ai-assets.html
---

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "VideoObject",
  "name": "Identifying AI Assets: Inventory, Data Gathering & Documentation",
  "description": "Learn how to identify AI assets, build a non-punitive inventory, gather data through surveys and discovery tools, and combat shadow AI. ISACA AAIA Ep. 38.",
  "thumbnailUrl": "https://img.youtube.com/vi/ay0IQCHK9Z8/maxresdefault.jpg",
  "uploadDate": "2026-05-01",
  "contentUrl": "https://www.youtube.com/watch?v=ay0IQCHK9Z8",
  "embedUrl": "https://www.youtube.com/embed/ay0IQCHK9Z8",
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
      "name": "Why are AI assets harder to identify than traditional IT assets?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "A traditional program is like a simple hammer that does one job and is easy to track, while an AI solution is like a massive automated manufacturing plant of interconnected systems. A single AI solution may have several owners, rely on multiple underlying models, exist in many software versions at once, require workflow mappings, contain separate training and production datasets, use multiple algorithms, incorporate third-party tools, and need multiple legal licenses and regulatory frameworks."
      }
    },
    {
      "@type": "Question",
      "name": "Should internal audit lead the AI asset discovery effort?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Internal audit should never lead or manage the discovery effort. The department responsible for data management or AI operations should lead, while the auditor's job is to independently review their work. Finding what tools are running requires a structured, team-based approach combining the risk management, operations, and audit teams."
      }
    },
    {
      "@type": "Question",
      "name": "What ten data fields should an AI inventory capture for every tool?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For every tool you should capture the name of the solution, the exact version number, any required licenses, the financial cost, the deployment method, the business purpose, the frequency of use, the relevant stakeholders, the accountable organization owner, and all third-party vendor details. Using a standardized list of fields guarantees consistent, high-quality data."
      }
    },
    {
      "@type": "Question",
      "name": "What is shadow AI and why does it make inventory difficult?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Shadow AI occurs when a department purchases and uses software without ever involving the central technology team, such as a marketing team buying a cloud video editing tool that analyzes customer faces and paying with a corporate credit card. Because these tools are so accessible, ownership becomes highly decentralized and IT may not even know they exist, which makes the auditor's role in reviewing the discovery process vital."
      }
    }
  ]
}
</script>

**[🏠 Back to Exam Syllabus](../README.md)** | **[📺 RooCloud on YouTube](https://youtube.com/@roocloud)** | **[🌐 RooCloud Practice Exams](https://roocloud.com)**

---

# Identifying AI Assets: Inventory, Data Gathering, and Documentation

You cannot audit what you cannot see, and that makes the **identification of AI assets** the very first step in audit planning and design. This episode of the **ISACA Advanced in AI Audit (AAIA)** exam prep series explains why artificial intelligence systems are so much harder to catalog than traditional software, how to build a comprehensive non-punitive inventory, the exact data-gathering methods you should use, and how to combat the pervasive risk of shadow AI. Master these techniques and you will be able to pinpoint unmonitored technologies that could be leaking sensitive corporate data, secure your organization without halting business productivity, and avoid severe financial penalties during regulatory compliance checks.

<div class="video-embed">
  <iframe src="https://www.youtube.com/embed/ay0IQCHK9Z8" title="Identifying AI Assets: Inventory, Data Gathering & Documentation" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>

## Why AI Assets Are Fundamentally Different from Traditional IT

A standard software program is like a simple hammer: one tool that does one job, easy to track. An AI solution is nothing like a basic spreadsheet application. Instead, it behaves like a massive, automated manufacturing plant composed of many interconnected systems. Because of this complexity, one single solution might have several different owners across the company, rely on multiple underlying computational models, and exist in many different software versions simultaneously.

These solutions carry vast requirements. They need detailed workflow mappings, which are visual guides showing exactly how data travels through the system from start to finish. They contain multiple datasets: *training datasets* act like the textbooks used to teach the system, while separate *production datasets* are the live streams of data the system works on every day. They also use multiple mathematical algorithms to make decisions.

Looking at the system development life cycle reveals even more complexity. AI solutions frequently incorporate external third-party tools. Rather than building from scratch, developers pull in open-source frameworks, cloud-based machine learning platforms, and pre-packaged algorithms from major cloud vendors. Because all these puzzle pieces are stitched together, the final product often requires multiple different legal licenses and must comply with a wide variety of legal and regulatory frameworks depending on what data it touches.

## Who Leads Discovery, and Where to Start

Organizations rely heavily on AI to make decisions, run operations, improve efficiency, and drive innovation, so identifying both internal and external assets is absolutely critical. Finding what is actively running requires a structured, team-based approach that combines the risk management, operations, and audit teams.

There is one very important rule here: **internal audit should never lead or manage this discovery effort.** The department responsible for data management or AI operations should lead. As an auditor, your job is to independently review their work.

A good starting point for your inventory is the organization's official AI usage policy. Drafting that policy usually forces the company to identify the tools it already has. If a baseline inventory exists, it must be updated at least once every year; if it is out of date, the inventory owner needs to begin an immediate update. Companies that build their own custom products must also maintain a highly specific *model catalog*, a detailed library of every custom algorithm they have created.

## Building a Non-Punitive Inventory

Ideally, the inventory should be modeled after existing software tracking processes. The primary purpose is strictly to identify what is running. It is absolutely **not** meant to penalize employees who are using unapproved tools.

Think of it like a community safety check. If city inspectors penalize people for reporting broken water pipes, people will simply hide the leaks. To succeed, leadership must broadcast a clear, organization-wide communication that states the exact purpose of the inventory, mandates the disclosure of all tools, and explains how the effort will improve security and collaboration. Management must guarantee that no one will be reprimanded for being honest.

## Data Gathering Methods and Discovery Tools

To find solutions the company built in-house, the internal audit team should review formal project documentation, including change requests, deployment logs, release notes, and general program management documents.

To find external systems running on the network, security and technology teams can use specific discovery tools:

* **Dataflow diagrams** — a map showing how information travels from one system to another, like a map of city subway lines.
* **Metadata** — simply data about data, like a digital shipping label that tells you the origin and destination of a file.
* **Active directory or user access management systems** — the central control panel that manages employee passwords, which you review to see which external applications are requesting login permissions.

### The Ten Mandatory Data Fields

You cannot just collect random notes. The organization must establish a standardized list of data fields to guarantee consistent, high-quality data. You must collect exactly ten specific details for every tool:

1. The name of the solution
2. The exact version number
3. Any required licenses
4. The financial cost
5. The deployment method (a website, an installed application, or an application programming interface — an API being a digital bridge that lets two software programs talk to each other in the background)
6. The tool's business purpose
7. The frequency of use
8. The relevant stakeholders
9. The accountable organization owner
10. All details related to the third-party vendor

## Asking the Workforce Directly: Surveys and Interviews

Beyond scanning networks, you must ask the workforce directly. Surveys are incredibly efficient, and offering some level of anonymity is crucial because it encourages people to tell the truth rather than giving the answer they think the boss wants to hear. Be careful, though: if a survey is completely anonymous, people might ignore it entirely because there is zero accountability. Use quantifiable questions that produce structured data, like multiple-choice options, rather than open text boxes.

When you conduct live interviews, the questions must be strictly standardized with predetermined response options, because open-ended questions give you messy, unusable data. For example, if someone says they use a generic text generator, you must follow up to learn whether it is Text Generator Pro from Company A or Deep Writer from Company B. Getting precise names lets you group similar responses accurately. Interviews are particularly useful with development teams who might be quietly experimenting with new tools for their own education rather than building official products.

## Documentation and the Shadow AI Challenge

All collected artifacts must be integrated into standard enterprise tracking platforms. Managing this inventory is uniquely difficult because of a phenomenon known as **shadow AI**. Shadow technology occurs when a department purchases and uses software without ever involving the central technology team. Imagine the marketing team buying a cloud-based video editing tool that uses complex algorithms to analyze customer faces, paying for it with a corporate credit card — the IT department has no idea it exists. Because these tools are so accessible, ownership becomes highly decentralized, making your role in auditing this process absolutely vital.

<div class="takeaways" markdown="1">

## Key Takeaways

* AI solutions are highly complex, multi-layered systems with distinct datasets, models, owners, versions, and legal considerations — far harder to track than a single piece of traditional software.
* Discovery must be led by management (data or AI operations), never by internal audit, whose role is to independently review the work.
* The inventory must be non-punitive; leadership must communicate its purpose and guarantee no reprisals so people report honestly.
* Use formal project documentation, dataflow diagrams, metadata, and access systems, plus anonymous-but-accountable surveys and standardized interviews, to capture ten mandatory data fields per tool.
* Shadow AI, where departments buy tools outside central IT, decentralizes ownership and makes auditing the discovery process essential.

</div>

## Frequently Asked Questions

### Why are AI assets harder to identify than traditional IT assets?
A traditional program is like a simple hammer that does one job and is easy to track, while an AI solution is like a massive automated manufacturing plant of interconnected systems. A single AI solution may have several owners, rely on multiple underlying models, exist in many software versions at once, require workflow mappings, contain separate training and production datasets, use multiple algorithms, incorporate third-party tools, and need multiple legal licenses and regulatory frameworks.

### Should internal audit lead the AI asset discovery effort?
No. Internal audit should never lead or manage the discovery effort. The department responsible for data management or AI operations should lead, while the auditor's job is to independently review their work. Finding what tools are running requires a structured, team-based approach combining the risk management, operations, and audit teams.

### What ten data fields should an AI inventory capture for every tool?
For every tool you should capture the name of the solution, the exact version number, any required licenses, the financial cost, the deployment method, the business purpose, the frequency of use, the relevant stakeholders, the accountable organization owner, and all third-party vendor details. Using a standardized list of fields guarantees consistent, high-quality data.

### What is shadow AI and why does it make inventory difficult?
Shadow AI occurs when a department purchases and uses software without ever involving the central technology team, such as a marketing team buying a cloud video editing tool that analyzes customer faces and paying with a corporate credit card. Because these tools are so accessible, ownership becomes highly decentralized and IT may not even know they exist, which makes the auditor's role in reviewing the discovery process vital.

<div class="cta" markdown="1">

### 📚 Master the ISACA AAIA Exam!

Ready to test your knowledge? Access chapter-specific **Multiple Choice Questions (MCQs)** and full-length practice exams for the ISACA AAIA certification at **[RooCloud.com](https://roocloud.com)**. Solve the chapter-wise questions to reinforce this lesson before moving to the next episode.

</div>

---

*Reference: This article is based on concepts discussed in [Identifying AI Assets: Inventory, Data Gathering & Documentation](https://www.youtube.com/watch?v=ay0IQCHK9Z8).*
