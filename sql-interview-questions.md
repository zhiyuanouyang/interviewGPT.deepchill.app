# 20 Tricky SQL Interview Questions That Separate Good Candidates from Great Ones (2025)

SQL interviews at top tech companies have evolved. Forget basic `SELECT` queries — modern data engineering and backend interviews test your ability to handle window functions, complex aggregations, recursive CTEs, and real-world analytical scenarios.

This guide covers the most challenging SQL interview questions you'll face, each linked to a full solution on **InterviewGPT** so you can study interactively.

---

## What SQL Interviewers Are Really Testing

Most candidates can write a `GROUP BY` query. What separates top performers is their ability to:

- **Use window functions** (`ROW_NUMBER`, `RANK`, `LAG`, `LEAD`, `SUM OVER`) fluently
- **Write self-joins** for hierarchical or sequential data problems
- **Handle NULLs** carefully and intentionally
- **Think about performance** — indexes, query plans, and avoiding full scans
- **Pivot and reshape data** dynamically
- **Apply set theory** to solve complex membership and exclusion problems

---

## The SQL Questions (With Solutions)

### 📊 Window Functions & Rankings

- **[Identifying Quiet Students via Exam Performance Boundaries](https://interviewgpt.deepchill.app/blogs/sql/identify-consistently-quiet-students-4SgRTbjwWNmD5ZUkiU1Wf3)**  
  Find students who never scored the highest or lowest on any exam. Tests boundary-based filtering with window functions.

- **[Monthly Departmental Salary Benchmarking](https://interviewgpt.deepchill.app/blogs/sql/monthly-departmental-salary-benchmarking-hqVSAfmnTMVQx9zZYnnqyL)**  
  Compute month-over-month salary benchmarks across departments. Real-world HR analytics pattern.

- **[Nth Highest Distinct Value](https://interviewgpt.deepchill.app/blogs/sql/nth-highest-distinct-value-qLhsH2x4b949kojHhVS3ox)**  
  A classic interview question that tests your understanding of `DENSE_RANK` vs `RANK` vs `ROW_NUMBER`.

- **[Top Product per Category with Tie-breaking](https://interviewgpt.deepchill.app/blogs/sql/top-product-per-category-with-tie-breaking-wN2LCurEgbkrwcEwFyGJ6X)**  
  Select the top-selling product in each category — with a deterministic tie-breaking rule. Combines ranking with partition logic.

- **[Top-Grossing Products per Category](https://interviewgpt.deepchill.app/blogs/sql/top-grossing-products-per-category-c8MYzythY6KX5VKGakVkaK)**  
  Revenue-based ranking per category with filters and aggregations. Common in e-commerce analytics interviews.

---

### 🔁 Sequential & Time-Based Problems

- **[CRM Consecutive Engagement Analysis](https://interviewgpt.deepchill.app/blogs/sql/crm-consecutive-engagement-analysis-wNJUp4dAMA3AMXUcvuysgq)**  
  Identify users with consecutive days of activity in a CRM system. Tests the classic "islands and gaps" problem.

- **[Rolling Window Duplicate Transaction Detection](https://interviewgpt.deepchill.app/blogs/sql/rolling-window-duplicate-transaction-detection-n2E9FdUAdaPoQ5Q1Y7gUm8)**  
  Find duplicate financial transactions within a rolling time window. Critical for fraud detection scenarios.

- **[AWS Server Fleet Total Uptime](https://interviewgpt.deepchill.app/blogs/sql/aws-server-fleet-total-uptime-362eygDHXaFPWUiGTXh18J)**  
  Calculate total uptime across overlapping server intervals. Tests interval merging logic in pure SQL.

- **[Daily Sensor Parity Aggregation](https://interviewgpt.deepchill.app/blogs/sql/daily-sensor-parity-aggregation-ae2tXeST6aP4TX2q72Pxfz)**  
  Aggregate sensor readings with even/odd day parity logic. An uncommon but revealing problem type.

---

### 🏅 Customer Retention & Loyalty

- **[Identifying Multi-Year Customer Loyalty](https://interviewgpt.deepchill.app/blogs/sql/identifying-multi-year-customer-loyalty-guRQNdyG3MUjHL9T4vjSYs)**  
  Find customers who made purchases in every year of a multi-year window. Tests intersection and set-based thinking.

- **[Identifying Multi-Year Customer Retention](https://interviewgpt.deepchill.app/blogs/sql/identifying-multi-year-customer-retention-oYxXbrkTNJesktu1BCLjLw)**  
  A variation focusing on customer cohort retention rates across annual periods.

---

### 🔄 Data Transformation & Pivoting

- **[Alphabetical Continent Pivot](https://interviewgpt.deepchill.app/blogs/sql/alphabetical-continent-pivot-bmRsAZJztokKqsMeSsef8V)**  
  Pivot country names alphabetically into continent-based columns. Tests conditional aggregation and `CASE WHEN` mastery.

- **[Correcting Positional Data Swaps](https://interviewgpt.deepchill.app/blogs/sql/correcting-positional-data-swaps-3tGR73y7f39LarpLuswdai)**  
  Swap specific row positions in a result set without updating the underlying data.

- **[Deterministic Median Row Extraction](https://interviewgpt.deepchill.app/blogs/sql/deterministic-median-row-extraction-5wVrugLiH9biQytnHqr1t8)**  
  Find the median row of a dataset deterministically — a problem where `AVG` isn't good enough.

---

### 🏢 Organizational Hierarchy

- **[Identifying Middle Management Tiers](https://interviewgpt.deepchill.app/blogs/sql/identifying-middle-management-tiers-hEVpvvSsycFZkSYcKQ3r9R)**  
  Use self-joins or recursive CTEs to identify employees who are both managers and subordinates.

---

### 🔧 Data Quality & Deduplication

- **[Identifying Incomplete Assembly Parts](https://interviewgpt.deepchill.app/blogs/sql/identifying-incomplete-assembly-parts-smkFxMxVZ5wEp1NjNJepQt)**  
  Find assembly records where required component parts are missing. A manufacturing/logistics favorite.

---

## How to Study SQL for Interviews

### The three patterns that cover 80% of hard SQL questions:

**1. Window Functions**
```sql
SELECT 
  employee_id,
  salary,
  RANK() OVER (PARTITION BY department_id ORDER BY salary DESC) AS salary_rank
FROM employees;
```
Master `RANK`, `DENSE_RANK`, `ROW_NUMBER`, `NTILE`, `LAG`, `LEAD`, `SUM OVER`, `AVG OVER`.

**2. CTEs for Readability and Recursion**
```sql
WITH ranked AS (
  SELECT *, ROW_NUMBER() OVER (PARTITION BY category ORDER BY revenue DESC) AS rn
  FROM sales
)
SELECT * FROM ranked WHERE rn = 1;
```

**3. Self-Joins for Sequential Logic**
```sql
SELECT a.user_id
FROM activity a
JOIN activity b 
  ON a.user_id = b.user_id 
  AND DATEDIFF(b.activity_date, a.activity_date) = 1;
```

---

## Practice Tips

- Always think about **NULL handling** first — `COUNT(*)` vs `COUNT(col)` matters
- Use `EXPLAIN` to validate your solution isn't doing full table scans
- For "consecutive" problems, the **LAG/LEAD approach** is almost always cleaner than self-joins
- For "per group" questions, think `PARTITION BY` before `GROUP BY`
- Time-window problems almost always need `BETWEEN` or `DATEDIFF` with careful boundary thinking

---

Practice every one of these questions with full expert solutions, explanations, and hints at **[InterviewGPT](https://interviewgpt.deepchill.app)** — the AI-powered interview prep platform built for engineers targeting top tech companies.

---

*InterviewGPT covers SQL, system design, machine learning design, frontend design, and behavioral interviews — all in one place.*
