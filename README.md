# Maximizing Revenue with Customer Segmentation

This project focuses on customer segmentation to increase revenue through more targeted marketing strategies. Using clustering algorithms, we divided Amazon's customers into meaningful groups based on their purchasing behaviors. The primary goal is to develop strategies that enhance customer engagement and drive higher revenue.

## Table of Contents
1. [Project Description](#project-description)
2. [Key Features](#key-features)
3. [Dataset](#dataset)
4. [Methodology](#methodology)
5. [Results and Analysis](#results-and-analysis)
6. [Business Recommendations](#business-recommendations)
7. [How to Run the Project](#how-to-run-the-project)
8. [License](#license)
9. [Contact](#contact)

## Project Description
Customer segmentation involves dividing customers into groups based on similar characteristics or behaviors, such as purchase frequency, spending amount, and product preferences. This project aims to:
- Increase customer engagement.
- Identify high-value customers.
- Develop data-driven marketing strategies.

## Key Features
- **Automated Segmentation:** Use clustering algorithms to automatically segment customers.
- **Revenue Enhancement:** Segment-based strategies to boost Average Order Value (AOV) and purchase frequency.
- **Customer Retention:** Strategies to retain high-value customers.

## Dataset
The dataset contains Amazon's sales transaction data from 2020 and 2021, with a total of 286,392 records across 35 columns. It includes:
- **Transaction Details:** Order ID, date, quantity, payment method, and total value.
- **Customer Information:** Customer ID, age, gender, region, and contact information.
- **Product Details:** SKU, category, and discounts.
- **Geographical and Temporal Data:** City, state, zip code, and month of purchase.

## Methodology
- **Data Preprocessing:** Validating missing values, handling outliers, and ensuring correct data types.
- **Clustering:** Using the K-Means algorithm, which achieved the best silhouette score.
- **Model Evaluation:** Metrics such as Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Score were used to evaluate clustering quality.

## Results and Analysis
This project identified four distinct customer clusters with unique characteristics:
1. **Cluster 0:** Loyal customers with low purchase frequency.
2. **Cluster 1:** The largest group with high volume and moderate AOV.
3. **Cluster 2:** Tech-focused customers benefiting from high discounts.
4. **Cluster 3:** Premium customers with high-value orders.

Simulations suggest potential revenue increases of up to 92% with targeted strategies.

## Business Recommendations
1. **Increase Purchase Frequency:** Offer small discounts (2%-5%) to boost order volume.
2. **Upselling:** Promote premium products and bundling offers.
3. **Customer Retention:** Introduce loyalty programs for dormant customers and VIP programs for high-value customers.
4. **Targeted Marketing:** Use personalized campaigns based on cluster characteristics.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/Arsan24/Customer-Segmentation.git

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Contact

For any inquiries or further information, feel free to contact:

- **Email:** [arsan.nuzhairil@gmail.com](mailto:arsan.nuzhairil@gmail.com)  
- **GitHub Profile:** [Arsan24](https://github.com/Arsan24)  
- **LinkedIn:** [Nuzhairil Arsanurrahman](https://www.linkedin.com/in/nuzhairil-arsanurrahman-637315235/)
