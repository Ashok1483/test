
# Production Dashboard

An Excel dashboard analyzing production data across regions, product types, and managers, built with pivot tables and a summary dashboard view.

## File

- `Excel_Dashboard_2.xlsx`

## Contents

The workbook has 6 sheets:

| Sheet | Description |
|---|---|
| `Dashboard` | Summary dashboard view of key production metrics |
| `Pivot 1` | Total production cost by product type |
| `Pivot 2` | Number of tasks handled per manager |
| `Pivot 3` | Units produced by year and month |
| `Pivot 4` | Average production cost per unit by product type |
| `Production Dataset` | Raw underlying data (120 records) |

## Data Fields

The `Production Dataset` sheet includes the following columns:

- **ProductionID** – unique record identifier
- **ProductionDate** – date of production
- **Region** – region where production occurred (e.g. North, South, East, West)
- **Manager** – manager responsible for the batch
- **ProductType** – category of product (Automobiles, Electronics, Furniture, Machinery)
- **UnitsProduced** – number of units produced
- **TotalCost** – total production cost
- **Gender** – gender of the recorded individual
- **True Age** – age value
- **Age Groups** – age bracket classification
- **Production Cost Per Unit** – calculated cost per unit

## Key Insights

- **Total production cost** across all product types: **$3,371,078**
- **Automobiles** account for the highest total cost (**$1,152,805**), followed by Machinery (**$910,416**)
- **Furniture** has the highest average cost per unit (**$180.44**), while Electronics has the lowest (**$108.37**)
- **Nancy Grey** handled the most tasks (37), well ahead of the next-highest manager
- Production spans from **Sep 2023 to Sep 2024**, with **34,727 total units** produced over that period

## Notes

- This is a binary `.xlsx` file, so Git will track file-level changes only (no line-by-line diffs).
- Data appears to be sample/demo data used for dashboard practice.

## Usage

Open `Excel_Dashboard_2.xlsx` in Microsoft Excel or a compatible spreadsheet application (e.g. Google Sheets, LibreOffice Calc) to view the dashboard and interact with the pivot tables.
