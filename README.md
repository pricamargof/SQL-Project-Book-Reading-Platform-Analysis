# **Project: SQL Book Reading Platform Analysis**

## **Objective**

The goal of this project was to analyze a digital book-reading platform’s relational database and extract insights to guide the development of a competitive reading application. Using SQL, the project explored books, authors, publishers, user ratings, and review behavior to understand catalog quality and user engagement.

---

## **Results**

The analysis delivered several key insights about publishing patterns, book performance, and user behavior:

### **Books Published After 2000**

Counted all books released after **January 1st, 2000**, giving visibility into the platform’s volume of modern publications.

### **Book-Level Metrics**

For every book, the analysis calculated:

* Number of **text reviews**
* **Average user rating**

These metrics helped identify high-engagement and high-quality titles.

### **Publisher Output (Quality Filter Applied)**

Identified the publisher with the **largest number of books over 50 pages**, excluding pamphlets to focus only on substantial publications.

### **Top Author by Rating**

Found the author with the **highest average book rating**, considering only books with **at least 50 user ratings**, ensuring reliable statistical significance.

### **User Activity — Review Behavior**

Calculated the **average number of reviews per user** among those who have rated **more than 50 books**, identifying the platform’s most active and influential users.

---

## **Tools**

| **Tool / Library** | **Purpose**                                                      |
| ------------------ | ---------------------------------------------------------------- |
| SQL                | Core querying language for all analysis.                         |
| JOINs & Subqueries | Merging books, authors, publishers, ratings, and review tables.  |
| GROUP BY / HAVING  | Aggregation and filtering for book-level and user-level metrics. |
| Window Functions   | Ranking authors and publishers based on ratings and output.      |
| CTEs               | Organizing multi-step logic into clean, readable SQL queries.    |

---

## **Skills Learned**

* **Relational Database Analysis:** Understanding and navigating multi-table relationships in a book-reading platform.
* **Advanced SQL Querying:** Using CTEs, aggregations, and window functions to compute metrics at book, author, publisher, and user levels.
* **Data Quality Filtering:** Applying thresholds (≥50 ratings, >50 pages) to ensure stable and meaningful results.
* **Analytical Problem Solving:** Building KPIs that reveal engagement, catalog strength, and trusted author performance.
* **Business Insight Translation:** Converting SQL outputs into strategic recommendations for product and catalog improvements.

---

## **Next Steps / Recommendations**

### **1. Promote High-Rated Authors**

Use curated sections for authors with consistently high ratings (after filtering out low-volume noise).

### **2. Strengthen Publisher Partnerships**

Focus collaboration and licensing efforts on publishers who produce a larger volume of substantial books (>50 pages).

### **3. Boost User Engagement**

Encourage rating and reviewing behavior with:

* Monthly review challenges
* “Top Reviewer” recognition badges
* Incentives for reviewing newly added books



É só pedir!
