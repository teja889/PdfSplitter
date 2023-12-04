# PdfSplitter
# How to Use PDF Splitter

1. Ensure you have Java installed on your system.
2. Place the input PDF file in the same directory as the PdfSplitterUI.java file.
3. Create a folder named "output" in the same directory to store the split PDFs.
4. Open a terminal or command prompt and navigate to the directory containing PdfSplitterUI.java.
5. Compile the Java file using the command:
   javac -cp .:lib/pdfbox.jar PdfSplitterUI.java
6. Run the PDF Splitter UI using the command:
   java -cp .:lib/pdfbox.jar PdfSplitterUI
7. The PDF Splitter UI window will open.
8. Enter the input PDF file name (e.g., input.pdf) in the "Input PDF File" field.
9. Enter the output directory name (e.g., output) in the "Output Directory" field.
10. Click the "Split PDF" button.
11. The split PDFs will be saved in the specified output directory.
12. A success message or an error message will be displayed.

Note: Make sure to include the pdfbox.jar file in the "lib" folder before compiling and running the code.
