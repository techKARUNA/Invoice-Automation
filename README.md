# Invoice Analytics Dashboard

A professional Flask + Pandas based dashboard for analyzing invoice data.  
This project extracts invoice details (from CSV/PDF), processes them using **Pandas**, and provides an interactive dashboard built with **Chart.js** and **Bootstrap**.  

## 🔑 Key Features

### 📊 Financial Overview
- **Total Revenue**: Total earnings from all invoices  
- **Total GST Collected**: Total GST collected across all transactions  
- **Total Invoices**: Number of invoices uploaded so far  
- **Average Invoice Value**: Average value of all invoices  

### 🎛 Interactive Filters
- **Date Filter**: View data for a specific date or date range  
- **Item Filter**: Analyze performance of specific products  
- **Customer & City Filter**: Identify top customers and cities contributing to business  
- **Clear Filters Button**: Reset all filters with a single click  

### 📈 Dynamic Visualizations
- **Top Selling Items**: Bar charts highlighting items with highest sales or revenue  
- **Sales & GST Trends**: Line charts showing sales and GST collection trends over time  
- **Sales Distribution**: Pie charts showing distribution of sales across customers and cities  

  ## 🚀 Tech Stack
- **Backend:** Flask, Pandas  
- **Frontend:** Bootstrap, Chart.js  
- **Data:** CSV / Extracted PDFs  

## 📊 Example Use Case
This dashboard is ideal for businesses that want to:
- Track invoices efficiently  
- Monitor sales trends  
- Identify top-performing customers and products  
- Simplify financial reporting  

## ⚡ How to Run

If you don’t have Git installed, you can run the project using the ZIP download method:

1. **Download the Repository**  
   - Go to your GitHub repository page  
   - Click on the **Code** button → **Download ZIP**

2. **Extract Files**  
   - Unzip the downloaded file into a folder on your computer

3. **Open Terminal**  
   - Open **Command Prompt** or **PowerShell** in the extracted project folder

4. **Create and Activate Virtual Environment**

   ```bash
   python -m venv venv
   venv\Scripts\activate
   Install Dependencies : pip install Flask pandas pdfplumber
   Run the Flask App    : python app.py

  📸 Screenshots
   ### Dashboard Overview
      ![Dashboard Screenshot](https://github.com/user-attachments/assets/b363ecd5-63b8-45b4-9542-f3c4cf5b16d5)
   ### Charts & Insights
      ![Dashboard Screenshot](https://github.com/user-attachments/assets/2db44703-3cf1-44f1-b7dc-f65356462a11)
      ![Dashboard Screenshot](https://github.com/user-attachments/assets/299cfe67-977e-465e-9e65-9dda69c0101e)

