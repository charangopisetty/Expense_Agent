# Expense Agent

Expense Agent is a receipt extraction application that lets users upload receipts and get structured expense details in JSON format.

## Project Links

- Repository URL: [https://github.com/your-username/expense-agent](https://github.com/your-username/expense-agent)
- Live App URL: [https://your-app-name.onrender.com](https://your-app-name.onrender.com)

> Update the links above with your actual GitHub repository and deployed URL.

## What This App Extracts

From uploaded receipts (PDF, PNG, JPEG), the app extracts:

- Vendor name
- Store ID (if present)
- Phone number
- Address (street, city, state, zip)
- Transaction date and time
- Tax amount
- Total amount

## How Users Can Extract Receipt Details

1. Open the live app URL.
2. Upload a receipt file (`.pdf`, `.png`, `.jpg`, `.jpeg`).
3. Review the receipt preview shown in the UI.
4. Click **Analyze**.
5. View extracted JSON details on the right panel.

## Upload and Processing Rules

- Supported file types: PDF, PNG, JPG, JPEG
- Max upload size: 10MB
- Input is compressed to <=2MB before model analysis
- PDF processing uses the first page for extraction

## Local Setup (Optional)

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python app.py
```

## Need Help?

For support, feature requests, or integration help, contact the developer:

- **gopisettycharan@gmail.com**
