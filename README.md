# Views DB SQL Queries

## Problem and Solution Overview

### Problem to Solve

The `views.db` database contains information on 72 woodblock prints created by Japanese artists Katsushika Hokusai and Utagawa Hiroshige, showcasing various views of Mount Fuji. Each print includes attributes such as title, artist, average color, brightness, contrast, and entropy. The goal was to write SQL queries to extract meaningful insights from this database and address specific questions related to the prints.

### How I Used My Database Skills to Solve It

To address these challenges, I developed a series of SQL queries to retrieve and analyze data from the `views.db` database. Below is a summary of the problems addressed and the solutions provided:

1. **Listing Japanese and English Titles**:
   - **Problem**: Compare Japanese and English titles side by side for each print.
   - **Solution**: Created a query to list Japanese titles first, followed by English titles.

2. **Finding Average Colors for Hokusai’s Prints**:
   - **Problem**: Identify average colors of Hokusai’s prints with “river” in the English title.
   - **Solution**: Developed a query to list average colors for these prints.

3. **Counting Hokusai Prints with “Fuji” in the Title**:
   - **Problem**: Count how many of Hokusai’s prints include “Fuji” in the title.
   - **Solution**: Created a query to count these prints.

4. **Counting Hiroshige Prints Referring to “Eastern Capital”**:
   - **Problem**: Determine the number of Hiroshige’s prints with titles referring to “Eastern Capital” (Edo, now Tokyo).
   - **Solution**: Wrote a query to count these prints.

5. **Finding Highest Contrast Value for Hokusai’s Prints**:
   - **Problem**: Find the highest contrast value among Hokusai’s prints and assess its significance.
   - **Solution**: Developed a query to identify and label this maximum contrast value.

6. **Calculating Average Entropy for Hiroshige’s Prints**:
   - **Problem**: Calculate the average entropy of Hiroshige’s prints, rounded to two decimal places.
   - **Solution**: Created a query to compute and label the average entropy.

7. **Listing Brightest Prints by Hiroshige**:
   - **Problem**: List the 5 brightest prints by Hiroshige from most to least bright.
   - **Solution**: Wrote a query to retrieve and order these titles by brightness.

8. **Listing Prints with Least Contrast by Hokusai**:
   - **Problem**: Identify and list the 5 prints with the least contrast by Hokusai, from least to most contrast.
   - **Solution**: Developed a query to sort and list these prints accordingly.

9. **Finding Print with Highest Brightness**:
   - **Problem**: Determine the English title and artist of the print with the highest brightness.
   - **Solution**: Created a query to find and display the relevant details of this print.

10. **Exploring a Custom Query**:
    - **Problem**: Write a custom query to explore an additional question about the prints.
    - **Solution**: Developed a query involving column renaming, conditions, and sorting to answer a chosen question.

## Files

- `1.sql`: Lists Japanese and English titles side by side.
- `2.sql`: Lists average colors of Hokusai’s prints with “river” in the title.
- `3.sql`: Counts Hokusai prints with “Fuji” in the title.
- `4.sql`: Counts Hiroshige prints referring to “Eastern Capital”.
- `5.sql`: Finds the highest contrast value for Hokusai’s prints.
- `6.sql`: Calculates average entropy of Hiroshige’s prints.
- `7.sql`: Lists the 5 brightest prints by Hiroshige.
- `8.sql`: Lists the 5 prints with the least contrast by Hokusai.
- `9.sql`: Finds the print with the highest brightness.
- `10.sql`: Custom query based on additional exploration.

## Usage

To test the queries, you can run the following commands:

```bash
.read FILENAME
