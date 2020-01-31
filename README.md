# Processdocs
Processdocs – reads in pdf, docx and rtf files and performs the following:

•	Strips off the punctuation and lowercases all text

•	Replaces URLs, numbers and emails with strings

•	Destems all words (using an implementation of the porter stemmer)

•	Writes out the processed files with same file name but with a .txt suffice

•	Creates a dictionary (dictionary.txt) of all unique words (column 1) and word frequency (column 2).

Program uses third party libraries for reading and writing pdfs and word docs.
    iText is a PDF library that allows you to CREATE, ADAPT, INSPECT and MAINTAIN
    documents in the Portable Document Format (PDF), allowing you to add PDF 
    functionality to your software projects with ease.  We even have documentation 
    to help you get coding.

    Sautinsoft Document .Net is 100% C# managed library which gives you API to create, parse, 
    load, modify, convert, edit and merge documents in PDF, DOCX, RTF, HTML and 
    Text formats. Rasterize documents to Images and render to WPF FrameworkElement

