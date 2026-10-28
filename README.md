# supply-chain-inventory-optimization
Data-driven supply chain analytics project for inventory optimization, product segmentation, and supplier performance analysis using Python, Machine Learning, Excel, and Power BI.
# 📦 Supply Chain Analytics & Inventory Optimization using Machine Learning

## 📌 Project Overview

This project presents a **data-driven Supply Chain Decision Support System** designed to analyze inventory, product characteristics, and supplier performance.

The project combines traditional inventory-management techniques with data analytics and machine learning to support better supply chain decision-making.

The analysis covers a synthetic supply chain dataset for the period **January 2023 – December 2025**, including **500 products, 30 suppliers, and 5 warehouses**.

> **Note:** The dataset used in this project is synthetic. The results demonstrate the analytical approach and workflow and should not be interpreted as actual business savings or real-company performance.

---

## 🎯 Objectives

The main objective of this project is to build a data-driven framework that combines:

- Inventory optimization
- Product classification and segmentation
- Supplier performance analysis
- Data visualization and decision support

### Specific Objectives

1. Clean, validate, and explore supply chain data.
2. Classify products using **ABC Analysis**.
3. Segment products using **K-Means Clustering**.
4. Calculate **Economic Order Quantity (EOQ)**.
5. Calculate **Safety Stock**.
6. Determine **Reorder Point (ROP)**.
7. Evaluate supplier performance using key supply chain metrics.
8. Develop an interactive **Power BI dashboard** for decision support.

---

## 🗂️ Dataset

The project uses a **synthetic supply chain dataset** covering three years:

**January 2023 – December 2025**

The dataset contains information related to:

- Products
- Suppliers
- Orders
- Deliveries
- Inventory
- Warehouses
- Product costs
- Demand
- Lead time

### Dataset Scale

| Category | Count |
|---|---:|
| Products | 500 |
| Suppliers | 30 |
| Warehouses | 5 |
| Time Period | 2023–2025 |

---

## 🔄 Project Methodology

The project follows the following workflow:

```text
Data Collection
      ↓
Data Preparation
      ↓
Exploratory Data Analysis
      ↓
Product Classification & Segmentation
      ↓
Inventory Optimization
      ↓
Supplier Performance Analysis
      ↓
Power BI Dashboard
      ↓
Decision Support
```

---

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis was performed to understand the major patterns in the supply chain data.

The analysis includes:

- Demand patterns
- Sales and order patterns
- Inventory levels
- Inventory value
- Supplier delivery performance
- Lead-time patterns
- Product characteristics
- Stockout-related indicators

---

## 📊 ABC Analysis

ABC Analysis is used to classify products according to their **annual consumption value**.

The annual consumption value is calculated as:

```text
Annual Consumption Value
= Annual Demand × Unit Cost
```

Products are categorized into:

- **A:** High-value products requiring closer inventory control
- **B:** Medium-value products requiring moderate control
- **C:** Lower-value products requiring comparatively simpler control

ABC Analysis helps prioritize inventory-management efforts.

---

## 🤖 K-Means Clustering

**K-Means Clustering** is an unsupervised machine-learning technique used to group products based on similarities in their characteristics.

The project uses product-related numerical features to identify different product segments.

The clustering process involves:

1. Selecting relevant numerical features.
2. Preparing and scaling the features.
3. Selecting the number of clusters.
4. Applying K-Means.
5. Assigning products to clusters.
6. Analyzing the characteristics of each cluster.

This provides a different perspective from ABC Analysis because K-Means considers multiple product characteristics rather than only consumption value.

---

## 📦 Inventory Optimization

The project applies three major inventory-management calculations:

### 1. Economic Order Quantity (EOQ)

EOQ estimates an appropriate order quantity by balancing ordering and holding costs.

```text
EOQ = √(2DS / H)
```

Where:

- `D` = Annual demand
- `S` = Ordering cost per order
- `H` = Annual holding cost per unit

---

### 2. Safety Stock

Safety Stock acts as a buffer against demand variability and supplier lead-time uncertainty.

The project uses:

```text
Safety Stock = Z × σd × √L
```

Where:

- `Z` = Service-level factor
- `σd` = Standard deviation of daily demand
- `L` = Average lead time

---

### 3. Reorder Point (ROP)

The Reorder Point indicates the inventory level at which replenishment should be considered.

```text
ROP = (Average Daily Demand × Lead Time) + Safety Stock
```

These calculations are used to support inventory replenishment analysis.

---

## 🚚 Supplier Performance Analysis

Supplier performance is evaluated using multiple operational indicators.

The analysis includes:

- **On-Time Delivery**
- **Defect Rate**
- **Order Fulfillment**
- **Average Lead Time**

These metrics are combined into a supplier-performance scoring framework to help compare supplier reliability.

The supplier
