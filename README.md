# Insurance-Pricing-Validation

## 📌 Overview

This project is a simple Python program that validates motor insurance prices.

Insurance prices depend on:
- product type,
- coverage variant,
- deductible level.

The program automatically calculates the expected price using predefined business rules, detects inconsistencies in the input data, corrects them, and reports all detected pricing errors.

---

## ⚙️ How It Works

Each insurance product is defined by:
- a **base price**,
- a **variant factor** (basic, comfort, premium),
- a **deductible factor** (100, 200, 500).

The expected price is calculated by applying these factors step by step to the base product price.

If the provided price does not match the expected value, the program replaces it with the correct one and logs the discrepancy.

---

## 📊 Output

Given a dictionary of input prices, the program produces:
- a dictionary containing the **corrected prices**,
- a list of **detected inconsistencies**, showing:
