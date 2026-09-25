# Remediation: checkout-service

**Action:** config_adjustment

Restore cache max_size limit in cache/lru.py to prevent unbounded memory growth and subsequent OOMKilled errors on checkout-service.
