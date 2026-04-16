# ClawLink Nango Architecture

## Responsibility boundary

- **Nango** owns OAuth, token exchange, refresh, storage, and provider-specific connection normalization.
- **ClawLink** owns product UX, hosted connect orchestration, reconciliation, and tool execution.

ClawLink should not reimplement token lifecycle logic for Nango-managed providers.
