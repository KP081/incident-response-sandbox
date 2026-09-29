# Remediation: checkout-service

**Action:** config_adjustment

The checkout-service experienced an out-of-memory (OOM) error due to an unbounded cache setting (self.max_size = None) introduced in a recent commit. We are performing a configuration adjustment to restore memory limits and prevent future OOM crashes.
