# Web-Scraping-Intelligence-Tool

## Overview

This project is a **Web Scraping and Data Analysis** tool designed to collect information from websites and provide insights through statistical analysis and visualizations. It is modular, with separate components for data scraping (`scraper.py`) and analysis (`analyzer.py`), facilitating maintenance and extension.

## Features

-   **Data Scraping**: Collects data from specified URLs.
-   **Data Analysis**: Performs descriptive statistical analysis and builds a classification model (Random Forest) to identify patterns.
-   **Data Visualization**: Generates correlation plots, feature distribution, scatter plots, and feature importance to facilitate data understanding.

## Project Structure

```
Web-Scraping-Intelligence-Tool/
├── main.py
├── requirements.txt
├── src/
│   ├── __init__.py
│   ├── scraper.py
│   └── analyzer.py
└── tests/
    ├── __init__.py
    ├── test_scraper.py
    └── test_analyzer.py
```

-   `main.py`: Main entry point to perform scraping and analysis.
-   `requirements.txt`: Lists project dependencies.
-   `src/scraper.py`: Contains the logic for scraping data from websites.
-   `src/analyzer.py`: Contains the logic for analyzing and visualizing scraped data.
-   `tests/`: Contains unit tests for the `scraper` and `analyzer` modules.

## Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/galafis/Web-Scraping-Intelligence-Tool.git
    cd Web-Scraping-Intelligence-Tool
    ```

2.  **Create and activate a virtual environment (recommended):**

    ```bash
    python3.11 -m venv venv
    source venv/bin/activate  # On Linux/macOS
    # venv\Scripts\activate   # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the tool, you can use `main.py`:

```bash
python3.11 main.py
```

 The `main.py` script will:
1. Scrape data from an example URL (currently `http://example.com`).
2. Load the scraped data into the analyzer.
3. Perform statistical and machine learning analysis.
4. Generate visualizations and save them as `web_scraping_intelligence_tool_analysis.png`.

### Running Tests

To run the unit tests, navigate to the project root and execute:

```bash
python3.11 -m unittest discover tests
```

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

