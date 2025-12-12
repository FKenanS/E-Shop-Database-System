# E-Shop Database System (PostgreSQL)

This project is a database design and SQL implementation developed for an e-commerce–style system.  
It includes a complete conceptual model, relational schema, PostgreSQL database structure, sample data, and advanced SQL queries.

---

## 🔧 Features

- **Conceptual ER Diagram**
- **Relational (Logical) Schema**
- **PostgreSQL Table Definitions**
  - `CREATE TABLE`, constraints, primary/foreign keys
- **Sample Dataset**
  - `INSERT` statements
- **24+ SQL Queries**, including:
  - INNER / LEFT / RIGHT / FULL JOIN  
  - Subqueries (SELECT / FROM / WHERE)  
  - EXISTS / NOT EXISTS  
  - UNION / EXCEPT / INTERSECT  
  - GROUP BY + HAVING  
  - VIEW, UPDATE, DELETE
- **10 Relational Algebra Expressions**

---

## 🧱 Database Structure

**Main Tables:**
- Customer  
- Producer  
- Product  
- Category  
- ProductCategory  
- Orders  
- OrderItem  
- Payment  
- Review  
- Shipping  

**Key Relationships:**
- Customer → Orders → OrderItem → Product  
- Customer ↔ Review ↔ Product  
- Product ↔ Category  
- Orders → Payment  
- Orders → Shipping  

---

## 🎯 Purpose

This project demonstrates:
- Relational database modeling  
- ERD and schema design  
- Advanced SQL querying  
- Practical use of PostgreSQL features  

---

## 📁 Contents

- `/diagrams` – ERD & relational schema  
- `/schema.sql` – Table definitions + constraints  
- `/sample-data.sql` – INSERT statements  
- `/queries.sql` – All SQL queries (24+)  
- `/relational-algebra.txt` – RA expressions  

---

## 🚀 Technologies

- PostgreSQL  
- SQL (Advanced Queries)  
- Relational Algebra  
- ER Modeling  

