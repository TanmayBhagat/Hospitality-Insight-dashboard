# AtliQ Hospitality Analysis - Power BI

## Overview
As part of the **Codebasics Resume Challenge**, this project involves analyzing historical data for AtliQ Grands, a five-star hotel chain in India. AtliQ Grands has been facing a decline in market share and revenue due to competition and management inefficiencies. The goal of this project is to provide actionable insights that will help the company regain its market share in the luxury and business hotel segments.

## Project Links:
- [Challenge Details](https://codebasics.io/challenge/codebasics-resume-project-challenge)
- [Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiOTJkMTkwOTYtYTQ3MC00NDg5LWFjNzMtMGQwMzE0MzJkNzFkIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

## Problem Statement
AtliQ Grands has been in the hospitality industry for 20 years. They are losing their market share and revenue due to strategic missteps and lack of data-driven decision-making. To regain their position in the market, they have hired external data analytics services to analyze their historical data and provide insights.

The project involved:
- Creating key [metrics](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/metrics%20list.xlsx) as outlined by the stakeholders.
- Designing a dashboard based on a mock-up provided by the revenue management team.  
  ![Mockup Dashboard](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/mock%20up%20dashboard_atliq%20grands.png)
- Generating additional insights beyond the provided metrics.

## Key Deliverables:
- **Mock-up Dashboard**: Adhering to the stakeholder’s design specifications.
- **Data Model**: Created a structured data model for efficient analysis.  
  ![Data Model](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/Screenshot%202024-10-08%20120556.png)

## Key Insights from the Dashboard:
- Mumbai generates the highest revenue at ₹669M, followed by Bangalore, Hyderabad, and Delhi.
- AtliQ Exotica is the top-performing property, generating ₹320M in revenue, with a rating of 3.62, an occupancy rate of 57%, and a cancellation rate of 24.4%.
- AtliQ Bay has the highest occupancy rate at 66%.
- Week 24 recorded the highest revenue of ₹139.6M.
- Delhi leads in occupancy and rating, followed by Hyderabad, Mumbai, and Bangalore.
- AtliQ lost approximately ₹298M due to cancellations.
- Elite-type rooms have the highest booking volume but also the highest cancellation rate.

## Project Learnings:
- Explored hotel cancellation policies, understanding that most hotels charge 60-90% of the booking cost if cancellations occur within three months of the booking date.
- Mastered the use of bookmarks and creating clear filter buttons in Power BI dashboards.
- Applied a consistent color palette throughout the dashboard to ensure cohesive design.

## Technologies & Tools Used:
- **Power BI**: Data visualization and dashboard creation.
- **Excel**: Data preparation and initial exploration.

## How to Use:
Download the dataset and report files from the Downloads Section:

- [dim_date](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/dim_date.csv)
- [dim_hotels](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/dim_hotels.csv)
- [dim_rooms](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/dim_rooms.csv)
- [fact_aggregated_bookings](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/fact_aggregated_bookings.csv)
- [fact_bookings](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/fact_bookings.csv)

Open the Power BI report to interact with the dashboard and explore the insights.

![Revenue Insights GIF](https://github.com/TanmayBhagat/Hospitality-Insight-dashboard/blob/3ac28a599b1c7fb64915dec77e36f6120a695bda/revenue%20insight%20hospitality%20domain.gif)
