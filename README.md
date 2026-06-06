<div align="center">
  <img src="public/favicon.svg" alt="Venflow Logo" width="120" />

  # Venflow
  ### Smart procurement. Seamless flow.

  <p>
    <strong>A next-generation, end-to-end B2B Procurement and Vendor Management Platform.</strong>
  </p>

  <p>
    <a href="#features">Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#getting-started">Getting Started</a> •
    <a href="#demo-data">Seeding Demo Data</a>
  </p>
</div>

---

## 📖 About The Project

**Venflow** is designed to solve the massive headache of managing vendors, RFQs (Requests for Quotation), approvals, and purchase orders. By consolidating the entire procurement lifecycle into one beautiful, lightning-fast application, Venflow brings a consumer-grade user experience to the notoriously complex world of B2B procurement.

The application features a proprietary **"Liquid Glass"** design system that looks stunning in both Light and Dark modes.

---

## ✨ Key Features

- 🎨 **Liquid Glass UI**: A beautiful, fully responsive, and premium glassmorphic interface supporting both Light and Dark themes.
- 👥 **Role-Based Access**: Secure and tailored dashboards for Admins, Managers, Procurement Officers, and Vendors.
- 📑 **Smart RFQ Workflows**: An intuitive 3-step wizard to create RFQs, assign line items, and invite specific vendors to bid.
- ✅ **Approval Pipelines**: Seamlessly review quotations, request revisions, and automatically convert approved quotes into Purchase Orders.
- 📊 **Advanced Analytics**: Interactive, real-time charts displaying 6-month spending trends, spend by category, and vendor fulfillment rates.
- 🛡️ **Automated Fraud Detection**: An advanced Activity Log that automatically flags suspicious activities (e.g., quotations wildly above estimates) with color-coded severity badges.

---

## 🛠️ Tech Stack

**Frontend:**
- [React 19](https://react.dev/)
- [Vite](https://vitejs.dev/)
- [Tailwind CSS v4](https://tailwindcss.com/)
- [Recharts](https://recharts.org/) (Data Visualization)
- [Lucide React](https://lucide.dev/) (Icons)

**Backend & Database:**
- [Supabase](https://supabase.com/) (PostgreSQL, Authentication, Row Level Security)

---

## 🚀 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

- Node.js (v18 or higher)
- npm (or yarn/pnpm)
- A Supabase account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ridhamgohel2007-cmyk/Oddo-x-KSV-Vendor-bridge-.git
   cd Oddo-x-KSV-Vendor-bridge-
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Environment Variables**
   Create a `.env` file in the root directory and add your Supabase credentials:
   ```env
   VITE_SUPABASE_URL=your_supabase_project_url
   VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
   ```

4. **Run the Database Migrations**
   Execute the SQL snippet found in `supabase/migrations/0001_initial_schema.sql` in your Supabase SQL Editor to set up the tables and constraints.

5. **Start the development server**
   ```bash
   npm run dev
   ```

---

## 🌱 Seeding Demo Data

Venflow includes a robust seeding script to instantly populate your database with realistic demo data (Vendors, RFQs, Quotations, Invoices, and Activity Logs).

To seed the database, simply run:
```bash
node --env-file=.env seed.js
```
*(Note: Requires Node.js v20+ to use the `--env-file` flag natively. If using an older version, install `dotenv` and run accordingly).*

---
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 38 10" src="https://github.com/user-attachments/assets/5c154d00-1905-4adb-b9e2-b238434662db" />ts are welcome! Feel free to check the [issues page](../../issues).

## 📄 License

This project is licensed under the MIT License.

<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 38 10 (1)" src="https://github.com/user-attachments/assets/c4dcff1c-d045-46b9-ae05-e929c5f7c82f" />
<img width="1600" height="895" alt="WhatsApp Image 2026-06-06 at 16 39 43" src="https://github.com/user-attachments/assets/bcb9ecda-a6b2-4066-998c-88b0b85d6ae9" />
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 39 43 (1)" src="https://github.com/user-attachments/assets/ef44e126-1aef-468f-9e11-2823529de141" />
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 39 26" src="https://github.com/user-attachments/assets/52e7abd4-2d01-4f63-a399-e7da28ec36d5" />
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 39 26 (1)" src="https://github.com/user-attachments/assets/2cef287e-5952-4483-8289-dfe8ecbb39f2" />
<img width="1600" height="901" alt="WhatsApp Image 2026-06-06 at 16 38 48" src="https://github.com/user-attachments/assets/052ba04f-8150-419b-8947-f05ad0b4b835" />
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 38 26" src="https://github.com/user-attachments/assets/2ba9a351-17fa-4310-898e-b317084cf454" />
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 40 01" src="https://github.com/user-attachments/assets/bf3e1bbc-fa2d-457a-8bb1-711f23ed137a" />
<img width="1600" height="899" alt="WhatsApp Image 2026-06-06 at 16 40 01 (1)" src="https://github.com/user-attachments/assets/049ae197-85be-4dcf-b547-0dbe272d5e18" />


