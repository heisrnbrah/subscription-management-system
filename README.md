# BrightFlow — Subscription Management System

> **One platform. Every subscription. Zero billing chaos.**

BrightFlow is a modern **SaaS Subscription Management and Recurring Billing Platform** designed to manage the complete subscription lifecycle for businesses — from products and plans to quotations, subscriptions, automatic invoicing, payments, discounts, renewals, and revenue analytics.

Built for the **Odoo x Make-A-Ton 9.0 Kochi Hackathon 2026**.

---

## 🚀 Overview

Managing subscriptions manually can quickly become complicated.

Businesses often rely on:

- Spreadsheets to track customers
- Manual renewal reminders
- Manually created invoices
- Manual payment matching
- Separate reports for revenue
- Manually calculated discounts and taxes
- Multiple tools for different parts of the subscription lifecycle

BrightFlow brings these operations together into a single platform.

### Core lifecycle

```text
Products & Plans
       ↓
   Quotations
       ↓
  Subscriptions
       ↓
 Automatic Billing
       ↓
    Invoices
       ↓
    Payments
       ↓
 Revenue & Analytics
```

The goal is simple:

> **Automate the subscription lifecycle while giving administrators, staff, and customers the right information and controls.**

---

# 🎯 Problem Statement

Brightloop Software currently manages its subscription process through spreadsheets and manual workflows.

The existing process involves:

1. Creating products and subscription plans
2. Preparing quotations manually
3. Remembering subscription renewals
4. Creating invoices manually
5. Matching payments manually
6. Calculating discounts and taxes
7. Preparing revenue reports manually

This creates problems such as:

- Missed billing dates
- Duplicate invoices
- Incorrect payment matching
- Difficult subscription tracking
- Manual revenue calculations
- Poor visibility into business performance
- Increased operational workload

BrightFlow solves these problems by providing a centralized subscription management system.

---

# 💡 Solution

BrightFlow provides a unified platform for:

- Product management
- Product variants
- Subscription plans
- Customer management
- Quotations
- Subscription lifecycle management
- Recurring billing
- Invoice generation
- Payment tracking
- Discounts
- Taxes
- Renewal management
- Revenue analytics
- Customer portal
- Notifications
- AI-powered insights

---

# ✨ Key Features

## 1. Authentication & User Management

BrightFlow supports secure user authentication with role-based access.

### Roles

| Role | Access |
|---|---|
| Admin | Full system access |
| Staff | Access to permitted business operations |
| Customer | Own subscriptions, invoices and payment information |

### Authentication features

- Login
- Registration
- Unique email validation
- Password validation
- Forgot password
- Password reset
- Role-based access control
- Permission checks
- Protected pages

Password requirements include:

- More than 8 characters
- Uppercase character
- Lowercase character
- Special character

---

# 📦 2. Product Management

Administrators can manage the products offered by the business.

Each product can contain:

- Product name
- Product type
- Sales price
- Cost price
- Notes
- Product variants

### Product Variants

Variants can modify the base product price.

Example:

```text
Product: Premium Laptop

Base Price: ₹50,000

Variant:
Odoo Brand
+ ₹560

Final Price:
₹50,560
```

This allows businesses to represent different product configurations without creating completely separate products.

---

# 📋 3. Subscription Plans

BrightFlow supports configurable subscription plans.

Plans can contain:

- Product
- Billing frequency
- Subscription price
- Minimum quantity
- Available from date
- Available until date
- Auto-close configuration
- Early-close support
- Pause support
- Renewal support

### Billing frequencies

```text
Daily
Weekly
Monthly
Yearly
```

Plans provide the foundation for recurring subscriptions.

---

# 👥 4. Customer Management

Businesses can manage their customers from a centralized interface.

Customer information can be connected with:

- Quotations
- Subscriptions
- Invoices
- Payments
- Subscription plans
- Billing history

Customers can also access their own subscription and financial information through the customer experience.

---

# 📝 5. Quotations

BrightFlow supports the quotation stage before a subscription becomes active.

Features include:

- Create quotations
- Reusable quotation templates
- Customer selection
- Product selection
- Subscription plan selection
- Quantity
- Unit price
- Taxes
- Discount
- Validity period
- Quotation confirmation
- Conversion to subscription

### Quotation flow

```text
Draft Quotation
      ↓
Quotation Sent
      ↓
Customer Acceptance
      ↓
Confirmed
      ↓
Subscription Created
```

---

# 🔄 6. Subscription Management

Subscriptions are the central part of BrightFlow.

Each subscription contains information such as:

- Subscription number
- Customer
- Subscription plan
- Start date
- Expiry date
- Payment terms
- Products
- Quantity
- Unit price
- Tax
- Discount
- Total amount

