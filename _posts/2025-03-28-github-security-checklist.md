---
layout: post
title: "GitHub Security Checklist - Protect Your Code in 5 Minutes"
date: 2025-03-28
categories: [security]
tags: [github, devops, cybersecurity]
---

# Essential GitHub Security Steps

## Immediate Actions (Do Today)
1. **Enable 2FA**  
   Settings → Password and authentication → Enable 2FA  
   *Use an authenticator app, not SMS*

2. **Review Active Sessions**  
   Settings → Security → Active sessions  
   *Log out unfamiliar devices*

3. **Audit Repository Access**  
   Each repo → Settings → Collaborators  
   *Remove inactive contributors*

## Automated Protections
```yaml
# Recommended branch protections (Settings → Branches)
required_status_checks:
  strict: true
required_pull_request_reviews:
  required_approving_review_count: 1
enforce_admins: true
