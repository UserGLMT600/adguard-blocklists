
---

## ⚠️ CRITICAL WARNING

> 🚨 **This list is EXTREMELY AGGRESSIVE and will break websites.** Use only if you are an advanced user comfortable with manual troubleshooting. **No responsibility is taken for any damage or inconvenience.**

<details>
<summary><strong>📖 Click to read the full disclaimer</strong></summary>

By using this list, you acknowledge and agree that:
*   **High Resource Usage:** This is a large file (~94MB) and will significantly increase RAM and CPU usage on routers, DNS servers, and low-power devices.
*   **Widespread Website Breakage:** Many websites will break, lose functionality, or look broken. You **will** need to manually whitelist domains to restore access.
*   **False Positives:** Legitimate services and trackers may be blocked. This list prioritizes privacy over convenience.
*   **Performance Impact:** Page load times may be slightly slower due to the sheer number of blocked elements.
*   **No Responsibility:** The author provides this list "as-is" and is **not responsible** for any damage, data loss, or inconvenience caused.

**This is NOT a "set and forget" solution. If you are not comfortable troubleshooting network issues, DO NOT USE THIS LIST.**
</details>

---

## 📑 Table of Contents

<details>
<summary><strong>📋 Click to expand</strong></summary>

- [🔥 Known Issues & Functionality Breakage](#-known-issues--functionality-breakage)
- [📊 Technical Specifications](#-technical-specifications)
- [📥 How to Use](#-how-to-use)
- [❓ FAQ](️-faq)
- [📜 Sources](️-sources)
- [📄 Disclaimer & License](️-disclaimer--license)
</details>

---

## 🔥 Known Issues & Functionality Breakage

This list blocks domains that are essential for certain features of popular applications. You may need to whitelist domains to restore functionality.

| Service / Platform | Known Issues | Potential Solution |
| :--- | :--- | :--- |
| **📘 META** (Facebook, Messenger, WhatsApp) | Broken avatars, help center, and video effects in WhatsApp. Restricted use of Facebook/Messenger apps. | Unblock specific META tracker domains if needed. |
| **🪟 Microsoft** (Windows, Xbox) | Windows Spotlight, Xbox Live Achievements Activity History may not work. | Unblock specific Microsoft telemetry domains if needed. |
| **🗺️ Location Services** | Incorrect regional settings, more CAPTCHAs, reduced functionality on location-based sites. | Whitelist the specific domain providing the service. |
| **💸 Affiliate Links** | Some affiliate and referral links may be blocked. | This is intentional. Whitelist if you trust the source. |

---

## 📊 Technical Specifications

| Specification | Detail |
| :--- | :--- |
| **🎯 Purpose** | Strictly cleans the Internet and protects your privacy. |
| **⚡ Blocking Type** | **Aggressive** |
| **🧑‍💻 Target User** | Experienced users, privacy enthusiasts, researchers. |
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
A: This is expected. Use AdGuard's blocking log to identify the blocked domain and add it to your "allowlist".

**Q: How often is this list updated?**
A: Manually, on an irregular basis.

**Q: Can I request a domain to be added or removed?**
A: No. This is a personal project.

---

## 📜 Sources

This list is a curated, deduplicated, and extended fusion of dozens of public sources, including:
-   EasyList/EasyPrivacy families
-   StevenBlack's hosts file
-   PhishTank
-   MalwareDomainList
-   Various threat intelligence and community feeds

---

## 📄 Disclaimer & License

**Disclaimer:** This project is provided for educational and personal use only. Use at your own risk.

**License:** This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for full details.
