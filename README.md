# Financial Accounting Process Re-Design, Analysis, & Automation

![alt text](https://github.com/sp794uk/financial_accounting_process_design_analysis_automation/blob/main/Images/banner.png "banner image")

## Keywords:
_automatictextextraction, processautomation, automation, dataanalysis, aws, python, pandas, jupyter, powerbi, tableau, dashboard, datalake, machinelearning, documenttotext._

Proof of concept implementation and end-to-end system architecture for the automated processing of multi-format invoice data from third-party vendors and customers. Unfortunately, we are unable to upload original reports and code 

## Supported Data Formats: 
PDF, HTML, Spreadsheets (direct & via API), Image, hard copy etc. formats for text.
Note: To incorporate data from hard-copy-text into our process, it must either be received in digital format (i.e. JPEG/Pdf, etc.) from the source or converted in-house to digital format.

## Challenges:
- Inconsistent Invoices: Multiple template versions (i.e. changing identifier-value pair): Must programatically fix in the implimentation using Pandas, unless a consistent format per vendor is enforced.
- Supporting both API-driven and traditional manual data collection processes: This should reduce operational load significantly. Instead of collecting files via email, a web app is proposed that allows for direct data-file upload (invoices, spreadsheets, etc.) via web. This should result in a significant reduction in operational load.

## Flow:
1. Web-based (inbound) Data Collection from Vendors and Customers.
2. Automatic Processing of Data Files (AWS *.-to-text API / Open-Source Python based *.-to-text lib).
3. Processing of hard-copy-files (i.e. invoices from vendors; digitized copy obtained from the source and uploaded or via in-house manual digitization).
4. Automatic Insights/Dashboard: Notes, Customer Invoices, and Red-flags-report highlighting mismatches between manual data and digital invoices etc.

Note: Inluded ideas for 'Human-in-the-loop' approach.

## Tools:
- *.-to-text conversion APIs: AWS (API) vs. OpenSource Python (*.-to-text) lib
- AWS: Lambda
- Python: Pandas, Jupyter Notebook, Anaconda
- Dashboard: Power BI / Tableau

## Note:
We are unable to share our sponsored-project specific design, code, and data due to confidentiality requirements (GDPR). However, please feel free to contact me to discuss your custom scenarios.
