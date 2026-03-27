AirBnB Pricing Analysis Dashboard

This project features a data-driven dashboard created in Tableau to analyze the factors influencing AirBnB pricing. By leveraging a pre-cleaned dataset, the analysis explores how property attributes, geographic location, and seasonal trends impact market value.

🛠️ The Stack

This project utilizes a modern data visualization stack focused on efficiency and clarity:

    Tableau Public / Desktop: Used for building the interactive dashboard and complex calculations.

    Data Processing: Pre-cleaned Excel/CSV dataset.

    Methodology:

        Data Aggregation: Grouping listings by physical attributes (Bedrooms) and temporal attributes (Month/Season).

        Geospatial Analysis: Utilizing Zipcodes to map regional price fluctuations.

        Time-Series Analysis: Tracking "Revenue for Year" to identify high-occupancy months.


📈 Key Insights & Visualizations
1. Pricing vs. Capacity (Avg Price per Bedrooms)

A bar chart demonstrating the direct correlation between the number of bedrooms and average price.

    Finding: Pricing scales significantly from $96.2 (1-bedroom) up to $584.8 (6-bedroom), indicating a premium on large-group accommodations.

2. Geographic Distribution (Price by Zipcode)

A granular look at pricing across different postal codes.

    Finding: The visualization identifies specific high-value neighborhoods where the average price consistently exceeds $150, regardless of apartment size.

3. Seasonality & Revenue (Revenue for Year)

A time-series line graph tracking revenue fluctuations over the 2016 calendar year.

    Finding: Revenue shows a steady climb through March, peaking in the summer months, which highlights the seasonality of when houses are most frequently "taken."


🚀 Usage & Deployment
How to Reproduce

    Clone the Repository:
    Bash

    git clone https://github.com/Furybuy/AirBnB-Project.git

    Open in Tableau: Launch Tableau Desktop or Tableau Public and open the AirBnB-Project.twb file.

    Data Connection: If prompted, point the data source to the included cleaned CSV/Excel file in the /Data folder.

Portfolio Highlights

    Business Intelligence: Demonstrates the ability to transform raw data into actionable insights for property owners.

    UI/UX Design: Focuses on a clean, tiled layout for high scannability and "at-a-glance" metric tracking.

    Data Storytelling: Connects disparate variables (location, size, and time) into a single cohesive narrative.
