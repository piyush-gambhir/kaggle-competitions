# Security scanning

Ruff 0.17.3 checks notebook Python security rules without executing cells. GitHub secret
scanning remains enabled for recognized provider credentials. The initial security-rule scan
on 2026-10-29 required no suppressions. Passing this check does not audit datasets or models.
