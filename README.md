# Support_ticket_analysis

## Overview
This project is focused on analyzing customer support data from 2022 to 2023. The goal is to assess the relationship between customer value and the amount of attention required in terms of number of tickets and time required to solve them. Some of the questions to be answered are: 
Understanding the amount of time required to solve a ticket and identifying trends of level of attention per customer.

## Dataset Description
The analysis is based on two primary datasets:
- `customers`: Contains information about customers, including account IDs, account names, and total Annual Recurring Revenue (ARR).
- `tickets`: Records individual support tickets with details such as creation and resolution dates.

## Features
The key features of the project include:
- Quantifying the number clients
- Analysis of the number of tickets submitted per customer.
- Segmentation of customers based on Annual revenue.
- Monthly trends of level of service required
- Trends of quality of service (time required to close a ticket)
- Calculation of the percentage of customers with fewer than 5 tickets.

## Requirements
This project uses PySpark to perform queries using SQL language especially handy where working with large databases
