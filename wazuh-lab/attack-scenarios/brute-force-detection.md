# Wazuh Brute-Force Detection Lab

## Objective
Document how repeated authentication failures are monitored and investigated in the Wazuh lab.

## Lab Environment
- SIEM: Wazuh
- Test systems: Windows and/or Linux, as applicable
- Log source: To be confirmed from the actual test
- Network monitoring: Suricata, if involved in this scenario

## Test Scenario
Describe the authorized brute-force simulation, the system tested, and the date of the test.

## Log Source and Detection Logic
Record the actual authentication log source, relevant event fields, and Wazuh rule ID or detection logic after verifying them in the lab.

## Expected Behavior
Explain what activity the detection is intended to identify, such as repeated authentication failures within a defined period.

## Observed Results
Pending lab validation.

Record whether the expected event was collected and whether a corresponding alert was generated. Include a sanitized sample event or screenshot.

## Investigation
Document the source IP, targeted account, timestamps, event sequence, and other relevant evidence available in the logs.

## MITRE ATT&CK Mapping
Select the applicable technique only after confirming that the simulated activity and evidence support the mapping.

## Limitations and Next Steps
Record untested conditions, detection gaps, and possible tuning improvements.

## Safety
All testing must be authorized and restricted to the lab environment. Do not publish credentials, secrets, or confidential data.
