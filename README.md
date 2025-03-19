# 🕵️‍♂️ Wireshark Packet Analysis Assignment

Welcome students! In this assignment, you'll analyze a provided `.pcap` (packet capture) file using **Wireshark** and apply some basic network filters to understand packet flow and identify key information.

---

## 📂 Instructions

1. Open the `.pcap` file using **Wireshark**.
2. Apply the following display filters in the top filter bar:
   - `dns` → to view all Domain Name System (DNS) queries and responses.
   - `tls` → to view all Transport Layer Security (TLS/SSL) traffic.

---

## 🔍 Questions to Answer

1. **How many packets are there in total?**  
   *(Tip: Look at the packet list area or bottom status bar.)*

2. **Identify 3 packets that are potentially suspicious or problematic**  
   *(Hint: Look for the packets in red color.)*

3. **Which packet number corresponds to the request for `chatgpt.com`?**  
   *(Hint: Same as above – check DNS queries or follow TLS packets related to that domain.)*

---

## 💡 Tips

- Use **Wireshark's display filter bar** to narrow down the packets.
- Right-click on a packet and choose **"Follow > TCP Stream"** or **"Follow > TLS Stream"** for more context.
- DNS packets often appear before TLS handshakes.
- You can also filter for specific IP addresses or use `ip.addr == x.x.x.x` if needed.

---

## 📥 Submission Instructions

Please submit your answers in a text or PDF file, and include screenshots of the packets you identified for questions 2 and 3.

---

Happy packet hunting! 🐙
