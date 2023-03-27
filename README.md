# Lottery-Picker
### Lottery-Picker is a data analysis project which is designed to identify whether atmospheric conditions at the time and place of the drawing have any affect on the winning numbers drawn. By importing, cleaning, and transforming all historic lottery(MegaMillions) winning number data available and ten years of meteoroligical data for the drawing site(Atlanta, GA.) a comparison analysis is done. This establishes a baseline for future endevors such as:
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

