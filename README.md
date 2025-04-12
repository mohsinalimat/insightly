# Insightly - Customer & Supplier Intelligence

**Insightly** is a Frappe-based custom app that provides deep insights into your **sales** and **purchase cycles** through two powerful dashboards:

- 📊 **Customer Insights**
- 📦 **Supplier Insights**

These dashboards help business users track key metrics, identify trends, and drill down into transaction details — all from one place.

## 🚀 Features

### 🔹 Customer Insights Page

- Displays an overview of the complete **sales cycle** for the selected date range:
  - **Sales Orders**
  - **Delivery Notes**
  - **Payment Requests**
  - **Payment Entries**
- Shows **total counts and amounts** per Doctype.
- Click on any Doctype (e.g., Sales Order) to view detailed records instantly.
- View **customer-wise breakdown** of documents and filter the data dynamically.

---

### 🔹 Supplier Insights Page

- Gives a clear view of your **purchase cycle**:
  - **Purchase Orders**
  - **Purchase Receipts**
  - **Purchase Invoices**
  - **Payment Entries**
- Click on any section to drill down and analyze detailed transaction data.
- Filter by supplier, date range, and other key fields.
- Analyze data per supplier to make smarter procurement decisions.

---

## 🧠 Use Cases

- Understand your sales performance by customer or region.
- Monitor overdue or pending delivery/payment scenarios.
- Identify supplier performance and payment trends.
- Gain executive-level visibility without running multiple reports.

---

## 📦 Installation

From your Frappe bench directory:

```bash
# Clone the repo inside the apps directory
cd apps
git clone https://github.com/MeetSherasiya/insightly.git

# Install the app
cd ..
bench --site your-site-name install-app insightly

# Migrate Site
bench --site your-site-name migrate

# Bench Build
bench build
bench --site your-site-name clear-cache
bench --site your-site-name clear-website-cache
```

####
Licencse

mit
