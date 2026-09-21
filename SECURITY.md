# Security

This is a public product/project repository.

## Never commit

- API keys
- Access tokens
- Passwords
- Database credentials
- Private encryption keys
- Cloud credentials
- Payment provider secret keys
- Private user information
- Private meeting recordings or transcripts
- Production environment files

Use environment variables for secrets.

A safe example can be documented in `.env.example` using placeholder values only.

If a credential is accidentally exposed, revoke or rotate it immediately rather than simply deleting it from a later commit.
