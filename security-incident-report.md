# 🔐 Security Risk Report – Credential Exposure

## 📍 Context

This report documents a critical security vulnerability identified in a real retail environment involving a CCTV system.

Sensitive details have been omitted for ethical reasons.

---

## 🧨 Vulnerability Summary

A critical flaw was identified in the camera system:

- Access to a restricted system area using default credentials
- Discovery of stored master credentials within the system interface
- Ability to view username and password directly
- Access granted to multiple environments (stores, office, factory)

---

## 🚨 Risk Description

The exposed credentials provide:

- Full access to all camera systems
- Visibility into multiple physical locations
- Potential unauthorized monitoring

---

## 🔥 Impact

- Violation of privacy
- Exposure of sensitive environments
- Risk of internal and external misuse
- Loss of organizational trust

---

## 📊 Risk Classification

- Likelihood: High  
- Impact: Critical  

➡️ Risk Level: 🔴 CRITICAL

---

## 🧠 Root Cause

- Insecure storage of credentials
- Lack of access control
- Poor system design
- Absence of security policies

---

## 🛡️ Recommended Actions

### Immediate
- Remove stored credentials from system interface
- Change all exposed credentials
- Restrict access by user role

### Short-Term
- Implement password security policy
- Apply least privilege principle
- Audit all system access

### Long-Term
- Implement monitoring and logging
- Conduct periodic security assessments
- Security awareness training

---

## 🔁 Status

- Issue reported to IT team
- Vulnerability still present (not remediated)

---

## ⚠️ Ethical Note

This analysis was conducted without exploiting the vulnerability.

The objective is risk identification and mitigation only.
