# pdf-to-doc
Certainly! Here's an example of how you can create a README file for your PDF to DOC converter software:

# PDF to DOC Converter

This is a Python-based software that allows you to convert PDF files to DOC files.

## Installation

1. Clone the repository or download the source code to your local machine.
2. Make sure you have Python 3.x installed on your system.
3. Install the required dependencies by running the following command:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Open a terminal or command prompt.
2. Navigate to the directory where the source code is located.
3. Run the following command to start the PDF to DOC converter:
   ```
   python pdftodoc.py
   ```
4. The GUI window will appear. Click the "Select PDF" button to choose the PDF file you want to convert.
5. Click the "Select Destination" button to choose the folder where you want to save the converted DOC file.
6. Click the "Convert" button to start the conversion process.
7. Once the conversion is complete, a success message will be displayed, and the converted DOC file will be saved in the selected destination folder.
8. If you are using non windows devise then downgrade pip to 22

## Dependencies

- pdf2image: A Python library for converting PDF pages to images.
- pytesseract: A Python wrapper for Google's Tesseract OCR engine.
- python-docx: A Python library for creating and updating Microsoft Word (.docx) files.
- tkinter: The standard Python interface to the Tk GUI toolkit.

## License

This project is licensed under the chaturveda.
