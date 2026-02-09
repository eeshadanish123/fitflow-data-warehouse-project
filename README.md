# FitFlow Fitness Data Warehouse & Analytics Project

## Overview
This project designs and implements a scalable data architecture for a multi-location fitness and wellness company. The system separates operational (OLTP) and analytical (OLAP) workloads to support real-time business operations while enabling historical analysis and decision-making.

## Key Components
- OLTP relational schema supporting memberships, bookings, payments, and check-ins  
- OLAP star schema with dimension and fact tables for revenue and attendance analytics  
- ETL pipeline built in Python (pandas, SQLAlchemy) to extract, transform, and load transactional data into the analytical warehouse  
- Interactive dashboard developed using Dash/Plotly for revenue trends, attendance analysis, and seasonality insights  
- Time-series forecasting models (SARIMA) for utilization and revenue prediction  

## Technologies
- SQL / Azure SQL Database  
- Python (pandas, SQLAlchemy, Dash, Plotly, statsmodels)  
- Data warehousing (OLTP → OLAP architecture)  
- Time-series modeling (SARIMA)  

## Repository Contents
- Project report (architecture, schema design, ETL workflow, and analysis)  
- SQL schema definitions and analytical design  
- Dashboard and forecasting methodology documentation  

