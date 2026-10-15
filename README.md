# AD450-javabeans-sales
JavaBeans beverage sales analysis using Python and Pandas.

Course Assignment: Creating a DataFrame in Pandas
Due Date: October 11, 2026, at 11:59 PM
Status: In Progress

## Objective

Learn how to create, index, and manipulate a Pandas DataFrame from scratch. This project simulates a real-world business analytics scenario in which historical coffee sales data is organized and analyzed to identify performance trends and support business decisions.

## Business Context

JavaBeans is a growing coffee chain that wants to analyze its historical beverage sales to make informed decisions about future marketing strategies and menu offerings.

As a data analyst, the goal is to reconstruct the company's manual sales records into a structured Pandas DataFrame, calculate sales totals and year-over-year growth, and provide strategic recommendations based on the results.

Technologies Used
Python — Programming language
Pandas — Data manipulation and analysis
Jupyter Notebook — Interactive coding and documentation
uv — Python project and dependency management
VS Code — Development environment

## Project Setup
1. Initialize the Project

Open the integrated terminal in VS Code and create the project:

uv init javabeans-sales
cd javabeans-sales


Open the javabeans-sales folder in VS Code.

2. Install Dependencies

Install Pandas and Jupyter Notebook:

uv add pandas notebook


The dependencies will be recorded in pyproject.toml, and uv.lock will track the resolved package versions.

3. Create the Notebook

Create a notebook named:

dataframe_creation.ipynb


In VS Code, select Select Kernel and choose the Python environment managed by uv.

4. Run the Notebook

Launch Jupyter Notebook using:

uv run jupyter notebook


Alternatively, open dataframe_creation.ipynb directly in VS Code and execute the cells using the selected Python kernel.

## Project Tasks
Part 1: Construct the DataFrame

Create a Pandas DataFrame named coffee_sales using a Python dictionary or NumPy array.

The DataFrame must contain the following sales data:

Year (Index)	Americano	Latte	Espresso	Cappuccino
2021 Sales	5628	12426	852	8522
2022 Sales	6239	25384	756	7561

The row index and column names must match the assignment requirements exactly.

Part 2: Data Manipulation

Use Pandas operations to perform the following analyses:

Total Product Sales: Calculate the cumulative sales for each beverage across 2021 and 2022.
Year-over-Year (YoY) Growth: Calculate the percentage growth or decline for each beverage from 2021 to 2022.

Display the results clearly in the notebook.

Part 3: Business Insights and Strategy

Use Pandas operations to answer the following questions:

Which beverage had the highest sales in 2021?
Which beverage had the lowest sales in 2021?
Which beverage had the highest sales in 2022?
Which beverage had the lowest sales in 2022?
What do the sales totals and YoY growth rates reveal about customer preferences and product performance?
Which beverages should receive additional marketing investment?
Should any beverages be considered for redesign or removal from the menu?

Include a strategic analysis of one to two paragraphs in a Markdown cell in the notebook. Support the recommendations with the calculated sales figures and growth rates.

Expected Project Structure

After completing the assignment, the project should have a structure similar to the following:

javabeans-sales/
├── README.md
├── pyproject.toml
├── uv.lock
└── dataframe_creation.ipynb


Additional source files or folders may be included if needed.

## Submission Requirements

Submit the completed project workspace containing:

pyproject.toml — Project configuration and dependency manifest.
uv.lock — Locked dependency versions.
dataframe_creation.ipynb — Completed and executed Jupyter Notebook.

The notebook must include:

Markdown headings explaining each part of the assignment.
Python code with appropriate comments.
The completed coffee_sales DataFrame.
Visible outputs for total sales and YoY growth calculations.
Answers identifying the best-selling and least-selling beverages for both years.
A written strategic analysis with business recommendations.
Project Goal

Transform JavaBeans' historical coffee sales records into meaningful business insights using Python and Pandas. The final analysis should demonstrate foundational data manipulation skills and explain how sales trends can inform marketing investment and menu planning.

Repository: JavaBeans Sales Analysis
Primary Notebook: dataframe_creation.ipynb
