[linux] [devops] [docker] [containers]

(copied from a message in the Free Linux course)

Over the past weekend, I had a DevOps interview task focused on enterprise Linux administration.

The requirement was clear:Install AlmaLinux 9.x and configure it to production standards — secure networking, system hardening, proper package management, and operational best practices. Docker had to be installed, but only after the OS was secured.

My approach on AlmaLinux 9.7:

- Configured static IP, hostname, and DNS
- Set SELinux to enforcing
- Disabled unnecessary services
- Hardened SSH (no password auth, no root login)
- Set umask 027 (To understand this better check out unit 9 of the course in the class room section “Users, Groups & Permissions”)
- Mounted /tmp with noexec,nosuid
- Configured auditd for critical file monitoring
- Fully updated the system before deploying Docker

It passed validation, including Docker running correctly under SELinux contexts.

The interview had additional layers beyond Linux, but I’m sharing only this part because this community is Linux-first.

Big takeaway for me:If the base OS isn’t secure and well-configured, everything built on top of it is fragile.