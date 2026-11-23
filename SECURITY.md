# Security

Tuatara is made to open files from sources nobody trusts, so a way for a
file, a folder, a terminal's output, a pasted text or a package to make
Tuatara run something, read or write outside what was asked, or reach the
network unasked is a security fault. So is a way to change a file that was
opened safely (`C-u C-x C-f`).

## Reporting a fault

Report it privately, never in a public issue: in the repository concerned,
Security, then "Report a vulnerability". Give:

- what Tuatara does that it should not, and what it should do;
- the steps or a file that shows it, made as small as you can;
- the version (`tuatara --version`) and the system it runs on.

A maintainer answers within a week. Once a fix is ready it is released, and
the advisory is published with credit to you unless you ask otherwise.

## Versions

Only the newest release, and the `main` branch, get security fixes.
