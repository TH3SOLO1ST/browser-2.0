# browser-2.0
browser using PyQt5
## Code README

This is a Python script that creates a basic web browser using the PyQt5 library. The browser allows the user to navigate web pages, go back and forward in the browsing history, reload the current page, and enter a URL to visit a specific website.

### Prerequisites

Before running the script, make sure you have the following installed:

- Python (version 3 or above)
- PyQt5 library

You can install the PyQt5 library using pip:

```
pip install PyQt5
```

### Running the Script

To run the script, use the following command:

```
python <filename>.py
```

Replace `<filename>` with the name of the file where you have saved the code.

### Usage

- The web browser will open with the Google homepage as the default page.
- To navigate to a different web page, enter the URL in the address bar and press Enter.
- The back, forward, and reload buttons can be used to perform the corresponding actions.
- The home button will navigate to a specific website (http://copyassignment.com) defined in the `navigate_home` method. You can change this URL if desired.
- The URL in the address bar will automatically update as you navigate to different pages.

### Customization

- You can customize the browser title by modifying the `QApplication.setApplicationName` line in the script.
- You can modify the default homepage in the `MainWindow` class by changing the URL in the `self.browser.setUrl(QUrl('http://google.com'))` line.
- Feel free to modify the appearance and functionality of the browser by exploring the PyQt5 documentation and making changes to the script.

### Dependencies

The script requires the following dependencies:

- PyQt5.QtCore
- PyQt5.QtWidgets
- PyQt5.QtWebEngineWidgets

These dependencies are imported at the beginning of the script.

**Note:** This README assumes basic knowledge of Python and the PyQt5 library. If you are not familiar with these, it is recommended to refer to the respective documentation for more information.
