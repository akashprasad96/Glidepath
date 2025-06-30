

# 📈 Excel Glidepath Simulation Tool

A dynamic and easy-to-use Excel-based tool to track progress toward annual KPI goals through monthly targets, performance trends, and goal simulation. Designed for program managers, analysts, and teams who want to monitor and course-correct KPI achievement using just three inputs.

---

## 🚀 Features

* ✅ **Real-time KPI simulation** based on performance trends
* 🧮 **Auto-calculating monthly targets** from Final Goal, Initial Value, and Due Date
* 📊 **Interactive visualizations** to compare Monthly Targets vs. Actuals
* 🧠 **Supports 3 types of KPIs**:

  * Numerical
  * Percentage-based
  * Average metrics
* ⚡ **Auto-adjusts for Tailwinds & Headwinds**
* 🔄 Fully dynamic — minimal manual effort required

---

## 📂 Sheet Structure

The workbook includes three sheets, each tailored for a specific KPI type:

* **Numerical KPI Sheet** – For metrics tracked as raw numbers (e.g., units, transactions)
* **Percentage KPI Sheet** – For metrics expressed in percentages (e.g., accuracy, completion rate)
* **Average KPI Sheet** – For metrics that represent averages (e.g., average handle time)

---

## ✍️ How to Use

### Step 1: Input Manual Values

Only fill in the **Manual Inputs** table. All calculations and charts will update automatically.

| Field                 | Description                             | Cell/Range |
| --------------------- | --------------------------------------- | ---------- |
| **Final Goal**        | Enter the target KPI value for year-end | `I37`      |
| **Initial KPI Value** | Your starting KPI value                 | `I38`      |
| **Actuals**           | Enter actuals achieved each month       | `D37:D48`  |

---

### Step 2: Set the Timeline

Adjust the "Month" column (`C37:C48`) to match your goal duration:

* Use **“Click to Add”** to include additional months
* Use **“Click to Remove”** to shorten the timeline

---

### Step 3: Add (Optional) Headwinds & Tailwinds

Input these values in `F37:F48` if applicable:

* **Headwinds** = Enter **negative** numbers for blockers or setbacks
* **Tailwinds** = Enter **positive** numbers for accelerators or favorable events
  These are automatically factored into the monthly projections.

---

### Step 4: Enter Goal Meta-Data

Provide context for your KPI in `C17:E23` to help track ownership, program relevance, and scope.

---

### Step 5: Review Calculations & Charts

All other fields (Monthly Targets, MoM, YTD, etc.) are auto-calculated. Graphs will update based on input values to visualize:

* Monthly Targets vs. Actuals
* Overall KPI progress

---

## 🛠️ Requirements

* Excel 2016 or later (for full macro and chart compatibility)
* Macros enabled

---

## 📌 Notes

* No formulas need manual editing
* Tailored for Tier 2 Kingpin KPI tracking but adaptable for any performance goal
* Built for scalability and usability across multiple programs and verticals
