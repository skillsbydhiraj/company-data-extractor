# 🚀 Company Data Extractor

A Python automation tool built using Selenium and OpenPyXL to automatically extract company information from websites.

## 🔥 Features
- Extract Address
- Extract Phone Numbers
- Extract Emails
- Extract Website URLs
- Extract LinkedIn Profiles

## 🛠 Technologies Used
- Python
- Selenium
- OpenPyXL

## 📌 Use Case
If you have a list of company or business website links, this tool can automatically extract contact and business details in bulk.

Useful for:
- Lead Generation
- Business Research
- Data Collection
- Market Research
- Automation Tasks

## ▶ How It Works
1. Add company links in Excel
2. Run the Python script
3. Tool visits each website automatically
4. Extracts business information
5. Saves data into output Excel sheet

## 💡 Skills Demonstrated
- Web Scraping
- Browser Automation
- Excel Automation
- Data Extraction

- **Added Excel setup instructions**
- ## 📄 Excel File Setup Before Running

Before running the Python script, prepare the Excel file properly.

### ✅ Step 1: Create Sheet1
Create a sheet named:

```text
Sheet1
```

### ✅ Step 2: Add Header
In cell A1 enter:

```text
Hyperlinks
```

### ✅ Step 3: Add Website Links
Starting from cell A2, paste company or website links.

Example:

```text
A1 → Hyperlinks
A2 → https://example.com
A3 → https://example2.com
```

### ✅ Step 4: Create Sheet2
Create another sheet named:

```text
Sheet2
```

No need to add headers or data inside Sheet2.  
Keep Sheet2 completely blank.

The Python script will automatically create headers and save extracted data into Sheet2.

### ✅ Step 5: Save and Close Excel File
Before running the Python script:
- Save the Excel file
- Close the Excel file completely

⚠️ Important:
If the Excel file is open while running the script, the code may show errors or fail to save data.

## ▶ Final Workflow

1. Add links in Sheet1
2. Keep "Hyperlinks" in A1
3. Create blank Sheet2
4. Save and close Excel file
5. Run Python script
6. Extracted data will appear in Sheet2
- Selenium Automation

## 👨‍💻 Developed By
SkillsByDhiraj
