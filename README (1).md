# COVID-19 Research Analysis

This project analyzes a dataset of COVID-19 research papers to provide
insights into publication trends, top journals, and frequent keywords.
The work includes data cleaning, exploratory analysis, and
visualization, and is deployed as a simple Streamlit app for interactive
exploration.

## Project Structure

-   `exploration.ipynb` → Jupyter notebook with data cleaning,
    exploration, and visualization.\
-   `app.py` → Streamlit web application for interactive analysis.\
-   `README.md` → Project documentation (this file).

## Findings

-   **Publication Trends:** Research activity peaked between 2020--2021,
    showing a strong global response to the pandemic.\
-   **Top Sources/Journals:** A small group of journals contributed a
    significant portion of COVID-19 publications.\
-   **Keyword Analysis:** Frequent keywords reflected major themes such
    as *COVID-19, pandemic response, vaccines, public health,* and
    *clinical studies*.

## Challenges and Learning

-   **Handling Missing Data:**\
    Initially, using `dropna()` removed nearly all rows because most had
    at least one missing value. This left the dataset empty, making
    further analysis impossible.\
    **Solution:** Instead of dropping rows, I dropped entire columns
    with a high percentage of missing values. This preserved enough data
    for meaningful analysis while reducing noise.

-   **Overlapping Labels in Plots:**\
    When plotting source distributions, x-axis labels overlapped and
    were unreadable.\
    **Solution:** Rotated labels by 90° to improve readability.

### Reflection

This project strengthened my skills in **data cleaning, exploratory data
analysis, and visualization**. I learned the importance of carefully
choosing missing data handling strategies and improving chart
readability for better communication of findings. The process also
showed how building an interactive Streamlit app can make analysis more
engaging and accessible.
