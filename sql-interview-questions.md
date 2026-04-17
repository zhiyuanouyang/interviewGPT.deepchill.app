# SQL Interview Questions & Database Design Challenges

> Expert-level SQL query challenges, database schema design, and optimization techniques for data-heavy roles.

<!-- Keywords: SQL interview, database design, query optimization, data engineering, PostgreSQL -->

[⬅ Back to All Categories](README.md)

---

## [Monthly Departmental Salary Benchmarking](https://interviewgpt.deepchill.app/blogs/sql/monthly-departmental-salary-benchmarking-hqVSAfmnTMVQx9zZYnnqyL)
> 📅 *4/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a salary ledger and employee department mappings, write a SQL query to benchmark each department's monthly average performance against the overall company average for that same month. The output should categorize each department as 'higher', 'lower', or 'same' compared to the company-wide mean, formatted by month (YYYY-MM).

</details>

---

## [Identifying Multi-Year Customer Loyalty](https://interviewgpt.deepchill.app/blogs/sql/identifying-multi-year-customer-loyalty-guRQNdyG3MUjHL9T4vjSYs)
> 📅 *4/9/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a table of tax filing records, identify all users who have used the 'TurboTax' product line to file their taxes for at least three consecutive calendar years. Ensure your solution accounts for users who may have multiple filing entries within the same year and returns a unique list of user IDs in ascending order.

</details>

---

## [Correcting Positional Data Swaps](https://interviewgpt.deepchill.app/blogs/sql/correcting-positional-data-swaps-3tGR73y7f39LarpLuswdai)
> 📅 *4/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a table of orders with sequential IDs, identify and correct a data entry error where the 'item' values for each pair of adjacent rows (1 and 2, 3 and 4, etc.) have been swapped. If the table contains an odd number of records, the final record should remain unchanged. Provide a SQL query that returns the original order IDs with their correctly assigned items.

</details>

---

## [Top-Grossing Products per Category](https://interviewgpt.deepchill.app/blogs/sql/top-grossing-products-per-category-c8MYzythY6KX5VKGakVkaK)
> 📅 *4/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a transactional dataset 'product_spend', write a query to identify the top two products by total revenue within each category for the fiscal year 2022. The solution must aggregate multiple transactions for the same product and handle categories with fewer than two products gracefully. Ensure the syntax is optimized for a columnar analytical database like ClickHouse.

</details>

---

## [Nth Highest Distinct Value](https://interviewgpt.deepchill.app/blogs/sql/nth-highest-distinct-value-qLhsH2x4b949kojHhVS3ox)
> 📅 *4/1/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a table representing entity attributes with potential duplicates (e.g., Salaries), design a robust PostgreSQL solution to retrieve the value at the Nth rank of the unique descending sorted list. The solution must handle the edge case where the total number of unique values is strictly less than N by returning a SQL NULL.

</details>

---

## [Deterministic Median Row Extraction](https://interviewgpt.deepchill.app/blogs/sql/deterministic-median-row-extraction-5wVrugLiH9biQytnHqr1t8)
> 📅 *3/31/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a dataset of employees, their respective companies, and salaries, identify the specific record(s) representing the median salary for each company. In the event of an even number of employees, return both middle records. Ensure the median calculation is deterministic by using the employee ID as a tie-breaker for identical salary values. Your solution should scale efficiently for companies with varying workforce sizes.

</details>

---

## [Identifying Incomplete Assembly Parts](https://interviewgpt.deepchill.app/blogs/sql/identifying-incomplete-assembly-parts-smkFxMxVZ5wEp1NjNJepQt)
> 📅 *3/30/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Tesla's manufacturing system tracks individual assembly steps for various car parts. A part is considered 'in-progress' if it appears in the assembly log but has at least one step where the completion timestamp is missing. Write a query to return a unique list of all parts that are currently unfinished.

</details>

---

