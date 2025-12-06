why using the ansible when shell script automate tasks too?
Shell scripting can automate tasks, but Ansible is built for large-scale, consistent, repeatable, idempotent automation across many servers.
Ansible solves all the problems that shell scripts cannot solve reliably in production.

1. Idempotency (Most Important)
Shell script:
If you run useradd devops twice → FAILS.
If you install a package that is already installed → unnecessary errors.

Ansible:
Checks the system state first.
Applies changes only if required.
Safe to run 100 times.

✅ Idempotency = predictable automation
This is why Ansible is trusted in production.

