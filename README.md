# Smart India Hackathon Workshop
# Date: 17-11-2026
## Reference Number: 26004326
## Name: J. Shyam Sundar

## Problem Title
SIH 26033: Multiple intermediaries reduce farmers earnings and increase consumer prices.

## Problem Creater's Organization
Ministry of Consumer Affairs, Food & Public Distribution

## Theme
Agriculture, FoodTech & Rural Development

## Problem Description
Expected Solution: Create a digital marketplace that:

• Connects farmers/FPOs directly with consumers and bulk buyers.
• Provides logistics support.
• Uses AI for demand forecasting and route optimization.

Benefits:

• Better prices for farmers.
• Lower prices for consumers.
• Reduced supply chain inefficiencies.

## Proposed Solution
CropCircle is a simple web app that helps small farmers find buyers for their produce. Farmers list a crop, quantity, price, and area. Buyers enter the crop and quantity they need. If one farmer cannot fill the order, CropCircle suggests combining listings from several farmers nearby.

For example, if a buyer needs 50 kg of tomatoes and three farmers list 20 kg, 15 kg, and 15 kg, the app shows that their listings together can meet the order. The buyer can then contact the farmers or their FPO to arrange the sale.

The main feature is grouping small farmer listings to help fill a larger buyer order. This gives buyers a simple way to find enough produce and gives small farmers a chance to be included. For the first version, pickup and payment are arranged directly between the buyer and farmers.

## Technical Approach
Technologies: HTML, CSS, and JavaScript for the website; Python with Flask for the backend; and SQLite to store farmer listings and buyer requests.

Methodology:
1. A farmer submits a crop listing with quantity, price, and area.
2. A buyer submits a request with the crop and required quantity.
3. The app finds listings for the same crop.
4. It adds the quantities until they meet the buyer’s requested amount.
5. It shows the suggested farmer group, or reports that there is not enough produce listed.
   
   <img width="912" height="566" alt="image" src="https://github.com/user-attachments/assets/48b9b390-bead-41b2-bc38-568853d677a0" />



## Feasibility and Viability
This project is suitable for a beginner because it uses forms, a small database, and basic searching and addition. A prototype can be tested with sample farmer listings and buyer requests.

Possible challenges include incorrect quantities, differences in produce quality, and farmers being too far apart. The first version can focus on one crop and one area. Farmers or an FPO should confirm the produce, pickup, and payment details before a real sale.

## Impact and Benefits
1. Small farmers can be found by buyers even when they have less produce than the buyer needs.
2. Buyers can see whether several farmer listings together meet their requested quantity.
3. Farmers and buyers can view crop, quantity, and asking price in one place.
4. The prototype demonstrates a simple way to connect farmers directly with buyers.

## Research and References
1. SIH 26033 problem statement and submission template: GitHub repository
2. e-NAM, the Government of India’s online agricultural trading platform: Official e-NAM website
