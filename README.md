# Hi, I'm Fidan 👋

**Data Analyst & System Specialist** · Finance systems, dashboards and internal tools

> ⚠️ The projects below are shown as **overviews only**.
> The real source code is **private** because it contains confidential information.

---

## 📊 [Financial Dashboard](https://github.com/fidanberisha-png/financial-dashboard-overview)

**Why:** Give the finance team a real-time view of invoices and revenue, without manual exports from the accounting system.

```mermaid
flowchart LR
    A[Accounting system] -->|OAuth 2.0| B[Server]
    B --> C[Fetch invoices]
    C --> D[Calculate KPIs]
    D --> E[Live dashboard]
```

**Tech:** JavaScript · Node.js · OAuth 2.0 · REST API

---

## 🗓️ [HR Leave Portal](https://github.com/fidanberisha-png/hr-leave-portal-overview)

**Why:** Replace leave and sick-leave requests sent by email or spreadsheet with one simple portal.

```mermaid
flowchart LR
    A[Employee submits request] --> B[Approver reviews]
    B -->|Approve / Reject| C[Email notification]
    C --> D[Allowance dashboard updated]
    D -.->|Nightly| E[Automatic backup]
```

**Tech:** Next.js · Prisma · PostgreSQL · Nodemailer · GitHub Actions

---

## 🎫 [IT Ticket Portal](https://github.com/fidanberisha-png/it-ticket-portal-overview)

**Why:** Let colleagues open IT tickets from a simple web page, without needing an account in the ticketing workspace.

```mermaid
flowchart LR
    A[Web form] --> B[Server validation & spam protection]
    B --> C[Ticket saved to Notion database]
    C --> D[Existing automation]
    D --> E[Email + Slack notification]
```

**Tech:** Node.js · Notion API

---

## 🛠️ [Support Ticket Tracker](https://github.com/fidanberisha-png/support-ticket-tracker-overview)

**Why:** Track support tickets opened with an external software vendor and measure how fast they respond and resolve them.

```mermaid
flowchart LR
    A[Add / edit tickets] --> B[Live metrics]
    B --> C[Response & resolution time]
    C --> D[Excel report with live formulas]
```

**Tech:** Node.js · HTML/CSS · Excel export

---

## 📁 [Document Access Portal](https://github.com/fidanberisha-png/document-access-portal-overview)

**Why:** Share confirmation PDFs securely, so each person only sees the documents they are allowed to see.

```mermaid
flowchart LR
    A[Admin invites user] --> B[User sets own password]
    B --> C[Admin grants access]
    C --> D[Server checks access]
    D --> E[View / download PDF]
```

**Tech:** Node.js · Server-side sessions

---

**Tools I work with:** Business Central · Power BI · Tableau · Notion · JavaScript · SQL

---

### 🤖 How these projects were built

All projects were built through **vibe coding**. I came up with the ideas, wrote the prompts, defined the parameters and requirements, and tested each project until it worked correctly. The code itself was written with the help of AI (Claude).
