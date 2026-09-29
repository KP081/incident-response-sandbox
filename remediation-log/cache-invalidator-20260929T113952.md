# Remediation: cache-invalidator

**Action:** config_adjustment

Fix cache TTL misconfiguration by restoring ttl_seconds to 300 to resolve the invalidation storm and prevent price mismatches between cache and DB as seen in log: 'assertion failed: price mismatch between cache and DB, aborting transaction batch'.
