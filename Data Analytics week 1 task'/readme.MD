# Data Cleaning & Preparation Project

## 🎯 Objective of Project
The goal of this project was to clean a raw dataset and improve data integrity by handling:
* Missing values
* Duplicate records
* Incorrect formatting
* Data consistency issues

The project was completed using **Microsoft Excel**.

---

## 🛠️ Tools Used
* Microsoft Excel
* Excel Formulas
* Conditional Formatting
* Data Validation
* Sorting & Filtering
* Freeze Panes
* Formatting Tools

---

## 📊 Dataset Information
The dataset contained order and sales transaction records with columns such as:
* `OrderID`
* `Date`
* `CustomerID`
* `Product`
* `Quantity`
* `UnitPrice`
* `ShippingAddress`
* `PaymentMethod`
* `OrderStatus`
* `TrackingNumber`
* `ItemsInCart`
* `CouponCode`
* `ReferralSource`
* `TotalPrice`

---

## ⚙️ Tasks Performed

### 1. Duplicate Detection & Verification
* **Highlight Duplicates:** Used conditional formatting to spot repeating records.
* **Remove Duplicates Tool:** Cleaned out redundant data automatically.
* **Manual Verification:** Double-checked records to ensure critical data wasn't lost.

### 2. Missing Values Handling
* **Filter Tool & Blank Cell Identification:** Located empty fields across columns.
* **Manual Filling:** Corrected missing data points individually.
* **Coupon Codes:** Replaced blank `CouponCode` values with *"No Coupon"* for better consistency.

### 3. Date Formatting
* Standardized all inconsistent date formats to a uniform **DD/MM/YYYY** structure.

### 4. Sorting Operations
* Sorted and organized the dataset dynamically by `Product`, `OrderStatus`, and `CouponCode`.

### 5. Filtering Operations
* Created targeted views to isolate **Shipped Orders** and **Cancelled Orders**.

### 6. Formula Verification
* **Formula Used:** $\text{Quantity} \times \text{UnitPrice}$
* **Created VerifiedTotal column:** Verified the existing mathematical logic.
* **Formula Example:** `=E2*F2`

### 7. Conditional Formatting
* Highlighted high-value sales where the total price was greater than **1500**.

### 8. Data Validation
* Applied drop-down data validation rules to the `OrderStatus` column to restrict inputs strictly to:
  * `Shipped`
  * `Delivered`
  * `Pending`
  * `Cancelled`
  * `Returned`

### 9. Freeze Top Row
* Applied `View` → `Freeze Top Row` to keep headers visible while scrolling through large numbers of transactions.

### 10. Professional Formatting
* **Visual Polish:** Applied bold headings, center-aligned headers, clean cell borders, and uniform font sizes.
* **AutoFit Columns:** Ensured no text or numeric values were clipped or hidden (`###` errors).

---

## 💡 Key Skills Learned
* Data Cleaning & Dataset Standardization
* Maintaining Data Integrity
* Excel Advanced Data Handling
* Formula Verification & Validation Techniques
* Advanced Sorting & Filtering
* Analytical Thinking

---

## 🚀 Final Outcome
The raw dataset was successfully transformed into a clean, organized, validated, and professional dataset, making it fully ready for further data analytics, visualization, and business reporting.
