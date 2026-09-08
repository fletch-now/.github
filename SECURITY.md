# Security

Report a vulnerability in any fletch-now repository or in fletch.now itself to security@fletch.now. Say which repository or route, what you observed, and how to reproduce it. You will get an acknowledgement within three working days.

We ask for 90 days before public disclosure, and we will credit you in the fix's changelog unless you ask otherwise.

Published clients read the API and do not persist API keys. Public registry reads need no key. The MCP client sends a configured key only to the webhook-list route; the TypeScript SDK attaches a configured key to its API reads. Both require HTTPS for authenticated requests. Configure only a trusted API base URL, and omit the key for public-only integrations.

Both clients refuse redirects, omit upstream failure bodies and redact exact echoes of their configured API key from returned data. Status and retry guidance remain available for error handling.