### Subscription lifecycle

```text
Draft
  ↓
Quotation
  ↓
Confirmed
  ↓
Active
  ↓
Closed
```

BrightFlow also supports subscription actions such as:

- Pause
- Resume
- Renew
- Cancel
- Upgrade
- Downgrade
- Early close

---

# 💳 7. Automatic Recurring Billing

BrightFlow is designed to automate recurring subscription billing.

The billing system determines when a subscription needs to be billed based on its billing frequency.

Example:

```text
Monthly Plan
      ↓
Billing Date
      ↓
Invoice Generated
      ↓
Customer Pays
      ↓
Invoice Marked Paid
```

The billing system is designed to prevent:

- Duplicate billing
- Missed billing cycles
- Incorrect invoice generation

A billing scheduler is included in the application architecture.

---

# 🧾 8. Invoice Management

BrightFlow manages invoices generated from subscriptions.

### Invoice lifecycle

```text
Draft
  ↓
Confirmed
  ↓
Paid
```

Additional states can include:

- Cancelled
- Overdue
- Partially Paid

Invoice operations include:

- Create
- Confirm
- Send
- Cancel
- Print
- View
- Track payment status

Each invoice is connected to the appropriate customer and subscription.

---

# 💰 9. Discounts

BrightFlow includes a configurable discount system.

Discounts can be:

- Fixed amount
- Percentage based

Discount rules can include:

- Minimum purchase amount
- Minimum quantity
- Start date
- End date
- Usage limit
- Product scope
- Subscription scope

Applicable discounts can automatically appear during billing and invoicing.

---

# 🧮 10. Taxes

BrightFlow supports tax calculation as part of billing.

Example tax rates:

```text
5%
12%
18%
Custom
```

Taxes can be applied to relevant products and subscription lines.

---

# 💵 11. Payment Management

Payments are connected to their corresponding invoices.

Payment information can include:

- Payment method
- Amount
- Payment date
- Notes
- Invoice reference
- Customer reference

BrightFlow can also support tracking of:

- Fully paid invoices
- Partially paid invoices
- Outstanding invoices
- Overdue invoices

---

# 📊 12. Dashboard & Analytics

The BrightFlow dashboard provides an overview of business performance.

### Key metrics

- Active subscriptions
- Monthly Recurring Revenue (MRR)
- Annual Recurring Revenue (ARR)
- Customers
- Outstanding invoices
- Overdue invoices
- Payments
- Renewals
- Revenue

### Analytics

The dashboard includes analytics for:

- Revenue
- Subscription health
- Revenue trends
- Subscription status
- Forecasting
- Performance
- Reports

The UI follows a modern SaaS dashboard design with:

- KPI cards
- Charts
- Analytics panels
- Tables
- Status indicators
- Responsive layouts
- Clean navigation

---

# 📈 13. Revenue Analytics

BrightFlow provides revenue-focused analytics to help administrators understand business performance.

Possible views include:

- Daily revenue
- Weekly revenue
- Monthly revenue
- Yearly revenue
- Revenue trends
- Revenue forecasts
- Subscription revenue
- Payment performance

---

# ❤️ 14. Subscription Health

Subscription health provides visibility into the current state of subscriptions.

It can help identify:

- Active subscriptions
- Pending subscriptions
- Paused subscriptions
- Expiring subscriptions
- Closed subscriptions
- Renewal opportunities

This gives administrators a quick understanding of the current subscription portfolio.

---

# 🔔 15. Renewal Management

BrightFlow is designed to help businesses avoid missed renewals.

Renewal monitoring can identify subscriptions approaching their expiry date.

Example reminder schedule:

```text
30 days before expiry
        ↓
7 days before expiry
        ↓
1 day before expiry
        ↓
Renewal date
```

Renewal actions can include:

- Renew
- Extend
- Cancel
- Close

---

# 🔎 16. Global Search & Filtering

The application provides centralized search and filtering capabilities.

Users can quickly find:

- Customers
- Products
- Plans
- Quotations
- Subscriptions
- Invoices
- Payments

Filtering can be based on relevant attributes such as:

- Status
- Date
- Customer
- Amount
- Subscription plan

---

# 🤖 17. AI Insights

BrightFlow includes an AI-oriented insights layer for presenting business information in a more understandable way.

The application includes components for:

- AI summary
- AI chat
- AI insights
- Revenue analysis

The goal is to help administrators understand business data without manually analyzing every report.

---

# 👤 18. Customer Experience

Customers should only have access to information belonging to their own account.

Customer functionality includes access to:

- Own profile
- Own subscriptions
- Subscription status
- Invoices
- Payment information
- Available plans
- Subscription actions where permitted

This creates a dedicated customer-facing experience while keeping administrative functionality restricted.

