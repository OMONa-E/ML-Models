# Machine Learning Models: Regression and Classification Tasks

## Author
Omona Emmanuel

---

## Overview

This repository contains machine learning models for both regression and classification tasks. Two distinct datasets are utilized for these tasks:

1. **Wine Price / Quality Prediction Model**
2. **Water Pump Functionality Prediction Model**

---

## Wine Price / Quality Prediction Model

### Dataset Description

The dataset comprises information about red variants of Spanish wines, including various popularity and description metrics affecting quality. This dataset can be utilized for classification or regression tasks. The classes are ordered and not balanced, ranging from almost 5 to 4 points. The task involves predicting either the quality of wine or the prices using the given data.

#### Target Vector: `price`

- Each row represents a **Product**.
- Our problem is a **Regression** task.
- The dataset comprises 7500 entries (rows) and 11 columns (Features).
- Challenges in data cleaning may involve handling missing values, outliers, and ensuring data consistency.

**Attribute Information (Data Dictionary):**

- `winery`: Winery name.
- `wine`: Name of the wine.
- `year`: Year in which the grapes were harvested.
- `rating`: Average rating given to the wine by users (1-5).
- `num_reviews`: Number of users that reviewed the wine.
- `country`: Country of origin (Spain).
- `region`: Region of the wine.
- `price`: Price in euros (€).
- `type`: Wine variety.
- `body`: Body score, indicating the richness and weight of the wine (1-5).
- `acidity`: Acidity score, representing the tartness of the wine (1-5).

[Source: fedesoriano. Spanish Wine Quality Dataset. Kaggle.](https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)

---

## Water Pump Functionality Prediction Model

### Dataset Description

The dataset, sourced from Taarifa and the Tanzanian Ministry of Water, provides information about water pumps and their operational metrics. It can be used for classification tasks, particularly to predict if a given water pump is faulty.

#### Target Vector: `status_group`

- Each row represents an **Event**.
- Our problem is a **Classification** task.
- The dataset comprises 59,400 entries (rows) and 40 columns (Features).
- Challenges in data cleaning and exploration may involve handling missing values, feature engineering, and understanding the relationships between features and the target variable.

**Attribute Information (Data Dictionary):**

- `amount_tsh`: Total static head (amount of water available to waterpoint).
- `date_recorded`: The date the row was entered.
- `funder`: Entity that funded the well.
- `gps_height`: Altitude of the well.
- `installer`: Organization that installed the well.
- `longitude`: GPS coordinate.
- `latitude`: GPS coordinate.
- `wpt_name`: Name of the waterpoint (if available).
- `num_private`: Indicator if the waterpoint is private.
- `basin`: Geographic water basin.
- `subvillage`: Geographic location.
- `region`: Geographic location.
- `region_code`: Geographic location (coded).
- `district_code`: Geographic location (coded).
- `lga`: Geographic location.
- `ward`: Geographic location.
- `population`: Population around the well.
- `public_meeting`: Boolean indicating if a public meeting was held to discuss the waterpoint.
- `recorded_by`: Group entering this row of data.
- `scheme_management`: Entity responsible for managing the waterpoint.
- `scheme_name`: Name of the scheme managing the waterpoint.
- `permit`: Indicator if the waterpoint is permitted.
- `construction_year`: Year the waterpoint was constructed.
- `extraction_type`: The kind of extraction the waterpoint uses.
- `extraction_type_group`: The kind of extraction the waterpoint uses (grouped).
- `extraction_type_class`: The kind of extraction the waterpoint uses (class).
- `management`: How the waterpoint is managed.
- `management_group`: How the waterpoint is managed (grouped).
- `payment`: What the water costs.
- `payment_type`: What the water costs (type).
- `water_quality`: The quality of the water.
- `quality_group`: The quality of the water (grouped).
- `quantity`: The quantity of water.
- `quantity_group`: The quantity of water (grouped).
- `source`: The source of the water.
- `source_type`: The source of the water (type).
- `source_class`: The source of the water (class).
- `waterpoint_type`: The kind of waterpoint.
- `waterpoint_type_group`: The kind of waterpoint (grouped).

Acknowledgements: This Data is taken from the Driven Data website. [Competition Link](https://www.drivendata.org/competitions/7/pump-it-up-data-mining-the-water-table/page/25/)
