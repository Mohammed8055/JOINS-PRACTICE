# JOINS-PRACTICE

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: MOHAMMED AFNAN

**INTERN ID**: 0E8F561AB1D3919F

**DOMAIN**: SQL

**BATCH DURATION**: DECEMBER 10TH, 2025 TO JANUARY 7TH, 2026

**MENTOR NAME**: NEELA SANTHOSH

# ENTER DESCRIPTION OF TASK PERFORMED NOT LESS THAN 500 WORDS

In the contemporary data-driven landscape, the ability to synthesize disparate information into a cohesive narrative is the hallmark of advanced database administration. This technical report, prepared as a core deliverable for the CodTech Internship, explores the sophisticated integration of Relational Joins, Common Table Expressions (CTEs), Window Functions, and Subqueries. The objective is to demonstrate a high-level mastery of SQL (Structured Query Language) in transforming raw transactional records into a "360-degree" organizational intelligence report.

The foundational layer of this analysis rests upon Relational Joins. In a normalized database environment, data is often fragmented across multiple tables to reduce redundancy. By executing Inner, Left, Right, and Full Outer Joins, this program bridges the gap between staff demographics and departmental structures. While an INNER JOIN identifies the "ideal state" of perfectly matched records, the strategic use of OUTER JOINS is where true business auditing occurs. For instance, a LEFT JOIN highlights "orphaned" employees without assigned departments, while a RIGHT JOIN exposes under-resourced departments. This methodology ensures that data integrity is maintained while providing a transparent view of organizational gaps.

Building upon this relational foundation, the analysis employs Common Table Expressions (CTEs). In Indian enterprise environments where datasets can be exceptionally dense, CTEs provide a mechanism for "Logical Decomposition." By encapsulating the join logic within a named temporary result set, the program maintains high readability and modularity. This allows for complex, multi-stage transformations—such as calculating monthly revenue totals—without the performance overhead of traditional temporary tables.

The analytical depth is further enhanced through Window Functions. Unlike standard aggregations that collapse data into a single summary row, Window Functions like AVG() OVER() and RANK() allow for comparative metrics to exist alongside individual records. This enables a "Contextual Performance" view, where a salesperson's revenue is directly compared to the Regional Monthly Average. By partitioning data by both geography and timeframe, the program identifies local leaders and national trends simultaneously. The inclusion of the LAG() function introduces a temporal dimension, allowing for the calculation of Month-on-Month (MoM) Growth, which is critical for identifying seasonal volatility in the market.

Finally, Correlated Subqueries are utilized to inject dynamic logic into the reporting layer. These subqueries act as internal filters that define "Elite" performance tiers based on real-time averages rather than static, hard-coded numbers. This ensures that the performance benchmarks remain relevant even as the overall market fluctuates.

# OUTPUT OF THE TASK 

TASK 1.1 RIGHT 
![Image](https://github.com/user-attachments/assets/0ee6480a-1624-484d-8ff5-6bcdc3ad4e68)

1.1 LEFT
![Image](https://github.com/user-attachments/assets/939d704c-83d8-4153-b029-c8da1ed0b71a)

1.1 INNER
![Image](https://github.com/user-attachments/assets/9eb64fd0-1814-4e28-9080-f0c32641c955)

1.1 FULL JOINS
![Image](https://github.com/user-attachments/assets/ef641467-2f32-4d35-8aae-559e69493bc4)

1.2 RIGHT
![Image](https://github.com/user-attachments/assets/84b55033-fa62-494c-ac03-9256e557fe42)

1.2 LEFT
![Image](https://github.com/user-attachments/assets/f97e50da-d34b-4f97-bfd8-ba52a2cdda06)

1.2 INNER
![Image](https://github.com/user-attachments/assets/4993d6e7-4cfb-445e-8390-ef3130bde67d)
