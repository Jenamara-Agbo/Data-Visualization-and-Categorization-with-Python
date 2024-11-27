# README: Data Visualization and Categorization with Python

This project demonstrates essential data visualization techniques, working with datasets, and performing categorical analysis. Below are the main sections of the project:

## Data Visualization: Unemployment Rates by Education Level
The project uses unemployment data (`ed_unemployment_historic.csv`) to explore trends in unemployment rates based on educational attainment.

### Key Steps:
1. **Loading the Data:**
   - Uses `pandas` to load a CSV file into a DataFrame.
   - Sets the `Year` column as the index for time-series plotting.
2. **Renaming Columns:**
   - Simplifies column names for easier access (e.g., `Masters_degree` → `Masters`).
3. **Plotting:**
   - Visualizes unemployment trends for different educational levels.
   - Demonstrates:
     - Color customization (e.g., using named colors like `'cornflowerblue'` and hex codes).
     - Use of line styles, markers, and legends.
     - Adding titles, labels, and annotations (e.g., marking the "Financial Crisis").
4. **Advanced Visualization:**
   - Creates comprehensive plots with all education levels.
   - Highlights customization with dark gradient colors and appropriate legends.

---

## Terrorism Data Analysis: RAND Database
Analyzes the motivations behind terrorism incidents using the RAND Database of Worldwide Terrorism Incidents.

### Key Steps:
1. **Loading and Preparing Data:**
   - Reads the dataset (`RAND_Database_of_Worldwide_Terrorism_Incidents.csv`) using `pandas`.
   - Adds a `Case_ID` column and sets it as the index for better identification.
2. **Motivation Categorization:**
   - Uses a text-based keyword matching approach to categorize incidents as:
     - `Economic`
     - `Political`
     - `Religious`
     - Combinations of these categories (e.g., `Economic-Political`).
3. **Categorization Logic:**
   - Defines keywords and phrases for each category (e.g., "ransom" for `Economic`, "jihad" for `Religious`).
   - Matches descriptions with these keywords to assign a category.
4. **Results Visualization:**
   - Counts and plots the frequency of each motivation category using bar charts.

---

## Tools and Libraries
The project leverages:
- **`pandas`**: For data manipulation and preprocessing.
- **`matplotlib`**: For plotting and visualization.
- **`numpy`**: For numerical operations.
- **Keyword Matching**: To categorize text data.

---

## Highlights
1. **Educational Data:**
   - Demonstrates practical visualization techniques to analyze unemployment rates over time.
   - Customizes plots with legends, labels, and annotations.
2. **Terrorism Data:**
   - Illustrates text categorization with logical reasoning and keyword matching.
   - Provides insights into terrorism motivations through advanced plotting.

This project serves as a resource for anyone looking to explore data visualization and text-based categorization using Python.
