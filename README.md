# Azure Production Training Guide

> **Comprehensive Azure Administrator training focused on real production operations, not theoretical concepts**

[![Azure](https://img.shields.io/badge/Azure-Administrator-0078D4?style=flat&logo=microsoft-azure)](https://azure.microsoft.com/)
[![Training](https://img.shields.io/badge/Training-Production--Ready-success)](https://github.com/cjohnny54/azure-production-training)
[![Exercises](https://img.shields.io/badge/Exercises-8_Hands--On-orange)](https://github.com/cjohnny54/azure-production-training)

---

## 🎯 Overview

This repository contains a **complete production-focused Azure training program** with:

- **13 comprehensive sections** covering all operational aspects
- **8 hands-on exercises** (15-20 hours total)
- **Real incident response procedures** from production environments
- **Interview preparation** with 4 complete scenarios + STAR format prep
- **Production-ready code examples** (Terraform, PowerShell, Azure CLI, KQL)
- **2,700+ lines** of detailed content

**⚠️ Note**: This is NOT a beginner's guide. It assumes you have basic Azure knowledge (AZ-900 level) and focuses on operating Azure at production scale.

---

## 📁 Repository Structure

```
azure-production-training/
├── README.md                    # This file - repository overview
├── START_HERE.md                # Quick start guide and navigation
├── docs/
│   ├── Part1_Sections_0-7.md     # Foundation through Monitoring
│   ├── Part2_Sections_8-13.md    # Governance through Interview Prep
│   └── Index_and_Reference.md    # Quick reference and commands
├── exercises/
│   ├── Exercise_1.1_Terraform_Multi_Region.md
│   ├── Exercise_2.1_Network_Troubleshooting.md
│   ├── Exercise_3.1_RBAC_Implementation.md
│   ├── Exercise_4.1_AKS_Multi_Tier.md
│   ├── Exercise_5.1_Database_Failover.md
│   ├── Exercise_7.1_Monitoring_Setup.md
│   ├── Exercise_8.1_Compliance_Automation.md
│   └── Exercise_9.1_Incident_Simulation.md
└── code-examples/
    ├── terraform/
    ├── powershell/
    └── scripts/
```

---

## 🚀 Quick Start

### 1. Choose Your Path

**🎓 Complete Learning Path** (20-30 hours)
- Best for: Comprehensive Azure production knowledge
- Timeline: 4 weeks
- Start: Read `START_HERE.md` then `docs/Part1_Sections_0-7.md`

**💔 Interview Prep Path** (8-10 hours)
- Best for: Upcoming Azure interviews
- Timeline: 1 week
- Start: Section 0 + Section 13 in Part 2

**🔧 Problem-Solving Path** (1-3 hours)
- Best for: Immediate production issues
- Timeline: Same day
- Start: Use `Index_and_Reference.md` to find your topic

**📦 Production Launch Path** (4-6 hours)
- Best for: Pre-production readiness
- Timeline: Before go-live
- Start: Production Readiness Checklist in Index

### 2. Install Prerequisites

```bash
# Azure CLI
curl -sL https://aka.ms/InstallAzureCLIDeb | sudo bash

# Terraform
wget https://releases.hashicorp.com/terraform/1.7.0/terraform_1.7.0_linux_amd64.zip
unzip terraform_1.7.0_linux_amd64.zip
sudo mv terraform /usr/local/bin/

# kubectl (for AKS exercises)
az aks install-cli

# Verify installations
az version
terraform version
kubectl version --client
```

### 3. Start Learning

Read **START_HERE.md** for detailed navigation and learning paths.

---

## 📚 Content Overview

### Part 1: Foundation & Core Services (Sections 0-7)

| Section | Topic | Key Concepts |
|---------|-------|-------------|
| 0 | Production Reality | Real architectures, shared responsibility, decision frameworks |
| 1 | Infrastructure as Code | Terraform, ARM, Bicep, CI/CD pipelines |
| 2 | Networking | Hub-spoke, NSGs, Network Watcher, ExpressRoute |
| 3 | Identity & Access | RBAC, managed identities, hybrid identity, zero-trust |
| 4 | Compute | VMs, AKS, Kubernetes autoscaling, update management |
| 5 | Data & Storage | SQL HA, failover groups, storage tiers, Cosmos DB |
| 6 | AI/ML Production | Azure OpenAI, cost control, responsible AI |
| 7 | Monitoring | Metrics, logs, traces, alert design, dashboards |

### Part 2: Operations & Advanced Topics (Sections 8-13)

| Section | Topic | Key Concepts |
|---------|-------|-------------|
| 8 | Governance | Azure Policy, compliance (SOX, GDPR, PCI-DSS) |
| 9 | Incident Response | Real runbooks, troubleshooting, incident lifecycle |
| 10 | Cost Operations | FinOps, right-sizing, reserved instances, optimization |
| 11 | Production Ops | Maintenance, change management, DR testing |
| 12 | Multi-Region | Traffic Manager, hybrid scenarios, global routing |
| 13 | Interview Prep | 4 scenarios, STAR format, system design |

---

## 🎯 Hands-On Exercises

All exercises are production-realistic and build on each other:

| Exercise | Description | Duration | Difficulty |
|----------|-------------|----------|-----------|
| **1.1** | Deploy multi-region infrastructure with Terraform | 2-3h | Intermediate |
| **2.1** | Troubleshoot network connectivity with NSGs | 1-2h | Intermediate |
| **3.1** | Implement least-privilege RBAC model | 1h | Beginner |
| **4.1** | Deploy multi-tier app on AKS with autoscaling | 3-4h | Advanced |
| **5.1** | Configure and test database geo-replication | 2h | Intermediate |
| **7.1** | Set up comprehensive monitoring and alerts | 2h | Intermediate |
| **8.1** | Automate compliance checking with Policy | 2-3h | Intermediate |
| **9.1** | Simulate and resolve production incident | 1-2h | Beginner |

**Total: 15-20 hours**

---

## ✨ What Makes This Different

### Traditional Azure Training:
- ❌ "Here's how to click buttons in the portal"
- ❌ Single-region examples
- ❌ Theory without real-world context
- ❌ No cost discussions
- ❌ No incident response
- ❌ No interview preparation

### This Training:
- ✅ "Here's what fails in production and how you fix it"
- ✅ Multi-region architectures by default
- ✅ Real incident timelines and resolutions
- ✅ Complete FinOps chapter with actual cost data
- ✅ Runbooks and troubleshooting procedures
- ✅ Complete interview preparation (Section 13)
- ✅ Infrastructure as Code first (Terraform)
- ✅ Ready for Day 1 on-call duty

---

## 📊 Learning Outcomes

After completing this training, you will be able to:

### Technical Skills
- ✅ Deploy infrastructure using Terraform (multi-region)
- ✅ Diagnose network issues systematically
- ✅ Implement least-privilege access control
- ✅ Scale Kubernetes workloads properly (HPA/CA)
- ✅ Design and test database failover (RTO/RPO)
- ✅ Set up production monitoring with alerts
- ✅ Automate compliance checking
- ✅ Lead incident response confidently

### Operational Skills
- ✅ Optimize cloud costs by 30-50%
- ✅ Operate multi-region infrastructure
- ✅ Handle on-call incidents independently
- ✅ Design highly available systems
- ✅ Implement disaster recovery procedures

### Interview Skills
- ✅ Answer architecture scenario questions
- ✅ Demonstrate production thinking
- ✅ Use STAR format for behavioral questions
- ✅ Design systems from requirements

---

## 👥 Target Audience

### Primary Audience
- Infrastructure Engineers preparing for production operations
- DevOps Engineers moving to Azure
- Cloud Engineers seeking Azure expertise
- SREs supporting Azure workloads
- Anyone preparing for Azure Administrator interviews

### Prerequisites
- Basic Azure knowledge (AZ-900 level or equivalent)
- Familiarity with command-line interfaces
- Understanding of networking fundamentals
- Basic scripting experience (PowerShell or Bash)

### NOT For
- Complete beginners to cloud computing
- Developers only writing application code
- Those seeking "click the portal" tutorials

---

## 🛠️ Technologies Covered

### Core Azure Services
- Virtual Networks, NSGs, Application Gateway
- Azure Kubernetes Service (AKS)
- Azure SQL Database with geo-replication
- Azure Storage (all tiers)
- Azure Key Vault
- Application Insights & Log Analytics
- Azure Policy
- Azure OpenAI Service

### Tools & Automation
- **Terraform** - Infrastructure as Code
- **Azure CLI** - Command-line management
- **PowerShell** - Automation scripts
- **kubectl** - Kubernetes management
- **KQL** - Log query language
- **Azure DevOps** - CI/CD pipelines

---

## 📝 Documentation Structure

### Main Documents

**START_HERE.md** - Navigation guide
- Learning path recommendations
- Quick reference section
- Success metrics

**Part 1 (Sections 0-7)** - Foundation & Core Services
- ~1,350 lines
- 3 hands-on exercises
- 15+ Terraform code examples

**Part 2 (Sections 8-13)** - Operations & Interview Prep
- ~1,370 lines
- 5 hands-on exercises
- Real incident timelines
- Complete interview scenarios

**Index & Reference** - Quick lookup
- Command reference (Terraform, CLI, PowerShell, KQL)
- Production readiness checklist
- Exercise summary table
- Architecture templates

---

## 🏆 Certification Alignment

### AZ-104: Azure Administrator Associate

This training covers **all AZ-104 objectives** with production focus:

| Domain | Coverage | Sections |
|--------|----------|----------|
| Manage Azure identities and governance | ✅ Complete | 3, 8 |
| Implement and manage storage | ✅ Complete | 5 |
| Deploy and manage Azure compute resources | ✅ Complete | 4 |
| Configure and manage virtual networking | ✅ Complete | 2 |
| Monitor and maintain Azure resources | ✅ Complete | 7, 11 |

**Bonus content beyond AZ-104:**
- Infrastructure as Code (Terraform)
- Production incident response
- FinOps and cost optimization
- Interview preparation
- Multi-region architectures

---

## ⭐ Key Features

### Real Production Content
- 📅 **Actual incident timelines** (25-min database resolution, 8-min failover)
- 💰 **Real cost data** ($50k → $12k storage optimization)
- 🎯 **RTO/RPO metrics** (what success actually looks like)
- 🚨 **On-call procedures** (severity frameworks, escalation paths)
- 🔄 **DR testing procedures** (monthly drills, verification)

### Code Examples
- 15+ production Terraform configurations
- 10+ PowerShell automation scripts
- 20+ Azure CLI commands
- 15+ KQL queries for monitoring
- 5+ Kubernetes YAML manifests

### Interview Preparation
- 4 complete scenario questions with expected answers
- STAR format behavioral interview guide
- System design challenge (100k requests/sec)
- Red flags to avoid / Green flags to highlight
- Technical deep-dive examples

---

## 📈 Recommended Timeline

### 4-Week Complete Path

**Week 1: Foundation**
- Days 1-2: Read Section 0 (production reality)
- Days 3-4: Complete Exercise 1.1 (Terraform)
- Day 5: Complete Exercise 2.1 (networking)
- Days 6-7: Complete Exercise 3.1 (identity)

**Week 2: Compute & Data**
- Days 1-2: Complete Exercise 4.1 (AKS)
- Days 3-4: Complete Exercise 5.1 (database)
- Days 5-7: Review and practice

**Week 3: Advanced Topics**
- Days 1-2: Sections 6-7 (AI/ML, monitoring)
- Day 3: Complete Exercise 7.1 (monitoring)
- Days 4-5: Sections 8-9 (governance, incidents)
- Days 6-7: Complete Exercises 8.1, 9.1

**Week 4: Operations & Interview**
- Days 1-2: Sections 11-12 (operations, multi-region)
- Days 3-5: Section 13 (interview prep)
- Days 6-7: Mock interviews, review

---

## 🤝 Contributing

Contributions are welcome! If you:
- Find errors or outdated information
- Have additional production scenarios to share
- Want to contribute exercises or code examples
- Suggest improvements to existing content

Please open an issue or submit a pull request.

---

## 📝 License

This training material is provided for educational purposes. Feel free to:
- Use for personal learning
- Share with your team
- Modify for your organization
- Reference in your own materials

Attribution appreciated but not required.

---

## ❓ FAQ

**Q: Do I need an Azure subscription?**
A: Yes, for the hands-on exercises. Free trial ($200 credit) is sufficient for most exercises.

**Q: How long does it take to complete?**
A: 20-30 hours for full completion (all exercises). 8-10 hours for interview prep only.

**Q: Is this suitable for beginners?**
A: No. You should have basic Azure knowledge (AZ-900 level) before starting.

**Q: Does this prepare me for AZ-104 certification?**
A: Yes! All AZ-104 objectives are covered, plus additional production-focused content.

**Q: Can I use this for team training?**
A: Absolutely! See the team training recommendations in START_HERE.md.

**Q: How current is the content?**
A: Created February 2026. Azure changes frequently, so verify current pricing and features.

---

## 🔗 Quick Links

- **Start Learning**: [START_HERE.md](./START_HERE.md)
- **Part 1 Content**: [docs/Part1_Sections_0-7.md](./docs/Part1_Sections_0-7.md)
- **Part 2 Content**: [docs/Part2_Sections_8-13.md](./docs/Part2_Sections_8-13.md)
- **Quick Reference**: [docs/Index_and_Reference.md](./docs/Index_and_Reference.md)
- **All Exercises**: [exercises/](./exercises/)

---

## 💬 Feedback

Found this helpful? Have questions or suggestions?

- Open an [Issue](https://github.com/cjohnny54/azure-production-training/issues)
- Submit a [Pull Request](https://github.com/cjohnny54/azure-production-training/pulls)
- Star ⭐ this repository if you found it useful!

---

**Ready to build production Azure systems? Start with [START_HERE.md](./START_HERE.md)!** 🚀

---

*Last Updated: February 2026*  
*Maintained by: [@cjohnny54](https://github.com/cjohnny54)*
