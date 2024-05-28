# PAGE RAVEN
Text Restrictions: NEVERMORE

- # Page Raven
### Overview:
Page Raven is a tool designed to help users capture screenshots of a specified region on their screen and save them as PDF or TXT files. This is particularly useful for users who own a text but face restrictions like DRM. Page Raven provides a quick and easy way to get around these restrictions and preserve your content.

### Usage
To use Page Raven, you have two options: download and run the standalone executable or run the Python script if you prefer.

#### Using the Executable 
1. **Download the executable** from the releases page: https://github.com/sdabney5/PAGERAVEN/releases
2. **Run the executable**:
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

To use this script, download or clone the repository to your local machine.
You can install these packages using the following command:
   **pip install -r requirements.txt**
	
Once you have the dependencies installed, you can run the program using the **Page_Raven.py** script. This script opens a GUI that allows you to configure settings and start the screenshot process.

Here's an example of how to run the program:  
_______________________________________________________________________________
python Page_Raven.py
_______________________________________________________________________________

### Notes
Please note that the program assumes the image is in a format that can be read by Pillow (not grayscale, CMYK, etc.).

Additionally, while Page Raven includes features for customizing the screenshot process, it is primarily intended for quickly capturing and saving screenshots from e-texts. If you need more advanced features, you might need to modify the script or integrate it with other tools.

### License
Page Raven is licensed under the BSD-3-Clause License. You must attribute the original creator in any derivative works or distributions.

**Thank you for using Page Raven! If you find it helpful, please cite me in your work by including a link to this repository.**

