---
runme:
  id: 01HQ91TH5NPT929KR36AQXC6RE
  version: v3
---

# Plan

- [ ] DX
  - [ ] UI: Nx + pnpm
  - [ ] Backend: Nx + pnpm
  - [ ] Docker Compose Local Dev (infrastructure deps)
  - [ ] Single Monorepo for Backend and Frontend?
  - [ ] Snyk
- [ ] DevOps
  - [ ] SAM template
  - [ ] Terraform and Ansible
  - [ ] Generalize getting the Branch an all pipelines / builds
  - [ ] Backend
    - [ ] Blue/Green Deployment
    - [ ] ECS FarGate
  - [ ] UI
    - [ ] Release Branch folder Deploys
    - [ ] Pipeline to redirect cloudformation from folder to folder
    - [ ] aws cli command to redirect cloudformation from folder to folder
  - [ ] Infrastructure Monitoring
  - [ ] Put App in OfflineMode (under maintenance folder)
  - [ ] Automatic cleanup jobs (i.e. remove old branches)
  - [ ] PlayWright + Jest
- [ ] App Monitoring
  - [ ] Usage tracking
  - [ ] RUM
  - [ ] Infrastructure monitoring
- [ ] Backend
  - [ ] NestJS + TypeORM + TypeScript
  - [ ] Bruno or similar
  - [ ] PlayWright? + e2e Jest
  - [ ] Login using Secure HTTP Only Cookies
  - [ ] CSP
  - [ ] Backward compatibility DB changes
- [ ] PM
  - [ ] [Release Notes](https://blog.logrocket.com/product-management/what-are-release-notes-how-to-write-good-ones/)
  - [ ] Required Meetings
  - [ ] Request of tasks by Tickets

[Production Readiness Checklist](https://gruntwork.io/devops-checklist/?ref=dailydev)

- Server-side
- Client-side
- Data storage
- Scalability and High Availability
- Continuous Integration
- Continuous Delivery
- Networking
- Security
- Monitoring
- Cost optimization
