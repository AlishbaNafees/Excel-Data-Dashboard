# Sales Performance Dashboard (Excel)

An Excel dashboard that ranks 141 sales executives across 8 regions against a fixed target of 500. Four pivot tables and three charts show who is ahead and who is furthest behind, and a region slicer narrows the view to any region you choose.

![Dashboard Preview](Excel_Dashboard_.png)

## Data

The Raw_Data sheet holds a sample dataset of 141 sales executives in Mumbai, Delhi, Nagpur, Chennai, Pune, Patna, Ranchi and Surat. Each row has five days of sales (Day1 to Day5) and the same target of 500. Calculated columns give each executive a Total Sales figure, a Target Hit % (total divided by target) and an Away From Target % (100% minus the hit rate).

## Dashboard

The Dashboard sheet has four pivot tables, each limited to five executives:

* Top 5 by Total Sales, shown with a bar chart
* Bottom 5 by Total Sales
* Top 5 by Target Hit %, shown with a pie chart
* Top 5 by Away From Target %, shown with a line chart

## Findings

Combined sales came to 38,945 against a combined target of 70,500, an average hit rate of 55.2%. No executive reached 500. Individual hit rates ranged from 28.6% in Mumbai to 77.8% in Surat. Nagpur had the highest average total per executive at 291.6, and Ranchi the lowest at 252.7.

## Using the workbook

Open the file in Excel and enable macros when prompted. Select a region in the slicer to filter the tables and charts, and clear the slicer to return to all 141 executives. The checkbox above each table, backed by a short macro called SlicerConnection, controls whether the slicer applies to that table.
