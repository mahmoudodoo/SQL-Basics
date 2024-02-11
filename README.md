# Introduction to SQL

Welcome to SQLBolt, a series of interactive lessons and exercises designed to help you quickly learn SQL right in your browser.

## What is SQL?

SQL, or Structured Query Language, is a language designed to allow both technical and non-technical users to query, manipulate, and transform data from a relational database. Due to its simplicity, SQL databases provide safe and scalable storage for millions of websites and mobile applications.

### Did you know?

There are many popular SQL databases including SQLite, MySQL, Postgres, Oracle, and Microsoft SQL Server. All of them support the common SQL language standard, which is what this site will be teaching, but each implementation can differ in the additional features and storage types it supports.

## Relational databases

Before learning the SQL syntax, it's important to have a model for what a relational database actually is. A relational database represents a collection of related (two-dimensional) tables. Each table is similar to an Excel spreadsheet, with a fixed number of named columns (the attributes or properties of the table) and any number of rows of data.

For example, if the Department of Motor Vehicles had a database, you might find a table containing all the known vehicles that people in the state are driving. This table might need to store the model name, type, number of wheels, and number of doors of each vehicle, for example.

**Table: Vehicles**

| Id | Make/Model       | # Wheels | # Doors | Type       |
|----|------------------|----------|---------|------------|
| 1  | Ford Focus       | 4        | 4       | Sedan      |
| 2  | Tesla Roadster   | 4        | 2       | Sports     |
| 3  | Kawakasi Ninja   | 2        | 0       | Motorcycle |
| 4  | McLaren Formula 1| 4        | 0       | Race       |
| 5  | Tesla S          | 4        | 4       | Sedan      |

In such a database, you might find additional related tables containing information such as a list of all registered drivers in the state, the types of driving licenses that can be granted, or even driving violations for each driver.

By learning SQL, the goal is to learn how to answer specific questions about this data, like "What types of vehicles on the road have less than four wheels?", or "How many models of cars does Tesla produce?", to help us make better decisions down the road.

## About the lessons

Since most users will be learning SQL to interact with an existing database, the lessons begin by introducing you to the various parts of an SQL query. The later lessons will then show you how to alter a table (or schema) and create new tables from scratch.

Each lesson will introduce a different concept and end with an interactive exercise. Go at your own pace and don't be afraid to spend time experimenting with the exercises before continuing! If you happen to be familiar with SQL already, you can skip ahead using the links in the top-right, but we would recommend you work through the lessons anyway!

By the end, we hope you will be able to have a strong foundation for using SQL in your own projects and beyond.
