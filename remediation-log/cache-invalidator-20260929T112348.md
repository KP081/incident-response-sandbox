# Remediation: cache-invalidator

**Action:** config_adjustment

Revert cache TTL configuration from 0 seconds back to 300 seconds to prevent invalidation storms and price mismatch assertion failures, as confirmed by logs and git diff.
