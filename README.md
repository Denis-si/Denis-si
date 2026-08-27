## Hi there, I'm Denis 👋 

### 🛡️ Cloud Security & DevSecOps Engineer

I am a **Cloud Security & DevSecOps Engineer** with a strong background in operational readiness, logistics, and disciplined systems analysis from my service in the **U.S. Army National Guard**. 

Through hands-on engineering fellowship training at **The Knowledge House**, I specialize in building immutable infrastructure using HashiCorp Terraform, automating shift-left security quality gates in CI/CD pipelines, and enforcing continuous compliance across AWS environments.

---

### 🧰 Technical Arsenal

| Domain | Technologies & Tools |
| :--- | :--- |
| **Cloud Infrastructure (AWS)** | AWS VPC, EC2, IAM, GuardDuty, AWS Config, Secrets Manager, S3 |
| **Infrastructure as Code (IaC)** | Terraform (HCL) |
| **DevSecOps & CI/CD** | GitHub Actions, Docker, `tfsec`, Trivy, Grype, Snyk, Syft (SBOM), Cosign |
| **Security & Incident Response** | Linux (Ubuntu), Suricata IDS, iptables, UFW, ELK SIEM (Elasticsearch/Kibana), Sleuth Kit |
| **Scripting & Automation** | Python (`subprocess`, `json`), Bash |

---

### ⚡ Featured Portfolio Projects

#### 🌐 [Secure Automated Web Architecture (Capstone)](https://github.com/Denis-si/TKH-Final-Capstone)
> *Automated, secure web stack deployment on AWS built with Terraform and guarded by a SAST CI/CD quality gate.*
* **Infrastructure as Code:** Provisioned custom AWS VPC, public subnets, Internet Gateway, and hardened EC2 web servers with encrypted `gp3` root volumes and IMDSv2 enforcement.
* **Shift-Left Security Gate:** Engineered a GitHub Actions pipeline using `tfsec` with `--soft-fail=false` to automatically fail builds on security policy violations prior to deployment.
* **Least-Privilege Firewalls:** Configured Security Groups restricting administrative SSH (Port 22) exclusively to authorized administrator IP ranges via `/32` CIDR masks.

#### 📦 [Container Security & Image Signing Pipeline](https://github.com/Denis-si)
> *End-to-end container hardening and supply chain security framework.*
* Built hardened, non-root Docker minimal base images for microservices.
* Integrated automated CVE vulnerability scanning using **Trivy** and **Grype**, generated Software Bill of Materials (**SBOM**) using **Syft**, and enforced supply chain integrity with **Cosign** image signatures.

#### 🔍 [Cloud Threat Detection & Security Automation Scripts](https://github.com/Denis-si)
> *Python-based system auditing and log analysis automation for digital forensics and incident response (DFIR).*
* Developed structured audit utilities (`system_auditor.py`) to parse Linux logs, carve memory artifacts, and output JSON threat intelligence reports directly into an ELK SIEM pipeline.

---

### 📜 Verified Credentials & Certifications

* ☁️ **AWS Certified Cloud Practitioner** — *Amazon Web Services*
* 🤖 **Anthropic AI Fluency Credential** — *Anthropic*
* 🛡️ **JKO Cyber Awareness** — *U.S. Department of Defense*
* 🔒 **JKO Operations Security (OPSEC)** — *U.S. Department of Defense*

---

### 📫 Connect With Me

* 💼 **LinkedIn:** www.linkedin.com/in/dennis-hanto
* 📍 **Location:** New York, NY
