# Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query
📌 Project Summary

Developed an end-to-end automation solution that extracts Excel attachments from Gmail using Google Apps Script, exposes the data through a Web API, and imports it into Microsoft Excel using Power Query. The solution automatically consolidates multiple Excel attachments into a single cleaned dataset, eliminating manual downloads and repetitive data preparation.

* Power Query data cleaning Image  <img width="1917" height="1077" alt="Power Query data cleaning" src="https://github.com/user-attachments/assets/4f551aa2-1250-40cf-bf29-f49c0e012f37" />

* App Script Code Image  <img width="1912" height="877" alt="App Script Code" src="https://github.com/user-attachments/assets/2bbd509a-959c-4037-bd69-0aa38f02afaf" />


* Received Gmail Image  <img width="1912" height="660" alt="Received Gmail" src="https://github.com/user-attachments/assets/823712cf-9d84-49b6-a58c-867b5e72b61c" />

* Data From Gmail to Excel Image  <img width="1900" height="1072" alt="Data From Gmail to Excel" src="https://github.com/user-attachments/assets/07917100-ae7d-4c9e-9072-e8ee33dafd2d" />


Data_Files 
1 GmailToExcel = <a href="[https://github.com/spvertex11-data/Quick_Bite_Food_Delivery/blob/main/Quick_Bite.xlsx](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/GmailToexcel.xlsx)"</a>

2 Files A = <a href="[[https://github.com/spvertex11-data/Quick_Bite_Food_Delivery/blob/main/Quick_Bite.xlsx](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/GmailToexcel.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/CHENNAI.xlsx)"</a>

B = <a href="[[[https://github.com/spvertex11-data/Quick_Bite_Food_Delivery/blob/main/Quick_Bite.xlsx](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/GmailToexcel.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/CHENNAI.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/MUMBAI.xlsx)"</a>

C = <a href="[[[https://github.com/spvertex11-data/Quick_Bite_Food_Delivery/blob/main/Quick_Bite.xlsx](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/GmailToexcel.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/CHENNAI.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/NAGPUR.xlsx)"</a>

D = <a href="[[[https://github.com/spvertex11-data/Quick_Bite_Food_Delivery/blob/main/Quick_Bite.xlsx](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/GmailToexcel.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/CHENNAI.xlsx)](https://github.com/spvertex11-data/Gmail-Attachment-Automation-using-Google-Apps-Script-and-Power-Query/blob/main/Narnaul.xlsx)"</a>



🚀 Key Highlights
Connected Gmail with Microsoft Excel Power Query using Google Apps Script.
Developed a Web API that retrieves Gmail email metadata and Excel attachments in JSON format.
Encoded Excel attachments as Base64 in Google Apps Script and decoded them back to Binary in Power Query.
Dynamically imported Excel attachments directly from Gmail without manual downloads.
Used Excel.Workbook() in Power Query to extract data from multiple Excel files automatically.
Combined (Appended) multiple Excel attachments into a single consolidated dataset.
Performed data cleaning, transformation, and type conversion using Power Query.
Enabled one-click refresh, allowing Excel to automatically import newly received Gmail attachments whenever Power Query is refreshed.
Eliminated manual copy-paste, file downloads, and repetitive data preparation tasks.
Built a reusable ETL pipeline that can be adapted for automated business reporting.

⚙️ Project Workflow
Daily Excel reports are received in Gmail.
Google Apps Script reads emails and extracts attachment details.
Excel attachments are converted into Base64 format.
Apps Script publishes the data through a Web App (JSON API).
Power Query connects to the API endpoint.
Base64 data is converted back into Binary.
Power Query dynamically opens each Excel attachment.
Data from all attachments is appended into a single table.
Data is cleaned, transformed, and loaded into Excel.
New emails are automatically included after refreshing the Power Query.

🛠️ Technologies Used
Microsoft Excel
Power Query 
Google Apps Script
Gmail API (GmailApp Service)
Web API

💡 Skills Demonstrated
ETL (Extract, Transform, Load)
Data Automation
Data Integration
Power Query
Google Apps Script
Append Queries
Excel.Workbook()
Data Cleaning & Transformation
Excel Automation
Business Process Automation

🎯 Business Impact
Reduced manual effort required to download and consolidate Excel reports.
Automated the complete data collection and preparation process.
Improved reporting efficiency with a refresh-based workflow.
Built a scalable solution that automatically processes new email attachments without modifying the Power Query.


