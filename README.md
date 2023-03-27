# Lottery-Picker
### Lottery-Picker is a data analysis project which is designed to identify whether atmospheric conditions at the time and place of the drawing have any affect on the winning numbers drawn. By importing, cleaning, and transforming all historic lottery(MegaMillions) winning number data available and ten years of meteoroligical data for the drawing site(Atlanta, GA.) a comparison analysis is done. This establishes a baseline for future enhancements such as:
   1. Inclusion of other data types, e.g., geophysical, astonomical, etc...
   2. Development of functions, e.g., enhanced quick-pick, web UI, etc...
   3. Addition of lottories other than MegaMillions.

## Setup development environment:

### This project was developed using Visual Studio Code Version: 1.76.2 with Jupyter v2023.2.1200692131 and Python Kernel version 3.10.6.

   1. Clone the Github Repository to your local workspace: 
[Link to repo](https://github.com/Mikdown/Lottery-Picker)
   
### This project can be executed using two different methods:
   1. Locally on the users workstation:
      - File to execute: MegaMil_lotto.ipynb.
         - Creates and reads a SQLite DB file in the /assets folder.
   2. Remotely in Google Colab:
      - File to execute: colab_lotto.ipynb *** NOTE *** this file will not run in the IDE because the path to the SQLite DB file is N/A.
         - Includes a link to "Run in Colab" in the first cell.
         - Creates and reads a SQLite DB file in the virtual desktop local folder.

## Setup virtual environment:

### It is recommended to create a python virtual environment so you do not pollute your working folder:
      
   1. In a Terminal App or Terminal window in your IDE navigate to the /Lottery-Picker folder.
       - To create a virtual environment named "venv" enter: python -m venv venv
       - To activate the virtual environment enter:
           - Unix/MacOS enter: source venv/bin/activate
           - Windows enter: venv\Scripts\activate
[Documentation Link - Creation of virtual environments.](https://docs.python.org/3/library/venv.html)
        
   2. While in the venv shell enter: pip install -r requirements.txt
[Documentation Link - Installing packages using pip and virtual environments.](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#creating-a-virtual-environment)
   
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
   - Click on Command Palette.
      - In the dropdown click on "Shaow and Run Commands>.
   - In Command Palette enter: Python: Select Interpreter
   - Chose the venv interpreter.
   
[Documentation Link - Using Python Environments.](https://code.visualstudio.com/docs/python/environments)

