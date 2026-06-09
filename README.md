# Will Hedrick

**Infrastructure & Automation Engineer** - I build self-hosted systems with production-grade patterns: explicit network boundaries, centralized identity, automated tooling, and documented operational decisions.

---

## Featured Project

### [DockerStack](https://github.com/Hedrick14/DockerStack)
A 26-service homelab running on Windows 11 / Docker Desktop. 39 containers organized as one Compose project per service, with Authentik SSO (OIDC / OAuth2 / LDAP), ZeroTier overlay networking, VPN sidecar egress, Prometheus + Grafana monitoring, and custom Python and PowerShell tooling for disk health, library repair, and service automation.

---

## Technical Focus

**Infrastructure & Containers**
Docker · Docker Compose · Nginx · Cloudflare Tunnels · ZeroTier · WireGuard · ProtonVPN

**Identity & Security**
Authentik · OIDC · OAuth2 · LDAP · SSO architecture

**Observability**
Prometheus · Grafana · cAdvisor · Scrutiny · Uptime Kuma

**Automation & Tooling**
PowerShell · Python · MCP (Model Context Protocol) · REST API automation

---

## How I Work

- One service, one Compose file - blast radius isolation over convenience
- Architecture decisions are written down before they become routine
- Scripts replace manual procedures; runbooks capture what scripts can't
- Secrets stay out of version control; configuration stays in it
