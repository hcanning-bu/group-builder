# Blackboard Ultra Group Builder

A single-file web app for splitting a class roster into named groups and
generating the CSV files Blackboard Ultra needs to import a Group Set.

## Usage

1. Use `input-gradebook-names-export-500.csv` as a sample input, representing
   students exported from Gradebook.
2. Download and use `index.html` as your app to create the CSVs for Group
   Sets and Groups. It's a single self-contained file, so it runs entirely
   in your browser with no internet connection required — just double-click
   it to open it locally.
3. Use the `templates` folder to see Blackboard's own CSV templates for
   groups.

## Files

- `index.html` — the app. Open it in a browser, upload a gradebook CSV,
  choose a naming category and number of groups, preview the assignment,
  and download the generated CSVs.
- `input-gradebook-names-export-500.csv` — a sample 500-student gradebook
  export you can use to try out the app.
- `templates/` — Blackboard's own CSV templates (`sample_groups.csv` and
  `sample_groupmembers.csv`) showing the expected column format for Group
  Set and Group Members imports.
