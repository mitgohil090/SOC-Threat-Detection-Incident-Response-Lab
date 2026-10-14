# Detection Exercises

This folder documents the security detection exercises performed in the local Wazuh lab.

## Exercise 1: Single Authentication Failure
**Status:** Verified

Generated a controlled authentication failure and reviewed the related Wazuh alerts.

## Exercise 2: Repeated Authentication Failures
**Status:** Verified

Generated repeated authentication failures and examined the resulting alerts. This exercise does not confirm that a dedicated brute-force detection rule triggered.

## Exercise 3: File Integrity Monitoring
**Status:** Verified

Created a test file under `/etc` and confirmed that Wazuh generated a file-added alert.

## Exercise 4: Privilege-Related Activity
**Status:** Verified

Performed a controlled sudo-to-root action and reviewed the related security event.


## Learning Outcome

These exercises provided practical experience with authentication monitoring, privilege-related events, file integrity monitoring, and basic detection-rule configuration.
