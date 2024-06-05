In this analysis, we started by loading the dataset using pandas and inspecting its structure to understand its composition. We checked the shape of the data and previewed the first few rows, which provided an initial overview of the dataset. Following this, we identified and cleaned null values by removing rows with missing data to ensure the dataset's integrity.

To further refine the data, we focused on cleaning the 'Rating' column by removing any unwanted characters and converting the data type to float. This step was essential to facilitate accurate numerical analysis of ratings.

Next, we visualized the distribution of colleges by sector (Private vs Public) using a count plot. This visualization helped us understand the proportion of colleges in each sector, providing insights into the overall landscape of educational institutions.

We then analyzed the distribution of ratings by plotting a histogram with a Kernel Density Estimate (KDE). This approach allowed us to see how ratings were spread across the dataset and identify any notable trends or patterns in the data.

To gain a deeper understanding of the study programs offered, we split the 'Study Program' column into multiple rows, ensuring each row represented an individual study program. This process, known as exploding the column, enabled us to identify and highlight the top 10 most common study programs.
