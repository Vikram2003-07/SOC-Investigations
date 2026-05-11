# Inbound Email Containing Suspicious External Link - Investigation

## Alert Information
- **Alert ID:** 8818
- **Alert Name:** Inbound Email Containing Suspicious External Link
- **Severity:** Medium
- **Category:** Phishing
- **Status:** Awaiting Action
- **Date:** May 9, 2026

## Objective
Investigate the suspicious inbound email containing an external onboarding link and determine whether the email is malicious or a false positive.

## Investigation Summary
The investigation focused on:
- Reviewing the sender domain reputation
- Analyzing the embedded onboarding URL
- Searching Splunk logs for URL access attempts
- Verifying indicators using TryDetectThis

## Key Findings
- The sender domain `hrconnex.thm` was analyzed and found to be clean.
- The embedded URL did not contain known malicious indicators.
- No suspicious activity or malicious network connections were identified.
- Splunk searches did not reveal any malicious endpoint communication related to the URL.

## Final Verdict
**False Positive**

The sender domain and embedded link appear legitimate with no malicious indicators detected during analysis.

## Files Included
- `investigation.md` → Detailed investigation steps and findings
- `analyst-note.md` → Short SOC analyst case note