---

# 🔐 19. Role-Based Access Control

BrightFlow uses permission-based access to protect business operations.

Example:

```text
ADMIN
 ├── Users
 ├── Customers
 ├── Products
 ├── Plans
 ├── Quotations
 ├── Subscriptions
 ├── Invoices
 ├── Payments
 ├── Discounts
 ├── Reports
 └── Settings

STAFF
 ├── Customers
 ├── Products
 ├── Plans
 ├── Quotations
 ├── Subscriptions
 ├── Invoices
 └── Payments

CUSTOMER
 ├── Own Subscriptions
 ├── Own Invoices
 └── Own Payments
```

Only administrators should be able to create/manage staff accounts.

---

# 🏗️ Technology Stack

## Frontend

- React
- TypeScript
- Vite
- Tailwind CSS
- Modern component architecture
- Responsive UI

## Backend

- Node.js
- Express
- TypeScript

## Data & Business Logic

- Local application data layer
- Authentication utilities
- Billing engine
- Discount engine
- Pricing engine
- Analytics engine
- Forecasting
- Permission system

## Libraries / Utilities

- Recharts / charting components
- Lucide icons
- PDF generation
- Authentication utilities
- Crypto utilities

---

# 📁 Project Structure

```text
subscription-management-system/
│
├── .env.example
├── .gitignore
├── README.md
├── index.html
├── package.json
├── server.ts
├── tsconfig.json
├── vite.config.ts
│
└── src/
    │
    ├── App.tsx
    ├── index.css
    ├── main.tsx
    │
    ├── components/
    │   │
    │   ├── ai/
    │   │   ├── common/
    │   │   ├── dashboard/
    │   │   ├── invoices/
    │   │   ├── layout/
    │   │   ├── plans/
    │   │   ├── quotations/
    │   │   ├── subscriptions/
    │   │   └── ui/
    │
    ├── context/
    │   ├── ThemeContext.tsx
    │   └── ToastContext.tsx
    │
    ├── hooks/
    │   └── useBillingScheduler.ts
    │
    ├── lib/
    │   ├── analytics.ts
    │   ├── auth.tsx
    │   ├── billing.ts
    │   ├── chartConfig.ts
    │   ├── crypto.ts
    │   ├── db.ts
    │   ├── discounts.ts
    │   ├── forecast.ts
    │   ├── formatters.ts
    │   ├── pdf.ts
    │   ├── permissions.ts
    │   ├── pricing.ts
    │   └── seed.ts
    │
    ├── pages/
    │   ├── AiInsightsPage.tsx
    │   ├── CustomersPage.tsx
    │   ├── DashboardPage.tsx
    │   ├── DemoGuidePage.tsx
    │   ├── DiscountsPage.tsx
    │   ├── InvoicesPage.tsx
    │   ├── LoginPage.tsx
    │   ├── MockInboxPage.tsx
    │   ├── PaymentsPage.tsx
    │   ├── PerformancePage.tsx
    │   ├── PlansPage.tsx
    │   ├── ProductsPage.tsx
    │   ├── QuotationsPage.tsx
    │   ├── RegisterPage.tsx
    │   ├── ReportsPage.tsx
    │   ├── ResetPasswordPage.tsx
    │   ├── SubscriptionsPage.tsx
    │   └── UsersPage.tsx
    │
    └── types/
        └── index.ts
```

---

# 🔄 Complete Business Workflow

BrightFlow connects the complete business workflow:

```text
                    ┌───────────────┐
                    │   PRODUCTS    │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │     PLANS     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │  QUOTATIONS   │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │ SUBSCRIPTION  │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │ AUTO BILLING  │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │   INVOICE     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │   PAYMENT     │
                    └───────┬───────┘
                            ↓
                    ┌───────────────┐
                    │   REPORTING   │
                    └───────────────┘
```

---

# 🧪 Hackathon Demo Flow

The recommended demonstration flow is:

```text
1. Login as Admin
       ↓
2. Create Product
       ↓
3. Add Product Variant
       ↓
4. Create Subscription Plan
       ↓
5. Create Customer
       ↓
6. Create Quotation
       ↓
7. Confirm Quotation
       ↓
8. Convert to Subscription
       ↓
9. Activate Subscription
       ↓
10. Generate Recurring Invoice
       ↓
11. Apply Discount & Tax
       ↓
12. Record Payment
       ↓
13. Invoice becomes Paid
       ↓
14. Dashboard updates
       ↓
15. View Revenue Analytics
       ↓
16. Login as Customer
       ↓
17. View Own Subscription & Invoice
```

---

# 📋 Hackathon Requirement Coverage

BrightFlow is designed around the required subscription lifecycle.

