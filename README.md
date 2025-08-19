# 📤 VBA Data Uploader

## 📌 Overview
This project is a **data uploader tool built using VBA (Visual Basic for Applications)**.  
It enables users to upload data from **Excel** into a target system such as a **database, server, or another Excel/CSV file** with a single click.

- Automates the process of transferring bulk data  
- Reduces manual work and human error  
- Flexible and customizable VBA script  

---

## 🚀 Features
- ✅ Upload structured data directly from Excel  
- ✅ Supports bulk data transfer  
- ✅ Predefined template for data formatting  
- ✅ Simple interface with one-click execution  
- ✅ Easy to modify for custom requirements  

---

## 🛠 Requirements
- Microsoft Windows  
- Microsoft Excel (with VBA enabled)  
- Target system credentials (Database / API / File Path)  

---

## 📂 Setup Instructions
1. Open **Excel VBA editor** (`Alt + F11`).  
2. Insert a **Module** and paste the provided VBA code.  
3. Configure:  
   - `Source Sheet` → Define the sheet from where data will be picked.  
   - `Target Path / Database Connection` → Define the location or DB credentials.  
   - `Mapping Rules` → Ensure Excel columns match database fields.  
4. Save the file as **Macro-Enabled Workbook** (`.xlsm`).  
5. Run the macro → Data will be uploaded automatically.  

---

## 📊 Example Workflow
1. Prepare your Excel file in the required format.  
2. Place data in the **designated columns (e.g., Name, Email, Amount, Date)**.  
3. Click the **Upload Data** button (macro).  
4. VBA script will:  
   - Read the Excel rows  
   - Connect to the target system  
   - Upload data in bulk  

---

## ⚠️ Notes
- Ensure **Excel data format matches the target system’s requirements**.  
- For databases, make sure you have **connection permissions**.  
- Always test with a small dataset before uploading large records.  

---

## 📜 License
This project is for **personal & organizational use**.  
You can freely customize the VBA script to meet your business needs.
