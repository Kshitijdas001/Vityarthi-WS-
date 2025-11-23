# Flipkart Laptops Under ₹40,000 Scraper

### Real-Life Problem it Solves
- You want a laptop ≤ 40,000 rupess but don’t want to open 50 tabs.
- Need to quickly compare price + RAM + processor + display across brands.
- Flipkart’s own filters are okay but still make you click each product.
- Perfect for students/parents who just want “good enough” without wasting hours.

### Features of the solution
- Scrapes first 2 pages (~48 laptops) within under 10 seconds and sorted it in very simple way.
- Extraction: Product name, current price, discription of the laptop (RAM, processor, display, etc.).
- Saves straight to `laptops_flipkart.csv` — open in Excel/Google Sheets and sort however you want. 
- It saves a lot of time with zero login, zero captcha headaches (for now).

### Technologies Used
- Python (because who uses anything else for this?).
- `requests` → to fetch the page.
- `BeautifulSoup` + `lxml` → to parse the messy HTML.
- `pandas` → to throw everything into a clean table.


## Working of the project
- Scrapes first 2 pages of search results for "laptop under 40000".
- Grabs: Product name, Price, Key specs/highlights.
- Dumps everything into `laptops_flipkart.csv`.

### How to run THE PROGRAM
pip install pandas requests beautifulsoup4 lxml.
python flipkart_laptops.py.

