# Managing major cyber incidents 

Quick-reference notes I use when responding to major cyber incidents. Loosely organised into four sections. 

## Arriving on scene

[The basics of incident management](#The-basics-of-incident-management)  
[Top priorities when arriving at an incident](#top-priorities-when-arriving-at-an-incident)  
[Gaining situational awareness](#gaining-situational-awareness)  
[Immediate priority checklist](#immediate-priority-checklist)   
[Common platform for secure communication and collaboration](#Common-platform-for-secure-communication-and-collaboration)  

## Understanding capabilities 

[Understanding the environment](#understanding-the-environment)  
[Key logs to consider](#key-logs-to-consider)  
[Detection capabilities](#Detection-capabilities)  

## Building a response strategy 

[The basics of a response strategy](#the-basics-of-a-response-strategy)  
[Building workstreams](#building-workstreams)  
[Focusing on key investigative questions](#focusing-on-key-investigative-questions)  
[Remediation objectives](#remediation-objectives)  
[Focusing on the attacker](#Focusing-on-the-attacker)  
[Data breach impacts](#Data-breach-impacts)  
[Key issues managing and coordinating response efforts](#key-issues-managing-and-coordinating-response-efforts)  

## Delivering the response 

[Building an action plan](#building-an-action-plan)  
[Driving forward delivery](#driving-forward-delivery)  
[Providing status updates](#providing-status-updates)  
[Defining a watch out criteria](#defining-a-watch-out-criteria)  
[Managing an interrupted remediation](#Managing-an-interrupted-remediation)  
[Delivering the response to an incident](#delivering-the-technical-response-to-an-incident)  
[Key response documents](#key-response-documents)  
[Communicating on data breaches](#Communicating-on-data-breaches)  

# Arriving on scene

## The basics of incident management

1. What has happened?

2. What is the plan? 

3. Who is in charge? 

Organisations time and time again struggle to clearly answer these questions during major cyber incidents. 

## Top priorities when arriving at an incident 

1. Understand organisational priorities

2. Ensure [immediate priorities](#immediate-priority-checklist) are being actioned

3. [Gain situational awareness](#gaining-situational-awareness)  

4. Assess risks and issues

5. Stand up / integrate with the business-wide strategic response

6. Define ways of working and build response tempo 

7. Stand up common platforms for [secure communication and collaboration](#Common-platform-for-secure-communication-and-collaboration)

8. Establish measurable incident objectives

9. Select appropriate strategies to achieve objectives 

10. Define and mobilise workstreams to deliver on strategies / tasks (define and document workstream processes)

11. Identify and resolve resourcing gaps 

12. Perform tactical direction and provide necessary follow-up

(Document everything)

## Gaining situational awareness

1. What has happened? 

2. How have you responded? 

3. What is unknown at this point?  

4. Have you considered the legal and regulatory implications?  

5. Has senior leadership been briefed? 

6. Who has been notified?  

7. What are you concerned about? (risks / issues)

8. What are your priorities? 

9. What is your plan? 

10. Who is in charge? (of the response and individual workstreams)

11. Have you thought about how the incident could escalate?  

11. What is your plan if the incident escalates? (and how will you identify this?)

13. Do you have a reactive press statement prepared?  

12. Are you in a crisis? 

## Immediate priority checklist 

1. Senior management are being briefed on the incident, risks and issues

2. Action is being taken to mitigate any unacceptable risks to the business 

3. Evidence is being collected and preserved

4. Legal & regulatory obligations are being assessed

4. Gaps in technical visibility have been identified and are being resolved 

5. Incident response and crisis management plans have been initiated

## Common platform for secure communication and collaboration 

Examples Teams, JIRA, Slack, Google Drive

Need to have a way to: 

1. Share documents / collaborate on document writing 

2. Communicate both with all teams working on the incident (often from multiple companies)

3. Track issues and projects with workflows

4. Centrally store key information 

# Understanding capabilities 

## Understanding the environment 

* Workstations
* Email and Web 
* Servers
* Cloud
* Networks / Data centers
* Applications
* Identity 
* Data

For each: 

* What do you have? 
* What capabilities do you have to prevent attackers? Coverage, features, constraints, limitations 
* What capabilities do you have to detect attackers? Coverage, features, constraints, limitations  
* What people and processes do you have to support this? 

Other questions:

* How quickly can new tech be deployed? (e.g. endpoint detection and response agents) 
* Who are the key contacts/SMEs?

## Key logs to consider 

* Server and workstation operating system logs
* Authentication logs (e.g. login, remote access, VPN)
* Application logs (e.g. web logs, database logs)
* Network logs (e.g. web proxy logs, firewall logs, DNS, NetFlow)
* Security Tool logs (e.g. EDR, AV, mail filtering logs)

## Detection capabilities

1. What are your roll-out plans and deployment statistics for endpoint agents? 

2. What are your roll-out plans and deployment statistics for network appliances? 

3. What is your availability of logging covering other sources of visibility? 

4. What visibility gaps do you have of the environment? 

5. What monitoring and detection tools are built on top of these sources of visibility?

6. How are these tools configured to detect attacker activity? 

7. How are detection alerts tracked? 

8. What processes are there to triage, investigate and respond to detection alerts?

Do you need to stand-up a tool e.g. JIRA to track and manage new detection alerts?

Key that all detection alerts are tracked centrally and moved through a single process. 

# Building a response strategy 

## The basics of a response strategy

A response strategy needs to be proportionate to respond to sophistication of the threat actor and the scale/complexity of the incident.

Encompasses "how" we are going to respond. Activities should then be grouped / organised into workstreams. 

Considering:

* Priorities and objectives
* Risks and issues 
* Understanding of the environment
* Visibility of the environment 
* Organisational and technical capability / capacity to respond 
* Investigative findings so far, including knowledge of the adversary

## Building workstreams

Workstreams should map to objectives / strategies, not aligned to any pre-existing business units / organisational hierarchies. 

Each workstream should have a lead responsible and accountable for the workstream's activities. 

Where possible the team working on a workstream should work and sit together.

Processes used by each workstream should be mapped out and communicated. 

Need to ensure response efforts have the capacity and speed to scale to the size of the incident.

Example workstreams for the strategic organization-wide response

* Communications
* Legal
* IT Operations
* Technical Incident Management
* Business Operations
* Strategic Improvements
* Finance / Administration

## Focusing on key investigative questions 

1. When was the window of compromise?

2. How did the attacker initially gain access to the environment?

3. What systems did the attacker access and/or compromise?

4. How did the attacker access and/or compromise these systems?

5. What accounts did the attacker compromise?

6. What activity was carried out by the attacker within the environment?

7. What data did the attacker access and how did the attacker do this?

8. What evidence is there of data exfiltration?

9. Does the attacker still have access to the environment?

10. Has the attack concluded?

## Remediation objectives

Remediation has four key objectives: 

1. Remove attacker access to the environment.

2. Prevent the attacker from re-gaining access to the environment.

3. Detect the attacker if they re-gain access to the environment. 

4. Limit the attacker’s ability to achieve any objectives if access to the environment is reacquired.

These four objectives are achieved by carrying out posturing, eradication and hardening. 

Against a motivated and targeted attacker, failure to identify all attacker access, improve detection capabilities and carry out improvements to prevent the attacker from immediately re-gaining access to the environment, will likely result in the eradication not being successful (with the attacker maintaining access and embedding deeper in the network). 

See my other GitHub repo [here](https://github.com/WillOram/cyber-remediation) for more information.

## Focusing on the attacker

1. What activity was carried out by the attacker within the environment?

2. What access does the attacker have into the environment? 

3. Has the attacker gained access to any data that will make it easier for them to re-compromise the environment? 

4. What are the likely motivations of the attacker? 

5. What are the assessed capabilities of the attacker? 

6. Has the attacker adapted their behaviour as a result of remediation activities undertaken?

## Data breach impacts 

* Reputational 
* Legal
* Technical
* Operational
* Financial 

## Key issues managing and coordinating response efforts

1. No clear or suitable incident management structures 

    Structures are formed ad-hoc, teams fail to interoperate, existing businesses structures are used 

2. Lack of "operational rhythm" and programme management 

    Response is not as quick as leadership desires, delays in recognising a crisis, lack of accountability and action tracking

3. No clear strategy and objectives driving response efforts

    Response is tactical not strategic, conflicting priorities/strategies, reactive decision making

4. Poor communication and collaboration

    Disjoined uses of tooling, conflicting terminology, poor interoperability and missed/delayed escalations 

5. Lack of leadership and accountability

    Unclear chains of command, blurred lines of responsibility, fragmented teams, lack of trust reduces collaboration

6. No clear understanding of the facts which matter 

    Risks and issues are missed, leadership inundated with noise, remediation efforts repeatedly fail
    
# Delivering the response  

## Building an action plan

1. What do we want to do? Priorities and objectives

2. How are we going to do it? Strategy, workstreams  

2. Who is responsible for doing it? Roles and responsibilities 

3. How do we communicate with each other? Daily rhythm and tempo

4. What is the procedure if the incident escalates? 

5. What are the expectations of team members working on the response? 

6. How will decisions be made? 

## Driving forward delivery 

* Break the organisation out of a business as usual mindset - removing pre-existing structures, expectations and assumptions
* Build and follow a planning process 
* Group tactical and tasks into workstreams with leads
* Communicate strategy and plans, roles and responsibilities to all involved 
* Track and hold teams to account to deliver on actions 
* Get teams to report on the delivery and effectiveness of plans in measurable ways
* Run effective meetings with defined outcomes
* Ensure situational awareness and document 
* Track risks and issues 

## Providing status updates

1. When was the first identified evidence of compromise? + delta

2. When was the last identified evidence of compromise? + delta

3. How many systems have been assessed as compromised? + delta

4. How many systems have been assessed as accessed? + delta

5. How many accounts have been assessed as compromised? + delta

6. How many privileged accounts have been assessed as compromised? + delta

7. Endpoing agent coverage + delta

8. What has been done over the status update period? 

9. What is planned for the next status update period? 

10. Risks and issues being tracked + delta

11. Update against key investigation questions 

12. Update against "Eradication event criteria"

## Defining a watch out criteria 

1. Attacker finds a previously unidentified route into the environment

2. Attacker moves towards sensitive or personal data

3. Attacker compresses or stages files

4. Attacker accesses internet facing servers

5. Attacker gains domain administrator privileges 

6. Attacker gains access to a domain controller

7. Attacker adds or edits users in Active Directory

8. Attacker carries out activity indicating potential destructive intentions

If triggered: 

1. Who should this be communicated to?

2. How should this be communicated to them?

3. How should this first be verified? 

4. Should this communication be written or verbal in the first instance?

5. What technical response playbooks have been written to ensure a rapidly and effectively response? 

6. What playbooks have been written for carrying out common response tasks such as blockings IPs, sinkholing DNS, resetting accounts and isolating systems? 

7. How is the organisation building an increased state of readiness? 

## Managing an interrupted remediation

If remediation activities are interrupted by an alert what are the key questions to ask. 

1. When did the first alert occur? 

2. What is the first evidence of compromise on this system? (e.g. before or after eradication, key to decide whether to rapidly remediate)

3. Should any of this activity have been blocked? 

4. Are we seeing any of the same indicators as used previously? (e.g. IP or domain names)

5. Are we seeing similar TTPs to previous activity? 

6. Are we confident this is the same attacker? 

7. Are we seeing attacker hands-on keyboard activity? 

8. What activity has the attacker performed? 

9. What level of access has the attacker gained? 

10. Is there any other related activity on other systems? 

Key decision making factors for response 

1. Are we confident all new activity has been identified? 

2. Will we alert on all instances of this activity going forward?

## Delivering the response to an incident 

Responding to a significant cyber security incident requires not only a technical response but a highly integrated strategic organization-wide response.

#### Crisis Management Team (CMT)

* Manages and coordinates the organization-wide response to the incident
* Sets the response objectives, priorities and strategies
* Has overall responsibility for all response activities
* Secures support from the wider organization including from senior management
* Leads with an example of the culture required to successfully navigate through the crisis

Needs to be tightly integrated with the technical response.

#### Strategy Advisory Group (SAG)

* Propose priorities and strategies to resolve the incident 
* Consist of cyber security leadership, external advisors and legal
* Consider technical risks and issues 

#### Incident Management Team (IMT)

* Delivers the technical response to the incident
* Uses the inter-operable / modular [FEMA Incident Command System (ICS)](https://training.fema.gov/emiweb/is/icsresource/index.htm)
* The incident command is in charge of the technical response to the incident

Needs to be tightly integrated with the strategic organization-wide response.


| Investigation         | Threat Hunting    | Remediation           | Monitoring            | Operations          | Logistics / PMO   |
|-----------------------|-------------------|-----------------------|-----------------------|---------------------|-------------------|
| Situational Awareness | Threat Detection  | Analysis and Planning | Alert Triage          | Evidence Collection | Action Tracking   |
| Forensic Analysis     | Hunting           | Triage                | Continuous Monitoring | Tech Deployment     | Resourcing        |
| Threat Intelligence   | Tuning            | Delivery              |                       | Agent Deployment    | Finance and Admin |
| Impact Assessment     |                   |                       |                       | Recovery            |                   |

Other ideas for workstreams:
- Agent Deployment
- Threat Intelligence 
- Pre-emptive containment (limit the impact of ransomware attacks before they detonate)
- Recovery
- Strategic Improvement

## Key response documents

1. Incident action plan

2. Ways of working

3. Red line / watch out criteria 

4. Immediate priorities checklist 

5. Incident timeline

6. Remediation plan

7. Risks, actions, issues, decisions tracker

8. Investigation tracker 
- What systems are compromised / suspected compromised?
- What systems has the attacker accessed? 
- What systems has the attacker performed recon against? 
- What accounts are compromised / suspected compromised?
- What systems have agents deployed? 

9. Stakeholder mapping 

10. Evidence tracker 

11. Media handling FAQ 

12. Comms tracker

## Communicating on data breaches 

Key messages to deliver: 

* Care and concern (about those affected)

* Control (of the situation)

* Commitment (to resolving the problem)

Key considerations: 

* Mapping stakeholders 

* Coordinating / sequencing communications based on priority 

* Anticipating stakeholder issues and preparing to respond 

* Incremental reassurance

* Media trackers 

* External comms trackers (e.g. vendors)

Key questions to answer: 

- What happened?

- How this happened?

- What will the impact be on customers? 

- How do you feel about it?

- What you are going to do to fix it?

- How you are committed to making this right? 

- How you are going to be transparent and maintain customer trust?

- How you are staying true to your values?

- What steps customers can take to protect themselves? (what are you doing to help customers?) 

- When are you going to provide your next update? 

- FAQs (see my other GitHub repo [here](https://github.com/WillOram/cyber-data-breach-q-and-a) for examples)

