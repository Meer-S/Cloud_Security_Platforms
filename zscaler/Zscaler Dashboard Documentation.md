# Zscaler Dashboard Documentation

## 📊 Overview
The Zscaler Dashboard provides real-time visibility into traffic, threats, policy enforcement, and user activity.  
This document outlines available widgets, configuration steps, and lab practice exercises.

---

## 🧩 Widgets

| Widget Name              | Purpose                                      | Configuration Steps | Example Use Case |
|--------------------------|----------------------------------------------|---------------------|------------------|
| Traffic Overview         | Shows total traffic volume (allowed/blocked) | Add widget → Filter by time range | Baseline monitoring |
| Top Blocked Categories   | Displays most frequently blocked categories  | Add widget → Filter by user group | Identify risky behavior |
| Threats Detected         | Malware, phishing, botnet activity           | Add widget → Severity filter | Track critical threats |
| Top Users by Traffic     | Identifies heavy bandwidth consumers         | Add widget → Filter by department | Troubleshoot performance |
| Top Applications Used    | SaaS/cloud services accessed                 | Add widget → Filter by location | Validate app adoption |
| Policy Hits              | Shows rules triggered most often             | Add widget → Filter by rule set | Tune policies |
| Bandwidth Control        | Displays shaping/throttling applied          | Add widget → QoS filter | Confirm collaboration app QoS |
| SSL Inspection Statistics| Inspected vs bypassed traffic                | Add widget → Filter by user group | Verify inspection coverage |

---

## ⚙️ Configuration Steps

1. **Add a Widget**  
   - Go to *Customize Dashboard → Add Widget*.  
   - Select from traffic, security, policy, or user categories.

2. **Resize/Move Widgets**  
   - Drag to reposition.  
   - Resize for visibility.

3. **Apply Filters**  
   - Time range, location, department, user group.  
   - Example: Filter for Bliss/Vistar groups during M&A integration.

4. **Export Data**  
   - Export widget data to CSV/PDF for reporting.  
   - Use exports as evidence for audits or client approval.

---

## 🧪 Lab Practice

### Lab Setup
- **Create Test Groups**: Add “M&A Test Users” in Zscaler.  
- **Generate Traffic**: Access flagged domains/apps from test accounts.  
- **Customize Dashboard**: Add widgets for traffic, policy hits, threats.  
- **Filter by Group**: Apply filters for “M&A Test Users.”  

### Validation
- Blocked sites appear in **Top Blocked Categories**.  
- Allowed apps show in **Top Applications Used**.  
- Rules triggered appear in **Policy Hits**.  

### Export
- Export dashboard data to CSV/PDF.  
- Attach exports to integration approval documents.

---

## ✅ Key Takeaways
- Dashboard is **widget-driven** and customizable.  
- Tailor widgets to **traffic visibility, threat monitoring, policy validation, or user adoption**.  
- Lab practice ensures **hands-on validation** before client rollout.  

---

## 📂 Next Steps
- Extend this documentation to:  
  - **Analyzer Tab** (detailed traffic and threat analysis)  
  - **Policy Tab** (rule configuration and enforcement)  
  - **Administrator Tab** (user/group management, authentication)  
  - **ZCC Tab** (Zscaler Client Connector visibility)

