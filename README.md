# Documentation Repository README

Welcome to our documentation repository! This README provides instructions on how to contribute to the documentation and organize its structure.

## Getting Started

To add or edit documentation content, follow these steps:

1. **Navigate to the `doc/en/` directory:** All English documentation files should be located under this directory.

2. **Edit Existing Documents:**
   - If you need to edit an existing document, locate the relevant Markdown file (`*.md`) under the appropriate section directory.
   - Make your changes directly in the Markdown file using a Markdown editor or any text editor.

3. **Add New Documents:**
   - To add a new document, create a new Markdown file under the appropriate section directory.
   - Ensure the file name is descriptive and follows a consistent naming convention, using PascalCase or separating different names with `-`.

4. **Structure the Document:**
   - Use Markdown syntax to structure the document content, including headings, lists, links, etc.
   - Follow existing document structures and styles for consistency.

5. **Navigation Menu Structure**

Ensure that the navigation menu accurately reflects the document structure for easy navigation within the documentation app.

To update the navigation menu:

- **Navigate to the `docs-nav.json` file:** This file is located in the root directory of the repository.

- **Add or Modify Menu Items:**
   - Use the `items` array in the JSON structure.
   - Each menu item is represented by an object containing `text` and `path` properties.
   - Ensure correct paths to the Markdown files.

6. **Use Visual Studio Code (VS Code) for Editing:**
   - It's recommended to use VS Code for editing Markdown files due to its rich features for Markdown editing.
   - Install the Markdown All in One extension for enhanced Markdown editing capabilities.

## Repository Structure

The repository follows a structured format to organize documentation content effectively. Here's an overview:

- `doc/en/`: Contains all English documentation files.
  - `SectionI/`, `SectionII/`, etc.: Sections of documentation organized by topics.
    - `Document1.md`, `Document2.md`, etc.: Individual Markdown files for documents.
  - `Appendix/`: Appendix section containing supplementary documentation.

## Navigation Menu Structure

The navigation menu (`docs-nav.json`) is structured to reflect the organization of the documentation sections and sub-sections. It consists of an array of items, each representing a menu item with its corresponding text and path.

```json
{
   "items":[
      {
         "text":"SECTION 1",
         "items":[
            {"text":"Document 1","path":"SectionI/Document1.md"},
            {"text":"Document 2","path":"SectionI/Document2.md"}
         ]
      },
      {
         "text":"SECTION 2",
         "items":[
            {"text":"Document 3","path":"SectionII/Document3.md"},
            {"text":"Document 4","path":"SectionII/Document4.md"}
         ]
      },
      {"text":"APPENDIX","path":"Appendix/Appendix.md"}
   ]
}
```
Ensure that the navigation menu accurately reflects the document structure for easy navigation within the documentation app.

## Contributing

Feel free to contribute to the documentation by adding new content, improving existing content, or updating the navigation menu. Follow the guidelines mentioned above for consistency and clarity.

Thank you for your contributions to our documentation repository! 🚀
