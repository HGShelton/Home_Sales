# Home Sales

The analysis focused on examining home sale prices in California spanning the years 2019 to 2022. Google Colab and Spark were utilized for data ingestion and processing to address the specified inquiries.

- The average price by year for a four-bedroom house sold fore each year.
    ![image](https://github.com/user-attachments/assets/6467dd9d-1289-4606-bd65-e743d2a8d881)

- The average price of a home for each year the home was built, that has three bedrooms and three bathrooms.
    ![image](https://github.com/user-attachments/assets/0c03cb2e-431f-411c-b476-8d6170b1e3d6)

- The average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 sqft.
    ![image](https://github.com/user-attachments/assets/91442b43-3085-4d79-8cd6-2d1effb09a2c)

- The average price of a home per "view" rating having an average home price greater than or equal to $350,000.
    ![image](https://github.com/user-attachments/assets/1a44af6d-c5ed-48d4-8018-dc5863a529d0)

The last question was executed using different optimization techniques to compare query performance. The data was processed uncached, cached, and partitioned to determine the fastest runtime
- uncached: 1.127293586730957 seconds
- cached: 1.0387239456176758 seconds
- partitioned: 0.46766066551208496 seconds
