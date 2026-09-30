# Risk and remediation example: recovery readiness

**Author:** Dr. Atdhe Buja  
**Context:** CIO, ICT Academy, January 2022–July 2024  
**Artifact type:** Illustrative portfolio example

This example combines my retrospective account of backup and risk-management responsibilities with a proposed remediation workflow. It is not an extract from the internal risk register, a record of an actual incident, or evidence of a completed recovery test.

## Basis in my CIO experience

I maintained a risk register, reviewed risks with the team, and used Asana for project and remediation follow-up. I designed a backup approach combining cloud-hosted services with local external storage intended to remain offline between backup operations. I reported risks and operational matters to the owner and general manager monthly.

## Illustrative risk record

The scenario, priority, ownership assignments, and relative deadlines below are proposed examples, not historical register values.

| Field | Illustrative entry |
| --- | --- |
| Reference | EXAMPLE-R01 — portfolio identifier only |
| Risk statement | If cloud access or primary data becomes unavailable, and the secondary copy cannot be restored, service interruption and loss of usable information may continue beyond business needs. |
| Potential causes | Account compromise, destructive changes, incomplete backup coverage, damaged media, or an untested recovery procedure. |
| Business impact | Delayed training, research, consulting, or internal operations; possible loss of work. |
| Proposed priority | High pending assessment of likelihood, impact, existing controls, and recovery needs; not a historical risk rating. |
| Proposed risk owner | CIO, accountable for coordinating treatment and reporting remaining risk. |
| Proposed action owner | Cloud/cybersecurity engineer, supported by the network administrator where needed. |
| Proposed treatment | Confirm scope, protect backup access, document offline handling, and test a representative restoration. |
| Target | Within 30 days of approval of this illustrative plan; not a recorded historical deadline. |
| Tracking | An Asana task linked to the risk record, with owner, deadline, dependencies, and verification notes. |
| Status | Illustrative plan only; no historical closure claimed. |

## Proposed treatment and verification

| Action | Proposed owner | Target after approval | Verification needed |
| --- | --- | --- | --- |
| Agree critical data scope and recovery needs | CIO with service owners | Day 5 | Reviewed scope and agreed recovery priorities. |
| Review backup permissions and handling of offline copies | Cloud/cybersecurity engineer | Day 10 | Restricted access and documented connection/disconnection procedure. |
| Perform an authorized restoration of representative data in an isolated test environment | Cloud/cybersecurity engineer | Day 20 | Restore log, integrity/usability checks, elapsed time, and any gaps. |
| Review test results and remaining exposure | CIO with owner/general manager | Day 30 | Treatment decision, follow-up actions, and next review date. |

The targets above illustrate sequencing. Actual deadlines would depend on scope, resources, and risk assessment.

## Closure criteria and remaining risk

A backup job completing successfully would not, by itself, demonstrate recovery. Closing the proposed remediation action would require a usable restoration, comparison with agreed recovery needs, documented gaps, and review by the responsible owner. The underlying risk could remain open for monitoring even after the action is completed.

No recovery time, recovery point, risk reduction, financial saving, or actual test result is asserted here. Internal records, system identifiers, credentials, client details, and storage locations are omitted.

## CIO judgment demonstrated

The example connects a technical control to business continuity, assigns responsibility, defines verification before closure, and makes remaining risk visible to leadership.
