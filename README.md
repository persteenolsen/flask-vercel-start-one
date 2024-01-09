# Python and Flask Tutorial

A Web Application with Python version 3.12.1 and Flask version 3.0.0 

# Installing

- Download Python from the official website [Python](https://python.org/)
- Make sure that you have installed Python and Flask by the commands in Powershell: "python --version" or "flask --version"
- Download the the Python extension for Visual Studio Code which automatically include the Pylance extionsion
- Download / fork this Flask Starter Web App from my GitHub
- Create the virtual envirement ".venv" for the Flask Web App by Powershell or by VS Code
- Virtual Enviroment by VS Code: "View - Command Palette - Python Create Enviroment"

# Run the Flask Web App without Debug from terminal

- Right click the local folder with the Flask Web App and open Powershell
- Run "flask run" and type "http://127.0.0.1:5000/" in your Browser and check the site is loaded
- If ".flaskenv" is not found run "pip install python-dotenv" and run "flask run" again
- You can also run the Flask Web App by run "flask --app api/index run" which point directly at the Flask entry file 
 
# Local development / debug / hot reload / refresh from VS Code:

- The folder ".vscode" includes the launch file for local development / debug by VS Code. Note: For some reason debug throw an exeption, but without chrashing and you can see the changes by f5. However, just "run without debug" and you will notise that the debug is still on and hit f5 for see the changes. This way you will avoid the exception
- Open a Browser and type "http://127.0.0.1:5000/" to see the site
- Make a change in a file and type f5 or refresh the Browser to see the change

# Local development / debug / hot reload / refresh outside VS Code:
 
- To debug from outside VS Code right click at the rootfolder with the repository forked from GitHub, open Powershell and type: "flask run --debug" which should use the settings in the .flaskenv file. 
- By using "flask run --debug" you could get promted to do: "pip install python-dotenv" for make things work
- Check that the package "python-dotenv" is installed by running "pip list" to display a package list
- Now you should be able to start in debug mode just by typing "flask run"
- Open a Browser and type "http://127.0.0.1:5000/" to see the site
- Make a change in a file and type f5 or refresh the Browser to see the change

# Deployment:

- Make sure to have both a GitHub and a Vercel Account
- Create a repository with the Web App Starter at GitHub
- Log in to Vercel and select the GitHub repository with your Web App Starter and follow the instructions
- The vercel.json file will be used at Vercel Serverless Functions
- Commit and sync your changes to GitHub which will create an automated Deployment to Vercel
- Check that your site is online at Vercel "your-repository-name.vercel.app"

# Helpfull commands by Powershell or command promt:

- "python --version" => Display the installed Python version
- "flask --version" => Display the version of installed Python, Flask and Werkzeug
- "flask run" => Run the Flask Web App
- "flask --app api/index run" => Run the Flask Web App which point directly at the Flask entry file 
- "flask run --debug" => Run the Flask Web App in Debug mode - Show the file cnage by hitting f5
- "pip install package name" => "pip install python-dotenv" => Installing a package
- "pip uninstall package name" => "pip uninstall python-dotenv" => Removing a package
- "pip list" => Display a list of the installed packages
- "pip freeze requirements.txt" => Create a requirements.txt file with the installed packages

# Features / Usefull links

- [Python](https://python.org/)
- [Flask](https://flask.palletsprojects.com/)
- [Vercel](https://vercel.com/)
- [GitHub](https://github.com/)
- [VS Code](https://code.visualstudio.com/)



# Author

- Per Olsen

# License

This project is open source and available under the [MIT License](LICENSE).



