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

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](../../issues).

## 📄 License

This project is licensed under the MIT License.
