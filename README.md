Web Page to PDF Downloader

This Python script provides a simple graphical user interface (GUI) using Tkinter, allowing users to download web pages as PDF files. The tool utilizes Selenium in conjunction with a headless Chrome browser to interact with web content and trigger the printing functionality, enabling the generation of PDF documents.
Description

The script aims to simplify the process of saving web pages as PDFs by providing a user-friendly interface. Users input the URL of the desired web page into the GUI. Upon clicking the "Download" button, the script launches a headless Chrome browser session, navigates to the specified URL, and programmatically triggers the browser's print functionality. This action generates a PDF rendition of the web page, saving it in the 'Downloads' folder within the user's home directory.
Features

    Graphical User Interface: Utilizes Tkinter to create an intuitive interface for users to input URLs.
    Headless Chrome Browser: Employs Selenium to interact with a headless Chrome browser.
    PDF Generation: Automates the process of converting web pages to PDF files.

Usage

    Installation: Ensure the required dependencies are installed using pip install -r requirements.txt.
    Execution: Run the script using Python (python web_page_to_pdf_downloader.py).
    GUI Input: Input the URL of the desired web page in the provided field.
    Download: Click the "Download" button to initiate the PDF generation process.
    PDF Location: The resulting PDF file will be saved in the 'Downloads' folder within the user's home directory.

Prerequisites

    Python 3.x
    tkinter
    selenium
    webdriver-manager
    requests
    Chrome browser

Troubleshooting

If encountering issues, ensure all dependencies are correctly installed and up-to-date. Verify the availability of a stable internet connection and the presence of an updated Chrome browser.
Contributions

Contributions to enhance the tool, fix issues, or add new features are welcome! Please fork the repository, make your changes, and submit a pull request.
License

This project is licensed under the MIT License.

