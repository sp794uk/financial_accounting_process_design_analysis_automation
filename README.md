Proof of concept implementation and end-to-end system architecture for automated processing of multi-format-invoice data from 3rd party vendors and customers.

# Supported Data Formats: 
PDF, HTML, Spreadsheets (direct or via API), Image, hard copy etc. formats for text.
Note: To incorporate data from hard-copy-text in our process, either it should be received in digital format (i.e. JPEG/Pdf etc.) from the source or otherwise be converted in-house to digital format.

# Challenges:
- Inconsistent Invoices: Multiple template versions (i.e. changing identifier-value pair): Must programatically fix in the implimentation using Pandas unless consistent format per vendor is enforced.
- Supporting both API-driven and traditional manual data collection processes: web app supporting direct data-file upload (Invoices, spreadsheets etc.) via web rather than collecting files over email. This should significantly reduce operational load.

# Flow:
1. Web-based (inbound) Data Collection from Vendors and Customers.
2. Automatic Processing of Data Files (AWS *.-to-text API / Open-Source Python based *.-to-text lib).
3. Processing of hard-copy-files (i.e. invoices from vendors; digitized copy obtained from the source and uploaded or via in-house manual digitization).
4. Automatic Insights/Dashboard: with click of a button (on demand) Notes, Customer Invoices, and Red-flags-report highlighting mismatches between manual data and digital invoices etc. can be generated by the concerned operator.

Note: Steps 4 & 5 incorporates 'Human-in-the-loop' approach.

# Tools:
- *.-to-text conversion APIs: AWS (API) vs. OpenSource Python (*.-to-text) lib
- AWS: Lambda
- Python: Pandas, Jupyter Notebook
- Dashboard: Power BI / Tableau


P.S. Above is a general-purose representation of the overall solution. Due to confidentiality agreement (GDPR), we are unable to share our sponsored project-specific drawings and data. However, please feel to connect at sp794uk@gmail.com to disucss your custom scenarios.