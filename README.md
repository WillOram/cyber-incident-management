# Managing major cyber incidents 

[Basics of incident management](#basics-of-incident-management)  
[Top priorities when arriving at an incident](#top-priorities-when-arriving-at-an-incident)  
[Gaining situational awareness](#gaining-situational-awareness)  
[Building a watch out criteria](#building-a-watch-out-criteria)  
[Focusing on key investigative questions](#focusing-on-key-investigative-questions)  
[Delivering the technical response to an incident](#delivering-the-technical-response-to-an-incident)  
[Key issues managing and coordinating response efforts](#key-issues-managing-and-coordinating-response-efforts)  
[Key response documents](#key-response-documents)  
[Key areas of the environment](#key-areas-of-the-environment)  
[Key logs to consider](#key-logs-to-consider)  
[Immediate priority checklist](#immediate-priority-checklist)  
[Considering response strategy](#considering-response-strategy)  
[Action plan](#action-plan)  
[Remediation goals](#remediation-goals)  

## Basics of incident management

1. What has happened?

2. What is the plan? 

3. Who is in charge? 

Organisations time and time again struggle to clearly answer these questions during major cyber incidnets. 

## Top priorities when arriving at an incident 

1. Understand organisational priorities

2. Ensure immediate priorities are being actioned

3. Gain situational awareness

4. Assess risks and issues

5. Integrate with the business-wide strategic response

6. Define ways of working and build response tempo

7. Establish measurable incident objectives

8. Select appropriate strategies to achieve objectives

9. Perform tactical direction 

10. Provide necessary follow-up

## Gaining situational awareness

1. What has happened? 

2. How have you responded? 

3. Have you considered the legal and regulatory implications? 

4. Have senior leadership been briefed? 

5. Who have you notified? 

6. What are you concerned about? (risks / issues)

7. What are your priorities? 

8. What is your plan? 

9. Who is in charge? 

10. What is your plan if the incident escalates? (and how will you identify this?)

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

1.  Who should this be communicated to?

2.  How should this be communicated to them?

3.  How should this first be verified? 

4.  Should this communication be written or verbal in the first instance?

## Focusing on key investigative questions 

1. When was the window of compromise?

2. How did the attacker initially gain access to the environment?

3. What systems did the attacker access and/or compromise?

4. How did the attacker access and/or compromise these systems?

5. What accounts did the attacker compromise?

6. What activity was carried out by the attacker within the environment?

7. What data did the attacker access and how did the attacker do this?

8. What evidence is there of data ex-filtration?

9. Does the attacker still have access to the environment?

10. Has the attack concluded?

## Delivering the technical response to an incident 

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

* Workstations
* Email and Web 
* Servers
* Cloud
* Networks / Data centers
* Applications
* Identity
* Data

## Key logs to consider 

* Server and workstation operating system logs
* Authentication logs (e.g. login, remote access, VPN)
* Application logs (e.g. web logs, database logs)
* Network logs (e.g. web proxy logs, firewall logs, NetFlow)
* Security Tool logs (e.g. EDR, anti-virus, mail filtering logs)

## Immediate priority checklist 

1. Senior management are being briefed on the incident, risks and issues

2. Action is being taken to mitigate any unacceptable risks to the business 

3. Evidence is being collected and preserved

4. Legal & regulatory obligations are being assessed

4. Gaps in technical visibility have been identified and are being resolved 

5. Incident response and crisis management plans have been initiated

## Considering response strategy

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
3. Limit the ability of the attacker to operate within the environment and achieve their objectivities
