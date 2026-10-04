# 🔐 URLens

### Reveal the Destination Before Access.

URLens is an **offline-first URL security analyzer** designed to help users identify suspicious and potentially dangerous links before accessing them.

In today's digital world, malicious links can appear in messages, emails, social media posts, websites, and QR codes. URLens provides users with a simple way to inspect a link, understand its risk, and make a safer decision before proceeding.

---

## 🎯 What is URLens?

URLens analyzes the structure and characteristics of a URL using a **local rule-based security engine**.

Instead of simply telling users whether a link is safe or unsafe, URLens provides an **explainable security assessment** by identifying suspicious characteristics within the URL.

The system evaluates factors such as HTTPS usage, IP-based URLs, suspicious keywords, unusual characters, deep subdomains, URL length, embedded credentials, and other potentially risky patterns.

Based on the detected indicators, URLens generates a clear risk score and classifies the URL as:

**🟢 SAFE · 🟡 LOW RISK · 🟠 RISK · 🔴 HIGH RISK**

---

## 📷 QR Code Security

QR codes are increasingly used for payments, authentication, events, websites, and digital services. However, users cannot easily see the destination hidden inside a QR code before opening it.

URLens addresses this by allowing users to **upload a QR code and extract the URL locally**.

The extracted URL is then passed through the same security analysis engine, allowing users to understand the potential risk before accessing the destination.

This makes URLens useful not only for traditional URLs but also for **QR-based links**.

---

## 🛡️ Privacy & Offline-First Design

Privacy is one of the core principles of URLens.

The current prototype performs its core URL analysis locally using HTML, CSS, and JavaScript. It does not require a backend server, database, or external security API for the basic analysis.

This offline-first approach provides:

- **Privacy** — URLs can be analyzed locally.
- **Speed** — No dependency on remote scanning services.
- **Accessibility** — The analyzer can run locally.
- **Lightweight operation** — No backend infrastructure is required for the prototype.

> **Your URL. Your device. Your analysis.**

---

## 🧠 Explainable Security

One of the key goals of URLens is to make cybersecurity understandable to everyone.

Instead of presenting users with a complicated technical warning, URLens explains the indicators detected in the URL.

For example, if a URL contains suspicious keywords, an unusual domain structure, or other risky characteristics, the user can see those reasons along with the overall risk score.

This approach helps users develop better **cybersecurity awareness and safer browsing habits**.

---

## ⚡ Why URLens?

Traditional security tools may depend heavily on online databases or external scanning services.

URLens takes a different approach by starting with **local URL analysis**.

The project focuses on four important principles:

**Privacy First**  
Keep core analysis local whenever possible.

**Security Before Access**  
Help users evaluate a link before interacting with its destination.

**Explainable Detection**  
Tell users why a URL appears suspicious.

**Simple User Experience**  
Make security analysis understandable even for non-technical users.

---

## 🔍 Security Indicators

URLens currently analyzes multiple characteristics of a URL, including:

- HTTPS and protocol information
- IP-based URLs
- Suspicious keywords
- Domain and subdomain structure
- Deep subdomains
- Excessively long URLs
- Unusual special characters
- Embedded usernames or passwords
- Suspicious URL patterns
- Other predefined security rules

These indicators are combined to generate a risk score and security classification.

---

## 📊 Risk Classification

| Risk Score | Verdict |
|------------|---------|
| 🟢 0–20 | **SAFE** |
| 🟡 21–40 | **LOW RISK** |
| 🟠 41–70 | **RISK** |
| 🔴 71–100 | **HIGH RISK** |

The score represents the presence of suspicious indicators detected by the current rule-based engine.

> **Note:** URLens is an analysis and awareness tool. A risk score does not guarantee that a website is malicious or completely safe.

---

## 🚀 Current Implementation

The current version of URLens is a working local prototype built using **HTML, CSS, and JavaScript**.

The following features have been successfully implemented:

- ✅ Offline URL analysis
- ✅ URL structure analysis
- ✅ Rule-based security engine
- ✅ Risk scoring
- ✅ Explainable security results
- ✅ QR code decoding
- ✅ Local QR-to-URL extraction
- ✅ Security analysis of extracted QR URLs
- ✅ Offline-first operation

The current prototype demonstrates the core security engine that will be integrated into the next stage of the project.

---

## 🔮 Future Scope

The next major stage of URLens is the development of a **Chrome Extension**.

The existing offline security engine will be integrated directly into the browser so that users can receive security analysis when interacting with links.

Future versions of URLens can provide **pre-access protection**, allowing users to receive a warning before navigating to a potentially suspicious destination.

The project can further evolve with:

- 🌐 Chrome Extension integration
- 🛡️ Real-time pre-access URL screening
- 🤖 AI-assisted phishing detection
- 🔎 Advanced domain and brand impersonation detection
- 🌍 Optional threat intelligence integration
- 📊 Security analytics and reporting
- 🏫 Institutional deployment for colleges and organizations
- 🏢 Enterprise-level security management

The long-term vision is to transform URLens from a standalone URL analyzer into a **lightweight browser security layer for everyday users**.

---

## 🎯 Our Vision

Most users ask:

> **"Is this website safe?"**

URLens aims to help them ask a better question:

> **"What does this URL tell me before I access it?"**

Our vision is to make safer browsing simple:

### **Check. Understand. Decide. Access.**

---

## 👥 Team

### **404 Team Not Found**

**Domain:** Cybersecurity  
**Project:** URLens  
**Tagline:** *Reveal the Destination Before Access.*

---

### **Behind the Team**

**Team Lead** Hari Vignesh L  
**Frontend** Jayshri J  
**Chrome Extension** Jeeva T  
**Testing** Jithisha G 

---

## ⭐ Project

URLens is being developed as a **privacy-focused cybersecurity solution** with an offline-first approach and a clear path toward browser-level protection.

> 🔐 **URLens — Reveal the Destination Before Access.**
