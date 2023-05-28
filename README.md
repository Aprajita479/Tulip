# Tulip

## Description

The code is written in Python and uses the `turtle` module to create a drawing based on data extracted from a Microsoft Word document (`docx` format). The code reads the document, parses the content, and extracts coordinate and color information to draw shapes on the screen.

## Dependencies

The code requires the following dependencies:
- Python 3.x
- Turtle module (`turtle`)
- Regular expression module (`re`)
- Python-docx module (`docx`)

Make sure these dependencies are installed before running the code.

## Usage

1. Make sure the Python dependencies are installed.
2. Save the Word document you want to use in the same directory as the code file, with the name `tulips.docx` (or modify the `source` variable to match your document's name).
3. Run the code.

## Functionality

1. The code imports necessary modules: `turtle` as `tu`, `re` (regular expressions), and `docx` (for working with Word documents).
2. The code initializes variables to store coordinate and color data: `coordinates` and `colour`.
3. It opens the Word document specified by the `source` variable and loops through its paragraphs.
4. For each paragraph, the code attempts to extract coordinate and color information using regular expressions.
5. The extracted data is processed and appended to the respective lists (`coordinates` and `colour`).
6. The code sets up the Turtle graphics environment (`pen` and `screen` objects).
7. Various configurations are applied to the Turtle graphics, such as tracer speed, hiding the turtle cursor, and making the canvas fullscreen.
8. The code iterates over the extracted data and draws shapes on the screen using the coordinates and colors.
9. Finally, the Turtle screen enters the main event loop, allowing the drawing to be displayed and interacted with.

## Note

The code includes a `try-except` block to handle any errors that may occur during parsing. If an error occurs, it is caught and ignored.
It is important to ensure that the Word document being used contains the expected coordinate and color information in the specified format for the code to work correctly.
Please review and adjust the code as necessary before running it with your specific Word document and requirements.

## License  
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
