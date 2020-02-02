# Managing major cyber incidents 

[Basics of incident management](#basics-of-incident-management)  
[Top priorities when arriving at an incident](#top-priorities-when-arriving-at-an-incident)  
[Gaining situational awareness](#gaining-situational-awareness)  
[Focusing on key investigative questions](#focusing-on-key-investigative-questions)  
[Building a watch out criteria](#building-a-watch-out-criteria)  
[Delivering the technical response to an incident](#delivering-the-technical-response-to-an-incident)  
[Key issues managing and coordinating response efforts](#key-issues-managing-and-coordinating-response-efforts)  
[Key response documents](#key-response-documents)  
[Key areas of the environment](#key-areas-of-the-environment)  
[Key logs to consider](#key-logs-to-consider)  
[Immediate priority checklist](#immediate-priority-checklist)  
[Considering response strategy](#considering-response-strategy)  
[Action plan](#action-plan)  
[Remediation goals](#remediation-goals)  
[Communicating on data breaches](#Communicating-on-data-breaches)  
[Focusing-on-the-attacker](#Focusing-on-the-attacker)  
[Data-breach-impacts](#Data-breach-impacts)  
[Detection-capabilities](#Detection-capabilities)  

## Basics of incident management

1. What has happened?

2. What is the plan? 

3. Who is in charge? 

Organisations time and time again struggle to clearly answer these questions during major cyber incidents. 

## Top priorities when arriving at an incident 

1. Understand organisational priorities

2. Ensure immediate priorities are being actioned

3. Gain situational awareness

4. Assess risks and issues

5. Integrate with the business-wide strategic response

6. Define ways of working and build response tempo (including secure tools for communication and collaboration) 

7. Establish measurable incident objectives

8. Select appropriate strategies to achieve objectives

9. Perform tactical direction 

10. Provide necessary follow-up

## Gaining situational awareness

1. What has happened? 

2. How have you responded? 

3. What is unknown at this point?  

4. Have you considered the legal and regulatory implications?  

5. Have senior leadership been briefed? 

6. Who has been notified?  

7. What are you concerned about? (risks / issues)

8. What are your priorities? 

9. What is your plan? 

10. Who is in charge? (of the response and individual workstreams)

11. Have you thought about how the incident could esclate?  

11. What is your plan if the incident escalates? (and how will you identify this?)

13. Do you have a reactive press statement prepared?  

12. Are you in a crisis? 

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

## Building a watch out criteria 

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

## Delivering the technical response to an incident 

| Investigation         | Remediation           | Monitoring            | Operations          | Logistics / PMO   |
|-----------------------|-----------------------|-----------------------|---------------------|-------------------|
| Situational Awareness | Analysis and Planning | Threat Detection      | Evidence Collection | Action Tracking   |
| Forensic Analysis     | Triage                | Continuous Monitoring | Tech Deployment     | Resourcing        |
| Threat Intelligence   | Delivery              | Threat Hunting        | Recovery            | Finance and Admin |
| Impact Assessment     |                       |                       |                     |                   |

| Investigation / Intelligence       | Monitoring       | Preemptive Containment  | Security Improvement |
|------------------------------------|------------------|-------------------------|----------------------|
| Situational Awareness and Planning | Threat Detection | Plan                    | Plan                 |
| Forensic Analysis                  | Monitoring       | Triage                  | Triage               |
| Threat Intelligence                | Threat Hunting   | Deliver                 | Deliver              |
| Impact Analysis                    |                  | Test                    | Test                 |

| Investigation / Intelligence | Operations                   | Planning               | Logistics / PMO   |
|------------------------------|------------------------------|------------------------|-------------------|
| Investigation                | Evidence Collection          | Investigation Planning | Action Tracking   |
| Threat Intelligence          | Tech Deployment (Visibility) | Situational Awareness  | Resourcing        |
| Impact Assessment            | Monitoring and Hunting       | Remediation Planning   | Finance and Admin |
|                              | Remediation and Recovery     |                        |                   |

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

## Key response documents

1. Incident action plan

2. Ways of working

3. Red line / watch out criteria 

4. Immediate priorities checklist 

5. Incident timeline

6. Remediation plan

7. Risks, actions, issues, decisions tracker

8. Investigation tracker 

9. Stakeholder mapping 

10. Evidence tracker 

## Key areas of the environment 

| Key areas     |                         |          |
|---------------|-------------------------|----------|
| Workstations  | Cloud                   | Identity |
| Email and Web | Networks / Data centers | Data     |
| Servers       | Applications            |          |

For each: 

* What do you have? 

* What capabilities do you have to prevent attacker activity? 

* What capabilities do you have to detect attacker activity? 

* What people and processes do you have to support this? 

## Key logs to consider 

* Server and workstation operating system logs

* Authentication logs (e.g. login, remote access, VPN)

* Application logs (e.g. web logs, database logs)

* Network logs (e.g. web proxy logs, firewall logs, DNS, NetFlow)

* Security Tool logs (e.g. EDR, AV, mail filtering logs)

## Immediate priority checklist 

1. Senior management are being briefed on the incident, risks and issues

2. Action is being taken to mitigate any unacceptable risks to the business 

3. Evidence is being collected and preserved

4. Legal & regulatory obligations are being assessed

4. Gaps in technical visibility have been identified and are being resolved 

5. Incident response and crisis management plans have been initiated

## Considering response strategy

Response strategy needs to be proportionate to respond to sophistication of the threat actor and the scale/complexity of the incident.

* Priorities and objectives

* Risks and issues 

* Understanding of the environment

* Visibility of the environment 

* Organisational and technical capability / capacity to respond 

* Investigative findings so far, including knowledge of the adversary

## Action plan

1. What do we want to do? Priorities, objectives and strategy

2. Who is responsible for doing it? Roles and responsibilities 

3. How do we communicate with each other? Daily rhythm and tempo

4. What is the procedure if the incident escalates? 

5. What are the expectations of team members working on the response? 

6. How will decisions be made? 

## Remediation goals

Increasing the cost to the attacker of achieving their objectives, including:

1. Remove attacker's access to the environment

2. Limit the attacker's ability to regain access to the environment

3. Limit the ability of the attacker to operate within the environment and achieve their objectives

Failure to fully identify and understand all attacker access to the environment will likely significantly impact the effectiveness of any response and remediation efforts.

## Communicating on data breaches 

Key messages to deliver: 

* Care and concern (about those affected)

* Control (of the situation)

* Commitment (to resolving the problem)

Key considerations: 

* Mapping stakeholders 

* Coordinating /sequencing communcations 

* Anticipating stakeholder issues and preparing to respond 

Key questions to answer: 

1. What happened?

2. What will the impact be on customers? 

3. How do you feel about it?

4. What are you doing about it?

5. When are you going to provide your next update? 

6. What steps customers can take to protect themselves? (what are you doing to help customers?) 

Good Examples: [Monzo](https://monzo.com/blog/2017/03/05/outage) 

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

## Detection capabilities 

1. What are your roll-out plans and deployment statistics for endpoint agents? 

2. What are your roll-out plans and deployment statistics for network appliances? 

3. What is your availability of logging covering other sources of visibility? 

4. What visibility gaps do you have of the environment? 

5. What monitoring and detection tools are built on top of these sources of visibility?

6. How are these tools  configured to detect attacker activity? 
