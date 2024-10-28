
# Singapore Business Entities Dashboard

This repository contains a Tableau dashboard that visualizes business entity data for Singapore. The dashboard provides insights into entity types, registration trends, geographic distribution, and other key metrics.

## Overview

The **Singapore Business Entities Dashboard** is designed to give a high-level overview of business registration data across various metrics, including entity types, geographic distribution by postal codes, and business constitution. The data visualizations help identify trends in business registration and concentration across Singapore.

## Visualizations

The dashboard includes the following seven visualizations:

1. **Entity Type Distribution** - Shows the count of unique entity types (e.g., Business, Foreign Company, LLP).
2. **Entity Status Overview** - Segregates entities into Active, Inactive, and Not Available categories.
3. **Time-series Registration Trends** - Plots business registration/incorporation counts over time.
4. **Business Constitution Share** - Displays the proportion of different business constitutions, such as Sole Proprietorship, Partnership, etc.
5. **Geographic Distribution** - Visualizes business distribution on a map of Singapore based on postal codes.
6. **Postal Code Density** - Represents the density of business registrations per postal code.
7. **SSIC Description Breakdown** - Highlights the breakdown of business sectors based on primary SSIC (Singapore Standard Industrial Classification) descriptions.

## Assumptions

- **Geographic Location**: The postal codes are assumed to be located in Singapore. This assumption was used to ensure that Tableau mapped the locations correctly, as some postal codes might be interpreted incorrectly if no country is specified.
- **Active vs. Inactive Status**: Entity status values were grouped under Active and Inactive categories for a simpler, high-level analysis. 

## File Contents

- **Dashboard.twbx**: Tableau workbook file containing the visualizations and dashboard layout.
- **Dashboard.jpg**: Static image of the dashboard for easy preview without opening Tableau.

## Instructions

1. **View Dashboard**: If you have Tableau installed, open the `.twbx` file to explore the interactive dashboard.
2. **Explore on GitHub**: If you don’t have Tableau, you can view the `.jpg` file for a static preview of the dashboard layout.

## Filtering and Customization

- The **Geographic Distribution** map is filtered to show the top 10-20 postal codes by frequency to avoid clutter. This setting can be adjusted by modifying the filters within Tableau.
- Entity status categories have been grouped to provide a cleaner view of active and inactive businesses.

## Usage

The dashboard can be used by analysts, business researchers, or policymakers to:

- Identify trends in business registrations over time.
- Analyze the concentration of business entities across various regions in Singapore.
- Understand the distribution of business entity types and sectors.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
