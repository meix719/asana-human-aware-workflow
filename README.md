# Human-Aware Workflow: NYU SPS × Asana Challenge

## Overview
Our team, DOF (Department of Future), developed a workflow prototype for the NYU SPS × Asana Challenge. It uses AI-powered rules to flag workload and availability risks and recommend scheduling actions for managers.

## Business Problem
A deadline may look reasonable while conflicting with an employee's holidays, planned leave, or existing assignments. Managers need clearer visibility into these constraints when assigning work.

## Example Scenario
A U.S.-based manager assigns a two-week project to a colleague in China shortly before Chinese New Year. The workflow checks availability and workload indicators, flags potential conflicts, and recommends reviewing the assignment or schedule.

## Workflow Approach
The prototype combines:
- Task deadlines and estimated effort
- Employee region and availability information
- A company directory
- A workload tracking list
- Availability and workload risk labels
- Recommended actions generated through AI-powered rules

Recommendations include proceeding as planned, adjusting the schedule, or considering reassignment to an available teammate.

## Decision Logic
The demonstration uses vacation-day ratios and workload scores to classify potential risks. These signals feed a combined risk label and recommended action.

The scores are operational indicators. They do not directly measure emotions, stress, or burnout. The thresholds are prototype design choices that require further testing.

## Tools and Skills
- Asana
- AI-powered workflow rules
- Workflow and decision-logic design
- Resource planning and scheduling
- Human-centered product thinking
- Prototype demonstration and business communication

## Intended Value
The workflow aims to help managers identify scheduling conflicts earlier, discuss workload constraints, and make more informed assignment decisions.

Reduced burnout and improved productivity are intended benefits, not measured outcomes established by this project.

## Project Materials
[View our team presentation](reports/asana-workflow-presentation.pdf)

This repository documents the workflow prototype as a portfolio case study.

## Limitations and Next Steps
- Recommendations depend on accurate availability and workload information.
- Risk thresholds need testing across different teams and project types.
- Managers and employees should review recommendations before changing assignments.
- Availability data should be handled with appropriate privacy and access controls.
- Future evaluation could track scheduling conflicts, recommendation usefulness, and feedback from users.

## Team
- Yu-Erh Li (Ariana)
- Jinyi Yuan
- Qunfeng Zhou
- Mei Qiong Xue
- Ishan Vaghani
