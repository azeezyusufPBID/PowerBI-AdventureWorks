cat << 'EOF' > README.md

\# PowerBI-AdventureWorks

AdventureWorks Power BI project in `.pbip` format, version-controlled with Git.



\## 📂 Project Structure

\- \*\*PowerBIReports/\*\* → Report layouts \& semantic model

\- \*\*SQLScripts/\*\* → Source queries (to be added later)

\- \*\*DAX/\*\* → Measures, KPIs, calculations

\- \*\*Docs/\*\* → Project documentation



\## 🚀 Workflow

1\. Develop locally in Power BI Desktop (save as `.pbip`).

2\. Commit \& push changes in Git.

3\. Use branches for features:

&nbsp;  - `main` → production-ready

&nbsp;  - `dev` → development

&nbsp;  - `feature/\*` → per dashboard, dataset, or KPI



\## 🛠 Tools

\- \*\*Power BI Desktop\*\* (with .pbip enabled)

\- \*\*Git \& GitHub\*\* for version control

\- Optional: \*\*PowerShell\*\* for automation (refresh, deploy)



\## ✅ Best Practice

Keep `.pbix` out of Git, track only `.pbip`, JSON, and TMDL files for collaboration \& clean version control.

EOF



