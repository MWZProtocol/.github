## Summary

Describe what changed and why.

## Scope

- [ ] No unrelated refactor
- [ ] Public/private repository boundary preserved
- [ ] No secrets or private operational data added

## Architecture

- [ ] Change follows existing repository boundaries
- [ ] Chain-specific behavior is implemented through adapters/capabilities rather than scattered conditionals
- [ ] Public contract changes are versioned/documented where applicable
- [ ] Money-critical protocol changes remain isolated to `mwz-protocol-core`

## Testing

List tests, builds, simulations, or manual checks performed.

## Security

- [ ] No `.env`, private keys, mnemonics, signer material, service-role credentials, or private RPC credentials committed
- [ ] Security-sensitive behavior has appropriate reviewer ownership

## Deployment / Migration

Describe any required deployment, migration, configuration, or follow-up. Write `None` if not applicable.

## Evidence

Include relevant logs, screenshots, transaction hashes, test output, or other acceptance evidence when applicable.
