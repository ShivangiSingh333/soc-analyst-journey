# 🧠 OSI Model - A Simple Explanation with Real Life Examples (for SOC Analyst Beginners)

The **OSI Model (Open Systems Interconnection)** is like a step-by-step guide that explains **how data travels** from one device to another over a network — like from your phone to a website.

Think of it like **sending a letter**: You write it, pack it, address it, send it via post, and it finally reaches your friend. Each step is like one layer of OSI.

---

## 📚 The 7 Layers of OSI Model:

| Layer | Name          | What it Does                                     | Real-Life Example                               |
|-------|---------------|--------------------------------------------------|--------------------------------------------------|
| 7     | Application   | Shows the final data to the user                 | Using Chrome to open Google                     |
| 6     | Presentation  | Converts data (like encryption or formatting)    | Watching a YouTube video (audio/video format)   |
| 5     | Session       | Manages connection between two devices           | WhatsApp call session                           |
| 4     | Transport     | Breaks data into smaller parts & delivers safely | Sending a parcel with tracking                  |
| 3     | Network       | Chooses best path to send data                   | Google Maps deciding best route                 |
| 2     | Data Link     | Adds device addresses to data                    | Like writing sender & receiver address on post  |
| 1     | Physical      | Sends raw data over cables or Wi-Fi              | Fiber cable, Wi-Fi signal                       |

---

## 🔁 OSI vs TCP/IP Model (Simple Comparison):

TCP/IP is used in the real world, but OSI helps us **understand the process** better.

| OSI Model         | TCP/IP Model         |
|-------------------|----------------------|
| Application       | Application          |
| Presentation      | ↘ (combined)         |
| Session           | ↘                   |
| Transport         | Transport            |
| Network           | Internet             |
| Data Link         | Network Interface    |
| Physical          | ↘ (combined)         |

---

## 👨‍💻 Why Should SOC Analysts Learn OSI?

As a **SOC Analyst**, you monitor and protect networks. Knowing OSI helps you:

- Understand where and how cyber attacks happen  
- Analyze network traffic layer-by-layer  
- Investigate logs and detect suspicious activity  
- Respond quickly and correctly to incidents

---
(SHORT NOTE )
# OSI Model

## Layers:
1. **Physical** – Cables, Switches
2. **Data Link** – MAC, Ethernet
3. **Network** – IP, Routers
4. **Transport** – TCP, UDP
5. **Session** – API Calls, Session Mngmt
6. **Presentation** – SSL/TLS
7. **Application** – HTTP, DNS

## Comparison with TCP/IP:
- Application (TCP/IP) = Application + Presentation + Session (OSI)

  # 🌐 Common Protocols & Ports Explained for SOC Analysts

In networking, **protocols** are like the rules that computers follow to communicate with each other. **Ports** are the doorways through which these communications happen. 

Here’s a breakdown of some of the most commonly used protocols and the ports they use, along with **real-world examples** to help understand them better.

---

## 📚 Common Protocols & Ports:

| Protocol | Port | Use Case                                       | Real-Life Example                               |
|----------|------|-----------------------------------------------|-------------------------------------------------|
| HTTP     | 80   | Web browsing (non-secure)                      | Opening a website without encryption            |
| HTTPS    | 443  | Secure web browsing (encrypted)                | Online shopping or bank transactions            |
| FTP      | 21   | File Transfer (sending or receiving files)     | Uploading files to a server or website          |
| SSH      | 22   | Secure remote login                            | Logging into a server securely using terminal   |
| DNS      | 53   | Domain Name System (name resolution)           | Translating 'google.com' to an IP address       |

---

## 👨‍💻 Why SOC Analysts Should Know This:

- **Monitoring**: Knowing which ports/protocols are active on a network helps identify **suspicious activity**.
- **Incident Response**: Helps in recognizing if malicious traffic is targeting **specific protocols/ports**.
- **Forensics**: Understanding which port is used by what service can aid in **network traffic analysis** and investigation.




✅ Made with 💻 by [Shivangi Kumari]  
📁 Part of: SOC Analyst Learning Journey  
🔗 GitHub Repo: [https://github.com/Choti62/soc-analyst-journey/new/main] ab isko ek sath github dalna kya rakhun file ka name in networking 
