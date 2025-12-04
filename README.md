# What CISOs want from Vendors

## Background
The origins of this is a roundtable around red-teaming, and some time on my hands to start thinking about this…

## Assurance we can trust
On paper, any organization can look good. It doesn't stop the breaches, usually because those breaches are caused by third-parties, we (buyers) have no control over. All of the Biggies in 2025 were related to third-party deficiences. 

  1. We want to know, clearly, what functions are in-house, what functions are out-sourced.
  1. We want to know that you have contractual clauses to prevent your outsourcer outsourcing without your prior approval.
  1. We want to know that you do a proper -- not just a paper exercise -- when it comes to auditing your suppliers. You visit them. You observe their working practices. You stress-test likely scenarios. You review incident reports and see the evidence for the root causes of "lessons learnt" being resolved. You check what's in scope of their assurance regime (and more importantly, what's not).

## No end-of-life software
  1. Unless absolutely unavoidable, we need to know that the software used to run services is maintained by its supplier, and that the software is patched and kept up to date.
  1. We want to know that this is an automated process and that changes are applied based on their severity (in the real world, not hypothetical scenarios)

## Vulnerabilities & Patching
  1. We want to know that you and your suppliers patch regularly and patch where it matters.
  1. When there's a Big Well Known Zero Day / Remote Code Execution vulnerability that you and your suppliers have accellerated this. We don't want to chase you. We want you to publish this information via standard processes (e.g. through a .well-known/security.txt URI, prominently on your public facing website, via Social Media, via STIX/TAXII feeds).

## Testing
  1. We want to know what's in scope of testing, and what's excluded from testing.
  1. We want to review the summaries of reports, and be aware of what's already been resolved, and what's waiting for time to resolve (and when). We want you to proactively inform us when things are done, and the retest confirms these as no longer being an issue.
  1. We want to know what type of test has been done. Is it black/grey/white box? Is it Threat Led? Is it manual or automated? 

## Contracts
  1. We expect to see security detailed in contracts and specific SLAs, KPIs, or KRIs relating to security  beyond "we take security seriously".
  1. We expect to use industry specific requirements -- e.g. rights of audit being reflected where they can be required.

## Security Incidents
  1. We expect you to tell us as soon as practicable, but within two hours of confirming, security incidents that affect us.
  1. We do not want to chase you for a full and frank post-mortem; we expect to receive an updated report that is clear, unambiguous, and straight to the details.
  1. We may need to disclose this to *our* customers and/or regulators, so it should be published online.

## Our counterpart
  1. We want to know who our counterpart is. Ideally, this will be on your "Team" page on the website.
  1. We want to know that our counterpart is sufficiently placed to be able to influence decisions, and is not just a titular, sub-ordinate role.
  1. We anticipate that you will confirm the independence of the CISO (and their department)

## Essential Cyber Hygeine
  1. We want to know that the basics are in place: 
    1. No passwords, or a strong (but sensible) password policy
    1. Default passwords are changed
    1. No passwords in the Top 100k password lists are used by anyone
    1. Passwords are not stored in plain text ever.
    1. Passwords do not have an upper limit of characters
    1. Principle of Least Privilege is adhered to, where ever possible
    1. Networks segmentation is adhered to
    1. "Production" data is only used in production, and not for testing.
    1. Data Leakage Prevention technologies are in use, and have been tested sufficiently
    1. Training is available to everyone covering modern practices, and that people who do not pass the training do not have elevated permissions, or access to sensitive data. 
    1. Training is continual, not annual.
    1. People do not walk around with "super admin" permissions all the time, but if they need it for a task, they can have access as needed.
    1. User accounts are not shared.
    1. HR support Cyber in taking appropriate action for breaches of policy, at all levels of the firm, including C-suite.
    1. People are not fired/treated unfairly for raising security concerns.
    1. A whistleblowing service is available in all countries you operate in and workers are made aware of it.
    1. You know, and will share (on request), the high-level types of data that flow through each system
    1. You will learn from incidents
    1. You will conduct realistic, cross-functional, desktop exercises to build up confidence in incidents and crises
    1. You strive for continual improvement, and increasing cyber maturity
    1. You won't sweep things under the carpet because they are inconvenient or embarassing

## The SSO Tax
  1. We don't believe we should pay extra for helping you secure your stack -- give us:
     1. SSO as a standard offering
     1. Full SCIM as standard
  1. We also want to know what's going on in our SaaS, so give us not just access to our log data, but also an API we can use, and ideally maintained connectors to our SIEM.

## Meaningful Encryption
< cloud makes it too easy to see stuff>
Not just at rest/in transit, but in use

## AI
  1. AI is used safely
  1. Impactful training has been delivered to everyone so they are aware what can/can't be shared with AI tooling (internal and external).

## Proportionate Training
  1. Some roles may be higer risk than others; people who can move money around, people with access to data etc. These should be assessed if extra, role-specific training is needed to manage the risks of what these colleagues can do.


## Citations
 - FCA SYSC 8
 - EBA & DORA
 - Corporate Governance Code
 - NCSC guides…
 - CIS…
 - SANs…
 