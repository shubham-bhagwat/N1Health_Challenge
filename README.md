# N1Health_Challenge

## Introduction
This project was conducted to analyze the client membership data provided by the project manager. The analysis was conducted using Python and SQLite, and the main objective was to generate insights into the client's membership.

## Methodology
The following steps were taken to analyze the data:

- Combined the member rosters into a single table called ‘std_member_info’. Only included members who were eligible during April 2022, resulting in a table with one row per member. Standardized the columns to include member ID, first and last name, date of birth, main address, city, state, zip code, and payer information.
- Identified that there were 105,680 distinct members who were eligible in April 2022.
- Found that the data did not have any Null values, however, identified that there were 23,485 members included more than once in the data. Thus, updated the ‘std_member_info’ table by removing these duplicate values for accurate analysis further.
- Identified that the members were primarily covered by two payers: ‘Madv’ and ‘Mdcd’. ‘Madv’ covered 39,539 members, while ‘Mdcd’ covered 66,141 members.
- Found that 8,127 members were living in a zip code with a food access score lower than 2.
- Identified that the average social isolation score for the members was 3.07.
- Found that there were 49 members living in the zip code i.e., 95950 where the ‘algorex_sdoh_composite_score’ is the highest.

## Findings
The analysis provided valuable insights into the client's membership and will help inform further analysis and decision-making. However, some data quality issues were encountered during the analysis, such as duplicate information in rosters. These issues were resolved through careful data cleaning and manipulation.

## Conclusion
The project was conducted successfully, and the analysis provided useful insights into the client's membership. The findings will be helpful in making informed decisions regarding the client's membership. If you have any questions or need further assistance, please feel free to reach out. Thank you for the opportunity to work on this project.

