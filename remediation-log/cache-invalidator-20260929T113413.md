# Remediation: cache-invalidator

**Action:** config_adjustment

Revert cache TTL configuration from ttl_seconds=0 back to ttl_seconds=300 to stop the invalidation storm of 38,000 evictions/sec and resolve the transaction batch price mismatch assertion failures.
