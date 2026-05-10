# Financial_Transactions_data

# Working with JSON Files in Python

This notebook explores how to fetch JSON data from the internet, convert it into a structured table, and save it as a CSV file.

I did this using two different JSON sources to understand how different JSON structures affect the process.

---

## Tools Used:

- Python
- requests method - fetches data from a URL
- pandas - converts and structures the data
- Google Colab

---

## What I Did

### 1. Fetched JSON Data from a URL
I used the `requests` library to pull JSON data directly from a raw GitHub link and from the DummyJSON API.

After fetching, I used `.json()` to convert the response into something Python can work with.

### 2. Converted to a DataFrame
I used `pandas` to turn the JSON data into a proper table with rows and columns.

### 3. Saved as a CSV
Finally, I saved the structured data as a `.csv` file.
