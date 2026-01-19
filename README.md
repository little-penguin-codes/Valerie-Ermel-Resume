# Valerie-Ermel-Resume

This assignment is designed to push you out of the "Low-Code" mindset and into Enterprise Software Engineering. It uses the exact "Polyglot" stack (Java, Python, TypeScript, SQL, Docker) found in the private-sector job postings you shared.

## 🎓 Final Project: "The Omnichannel Inventory Engine"
The Objective: Build a system that centralizes inventory data from multiple sources (Excel, Web, and Manual Entry) and provides a high-performance API for a remote team to consume.

## The Stack (Job Posting Alignment)
 * Backend Core: Java (Spring Boot) — The industry standard for private-sector scale.
 * Data Automation: Python (Pandas/Scripts) — Your "Excel on steroids" engine.
 * Frontend/Tooling: TypeScript (React or Node.js scripts) — To show you can build modern tools.
 * Database: PostgreSQL — The "gold standard" for relational data.
 * DevOps: Docker & Git — Proves you can work remotely and ship clean code.

## The Assignment Tasks

### Phase 1: The Relational Foundation (Database)
 * Goal: Design a database that handles relationships better than Excel ever could.
 * Requirement: Create a schema with at least three related tables: Products, Warehouses, and StockLevels.
 * The "Steroids" Twist: Write a SQL script that creates a "View" showing which products are under-stocked across all warehouses.

### Phase 2: The Logic Engine (Java + Spring Boot)
 * Goal: Build a "Secure API" that follows private-sector best practices.
 * Requirement: Create REST endpoints (GET, POST, DELETE) to manage your inventory.
 * Constraint: You must use Spring Data JPA (which is the Java version of the Entity Framework mentioned in your ads).
 * The "School" Challenge: Implement "Input Validation"—if someone tries to add "-5" items to stock, the API should return a professional 400 Error.

### Phase 3: The Data Transformer (Python)
 * Goal: Prove you can automate the manual work you used to do in government.
 * Requirement: Write a Python script that reads a "Legacy CSV/Excel" file and uses the requests library to "POST" that data into your Java API.
 * Why: This shows you know how to bridge the gap between old data (Excel) and new systems (APIs).

### Phase 4: The Interface (TypeScript)
 * Goal: Show you can build clean, typed code.
 * Requirement: Create a simple Dashboard in React (or a CLI tool in Node.js) that displays the current stock levels.
 * Why: Even for backend roles, private companies love seeing that you understand how a frontend consumes your data.

### Phase 5: The "Remote Ready" Packaging (Docker)
 * Goal: Make your project "One-Click" for a hiring manager.
 * Requirement: Write a docker-compose.yml file that starts your Java API and your PostgreSQL database together.
 * Why: In the private sector, "if I can't run it in 5 minutes, I'm not hiring you."

## Instruction Summary Table
| Component | Instruction | Technology |
|---|---|---|
| API | Build a RESTful service with 3+ endpoints. | Java / Spring Boot |
| Data Script | Automate an Excel-to-API data migration. | Python |
| Database | Create a normalized schema with Foreign Keys. | PostgreSQL |
| Frontend | Build a "Read-Only" dashboard to view data. | TypeScript / React |
| Deployment | Containerize the entire app for local testing. | Docker |

## Your First Step (Lab #1)
Before you write any code, you need a "Blueprint."

Would you like me to generate the Database Schema (The Table relationships) for this project so you can visualize how the data will flow?
