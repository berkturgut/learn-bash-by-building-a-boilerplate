# Anki Card Import Instructions

This document explains how to import the Anki cards from `bash_boilerplate_anki_tr.md` and `bash_boilerplate_anki_en.md` into the Anki application. The cards were created from the **Learn Bash by Building a Boilerplate** course and adhere to **Dr. Piotr Wozniak’s Twenty Rules of Formulating Knowledge**.

## Creating a Card Type
1. Open Anki and go to **Tools > Manage Note Types**.
2. Create a new note type:
   - Name: “Bash Card Type”.
3. In the **Fields** tab, add the following fields (in order):
   - Question
   - Answer
   - Example
   - Source
4. In the **Cards** tab, edit the template:
   - **Front**:
     ```
     {{Question}}
     ```
   - **Back**:
     ```
     {{Answer}}
     <hr>
     Example: {{Example}}
     <hr>
     Source: {{Source}}
     ```

## File Preparation
1. **File Selection**:
   - For Turkish cards: `bash_boilerplate_anki_tr.md`
   - For English cards: `bash_boilerplate_anki_en.md`
2. Copy the content from the Markdown file (the text within the ```text code block).
3. Save it in a text editor (e.g., Notepad, VS Code) with a `.txt` extension:
   - Turkish: `bash_boilerplate_anki_tr.txt`
   - English: `bash_boilerplate_anki_en.txt`
   - **Note**: Ensure UTF-8 encoding.

## Importing
1. In Anki, select **File > Import** and load the `.txt` file.
2. Configure the settings:
   - **Deck**: E.g., “Bash Lessons”.
   - **Type**: “Bash Card Type”.
   - **Field Mapping**:
     - Column 1: Question
     - Column 2: Answer
     - Column 3: Example
     - Column 4: Source
   - **Separator**: Tab
   - Keep “Treat first field as unique” enabled.
3. Click “Import” and review the cards.

## Troubleshooting
- **UTF-8 Issues**: Ensure the file is saved with UTF-8 encoding.
- **Separator Errors**: Verify that Anki’s separator is set to “Tab”.
- **Missing Fields**: Confirm the field mapping is correct.

## Notes
- The cards are in tab-separated format and include 30 cards (27 question-answer, 3 cloze deletion).
- Turkish and English cards present the same information in different languages.
- For questions or issues, open an issue on GitHub.