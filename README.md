# CleanStmt — AI-Powered Financial Document Converter

> **Convert bank statements, invoices, and receipts to clean Excel, CSV, and accounting formats in seconds.**

[![Website](https://img.shields.io/badge/Website-cleanstmt.com-blue)](https://www.cleanstmt.com)
[![Free Tier](https://img.shields.io/badge/Pricing-Free%20Tier%20Available-green)](https://www.cleanstmt.com)
[![AI Powered](https://img.shields.io/badge/AI-Claude%20Vision-purple)](https://www.cleanstmt.com)

---

## 🎯 What is CleanStmt?

CleanStmt is an **AI-powered financial document converter** built for accountants, bookkeepers, finance teams, and small business owners who are tired of manually re-entering transaction data from PDF statements.

Unlike generic PDF converters that produce messy spreadsheets with merged cells and broken columns, CleanStmt uses **Claude AI Vision OCR** to understand the structure of financial documents and extract transaction data **digit by digit** with no guessing.

🌐 **Try it now:** [www.cleanstmt.com](https://www.cleanstmt.com)

---

## 🚀 Key Features

### ✨ AI-Powered OCR
- **Digit-by-digit extraction** — reads transaction tables accurately without guessing uncertain values
- Handles multi-line descriptions, wrapped text, and complex statement layouts
- Works with both **native PDFs** and **scanned images**

### 📊 Clean Structured Output
- **No merged cells** — every transaction stays in a single row
- Dates formatted as Excel dates (not text strings)
- Amounts as numbers (not text with currency symbols)
- Ready for **pivot tables, VLOOKUP, and reconciliation** immediately

### 🏦 Wide Bank Support
- Optimized for **38+ major banks** including:
  - Chase, Bank of America, Wells Fargo, Citi, Capital One
  - US Bank, PNC, TD Bank, Truist, BMO Harris
  - HSBC, Barclays, Goldman Sachs Marcus, Discover, American Express

### 💾 Multiple Export Formats
Export one upload to:
- **Excel** (.xlsx)
- **CSV** (.csv)
- **QuickBooks** (.qbo, .iif)
- **Quicken** (.qif)
- **OFX** (.ofx)
- **Xero CSV**, **Sage CSV**, **Tally ERP**

### ⚡ Fast & Private
- Drag-and-drop upload with **results in under 30 seconds**
- Batch processing for multiple statements
- In-memory processing with **auto-delete after 1 hour** — no long-term data retention

---

## 🆓 Pricing

### Free Tier
- ✅ **No credit card required**
- ✅ Usage limits apply
- ✅ All core features included
- ✅ Perfect for occasional use

### Pro Subscription ($19/month)
- ✅ **500 conversions per month** (resets monthly, does not roll over)
- ✅ Priority processing
- ✅ Advanced export formats (Xero, Sage, QBO)
- ✅ Batch processing
- ✅ API access *(coming soon)*

👉 **Start free:** [cleanstmt.com](https://www.cleanstmt.com)

---

## 🎬 How It Works

1. **Upload** — Drag and drop your bank statement PDF or image
2. **Extract** — AI reads and structures your transaction data
3. **Export** — Download clean Excel, CSV, or accounting format files
4. **Import** — Ready for QuickBooks, Xero, or any spreadsheet tool

---

## 🧑‍💼 Who Uses CleanStmt?

### Accountants & Bookkeepers
- Reconciling client bank accounts
- Importing historical transactions into QuickBooks or Xero
- Converting statements from multiple banks efficiently

### Small Business Owners
- Analyzing cash flow from PDF statements
- Preparing tax records
- Tracking expenses across multiple accounts

### Finance Teams
- Processing expense reports and vendor invoices
- Consolidating multi-bank transaction data
- Automating financial reporting workflows

### Tax Professionals
- Organizing annual financial records for clients
- Converting years of PDF statements in bulk
- Preparing audit-ready transaction logs

---

## 🔥 Why Choose CleanStmt?

| Feature | Generic PDF Converters | CleanStmt |
|---------|----------------------|-----------|
| **Merged Cells** | ❌ Breaks formulas | ✅ Single-row transactions |
| **AI OCR Accuracy** | ❌ Guesses values | ✅ Digit-by-digit extraction |
| **Multi-Format Export** | ❌ Excel only | ✅ Excel, CSV, QBO, QIF, OFX, IIF |
| **Bank Optimization** | ❌ Generic parsing | ✅ 38+ banks optimized |
| **Accounting Integration** | ❌ Manual reformatting | ✅ QuickBooks-ready output |
| **Data Privacy** | ⚠️ Stored indefinitely | ✅ Auto-delete after 1 hour |

---

## 🛠️ Tech Stack

- **Frontend:** Next.js 14, React, TailwindCSS
- **AI Engine:** Claude Vision API (Anthropic)
- **Export Libraries:** `xlsx-js-style`, `docx`, custom serializers
- **Hosting:** Vercel (edge functions)
- **Database:** Supabase (user management, subscription tracking)

---

## 📖 Use Cases

### 1. Bank Statement Conversion
Upload Chase, Wells Fargo, or Bank of America PDFs → Get clean Excel with Date, Description, Amount columns.

### 2. Credit Card Statement Processing
Convert Amex, Citi, or Capital One statements → Export to QuickBooks or Xero CSV.

### 3. Invoice & Receipt Extraction
Extract line items from vendor invoices → Structured data for expense tracking.

### 4. Multi-Bank Reconciliation
Process statements from 5+ banks → Unified CSV for cash flow analysis.

### 5. Tax Preparation
Convert years of PDF statements → Audit-ready transaction logs in minutes.

---

## 🌐 Supported Formats

### Input Formats
- PDF (native and scanned)
- PNG, JPG, JPEG (images)
- Multi-page documents

### Output Formats
- **Excel** (.xlsx) — formatted with headers, no merged cells
- **CSV** — UTF-8 encoded, standard delimiters
- **QuickBooks** (.qbo, .iif) — direct import ready
- **Quicken** (.qif) — OFX-compatible
- **Xero CSV** — matches Xero's transaction import format
- **Sage 50 UK CSV** — bank reconciliation format
- **Tally ERP** — accounting ledger format

---

## 🔒 Privacy & Security

- ✅ **No long-term data storage** — files auto-delete after 1 hour
- ✅ **In-memory processing** — data is not written to persistent storage
- ✅ **HTTPS encryption** — all uploads are encrypted in transit
- ✅ **No third-party sharing** — your documents are never sold or shared
- ✅ **Compliant with financial data regulations**

---

## 🚧 Roadmap

- [ ] API access for developers
- [ ] Bulk processing dashboard
- [ ] Custom export templates
- [ ] Integration with Zapier & Make
- [ ] Mobile app (iOS & Android)
- [ ] Multi-language support

---

## 🙋 FAQ

### Is CleanStmt free?
Yes, we offer a **free tier with usage limits**. No credit card required to start. Upgrade to Pro ($19/month) for unlimited conversions.

### What banks do you support?
We support 38+ major banks including Chase, Bank of America, Wells Fargo, Citi, Capital One, US Bank, PNC, TD Bank, Truist, and more. See the full list at [cleanstmt.com/banks](https://www.cleanstmt.com).

### Can I convert scanned statements?
Yes! Our AI OCR works with both native PDFs and scanned images.

### Do you store my data?
No. Files are processed in-memory and **auto-deleted after 1 hour**. We don't retain your financial documents.

### Can I import results into QuickBooks?
Yes! Export directly to **QBO** or **IIF** format for seamless QuickBooks import.

### How accurate is the extraction?
Our AI reads transaction data **digit by digit** and does not guess uncertain values. For best results, use clear, high-resolution PDFs.

---

## 📧 Contact & Support

- **Website:** [cleanstmt.com](https://www.cleanstmt.com)
- **Email:** support@cleanstmt.com
- **GitHub:** [github.com/dis625406542/cleanstmt_pro](https://github.com/dis625406542/cleanstmt_pro)

---

## 📜 License

This project is proprietary software. The code in this repository is for demonstration and documentation purposes only.

---

## 🌟 Star This Repo

If you find CleanStmt useful, please **star this repo** to help others discover it!

[![GitHub stars](https://img.shields.io/github/stars/dis625406542/cleanstmt_pro?style=social)](https://github.com/dis625406542/cleanstmt_pro)

---

**Built by an indie maker. Used by accounting professionals worldwide.**

🚀 **Try CleanStmt for free:** [www.cleanstmt.com](https://www.cleanstmt.com)
