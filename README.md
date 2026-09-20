# Employee KPI Performance Appraisal System 📊

A data-driven human resource management application utilizing Key Performance Indicators (KPI) and weighted score matrices to conduct objective, multi-tier employee evaluations, performance audits, and promotion analytics.

---

## 🌟 Live Demo & Portfolio
- **Author:** Frans Kurniawan
- **Portfolio:** [https://franskur.github.io](https://franskur.github.io)
- **Role:** Full-Stack PHP Web Developer

---

## 🚀 Key Features

- **Dynamic KPI Weighting Engine:**
  - Flexible KPI criteria management with custom percentage weightings per department or role.
  - Automatic calculation of sub-scores, behavioral metrics, and final weighted aggregate ratings.

- **Multi-Tier Approval & Review Workflows:**
  - Standardized evaluation pipeline: Employee Self-Appraisal $\rightarrow$ Supervisor Review $\rightarrow$ Department Head $\rightarrow$ HR Approval.
  - Review status indicators, revision requests, and timestamped managerial commentary.

- **Historical Performance Analytics:**
  - Interactive visual graphs (Radar / Bar charts) charting employee score progression over quarters/years.
  - Bell-curve grade distribution analysis for annual bonus and promotion decision-making.

- **Automated Summary & PDF Reports:**
  - One-click generation of official performance appraisal report cards and CSV/Excel exports for executive reporting.

---

## 🛠️ Tech Stack & Architecture

- **Backend:** Laravel Framework (Eloquent Relationships, Form Requests, Policies/Gates)
- **Database:** MySQL (Structured relational schema with historical appraisal snapshots)
- **Visualization:** Chart.js / ApexCharts
- **Frontend:** Bootstrap 5, Blade, JavaScript (ES6+)
- **Security:** Role-Based Access Control (RBAC), SQL Injection Prevention, XSS Filtration

---

## ⚡ Local Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/franskur/employee-kpi-appraisal-system.git
   cd employee-kpi-appraisal-system
   ```

2. **Install Dependencies:**
   ```bash
   composer install
   ```

3. **Configure Environment:**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Run Migrations & Seed Sample Data:**
   ```bash
   php artisan migrate --seed
   ```

5. **Run the Development Server:**
   ```bash
   php artisan serve
   ```

---

## 📄 License & Notes
Designed and developed by **Frans Kurniawan**. Open for enterprise adaptation and portfolio review.
