# Remediation: cache-invalidator

**Action:** config_adjustment

Adjust cache TTL configuration from 0 seconds back to 300 seconds to resolve the invalidation storm and price mismatch errors, as cited in log line: 'cache TTL misconfigured: ttl_seconds=0, invalidation storm expected'.
