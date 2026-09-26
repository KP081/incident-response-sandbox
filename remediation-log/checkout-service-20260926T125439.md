# Remediation: checkout-service

**Action:** config_adjustment

Revert unbounded cache size configuration change that caused memory exhaustion and OOMKilled exit code 137 on checkout-service pods.
