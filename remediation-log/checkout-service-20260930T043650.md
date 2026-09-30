# Remediation: checkout-service

**Action:** rollback_deployment

Rolling back checkout-service deployment to revert unbounded cache commit (self.max_size = None) which caused memory exhaustion, GC pauses, and OOMKilled errors.
