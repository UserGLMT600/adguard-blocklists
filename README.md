
---

<div style="background-color: #fffbe6; border-left: 6px solid #f1c40f; padding: 15px; margin: 20px 0; border-radius: 5px;">
  <strong>⚠️ IMPORTANT NOTICE: FOR RESEARCH & PERSONAL USE ONLY</strong>
  <p>This blocklist is a highly curated aggregation of threats intended for <strong>cybersecurity professionals, researchers, and advanced users</strong> in a controlled environment (e.g., a home lab). It is not designed for general consumer or commercial use.</p>
  <p>Due to its comprehensive nature, it will likely disrupt services and break website functionality. Implementation requires expert knowledge to manage and troubleshoot.</p>
  <p>This project is provided <strong>"AS IS," WITHOUT WARRANTY OF ANY KIND</strong>. The authors assume no liability for data loss, service interruption, or any other damages resulting from its use.</p>
</div>

---

## 📜 Usage Terms

This blocklist is open-source under the MIT License, but its content is intended strictly for:

-   ✅ **Personal Use:** On your personal, private devices.
-   ✅ **Educational Use:** For learning about DNS filtering and network threats.
-   ✅ **Security Research:** In a lab environment for analysis and testing.

### ❌ Prohibited Use:

-   **Commercial Use:** Do not deploy this list on company hardware, corporate networks, or as part of a commercial product or service.
-   **Redistribution:** Do not re-host or sell this list or access to it.

---

## 📑 Table of Contents

<details>
<summary><strong>📋 Click to expand</strong></summary>

- [🔥 Known Functionality Impact](#-known-functionality-impact)
- [📊 Technical Specifications](#-technical-specifications)
- [📥 How to Use](#-how-to-use)
- [❓ FAQ](️-faq)
- [📜 Sources](️-sources)
- [📄 Full License](️-full-license)
</details>

---

## 🔥 Known Functionality Impact

This list blocks domains that are essential for certain features of popular applications. You may need to whitelist domains to restore functionality.

| Service / Platform | Known Impact | Potential Solution |
| :--- | :--- | :--- |
| **📘 META** (Facebook, Messenger, WhatsApp) | Broken avatars, help center, and video effects in WhatsApp. Restricted use of Facebook/Messenger apps. | Unblock specific META tracker domains if needed. |
| **🪟 Microsoft** (Windows, Xbox) | Windows Spotlight, Xbox Live Achievements Activity History may not work. | Unblock specific Microsoft telemetry domains if needed. |
| **🗺️ Location Services** | Incorrect regional settings, more CAPTCHAs, reduced functionality on location-based sites. | Whitelist the specific domain providing the service. |
| **💸 Affiliate Links** | Some affiliate and referral links may be blocked. | This is intentional. Whitelist if you trust the source. |

---

## 📊 Technical Specifications

| Specification | Detail |
| :--- | :--- |
| **🎯 Purpose** | Threat intelligence and privacy research. |
| **⚡ Filtering Level** | **Comprehensive** |
| **🧑‍💻 Target User** | Cybersecurity professionals, researchers, advanced home-lab users. |
| **📦 Total Unique Domains** | ~2,505,000 |
| **💾 File Size** | ~94 MB (Uncompressed) |
| **📜 Format** | AdGuard DNS Filter (`||domain.com^`) |
| **🔄 Update Frequency** | Manual, as needed. Not automated. |
| **✅ Compatibility** | AdGuard (Home, Desktop, Mobile), Pi-hole, Blocky, etc. |

---

## 📥 How to Use

### AdGuard Home
1.  Navigate to `Settings → DNS filters → Blocklists`.
2.  Click `Add blocklist`.
3.  Paste the direct link from the Quick Start section.
4.  Click `Save` and then `Apply`.

### AdGuard (Desktop, Android, iOS)
1.  Go to `Protection → Blocklists`.
2.  Tap `Add blocklist`.
3.  Paste the direct link from the Quick Start section.

---

## ❓ FAQ

**Q: A website I use is broken. What do I do?**
A: This is an expected outcome of a research-grade list. Use your client's blocking log to identify the blocked domain and add it to your "allowlist".

**Q: How often is this list updated?**
A: Manually, on an irregular basis as new threats are identified.

**Q: Can I request a domain to be added or removed?**
A: No. This is a personal research project.

---

## 📜 Sources

This list is a curated, deduplicated, and extended fusion of dozens of public sources, including:
-   EasyList/EasyPrivacy families
-   StevenBlack's hosts file
-   PhishTank
-   MalwareDomainList
-   Various threat intelligence and community feeds

---

## 📄 Full License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for full details.
