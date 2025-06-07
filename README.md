# Analyzing Parcel Shipments to Mexico  
**Correlation Between Parcel Count and Container Weight**

⚠️ **The data presented here is fictitious and does not contain any real or confidential information. A map of Cuba was used as an example to illustrate how the cities would appear.**

In this project, 8 months of shipment data were analyzed to identify which provinces send the most parcels to Mexico.  
Tableau was used to create a scatter plot to determine the correlation between the number of parcels shipped per container and the total weight shipped per container — since container pricing is based on weight.

---

## ⚙️ Workflow

### 1️⃣ Data Cleaning
- Renamed columns for consistency and standardization.
- Converted data types (dates, zip codes, text fields).
- Corrected typographical errors in city and state names.

### 2️⃣ Item Classification
- Classified shipments as either **Durable** or **Miscellaneous**.
- Further sub-classified durable goods into categories such as:
  - TV
  - Generator
  - Motorcycle
  - Mattress
  - Solar Panel
  - Car Parts
  - Bike
  - Kitchen utensils
  - Other unspecified durable goods.

### 3️⃣ Outlier Removal
- Removed records with:
  - Null `description` fields.
  - Weight greater than 700 kg (maximum business-defined threshold).

### 4️⃣ Unit Conversion
- Converted weight from kilograms to pounds to facilitate easier interpretation in subsequent analyses.

---

## 🛠️ Tools Used
- PostgreSQL
- Tableau

---

## 📊 Results
- Clean, standardized database ready for business analysis.
- Key insights obtained:
  - Identification of the region with the highest shipment volume.
  - Distribution of product types shipped.
  - Correlation between the number of parcels and the total weight shipped.

---

## 🚀 Next Steps
- Further visualization of results in Tableau.
- Implementation of automated reporting.
- Seasonal trend analysis of shipments.

---
