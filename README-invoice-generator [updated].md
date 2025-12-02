# Updated Invoice Generator - Matching Your PDF Style

## ✨ What's Changed

### Layout Updates
✅ **"BILLED TO:"** instead of "FROM" (left column)
✅ **"PAY TO:"** instead of "BILL TO" (right column)
✅ **Invoice metadata at top**: Invoice ID, Invoice Date, Due Date, Payment Terms
✅ **PAYMENT DETAILS section** with Bank, Account Name, Account Number
✅ **Column names changed**: DESCRIPTION, HOURS, RATE, AMOUNT
✅ **IDR currency format** (Indonesian Rupiah)
✅ **Signature line** at bottom right
✅ **Professional styling** matching your PDF

### Features Kept
✅ Auto-fill today's date (editable)
✅ Auto-fill due date to 30 days (editable)
✅ Blank default fields for privacy
✅ Add/remove items dynamically
✅ Automatic calculations
✅ Print to PDF
✅ Download as HTML

## 🚀 How to Update Your Live Site

### Option 1: Replace via GitHub Website (Easiest)

1. Download the new file: `index.html`
2. Go to: https://github.com/NRDL614/Invoice-Generator-2
3. Click on `index.html` (the current file)
4. Click the **trash icon** to delete it
5. Commit the deletion
6. Click **"Add file"** → **"Upload files"**
7. Upload the new `index.html` file
8. Commit changes
9. Wait 1-2 minutes
10. Visit: https://nrdl614.github.io/Invoice-Generator-2/

### Option 2: Edit Directly on GitHub

1. Go to: https://github.com/NRDL614/Invoice-Generator-2
2. Click on `index.html`
3. Click the **pencil icon** (Edit this file)
4. Select all (Ctrl+A / Cmd+A) and delete
5. Copy the entire content from the new `index.html` file
6. Paste it
7. Commit changes: "Updated to match PDF style"
8. Wait 1-2 minutes
9. Refresh: https://nrdl614.github.io/Invoice-Generator-2/

## 📋 New Invoice Structure Matches Your PDF

```
Invoice
├── Invoice ID: INV-2025-001
├── Invoice Date: [auto-filled]
├── Due Date: [auto-filled +30 days]
└── Payment Terms: 30 days

BILLED TO:                    PAY TO:
[Client Company]              [Your Name/Business]
[Client Address]              [Your Address]
                              [Email & Phone]

PAYMENT DETAILS:
Bank: [Your Bank]
Account Name: [Your Name]
Account Number: [Your Account]

DESCRIPTION          HOURS    RATE           AMOUNT
Service 1            9.03     150.000,00/hr  1.354.500,00
Service 2            7.97     150.000,00/hr  1.195.500,00

                              SUBTOTAL       2.550.000,00 IDR
                              TOTAL          2.550.000,00 IDR

Notes: Details of work and time entries are attached in separate file

                              _______________
                              [Your Name]
```

## 💡 Tips

- The signature name auto-updates from the first line of "PAY TO"
- Currency is formatted as Indonesian Rupiah (IDR)
- All fields start blank for privacy
- The "HOURS" column replaces "Quantity" to match your PDF

---

Your invoice generator is ready to match your professional PDF style! 🎉
