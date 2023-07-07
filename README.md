# it@M Policy for policy-as-code

This repository contains the default it@M policy for the GitHub Action [advanced-security/policy-as-code](https://github.com/advanced-security/policy-as-code) for compliance checks.

## Usage

```yml
# Compliance
- name: Advance Security Policy as Code
  uses: advanced-security/policy-as-code@v2.3.4
  with:
    policy: it-at-m/policy-as-code
    policy-path: default.yml
```
