# Expense Agent

Expense Agent is a receipt extraction application that lets users upload receipts and get structured expense details in JSON format.

## Project Links

- Live App URL: https://receipt-analysis-agent.onrender.com/

<video src="</video>https://github.com/charangopisetty/Expense_Agent/blob/a94cb2b506bc3b123a2bd5190b2e8782c82bce70/Expense_Agent.mp4" width="320" height="240" controls>

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



## Need Help?

For implementing line-by-line item analysis, feature requests, or integration help, contact the developer:

- **gopisettycharan@gmail.com**
