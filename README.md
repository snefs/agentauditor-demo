The tool AuditAgent can complement agent guardrails or an agent harness by providing auditability and feedback around agent execution.
It is developed by Sander Nefs under the label FlowCruncher, join the waitinglist for early access by sending a mail to info@flowcruncher.com

Benefits:
- Detect guardrail violations: identify skipped approvals, unauthorized steps, unsafe transitions, retries, loops, or out-of-order actions.
- Verify policy compliance: compare actual traces against expected workflows and rules.
- Expose failures between tools: find where an agent used the wrong tool, exceeded limits, or continued after an error.
- Measure reliability: track latency, overlapping activities, duplicate actions, failed runs, and incomplete workflows.
- Support regression testing: compare new agent versions against historical audit results.
- Provide evidence: retain trace data and reports for security reviews, compliance, and incident investigation.
- Improve guardrails: use recurring violations to decide where new constraints, approvals, or stop conditions are needed.
- Remain independent: the harness enforces rules at runtime; this tool verifies what actually happened afterward.
The key distinction is:
- Guardrails/harness: prevention and runtime control.
- AgentAuditor: observation, analysis, verification, and continuous improvement.
It could eventually become a closed feedback loop: audit failed traces, identify a pattern, update the harness policy, then use the auditor to confirm that the violation no longer occurs.

