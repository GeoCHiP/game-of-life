# About

A simple web-application written using Python Flask for educational purposes.

# Quick start

1. Clone repo

       git clone https://github.com/GeoCHiP/game-of-life.git

2. Create virtual environment

       cd game-of-life/
       python -m venv .venv

3. Activate virtual environment

    * Linux

           source .venv/bin/activate

    * Windows

        * Powershell

               .\.venv\Scripts\Activate.ps1
        
        * Command Prompt

               .\.venv\Scripts\activate.bat

4. Install the requirements

       pip install -r requirements.txt

5. Set environmental variable `FLASK_APP` to `app.py`

    * Linux

           export FLASK_APP=app.py
        
    * Windows

        * Powershell

               $env:FLASK_APP="app.py"
        
        * Command Prompt

               set FLASK_APP=app.py

6. Run the server

       flask run
