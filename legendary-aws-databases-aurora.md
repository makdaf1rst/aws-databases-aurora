<img src="https://cdn.prod.website-files.com/677c400686e724409a5a7409/6790ad949cf622dc8dcd9fe4_nextwork-logo-leather.svg" alt="NextWork" width="300" />

# Aurora Database with EC2

**Project Link:** [View Project](http://learn.nextwork.org/projects/aws-databases-aurora)

**Author:** saqibh49@gmail.com  
**Email:** saqibh49@gmail.com

---

## Connect a Web App to Amazon Aurora

![Image](http://learn.nextwork.org/grateful_white_lucky_bat/uploads/aws-databases-aurora_44443546)

---

## Introducing Today's Project!

### What is Amazon Aurora?

Amazon Aurora is AWS's souped-up version of MySQL and PostgreSQL that handles all the annoying database maintenance stuff automatically, and it is useful because it's way faster than regular MySQL or PostgreSQL (like 3-5x faster), automatically backs up your data, spreads it across multiple locations so it doesn't go down, and scales without you having to mess with it - basically giving you enterprise-level database performance without the enterprise-level headache.

### How I used Amazon Aurora in this project

In today's project, I used Amazon Aurora to connect to an EC2 instance so I can pull data from it in the future. 

### One thing I didn't expect in this project was...

One thing I didn't expect in this project was how many settings there would be in the process of setting up a relational database. 

### This project took me...

This project took me about 30 minutes to complete. 

---

## In the first part of my project...

### Creating an Aurora Cluster

A relational database is a database made of rowws and columns, basically a spreadsheet, that can be queried using SQL. 

Aurora is a good choice when you have large scale database needs, since it uses clusters, whereas MySQL and Oracle are better for smaller scale databases. 

![Image](http://learn.nextwork.org/grateful_white_lucky_bat/uploads/aws-databases-aurora_44443546)

---

## Halfway through I stopped!

I stopped creating my Aurora database because I need to first create my EC2 instance that the database will connect to. 

### Features of my EC2 instance

I created a new key pair for my EC2 instance because this provides me with a secure way of connecting with my EC2 instance. This will also keep out anyone not authorized to view my instance. 

When I created my EC2 instance, I took particular note of the pubic IPv4 address because this is essentially the address of my instance on the open internet.

![Image](http://learn.nextwork.org/grateful_white_lucky_bat/uploads/aws-databases-aurora_91b9fd1g)

---

## Then I could finish setting up my database

![Image](http://learn.nextwork.org/grateful_white_lucky_bat/uploads/aws-databases-aurora_1fddb0b5)

Aurora Database uses clusters because clusters can handle larger workloads without failing or slowing down. 

---

---
