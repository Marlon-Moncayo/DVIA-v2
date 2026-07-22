# Security Policy

## About this project

This repository is a fork of DVIA-v2 (Damn Vulnerable iOS App), used as part of
an academic Master's Thesis (TFM) on iOS mobile application penetration testing.
The application contains **intentional vulnerabilities** by design, used solely
for educational and authorized security testing purposes in a controlled,
isolated environment.

**This is not a production application.** Do not deploy it to real devices
connected to production networks, and do not use it to store real personal or
sensitive data.

## Supported Versions

Only the version used for this thesis is actively maintained and tested.

| Version              | Supported          |
| --------------------- | ------------------ |
| Thesis fork (current)  | :white_check_mark: |
| Upstream DVIA-v2 (latest) | :white_check_mark: |
| Older upstream tags    | :x:                |

## Reporting a Vulnerability

Since intentional vulnerabilities are the purpose of this repository, please
distinguish between two cases:

- **Intentional vulnerabilities** (part of the app's training challenges):
  no need to report these — they are documented and analyzed as part of the
  thesis itself.
- **Unintentional issues** (e.g. a bug in the build/CI setup, a dependency
  with a real known CVE unrelated to the training challenges, or something
  that could affect the security of the environment running this repo):
  please open a GitHub Issue tagged `security`, or contact [tu-email-academico]
  directly.

You can expect an initial response within 5–7 days. Given the academic and
non-commercial nature of this project, fixes will be prioritized based on
thesis timelines and supervisor guidance.
