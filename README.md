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

![Screenshot 2025-05-25 at 3 25 48 PM](https://github.com/user-attachments/assets/4f05124b-506a-403b-aad0-62678e98d6c2)
![Screenshot 2025-05-25 at 11 54 28 AM](https://github.com/user-attachments/assets/a0422cca-0edc-4ebc-9df5-ad7c67a54c8f)
![Screenshot 2025-05-25 at 11 57 04 AM](https://github.com/user-attachments/assets/1d71c67d-a06e-491b-b695-e852878a49c2)
![Screenshot 2025-05-25 at 11 56 25 AM](https://github.com/user-attachments/assets/3a65b95d-1673-4af6-bb34-a4c6f88b9964)

