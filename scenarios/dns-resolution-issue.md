# Scenario: DNS Resolution Issue

Setup:
- Client obtains IP configuration from router.
- Router forwards DNS to upstream resolver.

Fault:
- Router DNS forwarding misconfigured or blocked.

Tasks:
- Verify IP configuration on client.
- Use ping and dig/nslookup to isolate DNS vs connectivity.
- Correct DNS settings on router and confirm recovery.
