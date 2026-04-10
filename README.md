# SOC Tier 1 Simulation Exercise

## Exercise Overview
This repository contains a comprehensive SOC Tier 1 simulation exercise for students to practice alert triage and basic investigation skills. The exercise simulates a real-world scenario where students must investigate a potential SQL injection attack against a web server.

## Exercise Description
You are a Tier 1 SOC analyst monitoring network security alerts. A critical alert has been generated indicating potential compromise of a web server. Your task is to perform initial triage and basic investigation to determine if this is a genuine threat or a false positive.

## Files Included
- `README.md` - This file (exercise instructions)
- `web_server_logs.txt` - Apache web server logs
- `firewall_logs.txt` - Firewall connection logs
- `ids_logs.txt` - IDS/IPS detection logs
- `database_logs.txt` - Database query logs
- `user_access_logs.txt` - User access attempt logs
- `triage_report_template.md` - Template for documenting findings

## Exercise Structure

### Phase 1: Initial Assessment (30 minutes)
- Review alert details
- Check system availability
- Identify attack pattern

### Phase 2: Basic Investigation (60 minutes)
- Analyze web server logs
- Cross-reference with firewall logs
- Examine database activity
- Check user access logs

### Phase 3: Documentation and Reporting (30 minutes)
- Create triage report
- Determine if escalation is needed
- Document investigation process

## Learning Objectives
By completing this exercise, students will:
- Understand alert triage process
- Perform basic log analysis
- Identify false positives vs real threats
- Document findings properly
- Communicate with team members
- Apply critical thinking to security incidents

## Getting Started
1. Review the alert details in the README
2. Examine each log file individually
3. Cross-reference information across logs
4. Document your findings using the `triage_report_template.md`
5. Determine if escalation to Tier 2 is necessary

## Expected Outcomes
Students should discover this is a SQL Injection attack attempt, likely from an automated scanner, and determine that while the attack pattern is suspicious, the web server was not compromised.

## Scoring Rubric

| Category          | Score | Description                              |
|-------------------|-------|------------------------------------------|
| Initial Assessment| 20    | Correct identification of attack type and source |
| Log Analysis      | 30    | Proper correlation of logs from different sources |
| Threat Evaluation | 25    | Accurate assessment of threat level and impact |
| Documentation     | 20    | Clear, structured triage report          |
| Communication     | 5     | Proper escalation decision               |

## Post-Exercise Discussion Questions
- How would you differentiate between a legitimate scan and an actual attack?
- What additional logs would you want to examine?
- How would you handle a situation where you're unsure about the threat level?
- What tools would you use to automate this type of triage process?
- How would you communicate your findings to management?

## Repository Structure
