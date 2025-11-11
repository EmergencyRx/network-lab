# Scenario: DNS Resolution Issue

Baseline:
- Client receives IP via DHCP.
- DNS should work via router.

Fault:
- DNS server misconfigured or unreachable.

Tasks:
- Inspect IP and DNS settings on client.
- Test ping by IP and hostname.
- Identify and correct DNS config on router or upstream.
