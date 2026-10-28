# CampusHelp — Week 2 Mini Semantic Search

## What it does
This project loads a small FAQ dataset, cleans the text, makes one text chunk per FAQ, stores the text in Chroma, and retrieves similar FAQs for a search question.

## Files
- `faqs.csv` — sample student FAQ data
- `semantic_search.ipynb` — notebook with the steps
- `requirements.txt` — required Python packages

## Run
Install packages in your Python environment:

```bash
pip install -r requirements.txt
```

Open `semantic_search.ipynb` in Jupyter or VS Code and run the cells from top to bottom.

**Note:** Chroma's default embedding model may download model files on its first run. An internet connection is needed if those files are not already cached.

## Example searches
- `How can I change my student portal password?`
- `I missed the deadline to choose my courses`
- `Where do I see my exam marks?`
- `Where can I study quietly?`

The FAQs are sample entries for demonstrating semantic search, not verified university policies.
