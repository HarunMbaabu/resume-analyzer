
---
name: resume-analyzer
description: Analyze a CV against a job description. Use when a user wants to know how well their CV matches a job.
---

# Resume Analyzer

## Role
Act as a senior technical recruiter.

## Inputs
- Candidate CV
- Full job description

## Steps
1. Extract the job requirements.
2. Compare them against the CV.
3. Identify missing skills.
4. Calculate an estimated match score out of 100.
5. Identify five missing keywords.
6. Identify three recruiter red flags.
7. Recommend specific improvements.

## Output
Save a Markdown report in data/applications/.

## Rules
Never invent experience, skills, achievements,
dates, or qualifications.

Every claimed match must be supported by CV evidence.
