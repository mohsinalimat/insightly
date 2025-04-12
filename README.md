# Insightly - Customer & Supplier Intelligence

**Insightly** is a Frappe-based custom app that provides deep insights into your **sales** and **purchase cycles** through two powerful dashboards:

- 📊 **Customer Insights**
- 📦 **Supplier Insights**

These dashboards help business users track key metrics, identify trends, and drill down into transaction details — all from one place.

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

Examples :


![Screenshot from 2025-04-12 11-23-32](https://github.com/user-attachments/assets/ced61b6d-4a3a-40d1-a988-595c3667d1dc)


![Screenshot from 2025-04-12 11-23-38](https://github.com/user-attachments/assets/a5138584-7daf-48bb-95ae-6f3343daa8e2)


![Screenshot from 2025-04-12 11-23-12](https://github.com/user-attachments/assets/702699db-b835-4d48-9c06-93709f852ff8)


![Screenshot from 2025-04-12 11-22-46](https://github.com/user-attachments/assets/83bd652e-c1c4-46a2-9ae9-8b4db95f40f0)


![Screenshot from 2025-04-12 11-23-01](https://github.com/user-attachments/assets/0466f5ab-8f90-47bf-a151-1e03ea8abd24)


---

#### Licencse

mit
