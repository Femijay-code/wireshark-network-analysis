# Wireshark DNS AAAA Query Analysis

This is the second project in my Wireshark network traffic analysis series. It focuses on inspecting DNS queries, particularly AAAA (IPv6) requests, using packet capture and protocol-level examination.

---

## 🔍 Project Overview

- Captured live DNS traffic using Wireshark
- Applied filters to isolate DNS AAAA queries
- Analyzed:
  - The structure of DNS requests and responses
  - The role of AAAA queries in IPv6 resolution
  - Packet timing and response behavior

---

## 📁 Files Included

- `wireshark-dns-aaaa-analysis.docx` – Step-by-step documentation of the DNS project
- `dns-capture.pcapng` – Packet capture file
- `screenshots/` – Highlighted DNS queries and responses

---

## ✅ Key Takeaways

- Demonstrated knowledge of DNS protocol behavior at the packet level
- Gained insight into how AAAA records function in IPv6 address resolution
- Practiced isolating and interpreting DNS traffic using Wireshark filters (`dns`, `dns.qry.type == 28`)

---

## 📌 Project Position

This is Project 2 of the Wireshark series. It follows the HTTP traffic analysis and precedes the TCP 3-Way Handshake deep dive.
