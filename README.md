Masarifi

An intuitive, responsive web application for tracking budgets, incomes, and expenses, complete with data visualization, speech input, dark mode, and AI-driven analysis.

Table of Contents

Features

Technologies

Demo

Getting Started

Prerequisites

Installation

Running Locally

Usage

Customization

Data Synchronization

Contributing

License

Features

Budget & Income Management

Set weekly budgets, add incomes with descriptions and dates.

Visual indicators for budget status: On track, saving, or overspending.

Expense Tracking

Add expenses with name, description, category, amount, and date.

Quick-add presets for common expense types.

Speech-to-text input for hands-free entry.

Data Visualization

Interactive charts (Chart.js) showing:

Expenses by weekday (bar chart)

Expense category breakdown (doughnut chart)

Income over time (line chart)

Budget vs. Income vs. Expenses (bar chart)

Dark Mode

Toggle between light and dark themes; preference persisted in localStorage.

CSV Import/Export

Export budgets, incomes, and expenses to CSV.

Import CSV to restore or migrate data.

AI-Driven Budget Diagnosis

Built-in rule-based analysis or optional AI assistant for personalized feedback.

Responsive Design

Mobile-friendly collapsible sections and smooth animations.

Technologies

Vanilla JavaScript for core logic and UI behavior

Tailwind CSS for utility-first styling

Font Awesome for icons

Chart.js for data visualization

Web Speech API for speech recognition

LocalStorage for data persistence

Google Apps Script endpoint for optional Google Sheets sync

Demo

A live demo is available at: masarifi.kesug.com

Getting Started

Prerequisites

Modern web browser (Chrome, Firefox, Edge)

Internet connection to load CDN assets (Tailwind, Font Awesome, Chart.js)

Installation

Clone the repository

git clone https://github.com/Moudabir/Masarifi
cd armadeus

Open in VS Code (optional):

code .

No build step required—the app is pure HTML/CSS/JS.

Running Locally

Simply open index.html in your browser:

open index.html

Or serve via a simple HTTP server:

npx http-server .

Usage

Set a Weekly Budget in the Income & Budget section.

Add Income entries for salary, gifts, etc.

Add Expenses by typing or using speech input.

Use Presets to quickly log frequent purchases.

View Charts under Expense Analysis for insights.

Export/Import CSV to backup or restore data.

Sync All Data to Google Sheets (optional).

Customization

Expense Presets: Modify or add via the + button in the preset bar.

Categories: Edit category options in the <select> elements.

Theme: Customize Tailwind classes or dark-mode CSS in <style>.

Data Synchronization

The app can optionally sync to a Google Sheets spreadsheet via an Apps Script endpoint. Configure the script URL in the sendDataToGoogleSheets function in index.html.

Contributing

Fork the repository

Create a feature branch (git checkout -b feature/my-feature)

Commit your changes (git commit -m "feat: add ...")

Push to your branch (git push origin feature/my-feature)

Open a Pull Request

Please ensure code is well-documented and follows existing style.
