# Lottery-Picker
### Lottery-Picker is a data analysis project which is designed to identify whether atmospheric conditions at the time and place of the drawing can affect the numbers drawn. By importing, cleaning, and transforming all historic lottery(MegaMillions) drawing data available and ten years of meteoroligical data for the drawing site(Atlanta, GA.) a comparison analysis is derived.

### The following project feature requirements are met:
   - Requirement - Annotate your code with markdown cells in Jupyter Notebook, write clear code comments, and have a well-written README.md.
   - Feature 1 - Read two data files (CSV).
   - Feature 1 - Set up a local database and read data in with SQLite.
       - Two CSV files are read in from Github.
       - After transformation the files are read into a local SQLite3 DB file to be used for futher analysis.
   - Feature 2 - Clean your data.
   - Feature 2 - Perform a SQL join.
       - The two files are cleaned(transformed) with Pandas.
       - Data is read in from the database, filtered, grouped and a SQL join is performed on 2 tables.
   - Feature 3 - Make a Tableau dashboard to display your data.
   - Feature 3 - Make a visualization with Bokeh.
       - I created a Tableau Dashboard containing bar charts of all previous drawing results with Tableau Public Desktop and then I published it to the Tableau Public site and embedded the html in a Jupyter Notebook code cell.
       - Unfortunately each of the bar charts have verticle sliders which are not interactive in Visual Studio Code but they are in Google Colab.
       - A Bokeh bar graph is created and displayed.

[Link to Tableau Public Dashboard](https://public.tableau.com/app/profile/mike7586/viz/MegamillionsNumbers/Dashboard1)

   - Feature 4 - Utilize a virtual environment and include instructions in your README on how the user should set one up.

## Setup development environment:

### This project was developed using Visual Studio Code Version: 1.76.2 with Jupyter v2023.2.1200692131 and Python Kernel version 3.10.6:

   1. Clone the Github Repository to your local workspace:
  
[Link to repo](https://github.com/Mikdown/Lottery-Picker)
   
### This project can be executed using two different methods:
   1. Locally on the users workstation:
      - File to execute: MegaMil_lotto.ipynb.
         - Creates and reads a SQLite DB file in the /assets folder.
   2. Remotely in Google Colab:
      - File to execute: colab_lotto.ipynb *** NOTE *** this file will not run in the IDE because the path to the SQLite DB file is N/A.
         - Includes a link to "Run in Colab" in the first cell.
         - Creates and reads a SQLite DB file in the Colab virtual desktop local folder.

## Setup virtual environment:

### It is recommended to create a python virtual environment so you do not pollute your working folder:
      
   1. In a Terminal App or Terminal window in your IDE navigate to the /Lottery-Picker folder.
       - To create a virtual environment named "venv" enter: python -m venv venv

[Python Documentation Link - 12.2. Creating virtual environments.](https://docs.python.org/3/library/venv.html)

[VS Code Documentation Link - Creating virtual environments.](https://code.visualstudio.com/docs/python/environments#_creating-environments)

   2. To activate the virtual environment enter:
        - Unix/MacOS enter: source venv/bin/activate
        - Windows enter: venv\Scripts\activate
           
[Python Documentation Link - 12.2. Creating virtual environments.](https://docs.python.org/3/library/venv.html)
           
[VS Code Documentation Link - Working with Python interpreters.](https://code.visualstudio.com/docs/python/environments#_working-with-python-interpreters)

   3. While in the venv shell enter: pip install -r requirements.txt

[Python Documentation Link - 12.3. Managing Packages with pip.](https://docs.python.org/3/library/venv.html)

[Python Documentation Link - Installing packages using pip and virtual environments.](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment)
   
## Requirements:
   
appnope==0.1.3
asttokens==2.2.1
backcall==0.2.0
bokeh==3.1.0
comm==0.1.3
contourpy==1.0.7
debugpy==1.6.6
decorator==5.1.1
executing==1.2.0
ipykernel==6.22.0
ipython==8.11.0
jedi==0.18.2
Jinja2==3.1.2
jupyter_client==8.1.0
jupyter_core==5.3.0
MarkupSafe==2.1.2
matplotlib-inline==0.1.6
nest-asyncio==1.5.6
numpy==1.24.2
packaging==23.0
pandas==1.5.3
parso==0.8.3
pexpect==4.8.0
pickleshare==0.7.5
Pillow==9.4.0
platformdirs==3.1.1
prompt-toolkit==3.0.38
psutil==5.9.4
ptyprocess==0.7.0
pure-eval==0.2.2
Pygments==2.14.0
python-dateutil==2.8.2
pytz==2022.7.1
PyYAML==6.0
pyzmq==25.0.2
six==1.16.0
stack-data==0.6.2
tornado==6.2
traitlets==5.9.0
wcwidth==0.2.6
xyzservices==2023.2.0
   
## Selecting the virtual environment interpreter in Visual Studio Code:
   
### To select a specific environment, use the Python: Select Interpreter command from the Command Palette (⇧⌘P).
   1. Click on Command Palette.
      - In the dropdown click on "Show and Run Commands>.
   2. In Command Palette enter: Python: Select Interpreter
   3. Choose the "venv" interpreter.
   
 [VS Code Documentation Link - Using Python Environments.](https://code.visualstudio.com/docs/python/environments)

