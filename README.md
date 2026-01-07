# The Hands-On Hub — Workshop Series

A collection of hands-on workshop materials for Python, Power Query, Power BI, and Power Automate. Includes static web pages, sample data, and Jupyter notebooks.

## Repository structure
- Web pages and styles:
  - [WebPage/index.html](WebPage/index.html)
  - [WebPage/python.html](WebPage/python.html)
  - [WebPage/powerquery.html](WebPage/powerquery.html)
  - [WebPage/powerbi.html](WebPage/powerbi.html)
  - [WebPage/powerautomate.html](WebPage/powerautomate.html)
  - [WebPage/style.css](WebPage/style.css)
  - [WebPage/image/](WebPage/image/)
- Sample data:
  - [Data/ItemBarcode.csv](Data/ItemBarcode.csv)
  - [Data/SalesData.csv](Data/SalesData.csv)
  - [Data/StoreCode.csv](Data/StoreCode.csv)
- Notebooks:
  - [PowerQuery/PowerQuery.ipynb](PowerQuery/PowerQuery.ipynb) — generates [Data/SalesData.csv](Data/SalesData.csv)
  - [Python/Python Workshop Beginner Day 1.ipynb](Python/Python Workshop Beginner Day 1.ipynb)
  - [Python/Python Workshop Beginner Day 2.ipynb](Python/Python Workshop Beginner Day 2.ipynb)
- Other folders:
  - [PowerBI/](PowerBI/)
  - [PowerAutomate/](PowerAutomate/)

## Quick start
- View site: open [WebPage/index.html](WebPage/index.html) in your browser, or serve locally:
```bash
python -m http.server 8000
# then open http://localhost:8000/WebPage/index.html
```
- Notebooks: open the .ipynb files in Jupyter or VS Code.
- Data: run [PowerQuery/PowerQuery.ipynb](PowerQuery/PowerQuery.ipynb) to regenerate [Data/SalesData.csv](Data/SalesData.csv).

## Contributing
- Suggestions, fixes, and improvements welcome via issues or pull requests.
- Add a LICENSE file if you want to set reuse terms.
