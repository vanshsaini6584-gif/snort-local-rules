# 🛡️ Snort IDS - Local Rules  

This repository contains a **custom Snort Intrusion Detection System (IDS) rules file** named `local.rules`.  
It is used to define, test, and deploy security rules for detecting suspicious or malicious network traffic.  

---

## 📁 File Included
| File | Description |
|------|-------------|
| `local.rules` | Custom Snort IDS rules file |

---

## 🚀 Usage  

1. Copy the `local.rules` file into your Snort rules directory:  
   ```
   /etc/snort/rules/
   ```
2. Update your Snort configuration (`snort.conf`) to include this rules file.  
   Example:  
   ```
   include $RULE_PATH/local.rules
   ```
3. Restart Snort and verify that the custom rules are loaded:  
   ```bash
   snort -T -c /etc/snort/snort.conf
   ```

---

## 📌 Notes  
- Modify or add rules in this file according to your network security needs.  
- Test rules in a controlled environment before deploying in production.  
- Requires Snort installed and configured properly.  

---

## 👨‍💻 Author  
Created by **Vansh Saini**  
Cybersecurity Enthusiast | IDS/IPS Rules Development  
