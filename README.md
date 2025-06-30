# HVAC Field Service Web Tools

A collection of standalone web-based forms and calculators designed for HVAC technicians and sales engineers in the field. These tools are built with **HTML**, **Tailwind CSS**, and **JavaScript** to be fast, responsive, and easy to use on any device with a web browser, such as a tablet, laptop, or smartphone.

---

## 📚 Table of Contents

- [Overview](#overview)
- [Webpages](#webpages)
  - [1. Maintenance Evaluation Form](#1-maintenance-evaluation-form-evaluation_formhtml)
  - [2. Installation Evaluation Form](#2-installation-evaluation-form-hvac_installation_formhtml)
  - [3. Margin Price Calculator](#3-margin-price-calculator-margin_calculatorhtml)
- [How to Use](#how-to-use)
- [Technologies Used](#technologies-used)

---

## 🧰 Overview

This project provides a suite of digital tools to streamline common HVAC field operations, from routine maintenance checks to complex new system installations. The goal is to replace paper forms with interactive, intelligent web pages that can perform calculations, capture more data, and provide a professional appearance to customers.

---

## 🌐 Webpages

### 1. Maintenance Evaluation Form  
**File:** `evaluation_form.html`

This is a comprehensive form for conducting initial evaluations and planned maintenance visits. It's designed to be the primary tool for technicians on service calls.

**Key Features:**
- **Multi-Unit Support**: Dynamically add and remove individual HVAC units.
- **Dynamic Calculations**: Automatically calculates totals for recommended repairs.
- **Photo Uploads**: Attach photos of units and issues directly to the form.
- **AI Nameplate Scanning**: Auto-fill model and serial numbers using image recognition.
- **Maintenance Plan Calculator**: Generates pricing for annual, semi-annual, and quarterly maintenance plans.
- **Database Integration**: Saves form data to a Firebase Firestore database.

---

### 2. Installation Evaluation Form  
**File:** `hvac_installation_form.html`

A universal evaluation form for quoting new residential and commercial HVAC installations. This tool guides a sales engineer or technician through a complete site assessment.

**Key Features:**
- **Residential & Commercial Modes**: Dynamically shows fields based on job type.
- **Conditional Sections**: Hides unnecessary inputs to keep the interface clean.
- **Multi-System Support**: Add multiple systems with separate equipment configurations.
- **Detailed Costing**: Breaks down labor, materials, equipment, and add-ons.
- **Integrated Margin Calculator**: Automatically calculates final price after markup.

---

### 3. Margin Price Calculator  
**File:** `margin_calculator.html`

A quick and easy-to-use tool for calculating the selling price of parts or services based on cost and target margin.

**Key Features:**
- **Detailed Cost Inputs**: Enter part, labor, and shipping costs.
- **Preset Margins**: Instantly view markup options (20%, 30%, etc.).
- **Custom Margin**: Manually enter any percentage.
- **Modern UI**: Dark theme for visibility in various lighting conditions.

---

## ⚙️ How to Use

These are standalone HTML files. No server setup is required.

1. Clone or download this repository.
2. Open any `.html` file (e.g. `hvac_installation_form.html`) in a modern web browser.
3. The tools work offline. Internet is only required for AI and database features.

---

## 🛠️ Technologies Used

- **HTML5** – Page structure and content
- **Tailwind CSS** – Modern, utility-first styling
- **JavaScript (ES6)** – Interactivity and logic

---

