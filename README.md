# ☁️ Cloud vs. On-Premise Services – Performance & Preference Comparison

This project is based on the IEEE research paper titled:  
**“Cloud-Based Service versus On-Premise Services: A Comparative Study at a Local Organization in Fiji”**  
(IEEE DOI: [10.1109/CSDSE59766.2023.10487723](https://ieeexplore.ieee.org/document/10487723))

---

## 📌 Objective

To analyze and compare **cloud-based services** (like Google Docs, Office 365, SharePoint) and **on-premise services** (like offline MS Office and local storage) in terms of:

- 📈 Performance (latency, sync speed, offline usability)
- 🌍 Accessibility (cross-device compatibility, collaboration)
- 🧠 User Preference (based on a real-world mini-survey)

This project is a simplified yet practical recreation of the original Fiji-based study, adapted for academic assessment (IA2).

---

## 🧪 Performance & Accessibility Test

We tested the same document-based tasks in both environments and recorded observations:

| Task                                | Cloud-Based (Google Docs / Office 365) | On-Premise (Local Word / File Explorer) |
|-------------------------------------|----------------------------------------|------------------------------------------|
| **Open File Time**                  | ~520 ms (depends on connection)        | ~180 ms                                  |
| **File Save/Sync Time**             | ~1.2 seconds (cloud sync latency)      | ~0.2 seconds (instant local write)       |
| **Mobile Accessibility**            | ✅ Yes                                  | ❌ Not accessible                         |
| **Cross-Device Sync**               | ✅ Real-time auto-sync                  | ❌ Manual transfer required               |
| **Collaboration Support**           | ✅ Co-authoring supported               | ❌ No built-in support                    |
| **Internet Dependency**             | ✅ Required                             | ❌ Not needed                             |
| **Offline Access**                  | 🔶 Partial (offline mode setup)         | ✅ Fully available                        |
| **Security & Backup**               | Cloud-managed encryption + auto-backup | Manual backup by user                    |

> 🔎 **Insight**: Cloud services offer better collaboration and mobility, while on-prem services are faster and offer more control offline.

---

## 📊 User Preference Survey (20 Participants)
> Survey is from research paper

Here are the results:

### 🔷 Preferred Platform:
- **Cloud-Based Services**: 65%
- **On-Premise Tools**: 35%

### 🔷 Why Cloud Was Preferred:
- Accessible from anywhere: 45%
- Easier collaboration: 25%
- Auto-saving & sync: 20%
- No need to carry files physically: 10%

### 🔷 Ratings:

| Rating Type       | Cloud-Based | On-Premise |
|-------------------|-------------|------------|
| Very Satisfied    | 6           | 2          |
| Satisfied         | 9           | 7          |
| Neutral           | 3           | 5          |
| Dissatisfied      | 2           | 3          |
| Very Dissatisfied | 0           | 3          |

> 📌 **Conclusion**: Most users leaned toward cloud services for accessibility and convenience. However, on-premise tools were still appreciated for speed and data control.

---

## 🛠 Technologies Used

- **Google Docs & Office 365** – Cloud service testing
- **MS Word & File Explorer** – On-prem service simulation
- **Google Forms + Sheets** – Survey creation & analysis
- **Python** – For local/backup simulation (optional)
- **Stopwatch / curl** – Response timing & latency estimation

---

## ✅ Conclusion

Our simplified implementation supports the original study's findings:
- **Cloud-based services** outperform in **collaboration, mobility, and flexibility**, especially for remote or hybrid work.
- **On-premise services** remain relevant where **speed, offline access, or control over data** is a priority.
- A **hybrid model** is the most balanced solution in regions with limited infrastructure or mixed workloads.

---

### 👥 Authors

- **Nikhil Patil** (16010122136)  
- **Meetesh Nagrecha** (16010122123)

**Mentor**: Prof. Zaheed Shaikh  
**Institution**: K. J. Somaiya College of Engineering

---

### 📄 License

This repository is part of an academic submission and is intended for educational purposes only.

