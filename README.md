# Masarifi

[![Live Demo](https://img.shields.io/badge/demo-online-blue?style=flat-square)](https://masarifi.kesug.com) [![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

![1](https://iili.io/F07i2fe.png)
> **Masarifi** is an easy to use, responsive web app for tracking budgets, incomes, and expenses—complete with data visualization, speech input, dark mode, and with an exquisite cvs import and export! Excel/Google sheets is goated. It is my first code attempt so all of it is in one HTML. My appolocheese.

---

## Visuals

![2](https://iili.io/F0YuLB4.png)

![3](https://iili.io/F0YYlUl.png)

![4](https://iili.io/F0Yadg4.png)

![5](https://iili.io/F0YcV6b.png)

---

## Table of Contents
1. [Features](#features)
2. [Technologies](#technologies)
3. [Demo](#demo)
4. [Getting Started](#getting-started)
   - [Prerequisites](#prerequisites)
   - [Installation](#installation)
   - [Running Locally](#running-locally)
5. [Usage](#usage)
6. [Customization](#customization)
7. [Data Synchronization](#data-synchronization)
8. [Contributing](#contributing)
9. [License](#license)

---

## Features

- **Budget & Income Management**
  - Set weekly budgets and log income (salary, gifts, etc.) with descriptions and dates.
  - Visual status badges: _On Track_, _Saving_, or _Overspending_.
- **Expense Tracking**
  - Add expenses with **name**, **description**, **category**, **amount**, and **date**.
  - Quick-add presets for frequent items.
  - Speech-to-text input for hands-free entry.
- **Data Visualization**
  - Charts powered by Chart.js:
    - Expenses by weekday (bar)
    - Category breakdown (doughnut)
    - Income over time (line)
    - Budget vs. Income vs. Expenses (bar)
- **Dark Mode**
  - Toggle light/dark themes; preference saved in **localStorage**.
- **CSV Import/Export**
  - Export budgets, incomes, and expenses.
  - Import CSV to restore or migrate data.
- **AI-Driven Budget Diagnosis**
  - Built-in rule-based analysis or optional AI assistant for personalized feedback.
- **Responsive Design**
  - Mobile-first collapsible sections and smooth animations.

---

## Technologies

- **Vanilla JavaScript** for core logic & UI behavior
- **Tailwind CSS** for utility-first styling
- **Font Awesome** for icons
- **Chart.js** for interactive charts
- **Web Speech API** for voice input
- **localStorage** for persistence and privacy
- **Google Apps Script** for optional Google Sheets sync (experimental) 

---

## Demo

Check out the live demo: [masarifi.kesug.com](https://masarifi.kesug.com)

---

## Getting Started

### Prerequisites

- A modern browser: Chrome, Firefox, or Edge
- Internet connection (to load CDN assets)

### Installation

```bash
# Clone the repo
git clone https://github.com/Moudabir/Masarifi.git
cd Masarifi
````

> **Note:** No build step—pure HTML/CSS/JS.

### Running Locally

```bash
# Option 1: Open directly
open index.html

# Option 2: Serve via HTTP server
npx http-server .
```

---

## Usage

1. Set Weekly Budget in the Income & Budget section.
2. Log Income entries with amount, description, and date.
3. Add Expenses by typing or using the microphone button.
4. Use Presets to quickly log recurring costs.
5. Explore charts under Expense Analysis for insights.
6. Export/Import CSV to back up or restore data.
7. Sync all data to Google Sheets via the Sync button (optional).

---

## Customization

* **Expense Presets:** Click the + in the preset bar to add or edit.
* **Categories:** Modify `<select>` options in the HTML.
* **Styling:** Tweak Tailwind classes or dark-mode CSS in `index.html`.

---

## Contributing

```bash
# Fork the repo
# Create a branch
git checkout -b feature/my-feature
# Commit changes
git commit -m "feat: add awesome feature"
# Push and open PR
git push origin feature/my-feature
```

Please follow the existing code style and document new features, or i'll come to your house and fork you instead.
