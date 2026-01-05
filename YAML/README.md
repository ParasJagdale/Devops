
# 📘 YAML – The ABCs of DevOps

## 1. What is YAML?

**YAML** stands for **“YAML Ain’t Markup Language”**.  
It is a **human-readable data serialization language** used to store and exchange configuration data.

YAML is **not a programming language**.  
It cannot execute logic or commands.  
Its sole purpose is to **describe data in a clean and structured format**.

---

## 2. Why YAML is the ABC of DevOps

YAML is considered the **foundation of DevOps** because almost every major DevOps tool depends on it.

YAML is widely used in:
- Kubernetes (manifests, deployments, services)
- Docker (docker-compose files)
- CI/CD pipelines (GitHub Actions, GitLab CI, Azure Pipelines)
- Cloud platforms (AWS, Azure, GCP)
- Infrastructure as Code tools

Understanding YAML makes it easier to **read, write, and debug DevOps configurations**.

---

## 3. What is Data Serialization?

**Data Serialization** is the process of converting data into a format that can be:
- Stored
- Transmitted
- Reconstructed later

- **Serialization** → Object → File / Stream  
- **Deserialization** → File / Stream → Object  

YAML is one of the formats used for data serialization, similar to JSON and XML.

---

## 4. YAML vs Programming Languages

| Feature | YAML | Programming Language |
|------|------|---------------------|
| Purpose | Store data/configuration | Execute logic |
| Can run commands | ❌ No | ✅ Yes |
| Human-readable | ✅ High | ❌ Depends |
| Typical usage | Config files | Applications |

YAML defines **what exists**, not **how it behaves**.

---

## 5. Where YAML is Used

- Configuration files
- Kubernetes manifests
- Docker Compose files
- CI/CD pipeline definitions
- Logs and cache configurations

YAML answers **what should be configured**, not **how to execute tasks**.

---

## 6. Core YAML Syntax Rules

### 6.1 Indentation
- Indentation is **mandatory**
- Only **spaces** are allowed (no tabs)
- Similar to Python

```yaml
server:
  port: 8080
