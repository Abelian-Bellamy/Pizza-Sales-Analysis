# 🍕 Pizza Sales Analysis

An interactive Power BI dashboard built to analyze pizza sales performance, ordering patterns, product performance, and seasonality.

## 📊 Project Overview

This project analyzes pizza sales data to answer four key business questions:

1. How many customers do we have each day, and are there peak ordering hours?
2. How many pizzas are typically included in an order, and which pizzas are bestsellers?
3. How much revenue was generated, and is there any seasonal pattern?
4. Are there pizzas that may need menu review, and are there opportunities for promotions?

> **Note:** The dataset does not contain a customer identifier, so customers per day cannot be directly calculated. Orders are therefore used as the measurable activity.

## 📈 Dashboard

![Pizza Sales Dashboard](dashboard/Pizza Sales Dashboard.png)

The dashboard brings together key performance indicators and visualizations covering revenue, orders, pizzas sold, ordering patterns, bestsellers, monthly revenue, and menu performance.

## 🔑 Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Revenue | $817,860 |
| Total Pizzas Sold | 49,574 |
| Total Orders | 21,350 |
| Average Orders per Day | 60 |
| Average Pizzas per Order | 2.32 |
| Active Ordering Days | 358 |

## 🕒 Ordering Patterns

Orders varied considerably throughout the day:

- **Afternoon:** ~9.8K orders
- **Evening:** ~6.7K
- **Night:** ~3.5K
- **Morning:** ~1.2K

The afternoon recorded the highest number of orders, while morning had the lowest.

This suggests that customer ordering activity is concentrated later in the day, particularly during the afternoon.

## 🍕 Pizzas per Order & Bestsellers

Customers purchased an average of **2.32 pizzas per order**.

The best-performing pizzas were identified by examining both quantity sold and revenue generated.

Some of the strongest performers included:

- The Barbecue Chicken Pizza
- The California Chicken Pizza
- The Classic Deluxe Pizza
- The Thai Chicken Pizza

Looking at both quantity and revenue provides a better picture of product performance than relying on either metric alone.

## 💰 Revenue & Seasonality

The business generated approximately **$817,860** in total revenue.

Monthly revenue showed noticeable fluctuations throughout the year.

**July recorded the strongest monthly revenue**, while revenue declined considerably after the peak, reaching its lowest levels around September/October before recovering in November.

This indicates a noticeable seasonal pattern in the dataset.

## 📋 Menu Performance

To identify pizzas that may require further review, each pizza's total quantity sold and total revenue were compared against the median performance across pizzas.

### Median Benchmarks

- **Median quantity:** 1,451.5 pizzas
- **Median revenue:** $24,734.38

Pizzas falling below both benchmarks were treated as low performers.

| Pizza | Quantity | Revenue |
|---|---:|---:|
| The Brie Carré Pizza | 490 | $11,588.50 |
| The Mediterranean Pizza | 934 | $15,360.50 |
| The Calabrese Pizza | 937 | $15,934.25 |

These results don't automatically mean these pizzas should be removed from the menu. They identify products that may warrant further investigation.

## 💡 Potential Business Opportunities

### Menu Review

Low-performing pizzas could be investigated further to understand whether their performance is related to pricing, customer preferences, or other factors before making menu decisions.

### Promotional Opportunities

Since July was the strongest sales period and revenue declined afterward, targeted promotions during weaker periods could be explored to help sustain demand.

These are **data-informed opportunities rather than conclusions about causation**. Additional information such as promotional history, costs, and customer-level data would be needed to evaluate them properly.

## 🛠️ Tools Used

- **Power BI** — Dashboard development and visualization
- **DAX** — Measures and calculations
- **Power Query** — Data preparation
- **Figma** — Dashboard UI/design concept

## 📄 Project Documentation

For the complete analysis and detailed findings:

**[View the Full Project Documentation](Pizza_Sales_Analysis_Documentation.pdf)**

## 📌 Final Takeaway

The analysis revealed that sales performance is influenced by **when customers order, which pizzas they purchase, and how demand changes throughout the year**.

Combining these dimensions provides a clearer view of the business than looking at total revenue alone.
