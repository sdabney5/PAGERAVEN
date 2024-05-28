# PAGE RAVEN
## Text Restrictions: NEVERMORE


### Overview:
Page Raven is a tool I designed to easily capture screenshots of etext pages and save them as PDF or TXT files. 
This is particularly useful if you own a text but face restrictions like DRM. Page Raven provides a quick and easy way to get around these restrictions and preserve your content.
Basically, it flips through text pages in (pretty much) any app for reading electronic text, it screenshots each page (you specify the screenshot area with a rectangle tool), and saves it to a folder on your computer.

### Usage
To use Page Raven, you have two options: download and run the standalone executable (the best way) or run the Python script if you prefer.

#### HOW TO DOWNLOAD: 
1. **Download the executable**
   - Direct download: [Page_Raven.exe](https://github.com/sdabney5/PAGERAVEN/releases/download/v1.0.0/Page_Raven.exe) OR
   - From the releases page: [https://github.com/sdabney5/PAGERAVEN/releases](https://github.com/sdabney5/PAGERAVEN/releases) (click Page_Raven.exe, download it)
   - Your laptop will probably tell you this is an unsafe or unrecognized file. You will have to tell it to trust the program, or 'run anyway'. 
   
2. **Run it**:
   - On Windows: Double-click the executable file.
   - On macOS/Linux: Open a terminal and run `./Page_Raven.exe`.


No additional dependencies are required. The executable includes everything needed to run the application.

#### Using the Python Script
If you prefer to run the Python script, you must have Python 3.x installed on your computer along with the following dependencies:  
- customtkinter
- pillow
- pyautogui
- PyPDF2
- MouseInfo
- PyGetWindow
- PyMsgBox
- pyperclip
- PyRect
- PyScreeze
- pytweening
- typing_extensions

To use this script, download or clone the repository.
You can install these packages using the following command:
   **pip install -r requirements.txt**
	
Once you have the dependencies installed, you can run the program using the **Page_Raven.py** script. This script opens a GUI.

Here's an example of how to run the program:  
_______________________________________________________________________________
python Page_Raven.py
_______________________________________________________________________________

### Notes
Please note that the program assumes the image is in a format that can be read by Pillow (not grayscale, CMYK, etc.).

Additionally, while Page Raven includes basic features the screenshot process, it is primarily intended for quickly capturing and saving screenshots from e-texts. If you need more advanced features, you might need to modify the script or integrate it with other tools.

### License
Page Raven is licensed under the BSD-3-Clause License. You must attribute the original creator in any derivative works or distributions.

**Thank you for using Page Raven! If you find it helpful, please cite me in your work by including a link to this repository.**

