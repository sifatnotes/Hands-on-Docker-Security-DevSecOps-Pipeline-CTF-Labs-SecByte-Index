# Hands-on-Docker-Security-DevSecOps-Pipeline-CTF-Labs-SecByte-Index
A practical collection of cybersecurity CTF labs focusing on Docker host auditing, container breakouts, root privilege escalation, registry security, supply chain hardening, and secure DevSecOps pipelines.
# Docker Security & DevSecOps Pipeline CTF Lab Collection

Welcome to the **Docker Security & DevSecOps Pipeline CTF Lab Collection**. This repository provides an organized, searchable index of hands-on security labs and Capture The Flag (CTF) exercises hosted on Learn SecByte.

This catalog covers containerization fundamentals, Docker host auditing, container escapes, privilege escalation, secure registry architecture, supply chain security, and end-to-end DevSecOps release pipelines.

---

## Lab Collection Index

### 1. Docker Fundamentals & Host Security Auditing
* **Docker Fundamentals: Containers, Images, Security Basics**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-fundamentals-containers-images-security-basics](https://learn.secbyte.org/ctf/docker-fundamentals-containers-images-security-basics)  
  *Focus:* Understanding namespaces, cgroups, image layering, basic container runtime flags, and baseline security concepts.

* **Docker Security Basics: Containers Isolation & Misconfiguration**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-security-basics-containers-isolation-misconfiguration](https://learn.secbyte.org/ctf/docker-security-basics-containers-isolation-misconfiguration)  
  *Focus:* Identifying runtime misconfigurations, weak container isolation parameters, insecure capabilities, and default configuration flaws.

* **Docker Bench Security: Auditing Container Hosts**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-bench-security-auditing-container-hosts](https://learn.secbyte.org/ctf/docker-bench-security-auditing-container-hosts)  
  *Focus:* Running automated CIS Docker Benchmark audits against host daemons, evaluating host configuration compliance, and remediating audit failures.

### 2. Container Isolation, Escapes & Privilege Escalation
* **Docker Containers Security: Isolation & Abuse Paths**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-containers-security-isolation-abuse-paths](https://learn.secbyte.org/ctf/docker-containers-security-isolation-abuse-paths)  
  *Focus:* Mapping process isolation boundaries, cgroup resource limits, Linux capabilities (`CAP_SYS_ADMIN`), and kernel attack surfaces.

* **Docker Escape: From Container to Host**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-escape-from-container-to-host](https://learn.secbyte.org/ctf/docker-escape-from-container-to-host)  
  *Focus:* Executing breakouts via mounted Docker sockets (`/var/run/docker.sock`), host IPC/PID namespaces, kernel exploits, and device mounting.

* **Docker Privilege Escalation: Containers to Root**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-privilege-escalation-containers-to-root](https://learn.secbyte.org/ctf/docker-privilege-escalation-containers-to-root)  
  *Focus:* Escalating limited container user privileges to host root access via SUID binaries, group memberships, and over-privileged runtimes.

### 3. Container Components, Networking & Supply Chain
* **Docker Volumes: Persistence Abuse and Defense**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-volumes-persistence-abuse-and-defense](https://learn.secbyte.org/ctf/docker-volumes-persistence-abuse-and-defense)  
  *Focus:* Investigating bind mounts, persistent storage permissions, sensitive host path mounting risks, and data leakage defense.

* **Docker Networks: Container Connectivity, Segmentation, and Security**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-networks-container-connectivity--segmentation-and-secu](https://learn.secbyte.org/ctf/docker-networks-container-connectivity--segmentation-and-secu)  
  *Focus:* Analyzing custom bridge networks, overlay networks, network driver isolation, cross-container traffic sniffing, and port exposure risks.

* **Docker Registry Security: From Enumeration to Hardening**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-registry-security-from-enumeration-to-hardening](https://learn.secbyte.org/ctf/docker-registry-security-from-enumeration-to-hardening)  
  *Focus:* Enumerating private V2 container registries, enforcing authentication/RBAC, restricting image pulls, and securing registry endpoints.

* **Docker Images Trust, Layers, and Container Supply Chain Security**  
  *Lab Link:* [https://learn.secbyte.org/ctf/docker-images-trust-layers-and-container-supply-chain-securi](https://learn.secbyte.org/ctf/docker-images-trust-layers-and-container-supply-chain-securi)  
  *Focus:* Image vulnerability scanning, layer diff analysis, Docker Content Trust (DCT), base image signing, and preventing supply chain poisoning.

### 4. DevSecOps & CI/CD Pipeline Security
* **Release Security: Build to Deploy**  
  *Lab Link:* [https://learn.secbyte.org/ctf/release-security-build-to-deploy](https://learn.secbyte.org/ctf/release-security-build-to-deploy)  
  *Focus:* Integrating SAST, DAST, and secret scanning into build steps, enforcing artifact attestation, and securing deployment gates.

* **DevSecOps Capstone: Secure Delivery Pipeline**  
  *Lab Link:* [https://learn.secbyte.org/ctf/devsecops-capstone-secure-delivery-pipeline](https://learn.secbyte.org/ctf/devsecops-capstone-secure-delivery-pipeline)  
  *Focus:* Comprehensive scenario building, auditing, and hardening a complete CI/CD release pipeline against real-world supply chain threats.

---

## Learning Path

### Path A: Docker Hardening & Isolation Specialist
1. **Runtimes & Baseline:** Start with [Docker Fundamentals](https://learn.secbyte.org/ctf/docker-fundamentals-containers-images-security-basics) and [Docker Security Basics](https://learn.secbyte.org/ctf/docker-security-basics-containers-isolation-misconfiguration).
2. **Audit & Compliance:** Practice auditing via [Docker Bench Security](https://learn.secbyte.org/ctf/docker-bench-security-auditing-container-hosts).
3. **Component Security:** Secure data and communications using [Docker Volumes](https://learn.secbyte.org/ctf/docker-volumes-persistence-abuse-and-defense) and [Docker Networks](https://learn.secbyte.org/ctf/docker-networks-container-connectivity--segmentation-and-secu).

### Path B: Red Team & Container Breakout
1. **Isolation Analysis:** Understand boundaries with [Docker Containers Security: Isolation & Abuse Paths](https://learn.secbyte.org/ctf/docker-containers-security-isolation-abuse-paths).
2. **Escalation & Breakouts:** Execute advanced attacks in [Docker Privilege Escalation](https://learn.secbyte.org/ctf/docker-privilege-escalation-containers-to-root) and [Docker Escape](https://learn.secbyte.org/ctf/docker-escape-from-container-to-host).

### Path C: DevSecOps & Supply Chain Security
1. **Registry & Image Trust:** Master artifact integrity with [Docker Registry Security](https://learn.secbyte.org/ctf/docker-registry-security-from-enumeration-to-hardening) and [Docker Images Trust & Supply Chain Security](https://learn.secbyte.org/ctf/docker-images-trust-layers-and-container-supply-chain-securi).
2. **Pipeline Integration:** Practice automated gates via [Release Security: Build to Deploy](https://learn.secbyte.org/ctf/release-security-build-to-deploy).
3. **Capstone Synthesis:** Complete the hands-on assessment in [DevSecOps Capstone: Secure Delivery Pipeline](https://learn.secbyte.org/ctf/devsecops-capstone-secure-delivery-pipeline).

---

## How to Use the Labs

1. Choose a exercise from the **Lab Collection Index**.
2. Click the corresponding link to launch the lab directly on Learn SecByte.
3. Review scenario directives, technical requirements, and target goals.
4. Complete container checks, execute penetration testing tools, or fix pipeline configurations to capture flags.

---

## Target Audience

* **DevSecOps Engineers:** Integrate automated security testing, image scanning, and registry access controls into release cycles.
* **Security Engineers & System Admins:** Benchmark host daemons, configure network segmentation, and secure volume mounts.
* **Penetration Testers & Red Teams:** Practice container breakout vectors, socket abuse, and privilege escalation techniques.
* **Cybersecurity Students:** Acquire practical container defense and CI/CD security skills through interactive exercises.

---

## Disclaimer

All links listed in this repository lead to official training environments hosted on Learn SecByte. Exercises are intended strictly for educational research, authorized skill development, and defensive engineering practice. Applying these techniques to unauthorized systems is strictly prohibited.
