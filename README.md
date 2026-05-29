# Lab compound matching app

Streamlit app for matching user-supplied compound lists against local MCE/library Excel workbooks.

The app searches a selected local database by common identifiers such as plate/seat, CAS, compound ID, and SMILES, then exports a completed Excel result table.

## Run

Install dependencies:

```powershell
pip install -r requirements.txt
```

Start the Streamlit app:

```powershell
streamlit run "import pandas as pd.py"
```

Place local compound database workbooks in the same folder as the app before running it. Database and upload files are intentionally ignored by Git.

## Notes

- Keep MCE/vendor spreadsheets out of the repository.
- The current script filename is preserved for compatibility with the original upload.
- If the interface text appears garbled in a terminal, verify that the file was saved and opened with UTF-8 compatible settings.