## [Identifying Multi-Year Customer Retention](https://interviewgpt.deepchill.app/blogs/sql/identifying-multi-year-customer-retention-oYxXbrkTNJesktu1BCLjLw)
> 📅 *3/30/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a table of tax filing transactions containing filing IDs, user IDs, filing dates, and product names, write a query to identify all users who have demonstrated brand loyalty by filing with any 'TurboTax' product for at least three consecutive calendar years. Ensure the results are deduplicated at the user-year level and the final list of user IDs is sorted in ascending order.

</details>

---

## [Daily Sensor Parity Aggregation](https://interviewgpt.deepchill.app/blogs/sql/daily-sensor-parity-aggregation-ae2tXeST6aP4TX2q72Pxfz)
> 📅 *3/22/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a time-series dataset of sensor readings, calculate the daily aggregate sums of values partitioned by their chronological sequence. Specifically, for each day, compute the total sum of all 'odd-sequence' readings (1st, 3rd, 5th...) and 'even-sequence' readings (2nd, 4th, 6th...) based on their arrival time. The output should contain the date, the sum of odd-numbered readings, and the sum of even-numbered readings.

</details>

---

## [Top Product per Category with Tie-breaking](https://interviewgpt.deepchill.app/blogs/sql/top-product-per-category-with-tie-breaking-wN2LCurEgbkrwcEwFyGJ6X)
> 📅 *3/16/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a 'products' table (product_id, product_name, category_name) and a transactional 'product_sales' table (product_id, sales_quantity, rating), identify the best-selling product within each category. The 'best-selling' product is defined as having the highest aggregate sales quantity. In the event of a tie in sales volume, the product with the higher average rating should be selected. If a tie still exists after considering both metrics, return all such tied products. The final output must include the category name and product name, sorted alphabetically by category name.

</details>

---

## [CRM Consecutive Engagement Analysis](https://interviewgpt.deepchill.app/blogs/sql/crm-consecutive-engagement-analysis-wNJUp4dAMA3AMXUcvuysgq)
> 📅 *3/12/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Identify high-intent customers from CRM and marketing logs. Specifically, extract the unique email addresses of contacts who have shown sustained engagement—defined as having at least one marketing interaction per week for a minimum of three consecutive weeks—and who have also specifically requested a product trial ('trial_request') at any point in their interaction history.

</details>

---

## [Rolling Window Duplicate Transaction Detection](https://interviewgpt.deepchill.app/blogs/sql/rolling-window-duplicate-transaction-detection-n2E9FdUAdaPoQ5Q1Y7gUm8)
> 📅 *3/8/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a dataset of financial transactions, identify the number of 'accidental' repeat payments. A repeat payment is defined as a transaction that occurs at the same merchant, using the same credit card, for the same amount, within a 10-minute rolling window of a previous successful transaction. Ensure that only the subsequent (redundant) transactions are counted, excluding the initial valid payment from the total count.

</details>

---

## [AWS Server Fleet Total Uptime](https://interviewgpt.deepchill.app/blogs/sql/aws-server-fleet-total-uptime-362eygDHXaFPWUiGTXh18J)
> 📅 *3/3/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a log of server lifecycle events including start and stop timestamps for a fleet of instances, calculate the total cumulative uptime across all servers. The final result should be expressed as the total number of complete 24-hour days the entire fleet was operational.

</details>

---

## [Identifying Middle Management Tiers](https://interviewgpt.deepchill.app/blogs/sql/identifying-middle-management-tiers-hEVpvvSsycFZkSYcKQ3r9R)
> 📅 *3/3/2026*

<details>
<summary><b>🔍 View Detailed Interview Prompt</b></summary>

Given a corporate reporting structure where some employees manage others, identify 'Senior Managers'. A Senior Manager is defined as someone who manages at least one person who is also a manager, provided that none of their direct reports are themselves Senior Managers. For all such individuals, calculate the total number of their direct reports and return the list sorted by the largest organization size.

</details>

---

*Generated by [InterviewGPT](https://interviewgpt.ai) on Thu Apr 16 2026*
