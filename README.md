# Business Continuity and Disaster Recovery (BCDR): Theory, Techniques, Testing and Tools


An ongoing & curated collection of awesome software best practices and techniques, libraries and frameworks, E-books and videos, websites, blog posts, links to github Repositories, technical guidelines and important resources about Business Continuity and Disaster Recovery in Cybersecurity.
> Thanks to all contributors, you're awesome and wouldn't be possible without you! Our goal is to build a categorized community-driven collection of very well-known resources.


## `Table of Contents`

## What is Business Continuity and Disaster Recovery?

## 1 - Business Continuity Planning

## 2 - Disaster Recovery
Disaster recovery (DR) is an organization’s ability to restore access and functionality to IT infrastructure after a disaster event, whether natural or caused by human action (or error). DR is considered a subset of business continuity, explicitly focusing on ensuring that the IT systems that support critical business functions are operational as soon as possible after a disruptive event occurs.

[IT disaster recovery](https://cloud.google.com/learn/what-is-disaster-recovery?hl=en#what-is-considered-a-disaster) is a portfolio of policies, tools, and processes used to recover or continue operations of critical IT infrastructure, software, and systems after a natural or human-made disaster.


### 2.1 Disaster Recovery Management

  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/dcm-0.png?raw=true" alt="Sublime's custom image"/>
</p>



### 2.2 Disaster Recovery Plan

### 2.3 IT Disaster Recovery Process

### 2.4 Disaster Recovery Tools


### 2.5 Disaster Recovery Terms


### 2.6 Disaster Recovery Lifecycle

- Before starting to develop the BC strategy, it is important to understand the overview of a typical disaster lifecycle.

  <p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/dr-lifecycle.png?raw=true" alt="Sublime's custom image"/>
</p>

There are some basic questions that you will need to ask for each phase of the lifecycle.

#### Reduce (or Prevent)
Have all threats been identified and their effects minimized?
Have the appropriate countermeasures been implemented?
Have all pre-disaster preventive measures been taken?

####  Respond
What should the team do while waiting either for the situation to be assessed or for the decision to activate the plan?
What is the immediate emergency response that has been considered?

#### Recover
What steps or alternative processing procedures may be taken to work around the problem until it is fixed?
What are the immediate actions to be taken for time-sensitive business functions?

#### Resume
How are the critical business functions going to be operated at another location?
How are contracted equipment and third party resources to be acquired?

#### Restore
What must the team do if operations must stop because continuing the operations may corrupt or destroy future work or processes?
What are the methods to be used to process or catch up on work that has been deferred?

#### Return
How to stop the recovery operations and resume normal business?



### 2.10 RTO and RPO requirements





## 3 - Business Continuity Management
Often, as part of the discussion on business continuity management (BCM), there is a difference in the way the terms are defined.  To ensure consistency in our training of BCM - which includes Crisis Management (CM), Crisis Communication (CC), IT Disaster Recovery Planning (DRP) and Operational Resilience (OR) professionals, the "BCM Umbrella" is one of the several diagrams used to integrate and better explain the holistic view.

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/businesscontinuity-1.png?raw=true" alt="Sublime's custom image"/>
</p>



Business Continuity Management or BCM is a holistic management process for identifying potential impacts from threats, and for developing response plans.  The key objective is to increase an organization's resilience to business disruptions and to minimize the impact of such disruptions.

#### So what do we mean by business continuity?

Business continuity is the holistic management process that ensures operations continue and that products and services are delivered at predefined levels (e.g. no shortages, no halt to an ongoing clinical trial). 
> This approach is aligned with ISO 22301 Business Continuity Management Systems.

Business continuity management is an ongoing process based on the plan-do-check-act methodology that is made up of 4 key elements:

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/businesscontinuity-0.png?raw=true" alt="Sublime's custom image"/>
</p>


- Emergency Action and Response Plans
- Disaster Recovery Plans
- Crisis Management Plans
- Business Continuity Plans

##### Emergency Action Plans
An emergency action plan is designed to respond to an emergency with mitigating procedures to protect, secure and evacuate people to safety. This is more an OSHA thing; chances are your average Quality unit doesn’t end up owning it. Unless you have no HS&E unit, and then you write one.

This plan includes procedures for detecting, warning, and responding to specific potential emergencies such as fire, severe weather, earthquake, medical emergencies, workplace violence, and other potential threats.

##### Disaster Recovery Plan
Disaster recovery plans are designed to recover from a disaster, usually related to equipment, infrastructure, and information technology. Something big goes boom, how do you restore this vital support system or equipment as soon as possible and minimize downtime and loss of data. Very important for computer system lifecycle, disaster recovery plans should include specific plans for recovery functions, resumption strategies, critical personnel, equipment, services, and external and internal communications.

##### Crisis Management Plans
Crisis management is all about planning and mitigating situations that have risk, and are usually a lot of management of communications internally and externally. This includes with regulators, health care providers, etc. When we implement SOPs for health authority notifications we are engaging in crisis management planning.

##### Business Continuity Plans
Business continuity planning identifies and plans for disasters to events that could negatively an organization’s business functions, objectives, income, reputation, and ultimate survival. This planning takes place in advance of the potential disasters or events that could harm an organization. It takes potential disasters and events into consideration with their effects on suppliers, vendors customers, and the organization’s other stakeholders.

In a GxP environment, we are looking at the potential impact of disasters on drug supply and clinical study outcomes (amongst other key activities).

The BCP is all about minimizing the effects of the disaster or event on the organization and returning to normal operations as soon as possible.

These Plans are Interrelated
All four plans are interrelated and should be coordinated. The plans can be combined, but as there are usually very different owners they are often separated.

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

### 3.1.1 - Examples of a ** Business Continuity Plan for Hospitals**

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/bcp-hospitals.png?raw=true" alt="Sublime's custom image"/>
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

The output of the business continuity (BC) strategy phase would generally include a strategy for:
- mitigation,
- (crisis) response,
- and recovery.

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/bc-strategies.png?raw=true" alt="Sublime's custom image"/>
</p>


## 4 - Documents Management

Today many companies are going digital, striving for paperless, reinventing how individuals find information, record data and make decisions. It is often good when undergoing these decisions to go back to basics and make sure we are all on the same page before we proceed.

There are three major types/functions of documents:

#### Functional Documents
- Functional Documents provide instructions so people can perform tasks and make decisions safely effectively, compliantly and consistently. This usually includes things like procedures, process instructions, protocols, methods and specifications. Many of these need some sort of training decision. Functional documents should involve a process to ensure they are up-to-date, especially in relation to current practices and relevant standards (periodic review)

#### Records
- Records provide evidence that actions were taken and decisions were made in keeping with procedures. This includes batch manufacturing records, logbooks and laboratory data sheets and notebooks. Records are a popular target for electronic alternatives.

#### Reports
- Reports provide specific information on a particular topic on a formal, standardized way. Reports may include data summaries, findings and actions to be taken.

Often times these types are all engaged in a lifecycle. An SOP directs us to write a protocol (two documents), we execute the protocol (a record) and then write a report. This fluidity allows us to combine the types.

Throughout these types we need to apply good change management and data integrity practices (ALCOA).

All of these types follow a very similar path for their lifecycle.

### 4.1 - Documents Management lifecycle

<p align="center">
  <img src="https://github.com/paulveillard/cybersecurity-bcdr/blob/main/img/document-lifecycle.png?raw=true" alt="Sublime's custom image"/>
</p>

Everything we do is risk based. Some questions to ask when developing and improving this system include:

What are the risks of writing procedures at a “low level of detail versus a high level of detail) how much variability do we allow individuals performing a task?) – Both have advantages, both have disadvantages and it is not a one-sized fits all approach.
- What are the risks in verifying (witnessing) non-critical tasks? How do we identify critical tasks?
- What are the risks in not having evidence that a procedure-defined task was completed?
- What are the risks in relation to archiving and documentation retrieval?

There is very little difference between paper records and documents and electronic records and documents as far as what is given above. Electronic records require the same concerns around generation, distribution and maintenance. Just now you are looking at a different set of safeguards and activities to make it happen.

  
