# Secret Management Policy

## 🛡️ Principles
1. **Isolation**: Keep deployment secrets away from code repositories.
2. **Persistence**: Use `.env` files for local development but ensure they are in `.gitignore`.
3. **Rotation**: Recommend rotating tokens every 30-90 days.
4. **Scope Audits**: Periodically review active tokens and their scopes.

## 🔑 Active Credentials Log (Redacted)
- **Cloudflare API Token**: [REDACTED]
  - Purpose: `daimirai` deployment via Wrangler
  - Last Verified: 2026-03-03
- **GitHub PAT**: [REDACTED]
  - Purpose: `daimirai` org management & git operations
  - Last Verified: 2026-03-03
