## 📋 Change Summary
<!-- Brief description of what is being changed and why -->

- **Shortcut / Ticket Ref:** [e.g. sc-1234]
- **Change Category:** 
  - [ ] Standard Feature / Bug Fix
  - [ ] Security / Dependency Update
  - [ ] Major Infrastructure Change *(Requires Major Change Register entry)*

## Screenshots (If applicable)

---

## 🔒 ISO 27001 Security Checklist
<!-- Verify each item before requesting review (Controls 8.25, 8.28) -->

- [ ] **No Secrets:** Verified no credentials, tokens, connection strings, or secrets are committed.
- [ ] **Dependencies:** New package dependencies (npm / NuGet) checked for vulnerabilities.
- [ ] **Access & Data:** Role-based access control and tenant isolation respected.

---

## 🧪 Staging Verification (Mandatory for Merge)
<!-- Control 8.32 requires testing in staging prior to production deployment -->

- [ ] **Staging Tested:** Tested and verified in the Staging environment.
- **Verified By:** @developer_handle
- **Date Verified:** YYYY-MM-DD
- **Test Notes:** Passed verification with no regressions.

---

## 👥 Review & Sign-Off
<!-- Approved by lead-reviewers (Neil, James, or Adam) -->
- [ ] Senior Developer review completed and approved by `@lead-reviewers`.
- [ ] Automated CI/CD build / checks passed.
