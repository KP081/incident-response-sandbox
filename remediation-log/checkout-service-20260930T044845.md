# Remediation: checkout-service

**Action:** config_adjustment

The checkout-service experienced OOMKilled errors (exit code 137) and pod restarts due to an unbounded cache setting (self.max_size = None) introduced in the recent commit, causing memory usage to climb to 100%. We are adjusting the configuration/code to restore the cache size limit.
