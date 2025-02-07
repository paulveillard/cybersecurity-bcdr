# Business Continuity and Disaster Recovery (BCDR): Theory, Techniques, Testing and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about Business Continuity and Disaster Recovery in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## `Table of Contents`

## What is Business Continuity and Disaster Recovery?

## 1 - Business Continuity Planning

## 2 - Disaster Recovery

### 2.1 Disaster Recovery Lifecycle

### 2.10 RTO and RPO requirements

## 3 - Business Continuity Management

### 3.1 - What is Business Continuity Planning?

Often, we think business continuity plans (BCP) and disaster recovery plans (DRP) are the same. 
> In reality, these two are not the same. DR is a subset of BCP and focuses on how to recover once a disaster has struck. BCP is at a more strategic level, it will talk about plans for business continuity in the event of a disaster.

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/bcm-1.png?raw=true" alt="Sublime's custom image"/>
</p>

Business continuity management (BCM) is a holistic management process to handle both BCP and DRP. BCM provides a framework for integrating resilience with the capability for effective responses in a manner that protects the interests of the organization’s key stakeholders. The main objective of BCM is to allow the organisation to continue to perform business operations under various conditions. BCM is the main approach to managing all aspects of BCP and DRP.

The following are a few widely used industrial standards and frameworks that are available for BCP.

- ISO/IEC 27031:2011: describes the concepts and principles of information and communication technology (ICT) readiness for business continuity
- ISO 22301:2019 Security and resilience — Business continuity management systems — Requirements
- NIST outlines the following steps in SP 800-34

Business Continuity Planning (BCP) helps organizations achieve
- Appropriate response to emergency situations
- Safety of employees and data
- a Reduced business impact
- swift resumption of critical business functions.
- a plan to work efficiently with your chosen DR vendor/partner
- Reduced confusion during a crisis
- an increase customer confidence (many parties now ask for details of BCPs)
- a return to normal operations within availability objectives after a disaster

#### NIST SP 800-34 outlined following steps:

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/bcm-2.png?raw=true" alt="Sublime's custom image"/>
</p>

Business continuity planning (BCP) entails assessing organisational risks and developing policies, plans, and procedures to mitigate their impact if they occur.
> The BCP focused on how to keep the organisation in business after a major disruption event takes place. It is about the survivability of the organisation and making sure that critical functions can still operate even after a disaster (e.g. the ability to make payments) . The goal of BCP planners is to implement a combination of policies, procedures, and processes such that a potentially disruptive event has as little impact on the business as possible.

The BCP process has four major steps.

1)     Project scope and planning

2)     Business impact analysis

3)     Continuity planning

4)     Approval and implementation

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/bcm-3.png?raw=true" alt="Sublime's custom image"/>
</p>

### 3.2 -  What is Business Continuity Policy?

So you are building a house...a plan is essential right?

#### 3.2.1 - Business Continuity Lifecycle

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/bcp-lifecycle.png?raw=true" alt="Sublime's custom image"/>
</p>

But before we can engage an architect we need to define our requirements and set some guidelines. 
- What is our budget?
- Where are we building and what section size?
- When do we need it completed? what are the local regulations?
- Who are the stakeholders?
- What regulations or standards we need to be aware of?
- What are the roles and responsibilities of the various stakeholders?
- Who is the project manager/owner? Who is the key sponsor?

> This is what a Business Continuity policy is all about.   It is about defining these sorts of things at a high level.

> As per the BCI Good Practice guidelines a Business Continuity Policy has a primary purpose of communication, it should be short, clear and concise and should include:

- The organisation’s definition of Business Continuity
- A definition of the scope of the Business Continuity Management (BCM) programme
- Business Continuity roles and responsibilities
- An organisational framework for the management of the organisations BCM programme
- A set of principles, guidelines and minimum standards
- A clearly defined budget, audit and governance responsibilities

Once an organisation has a policy in place a key output is a Business Continuity owner (the Programme Manager if you like). He/she may also be a part of a Steering Group and will ultimately report to the Business Continuity Sponsor (the person whose neck is on the line if things go bad).

Once this is in place it becomes a lot easier to implement the following stages of the Business Continuity Lifecycle including: Business Impact Analysis/Risk Assessment, Design Strategies, Implementation/Planning and Validation of the overall programme to ensure that the objectives are being met.

### 3.2 -  What is Business Continuity Strategy?

>  “An approach selected by an organization to ensure its recovery and continuity in the face of a disaster or other business disruption.”

### 3.2 -  Types of BC Strategies?

  