| Requirement | BrightFlow Feature |
|---|---|
| Admin / Staff / Customer roles | Role-based access |
| Authentication | Login / Register / Reset Password |
| Products | Product Management |
| Product Variants | Variant Pricing |
| Subscription Plans | Daily / Weekly / Monthly / Yearly |
| Quotations | Quotation Management |
| Quotation Templates | Reusable Templates |
| Subscriptions | Subscription Management |
| Subscription Lifecycle | Draft → Quotation → Confirmed → Active → Closed |
| Automatic Billing | Billing Scheduler |
| Invoices | Invoice Management |
| Invoice Lifecycle | Draft → Confirmed → Paid |
| Discounts | Fixed / Percentage Discounts |
| Taxes | Configurable Tax Rates |
| Payments | Payment Management |
| Revenue Reporting | Analytics & Reports |
| Renewal Management | Renewal Tracking |
| Customer Portal | Customer-specific information |
| Performance | Pagination / optimized UI architecture |
| AI Insights | AI Summary / AI Chat |

---

# 🎨 UI/UX

BrightFlow follows a modern SaaS dashboard design philosophy.

### Design goals

- Clean interface
- Strong visual hierarchy
- Responsive layout
- Minimal unnecessary elements
- Clear KPI presentation
- Data-focused analytics
- Easy navigation
- Consistent components
- Clear status badges
- Professional business appearance

### Main navigation areas

```text
OVERVIEW
└── Dashboard

OPERATIONS
├── Customers
├── Quotations
├── Subscriptions
├── Invoices
└── Payments

CATALOG
├── Products
├── Plans
└── Discounts

ANALYTICS
├── Revenue
├── Reports
└── Performance

SYSTEM
├── Notifications
├── AI Insights
└── Settings
```

---

# ⚡ Getting Started

## Prerequisites

Make sure you have installed:

- Node.js
- npm
- Git

---

## Clone the repository

```bash
git clone https://github.com/heisrnbrah/subscription-management-system.git
```

Navigate into the project:

```bash
cd subscription-management-system
```

---

## Install dependencies

Because the current project dependency tree contains a Vite/esbuild peer-dependency conflict, install using:

```bash
npm install --legacy-peer-deps
```

---

## Environment Variables

Create a `.env` file based on `.env.example`.

Example:

```env
# Add required environment variables here
```

Do not commit secrets or API keys to GitHub.

---

## Start the development server

```bash
npm run dev
```

The application will run on:

```text
http://localhost:3000
```

---

# 🛡️ Security

BrightFlow follows basic application security principles:

- Environment variables for secrets
- Password validation
- Authentication
- Role-based authorization
- Protected routes
- Permission checks
- Input validation
- No hardcoded private API keys
- Customer data isolation

Never commit:

```text
.env
API keys
Private credentials
Database passwords
Authentication secrets
```

---

# 📌 Development Guidelines

For development:

1. Keep the `main` branch stable.
2. Test changes locally before committing.
3. Use meaningful commit messages.
4. Never commit secrets.
5. Avoid unnecessary dependencies.
6. Keep business logic separated from UI components.
7. Maintain reusable components.
8. Test subscription and billing flows carefully.

Example commit:

```bash
git add .
git commit -m "feat: improve recurring billing flow"
git push origin main
```

---

# 🏆 Project Goal

BrightFlow aims to transform subscription management from a collection of manual processes into a centralized automated platform.

Instead of managing:

```text
Spreadsheet
   +
Manual Renewals
   +
Manual Invoices
   +
Manual Payments
   +
Manual Reports
```

BrightFlow provides:

```text
                BRIGHTFLOW
                    │
        ┌───────────┼───────────┐
        ↓           ↓           ↓
     Products     Plans     Customers
        │           │           │
        └───────────┼───────────┘
                    ↓
               Quotations
                    ↓
              Subscriptions
                    ↓
             Auto Billing
                    ↓
                Invoices
                    ↓
                Payments
                    ↓
             Revenue Analytics
```

---

# 🌟 Vision

> **BrightFlow makes subscription businesses easier to operate by connecting every stage of the subscription lifecycle in one intelligent platform.**

From the first product configuration to the final payment and revenue report, BrightFlow provides a single source of truth for subscription operations.

---

# 👨‍💻 Built For

**Odoo x Make-A-Ton 9.0 Kochi Hackathon 2026**

### Project

**BrightFlow — Subscription Management System**

### Repository

`subscription-management-system`

### Development Team

Hackathon Team — Subscription Management System

---

## 📄 License

This project was developed as part of the **Odoo x Make-A-Ton 9.0 Kochi Hackathon 2026**.

---

## 🚀 BrightFlow

**One platform. Every subscription. Zero billing chaos.**
