# it@M Policy for policy-as-code

This repository contains the default it@M policy for the GitHub Action [advanced-security/policy-as-code](https://github.com/advanced-security/policy-as-code) for compliance checks.

## Usage

```yaml
# Compliance
- name: Advance Security Policy as Code
  uses: advanced-security/policy-as-code@v2.4.1
  with:
    policy: it-at-m/policy-as-code
    policy-path: default.yaml
```

## False Positives

If you discover a "false positive" for license compliance checks for a specific library, feel free to open a PR whichs adds the library [to the ignore list](https://github.com/it-at-m/policy-as-code/blob/main/default.yaml#L24). Please also include a comment for why this is a "false positive". 
