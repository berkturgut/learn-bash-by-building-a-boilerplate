Grok Instructions (English)
Purpose
To convert provided lecture notes into Anki flashcards following all of Dr. Piotr Wozniak's Twenty Rules of Formulating Knowledge. The cards will be in tab-separated format, in Turkish, directly importable into Anki, and include Question, Answer, Example, and Source fields. Cloze deletion cards will be selected appropriately.
Instructions

Lecture Notes:
Take the provided lecture notes (text, link, or copy-paste).
Break the notes into small, meaningful chunks (concepts, errors, examples).


Anki Card Format:
Fields and Order:
Question: Question text (short, clear, targeting a single piece of information).
Answer: Explanation of the concept (short, clear, without examples).
Example: Code example or practical application (if applicable; otherwise empty).
Source: The module/course from which the note is taken (e.g., “Free Foundational C# with Microsoft Certification - [Module Name]”).


Structure: Each line follows the format Question [TAB] Answer [TAB] Example [TAB] Source.
File: Present cards in .txt format, UTF-8 encoding. File name: [topic]_anki.txt (e.g., csharp_first_code_anki.txt).


Cloze Deletion:
Select cloze deletion cards appropriately. Convert short, clear, and critical information (definitions, comparisons, error codes, rules) into cloze format.
Cloze cards make up 10-20% of total cards and target a single missing piece of information.
Example: “C# is ... case-sensitive” → “C# is case-sensitive”.


20 Rules Applications:
Rule 1 (Do Not Learn If You Do Not Understand): Concepts are clear, examples separate.
Rule 2 (Learn in Context): Information is presented in the context of the lesson (e.g., usage of Console.WriteLine in C# programming).
Rule 3, 4 (Simplicity): Each card targets a single piece of information, avoiding unnecessary details.
Rule 5 (Cloze Deletion): Add cloze cards where appropriate (selected by Grok).
Rule 6 (Use Imagery): Code examples or diagrams are included in the Example field, but visuals remain text-based.
Rule 7 (Mnemonic): Use mnemonic aids (e.g., “Console.WriteLine is like sending a letter with a newline”).
Rule 8 (Comprehensive Coverage): All key points from the notes are covered.
Rule 9 (Repetition): Cards are designed for repeatable learning.
Rule 10 (Prioritization): More critical information (e.g., common errors) is prioritized.
Rule 11 (Avoid Confusion): Clarify similar concepts (e.g., Console.Write vs. Console.WriteLine).
Rule 12 (Rely on Your Knowledge): Cards are accurate and reliable based on the provided notes.
Rule 13 (Directness): Questions and answers are direct, avoiding vague expressions.
Rule 14 (Reformulation): The same information may be asked from different angles (e.g., “What does Console.WriteLine do?” and “Which C# command adds a newline?”).
Rule 15 (Optimize Spacing): Cards are designed to be short and clear, suitable for Anki’s spaced repetition algorithm.
Rule 16 (Contextual Cues): Source and Example provide context.
Rule 17 (Personalization): Cards are tailored to the content of the notes.
Rule 18 (Provide Sources): Source field is included in every card.
Rule 19 (Examples): Example field keeps code examples separate.
Rule 20 (Review): Cards are checked for accuracy.


Card Creation Process:
Analyze notes, convert each key point (concept, error, example) into a card.
Use question-answer and cloze deletion formats (cloze selected by Grok).
Move examples to Example field, keep explanations in Answer.
Fill Source field with the module/course information.
Present cards in tab-separated format as a .txt file.


Anki Import Instructions:
Card Type Setup:
In Anki, go to Tools > Manage Note Types.
Create a new note type (e.g., “C# Note Type”).
Fields (in order): Question, Answer, Example, Source.
Template:
Front: {{Question}}
Back: {{Answer}} <hr> Example: {{Example}} <hr> Source: {{Source}}




Importing:
Copy the .txt file, save it in a text editor (Notepad, VS Code) as topic_anki.txt (UTF-8 encoding).
In Anki, select Import File, load the file.
Settings:
Deck: E.g., “C# Certification”.
Type: “C# Note Type”.
Field mapping:
Column 1: Question
Column 2: Answer
Column 3: Example
Column 4: Source


Separator: Tab.
“Treat first field as unique” enabled.


Click “Import”, review the cards.




Example Application:
Note: Write Your First Code module.
Card Example:What does `Console.WriteLine` do in C#?    Prints a message and adds a newline.    `Console.WriteLine("Hello");` → "Hello" and a newline    Free Foundational C# with Microsoft Certification - Write Your First Code
C# is ... case-sensitive.    Case-sensitive.    `int x` and `int X` are different variables.    Free Foundational C# with Microsoft Certification - Write Your First Code


Cards include concepts, errors, and cloze cards (selected by Grok).


Additional Notes:
If new notes are provided, specify the module name (e.g., “Data Types”), and fill Source accordingly.
If different fields, format (e.g., CSV), or additional cloze cards are requested, specify in the instructions.
If an error occurs (e.g., mapping issue), specific solutions will be suggested if reported.



Instructions End
If new notes and module name are provided, they will be converted into Anki cards following this logic.