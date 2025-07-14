# 🏈 Fantasy Football Stats Scraper (2017–2024)

This project scrapes historical fantasy football player statistics from [Pro-Football-Reference](https://www.pro-football-reference.com/) for the NFL seasons from **2017 through 2024**.

---

## 📦 Features

- Scrapes fantasy data by season (2017–2024)
- Extracts data from within HTML comments using `BeautifulSoup`
- Normalizes and cleans column names
- Fills missing values and converts numeric fields
- Splits the full dataset into **individual season DataFrames**
- Ready for fantasy draft analysis and model building

---

## 🔧 Technologies Used

- Python 3
- Pandas
- Requests
- BeautifulSoup

---

## 🗂️ Project Structure

```
fantasy_football_scraper.ipynb   # Jupyter Notebook with scraping and cleaning logic
README.md                        # You're here!
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open the `fantasy_football_scraper.ipynb` notebook in VS Code or Jupyter.
3. Run the cells step-by-step to:
   - Scrape fantasy data
   - Normalize column names
   - Clean missing data
   - Split into individual seasons

---

## 📊 Example Output

After splitting, you can access seasons like:

```python
season_dfs[2020].head()
season_dfs[2023]['player'].value_counts()
```

---

## 🧠 Next Steps (Coming Soon)

- Generate top 5 players per position by season
- Calculate fantasy points per game
- Merge with Average Draft Position (ADP) data
- Build a draft recommendation engine

---

## 🙌 Contributions

Pull requests and fantasy feature suggestions are welcome!

---

## 📜 License

MIT License
