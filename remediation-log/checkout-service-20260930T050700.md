# Remediation: checkout-service

**Action:** config_adjustment

The checkout-service experienced an OOMKilled (exit code 137) incident due to an unbounded cache setting (self.max_size = None) introduced in a recent commit, causing memory usage to climb to 100%. We will adjust the configuration/code to restore a bounded cache size.
