# This project is for baselining the production DevOps projects.

# Introduction
- Multi-tier web application project
- Setup on laptop or desktop
- Bseline for future projects [ Production Level ]

# Scenario
  - Working on project
  - Varieties os services that powers your project runtime [e.g.: MySQL, JBoss, PHP, Apache, JQuery, etc.]
  - Run / Setup document
 
# Problem
  - No comfortable in making changes in real-time server
  - Local setup is complex
  - Time consuming
  - Not repeatable
 
# Solution
  - Local setup [Repeatable] - One can do as much as R & D they want
  - CODE - IAAC
  -  R & D in your local machine
 
# Tools
- Hypervisor - Oracle VM virtuabox
- Automation - Vagrant tool
- CLI - GitBash
- IDE - VS code/Sublime/Notepad++ (any)

# Objective
- VM automation locally
- Baseline for furture real-time projects
- Real word project setup locally [For R & D]

# Architecture of project services
- NGINX
- TOMCAT
- RABBITMQ
- MEMACED
- MYSQL

# Architecture of Automated setup
- Vagrant tool
- Virtual box
- GitBash

  ![image](https://github.com/uzair-ansar/devops/assets/146664651/350e5519-7e5b-413d-901f-9f5e43497492)

  

# Prerequisites
- JDK 11 
- Maven 3 
- MySQL 8

# Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- Tomcat
- MySQL
- Memcached
- Rabbitmq
- ElasticSearch
# Database
Here,we used Mysql DB 
sql dump file:
- /src/main/resources/db_backup.sql
- db_backup.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < db_backup.sql
