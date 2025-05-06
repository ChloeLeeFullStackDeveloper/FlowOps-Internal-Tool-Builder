
**FlowOps** is a custom-built internal workflow platform that automates task submissions, routing, notifications, and reporting using Google Apps Script, Google Workspace, Firebase, and optional low-code tools like Glide or Retool.

---

## 🚀 Features

- Submit tasks via Google Forms or Google Sheets
- Automatically assign/reroute tasks based on department/team using Google Apps Script
- Send real-time notifications via Gmail or Slack (optional API webhook)
- Store task logs in Firebase for persistent, scalable access
- Generate dynamic reports in Google Sheets
- Optional: Admin dashboard built with Glide or Retool
- Optional: Workflow automation via Zapier, n8n, or Make (Integromat)

---

## 🛠️ Tech Stack

| Component        | Technology Used |
|------------------|------------------|
| Scripting        | Google Apps Script (`main.gs`) |
| Data Storage     | Firebase Realtime DB or Firestore |
| UI Input         | Google Forms / Google Sheets |
| Notifications    | Gmail API / Slack Webhook |
| Dashboard (opt)  | Glide or Retool |
| Automation (opt) | Zapier / n8n / Make |
| APIs             | REST APIs, JSON |

---

## 📂 Project Structure
```
FlowOps/
├── README.md
├── apps-script/
│ └── main.gs # Core task logic
├── firebase/
│ ├── config.json # Firebase settings
│ └── functions.js # (Optional) Firebase cloud functions
├── reports/
│ └── report-template.xlsx
├── dashboard/ # (Optional)
│ └── dashboard-design.md
└── docs/
└── setup-guide.md # Step-by-step install & deploy
```
---

## 📚 Learning Goals

- Automate internal processes using Google Workspace tools
- Integrate Apps Script with Firebase and external APIs
- Explore low-code dashboards for internal visibility
- Build scalable, real-world digital workflows

---

## ✅ Project Status

- [x] Planning
- [x] Google Form & Sheet Setup
- [ ] Apps Script Task Automation
- [ ] Firebase Integration
- [ ] Slack/Gmail Notifications
- [ ] Dashboard Prototype
- [ ] Deployment & Documentation

---

## 🧠 How It Helps Companies

FlowOps helps small to mid-sized teams manage internal tasks more efficiently by replacing ad hoc emails or spreadsheet-based routing with automated, centralized workflows. It ensures consistency, traceability, and scalability.

---

## 📸 Screenshots (Coming Soon)

---

## 👤 Author

Eunsuk Lee  
[GitHub Profile](https://github.com/ChloeLeeFullStackDeveloper)

---

## 📄 License

MIT License
