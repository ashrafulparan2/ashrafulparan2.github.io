# Jupyter notebook markdown generator

These .ipynb files are Jupyter notebook files that convert a TSV containing structured data about talks (`talks.tsv`) or presentations (`presentations.tsv`) into individual markdown files that will be properly formatted for the academicpages template. The notebooks contain a lot of documentation about the process. The .py files are pure python that do the same things if they are executed in a terminal, they just don't have pretty documentation.

## Requirements

- Python 3.x
- Jupyter Notebook
- pandas library

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/ashrafulparan2/markdown_generator.git
    cd markdown_generator
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas jupyter
    ```

3. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```
    Open the notebook file and follow the instructions to generate markdown files.

4. Alternatively, run the Python script:
    ```bash
    python generate_markdown.py
    ```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes.




