# Replenishment Recommendation Engine

[Home](https://github.com/pembers1/portfolio-homepage#data-analytics--business-intelligence-portfolio)

## Project Summary
Developed a VBA-based replenishment review tool to provide a quick overview of output levels, replenishment settings and reserve codes across large datasets.

The tool was created to support manual review by highlighting styles that may warrant further investigation. It serves as an optional sense-checking tool rather than a replacement for existing replenishment processes or commercial decision-making.

## Business Problem
Reviewing replenishment outputs across hundreds of styles can require significant manual analysis.

While the existing process remains the primary method of review, there was no simple way to quickly identify styles where stock outputs or replenishment settings appeared unusual and may benefit from additional investigation.

## Solution Developed
Developed a VBA-based tool that analyses stock position, warehouse availability, future deliveries and recent trading performance to generate indicative replenishment recommendations and exception reports.

The objective was to provide a quick secondary review process that could highlight potential anomalies and support manual decision-making.

## Methodology




## Business Impact
Improved Review Efficiency
* Provides a quick overview of replenishment outputs across large datasets.

Faster Identification of Exceptions
* Highlights styles that may require additional review.

Supports Decision Making
* Acts as a supplementary review tool alongside existing replenishment processes.

Reduced Manual Searching
* Allows users to focus attention on styles where outputs appear unusual or inconsistent.

## Tools & Technologies Used
* MAPPER
* Other Internal Systems
* Microsoft Excel
* Office Scripts
* VBA (Visual Basic for Applications)

## Screenshots & Workflow Evidence
The screenshots below demonstrate the workflow used to identify size-level inventory imbalances across the retail network. They show how stock data was extracted, transformed, analysed, and automatically flagged to highlight styles with unusual size distributions that may require further investigation.

To protect commercially sensitive information, all screenshots used anonymized or representative data. The workflow, logic, and outputs accurately reflect the process used within the solution.

### Screenshot 1: Data Gathering in MAPPER
This screenshot shows the custom MAPPER query used to retrieve inventory data by style, size, and location across the business. The report was specifically designed to provide the detailed stock information required for identifying size distribution anomalies.

![Image Alt](https://github.com/pembers1/project-1/blob/main/Screenshot%202026-07-08%20123143.png?raw=true)

### Screenshot 2: Data Transformed in Excel
This screenshot demonstrates the exported inventory data was imported into Microsoft Excel and prepared for automated analysis. The data structure was organised to support size-level calculations and ensure consistent processing across large inventory datasets.

![Image Alt](https://github.com/pembers1/project-1/blob/main/Screenshot%202026-07-08%20140219.png?raw=true)

### Screenshot 3: Office Script Automation
This screenshot shows the Office Script used to automate the analysis process. The script applies predefined business rules, calculates size distribution percentages, and removes the need for manual review of individual size positions.

The automation standardises the process, improves consistency, and significantly reduces the time required to identify potential inventory issues.

![Image Alt](https://github.com/pembers1/project-1/blob/main/Screenshot%202026-07-08%20140616.png?raw=true)

### Screenshot 4: Office Script Automation
This screenshot shows the output after the automation has been executed. The model calculates the percentage contribution of each size against the total stock position for a style and automatically flags styles where a single size exceeds the defined threshold.

Items highlighted as Overweight indicate an unusually high concentration of stock in a particular size and are automatically marked for further investigation.

These anomalies can often indicate marketplace listing issues, missing sizes on online channels, inventory imbalances, or potential stock recall opportunities

![Image Alt](https://github.com/pembers1/project-1/blob/main/Screenshot%202026-07-08%20140630.png?raw=true)

### Screenshot 5: Filtered Exception Reporting
This screenshot demonstrates how the automated output can be filtered to focus exclusively on flagged styles. This exception-based approach allows stock controllers to concentrate on potential issues rather than manually reviewing every style within the dataset.

![Image Alt](https://github.com/pembers1/project-1/blob/main/Screenshot%202026-07-08%20141056.png?raw=true)

### Screenshot 6: Adjustable Business Rules
This screenshot shows how the threshold used to generate an Overweight flag can be configured within the Office Script.

In this example, styles are flagged when a single size accounts for more than 60% of total stock for that style. By adjusting this value, the tool can be tailored to match changing business requirements and inventory management strategies.

![Image Alt](https://github.com/pembers1/project-1/blob/main/Screenshot%202026-07-08%20141148.png?raw=true)

## Skills Demonstrated
* Data Preparation
* Data Transformation
* Data Analysis
* Inventory Analysis
* Office Scripts
* Excel Automation
* Exception Reporting
* Business Analysis
* Business Process Improvement
* Root Cause Investigation
* Data-Driven Decision Making
