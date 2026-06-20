---
id: SEC-NO-MD5-001
title: "No MD5 hashing allowed"
severity: critical
description: "MD5 is insecure and must not be used."
criteria:
  forbids_terms:
    - md5
tags:
  - security
  - crypto
---

# No MD5 hashing allowed

We do not use MD5 hashes for cryptography.
