# Markdown Challenge

Clone this directory to your local computer.

The `data` directory contains a list of markdown documents that are sorted into sections.
The title of each section can be found in the special `_index.md` file while its ID is part of the folder name.
All other markdown files have the ID as file name before the extension, e.g., '1.1'.
Each markdown document has frontmatter in YAML format at the top that contains the applicable filter.

- [ ] Create an application that loads all markdown files and renders a table that contains the IDs and titles of all sections and documents and displays the filters, one filter per column.

- [ ] _Stretch goal:_ Make it possible to edit the filters and write the changes back to the markdown files. Make your own assumptions regarding the allowed values.

You may use the UI framework of your choice. Also, you may include any other third party library, given no license conditions are violated.
